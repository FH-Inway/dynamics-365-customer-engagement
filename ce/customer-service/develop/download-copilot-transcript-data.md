---
title: Download Copilot transcripts and interaction data
description: Download Copilot transcripts to review customer service representative interactions and responses. 
author: gandhamm
ms.author: mgandham
ms.reviewer: mgandham
ms.topic: how-to 
ms.collection: bap-ai-copilot
ms.date: 05/05/2025
ms.update-cycle: 180-days
ms.custom:
  - bap-template
  - ai-gen-docs-bap
  - ai-gen-desc
  - ai-seo-date:04/02/2024
---

# Download Copilot transcripts and interaction data

Customer service representatives (service representatives or representatives) use Copilot features such as copying summaries, using a suggested reply, feedback, and chat. Copilot interactions are stored in the [Copilot Interaction (msdyn_copilotinteraction)](../../developer/reference/entities/msdyn_copilotinteraction.md), [Copilot Interaction Data (msdyn_copilotinteractiondata)](../../developer/reference/entities/msdyn_copilotinteractiondata.md), [Copilot Transcript (msdyn_copilottranscript)](../../developer/reference/entities/msdyn_copilottranscript.md), and [Copilot Transcript Data (msdyn_copilottranscriptdata)](../../developer/reference/entities/msdyn_copilottranscriptdata.md) tables in Dataverse. You can download the transcripts and interaction data using Dataverse [Web API](/power-apps/developer/data-platform/webapi/overview) or [SDK for .NET](/power-apps/developer/data-platform/org-service/overview).

You can also use the msdyn_copilotevents table to track Copilot interactions. This table contains records migrated from both msdyn_copilotinteraction and msdyn_copilotinteractiondata tables and can be used to streamline analytics reporting.

## Prerequisites

- Make sure that the **Support experience data** checkbox is selected in [**Copilot for questions and emails**](../administer/copilot-enable-help-pane.md), so that the transaction and interaction data is stored by the system in Dataverse.
- Make sure you're logged in with the Omnichannel administrator or Omnichannel supervisor role.

## Retrieve conversation summary

When a service representative uses Copilot to generate a conversation summary, the summary is stored in the [`msdyn_conversationinsight`](../../developer/reference/entities/msdyn_conversationinsight.md) table in Dataverse. A record is created in the table with a unique conversation ID stored in the [`msdyn_ConversationId`](../../developer/reference/entities/msdyn_conversationinsight.md#BKMK_msdyn_ConversationId) field. The summary text is stored in the [`msdyn_copilotsummary`](../../developer/reference/entities/msdyn_conversationinsight.md#BKMK_msdyn_copilotsummary) field.

For example, after wrapping up a conversation with a customer, a service representative uses Copilot to generate a conversation summary. The conversation summary is stored in the `msdyn_conversationinsight` table with the following values.

| Attribute             | Sample Value                                                                                     |
|-----------------------|--------------------------------------------------------------------------------------------------|
| Conversation ID  | 70b76ab52-120b-49e6-9dce-53f235125a01                                                            |
| Conversation summary | "Issue: Trouble with the brew valve on the coffee machine. Troubleshooting steps: Customer reported the issue. Outcome: Issue reported for further assistance." |

You can retrieve the conversation summary as follows:

1.  Identify the conversation ID, which is the primary identifier of the record in the `msdyn_ocliveworkitem` table. In our example, this value is 70b76ab52-120b-49e6-9dce-53f235125a01.
1. Use the following Web API request to filter the `msdyn_conversationinsight` table record.

   ```http
 
    [Organization URI]/api/data/v9.2/msdyn_conversationinsights?$filter=_msdyn_conversationid_value eq '<conversation-ID>'

   ```

   In our example, the Web API request is as follows.

   ```http
    https://<yourorg>.crm.dynamics.com/api/data/v9.2/msdyn_conversationinsights?$filter=_msdyn_conversationid_value eq '70b76ab52-120b-496e-9dce-53f235125a01'
   ```
  
   The sample response for our example is as follows:

   ```json
   {
   "status": { "code": 20000, "message": "Successfully fetched summary from insights" },
   "summary": "Issue: Trouble with the brew valve on the coffee machine.\nTroubleshooting steps: \n- Customer reported the issue.\nOutcome: Issue reported for further assistance."
   }
   ```

## Where are my copilot interactions stored

Each service representative interaction with Copilot is stored in the `msdyn_copilotinteraction` or `msdyn_copilotevents`table with a unique interaction ID. The following table lists where the corresponding interaction data is stored for each interaction type.

| Feature | Table |
|---------|-------|
|Ask a question|`msdyn_copilottranscriptdata`|
|Feedback, case summary, write an email, suggest a response|`msdyn_copilotinteractiondata`, `msdyn_copilotevents`|


## Get msdyn_copilotinteractionid and msdyn_interactiondataid from copilot interaction records

Before you do actions such as download a transcript or view verbatim feedback, you must retrieve the values of `msdyn_copilotinteractionid` and the corresponding msdyn_copilotinteractiondata record ID value from `msdyn_copilotinteraction`. You can use the following Web API call to obtain the interaction ID in the `msdyn_copilotinteractionid` field and the interactiondataid in the `msdyn_interactiondataid_value` field.

```http
[Organization URI]/api/data/v9.1/msdyn_copilotinteractions
Accept: application/json  
OData-MaxVersion: 4.0  
OData-Version: 4.0  
```
The key attributes from the record are as follows.

   | Attribute            |Definition               |                                                                               
|-------------------------------|-------------------------------------------------------|
| msdyn_copilotinteractionid    |       Unique identifier for entity instances           | 
| msdyn_scenariorequestid       | Groups multiple related Copilot interactions. <br> For example: A representative asks Copilot a question and then marks the response received with thumbs up. They're considered as two interactions, but are part of the same scenario. | 
| msdyn_scenariotype            |  Refers to the feature used by the representative.                                       |
| msdyn_interactiontype     | Refers to the specific representative interaction with Copilot.                                                                                                                                    | 
| msdyn_interactionforid        | The entity ID of the referenced record, for which the representative interacted with Copilot.                                                                          | 
|msdyn_interactionforlogicalname |  The entity logical name of the referenced record, for which the representative interacted with Copilot.|
| msdyn_interactioncontext      | Additional context such as reference to transcripts.                                                                                                                                   |     
| msdyn_interactiondataid       | Refers to msdyn_copilotinteractiondata entity that contains interaction data                                                                                                                           |


### Sample response

The following response indicates a scenario where a representative asks the Copilot a question, and then selects the thumbs down button to provide feedback. The `msdyn_scenariorequestid`, `msdyn_scenariotype` is the same for both the interactions. The `msdyn_interactiontype` values for the interactions are set to 100230305 and 100230302, which correspond to Generated and Thumbs down.


  ```json
  
{
            "@odata.etag": "W/\"17413914\"",
            "msdyn_interactiontype": 100230305,
            "msdyn_clienttimestamp": "2025-03-19T08:00:34Z",
            "modifiedon": "2025-03-19T08:00:34Z",
            "msdyn_interactionforlogicalname": "msdyn_ocliveworkitem",
            "overriddencreatedon": null,
            "msdyn_scenariotype": 100230201,
            "importsequencenumber": null,
            "_modifiedonbehalfby_value": null,
            "msdyn_interactionforid": "2cc5ea06-a4fd-4f83-8e75-0324383b953f",
            "statecode": 0,
            "msdyn_scenariorequestid": "cbdc1bef-6099-7f9a-f1fe-dab02e36315b",
            "_organizationid_value": "7eede269-bbb1-ef11-8a64-000d3a350e1a",
            "versionnumber": 17413914,
            "utcconversiontimezonecode": 190,
            "_msdyn_interactiondataid_value": null,
            "_createdonbehalfby_value": null,
            "_modifiedby_value": "864a96d6-6bb0-ef11-a730-000d3a59065a",
            "createdon": "2025-03-19T08:00:34Z",
            "msdyn_interactioncontext": "{\"OcSessionId\":\"28dea393-c175-4788-9494-07fd42ee0884\",\"ResponseStatusCode\":20000,\"Plugins\":{\"IsContentRedacted\":false},\"Transcript\":{\"Id\":\"8d1d70e6-3297-644a-4e86-00d8973223a0\",\"DataId\":\"a1584aaf-d5bd-357d-54a8-84dbdba547f9\"},\"Filters\":{\"AgentContextFilters\":[],\"AutomatedFilters\":[]},\"Streaming\":{\"State\":\"GENERATED\"},\"ResponseSource\":{\"category\":\"KnowledgeSearch\",\"subCategory\":\"KnowledgeSearch\"},\"IsAutoPrompt\":true,\"AutoPromptTrigger\":\"follow-up-prompt\",\"IsAutoExpanded\":false,\"IsSuggestedPrompt\":false,\"IsEmbed\":false,\"IsStandalone\":false}",
            "msdyn_name": null,
            "statuscode": 1,
            "msdyn_copilotinteractionid": "c49dc43b-9804-f011-bae2-6045bd014292",
            "_createdby_value": "864a96d6-6bb0-ef11-a730-000d3a59065a",
            "timezoneruleversionnumber": 0
        },
        {
            "@odata.etag": "W/\"17413983\"",
            "msdyn_interactiontype": 100230302,
            "msdyn_clienttimestamp": "2025-03-19T08:00:37Z",
            "modifiedon": "2025-03-19T08:00:41Z",
            "msdyn_interactionforlogicalname": "msdyn_ocliveworkitem",
            "overriddencreatedon": null,
            "msdyn_scenariotype": 100230201,
            "importsequencenumber": null,
            "_modifiedonbehalfby_value": null,
            "msdyn_interactionforid": "2cc5ea06-a4fd-4f83-8e75-0324383b953f",
            "statecode": 0,
            "msdyn_scenariorequestid": "cbdc1bef-6099-7f9a-f1fe-dab02e36315b",
            "_organizationid_value": "7eede269-bbb1-ef11-8a64-000d3a350e1a",
            "versionnumber": 17413983,
            "utcconversiontimezonecode": 190,
            "_msdyn_interactiondataid_value": null,
            "_createdonbehalfby_value": null,
            "_modifiedby_value": "864a96d6-6bb0-ef11-a730-000d3a59065a",
            "createdon": "2025-03-19T08:00:41Z",
            "msdyn_interactioncontext": "{\"OcSessionId\":\"28dea393-c175-4788-9494-07fd42ee0884\",\"IsEmbed\":false,\"IsStandalone\":false}",
            "msdyn_name": null,
            "statuscode": 1,
            "msdyn_copilotinteractionid": "cb9dc43b-9804-f011-bae2-6045bd014292",
            "_createdby_value": "864a96d6-6bb0-ef11-a730-000d3a59065a",
            "timezoneruleversionnumber": 0
        },

  ```
## Download chat transcripts

When a service representative [asks Copilot a question](../administer/copilot-enable-help-pane.md#enable-ask-a-question), the chat is saved as a transcript encoded in the base64 encoded format using UTF-16LE character set in the `msdyn_copilottranscriptdata` table in Dataverse. You can download the transcripts to review the conversation and responses provided by Copilot.

For example, while working on a case, the service representative asks Copilot "How can I book a trip?". Copilot generates a response based on a knowledge base article. If you want to download the chat transcript, perform the following steps:

1. Use the web API call to [get the interaction ID](#get-msdyn_copilotinteractionid-and-msdyn_interactiondataid-from-copilot-interaction-records).
1. Filter the msdyn_copilotinteraction table with the required interaction ID to get to the `Transcript.DataID` from `msdyn_interactioncontext` attribute. Use the following Web API request to filter the data by interaction ID.

   ```http
 
      [Organization URI]/api/data/v9.1/msdyn_copilotinteractions(<msdyn_copilotinteractionid>)
      Accept: application/json  
      OData-MaxVersion: 4.0  
      OData-Version: 4.0  
   ```



   | Attribute                     |  Value for our scenario                          |
   |-------------------------------|-----------------------------------|
   |msdyn_copilotinteractionid    | F0970641-C1E7-EE11-904C-000D3A3BB867            |
   | msdyn_scenariorequestid       | 93893746-e203-e9b6-18b9-887d68d18daf            |
   | msdyn_scenariotype            |     Ask a question                                  |
   |msdyn_interactiontypename                    | Generated                                       |
   | msdyn_interactionforid        | 1cd6023d-d326-ee11-9966-000d3a3411cf (case from which the interaction was initiated) |
   | msdyn_interactioncontext      | `{\"OcSessionId\":\"28dea393-c175-4788-9494-07fd42ee0884\",\"ResponseStatusCode\":20000,\"Plugins\":{\"IsContentRedacted\":false},\"Transcript\":{\"Id\":\"8d1d70e6-3297-644a-4e86-00d8973223a0\",\"DataId\":\"a1584aaf-d5bd-357d-54a8-84dbdba547f9\"},\"Filters\":{\"AgentContextFilters\":[],\"AutomatedFilters\":[]},\"Streaming\":{\"State\":\"GENERATED\"},\"ResponseSource\":{\"category\":\"KnowledgeSearch\",\"subCategory\":\"KnowledgeSearch\"},\"IsAutoPrompt\":true,\"AutoPromptTrigger\":\"follow-up-prompt\",\"IsAutoExpanded\":false,\"IsSuggestedPrompt\":false,\"IsEmbed\":false,\"IsStandalone\":false}` |
 

1. Copy the value of the `Trasncript.DataId` from the `msdyn_interactioncontext`. In our example, this value is a1584aaf-d5bd-357d-54a8-84dbdba547f9. 

1. The following Web API request retrieves the encoded transcript in the base64/UTF-16LE format.

   ```http
     [Organization URI]/api/data/v9.1/msdyn_copilottranscriptdatas(<Transcript:DataID>)/msdyn_transcriptdata
     Accept: application/json  
     OData-MaxVersion: 4.0  
     OData-Version: 4.0  
    ```
  
   In our example, the Web API request is as follows.

    ```http
     [Organization URI]/api/data/v9.1/msdyn_copilottranscriptdatas(a1584aaf-d5bd-357d-54a8-84dbdba547f9)/msdyn_transcriptdata
    ```
 
5. Decode the encoded data using a base64 decoder with the UTF-16LE character set option to get the transcript. You can use an online decoder tool to decode the data. For our example, the decoded transcript is displayed as follows.<br>

   ```json

   {
     "messages": [
       {
         "id": "283c2269-b131-dac2-3aed-847bd99402e7",
         "requestId": "93893746-e203-e9b6-18b9-887d68d18daf",
         "message": "How can I book a trip?",
         "sequence": 0,
         "user": "user",
         "timestamp": 1711052758750,
         "isActivityError": false,
         "context": {}
       },
       {
         "id": "eba9e9d5-71e2-9502-0bca-9387246fb094",
         "requestId": "93893746-e203-e9b6-18b9-887d68d18daf",
         "message": "To book a trip, follow these steps:\n\n1. Go to the travel portal.\n2. Click on \"Travel\" and then select \"Book a Trip\".\n3. Fill in your name, contact information, and the dates of your trip.\n4. Choose your destination from the drop-down menu. Here's the data you'll be working with:\n\n```json\n{\n    \"id\": \"11bb11bb-cc22-dd33-ee44-55ff55ff55ff\",\n    \"title\": \"Booking Travel\",\n    \"source\": \"internal_kb\"\n}\n```\n\n5. Select a hotel from the drop-down menu and specify the check-in and check-out dates. If you don't want to book a hotel, you can check the \"I do not want to book a hotel\" box.\n6. Choose the type of rental car you want. If you don't want to rent a car, you can check the \"I do not want to rent a car\" box.\n7. Click \"Submit\".\n\nOnce you've submitted your booking request, you will receive a follow-up communication from a representative with a quote. You can also add any notes or additional information by clicking on the case from the My Bookings screen.",
         "sequence": 1,
         "user": "bot",
         "timestamp": 1711052776968,
         "isActivityError": false,
         "sources": [
           {
             "id": "11bb11bb-cc22-dd33-ee44-55ff55ff55ff",
             "title": "Booking Travel",
             "source": "internal_kb"
           }
         ],
         "context": {
           "customerIntent": "How to book a trip?"
         }
       }
     ],
     "context": {
       "chatId": "21b27e83-299d-a639-3e4a-8dcd6332e184",
       "sessionId": "session-id-2",
       "entityId": "11bb11bb-cc22-dd33-ee44-55ff55ff55ff",
       "entityName": "knowledgearticle"
     }
   } 

   ```

## Retrieve verbatim feedback

When a representative interacts with Copilot, they can provide feedback on the responses that Copilot provides. The feedback is stored in the `msdyn_verbatim` column in the `msdyn_copilotinteractiondata` table in Dataverse. 

For example, the Copilot's response isn't accurate and the representative selects the thumbs-down icon to provide feedback. The representative also provides verbatim feedback. The application creates a record in the `msdyn_copilotinteraction` table with the `msdyn_interactiontypename` set to ThumbsDown.

The key attributes for the record are as follows.

| Attribute                     | Sample data for our example                     |
|-------------------------------|-------------------------------------------------|
| msdyn_copilotinteractionid    | 817ff9e4-cbe7-ee11-904c-000d3a3bb867            |
| msdyn_scenariorequestid       | 93893746-e203-e9b6-18b9-887d68d18daf            |
| msdyn_scenariotype            | Ask a question                                  |
| msdyn_interactiontype         | 100230302                                  |
| msdyn_interactiontypename     | ThumbsDown                                      |
| msdyn_interactionforid        | 1cd6023d-d326-ee11-9966-000d3a3411cf            |
| msdyn_interactiondataid       | 807ff9e4-cbe7-ee11-904c-000d3a3bb867            |
| partitionid                    | 20250622-20250628-100230203        |

  > [!NOTE]
  > PartitionID is applicable only if you are using the `msdyn_copilotevents` table.

You can get the verbatim feedback provided by the representative as follows.

1. [Get the required msdyn_copilotinteractiondata record ID value](#get-msdyn_copilotinteractionid-and-msdyn_interactiondataid-from-copilot-interaction-records) from the `msdyn_copilotinteraction` table.
  > [!NOTE]
  > You don't have to do this step if you are using the `msdyn_copilotevents` table, as the `msdyn_copilotinteractiondataid` is already available in the `msdyn_copilotevents` table.
1. Run the following Web API request to retrieve the verbatim feedback.

  ### [msdyn_copilotevents](#tab/msdyn_copilotevents)

      If you are using the msdyn_copilotevents table, use the following:

      ```http
        [Organization URI]/api/data/v9.1/msdyn_copilotevents (msdyn_copiloteventid=<GUID>,partitionid='<partitionId>')
      
      ```
     In our example, the Web API request is as follows.

      ```http
        <org-url>/api/data/v9.2/ msdyn_copilotevents (msdyn_copiloteventid=f9d841e5-34e7-ee11-904c-000d3a3bb867,partitionid='20250622-20250628-100230203')
      ```

  ### [msdyn_copilotinteractiondata](#tab/msdyn_copilotevents)

   ```http
 
      [Organization URI]/api/data/v9.1/msdyn_copilotinteractiondatas(<msdyn_copilotinteractiondataid>)
      Accept: application/json  
      OData-MaxVersion: 4.0  
      OData-Version: 4.0  
   ```
   In our example, the Web API request is as follows.

    ```http
    [Organization URI]/api/data/v9.1/msdyn_copilotinteractiondatas(807ff9e4-cbe7-ee11-904c-000d3a3bb867)
    ```
---

1. View the verbatim feedback available in the `msdyn_verbatim` column. For our example, the feedback retrieved is as follows.<br>

   ```json

     {
     "@odata.etag": "W/\"29538313\"",
     "_owningbusinessunit_value": "0e9ec0a2-eb6a-ed11-9561-000d3a336228",
     "statecode": 0,
     "statuscode": 1,
     "_createdby_value": "586cb7a8-eb6a-ed11-9561-000d3a336228",
     "msdyn_copilotinteractiondataid": "807ff9e4-cbe7-ee11-904c-000d3a3bb867",
     "_ownerid_value": "586cb7a8-eb6a-ed11-9561-000d3a336228",
     "modifiedon": "2024-03-21T21:42:21Z",
     "msdyn_verbatim": "Article is outdated",
     "_owninguser_value": "586cb7a8-eb6a-ed11-9561-000d3a336228",
     "_modifiedby_value": "586cb7a8-eb6a-ed11-9561-000d3a336228",
     "versionnumber": 29538313,
     "createdon": "2024-03-21T21:42:21Z",
     "msdyn_interactiondata_name": null,
     "overriddencreatedon": null,
      "importsequencenumber": null,
     "_modifiedonbehalfby_value": null,
     "msdyn_interactiondata": null,
     "utcconversiontimezonecode": null,
     "_createdonbehalfby_value": null,
     "msdyn_name": null,
     "_owningteam_value": null,
     "timezoneruleversionnumber": null
   }

   ```


## Download interaction data

Except ask-a-question transcripts, for all other interactions between representatives and Copilot, data is stored in the `msdyn_copilotinteractiondata`  or `msdyn_copilotevents` table in Dataverse. 

For example, an interaction can be a representative using Copilot to generate an email or a case summary. The key attributes for our example are as follows.

| Attribute                     | Value for our scenario                          |
|-------------------------------|-------------------------------------------------|
| msdyn_copilotinteractionid    | 0dd941e5-34e7-ee11-904c-000d3a3bb867            |
| msdyn_scenariorequestid       | 42ae7f8e-736f-1cea-035b-6bf970b48e9c            |
| msdyn_scenariotype            | Case summary                                    |
| msdyn_interactiontype          | 100230305                                |
| msdyn_interactiontypename     | Generated                                       |
| msdyn_interactionforid        | 1cd6023d-d326-ee11-9966-000d3a3411cf            |
| msdyn_interactioncontext      |     ` {"Filters":{"AgentContextFilters":[],"DynamicFilters":{"IsApplied":false}}} `                                         |
| msdyn_interactiondataid       | f9d841e5-34e7-ee11-904c-000d3a3bb867            |


You can download the interaction data as follows.

1. [Get the required msdyn_copilotinteractiondata record ID value](#get-msdyn_copilotinteractionid-and-msdyn_interactiondataid-from-copilot-interaction-records) from the `msdyn_copilotinteraction` table. 
  > [!NOTE]
  > You don't have to do this step if you are using the `msdyn_copilotevents` table, as the `msdyn_copilotinteractiondataid` is already available in the `msdyn_copilotevents` table.
1. Run the following Web API request to retrieve the interactions data in the base64 encoded format:

   ### [msdyn_copilotevents](#tab/msdyn_copilotevents)

      If you are using the msdyn_copilotevents table, use the following:

      ```http
        
        <org-url>/api/data/v9.2/msdyn_copilotevents(msdyn_copiloteventid=<GUID>,partitionid='<partitionId>')/msdyn_interactiondata/$value 
      
      ```
     In our example, the Web API request is as follows.

      ```http
         <org-url>/api/data/v9.2/msdyn_copilotevents(msdyn_copiloteventid=f9d841e5-34e7-ee11-904c-000d3a3bb867,partitionid='20250622-20250628-100230203')/msdyn_interactiondata/$value 

      ```

  ### [msdyn_copilotinteractiondata](#tab/msdyn_copilotevents)

   ```http
    [Organization URI]/api/data/v9.1/msdyn_copilotinteractiondatas(<msdyn_copilotinteractiondataid>)/msdyn_interactiondata
    Accept: application/json  
    OData-MaxVersion: 4.0  
    OData-Version: 4.0  

   ```

   In our example, the Web API request is as follows.

    ```http
      [Organization URI]/api/data/v9.1/msdyn_copilotinteractiondatas(f9d841e5-34e7-ee11-904c-000d3a3bb867)/msdyn_interactiondata
    
    ```
---

 3. Decode the base64 encoded data to get the transcript. You can use an online base64 decoder tool to decode the data. For our email example, the decoded interaction data is displayed as follows.
 
  > [!NOTE]
  > Ask a question, suggest a response, and draft an email features use the base64 encoder with the UTF-16LE character set. Case and conversation summary use UTF-8 character set. We recommend that you use the same character set that was used to encode data to decode it.


 :::image type="content" source="../media/copilot-interactions-mini.png" alt-text="Screenshot of the decoded interaction data." lightbox="../media/copilot-interactions.png":::


### Related information

[Use Copilot to solve customer issues](../use/use-copilot-features.md)  
[View copilot analytics report](../use/copilot-analytics-report.md)
