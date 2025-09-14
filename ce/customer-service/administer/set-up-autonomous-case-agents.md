---
title: Set up Case Management Agent for case creation and update (preview)
description: Learn how to set up autonomous Case Management Agent to help customer support teams efficiently handle case management tasks.
author: gandhamm
ms.author: mgandham
ms.reviewer: mgandham
ms.topic: how-to 
ms.collection: bap-ai-copilot
ms.date: 09/15/2025
ms.custom: bap-template
---


# Set up Case Management Agent to create and update cases (preview)

[!INCLUDE [preview-banner](~/../shared-content/shared/preview-includes/preview-banner.md)]

The Case Management Agent streamlines the case management process, reducing manual effort and data entry errors.

You can use the creation and update feature of the Case Management Agent to do the following actions:

- Create cases autonomously from conversations in voice, live chat, and other digital messaging channels. The agent identifies key details and creates cases automatically.
- Predict and update case fields autonomously in the following scenarios:
     - When the AI agent creates a case autonomously from a conversation
     - When a customer service representative (service representative or representative) manually creates a case from an email or conversation
     - When a case is created from an incoming email using automatic record creation and update rules

[!INCLUDE [preview-banner](../../../shared-content/shared/preview-includes/production-ready-preview-dynamics365.md)]

## Prerequisites

- Administrators must have the CSR Manager or System Administrator role.
- Enable [AI form fill assistance](/power-platform/admin/settings-features#ai-form-fill-assistance) in the Power Platform admin center application.
- [Automatically create or update records](automatically-create-update-records.md) are set up to create case records from emails.
- The following configurations are set up to create a case from conversations:
    - [Provision channels in Dynamics 365 Contact Center](/dynamics365/contact-center/implement/provision-channels).
    - Make sure you [configure authenticated chat](create-chat-auth-settings.md). The Case Management Agent can create and update cases from authenticated chats only.
    - [Create and manage workstreams](create-workstreams.md) and [Create and manage queues for unified routing](queues-omnichannel.md) are set up.
    - We recommend that you configure a [preconversation survey](configure-pre-chat-survey.md) so that customers can provide necessary details in the chat which can be used by the AI agent during case creation.
-  [Move data across regions for Copilots and generative AI features](/power-platform/admin/geographical-availability-copilot) in the Power Platform admin center application.
- The Autonomous Case Management agent uses the Data Entry Agent in the background. The Power Platform [Pay-as-you-go plan](/power-platform/admin/pay-as-you-go-overview) mandates the usage of an Azure subscription the system charges when the agent runs. Make sure you [Set up consumption-based billing](setup-pay-as-you-go.md).
- Transcription is enabled for the channels that support voice conversations. For more information, see [Enable transcription for voice channels](voice-channel-configure-transcripts.md#enable-call-recording-and-transcription-for-voice).
-  We recommend that you enable audit history and make sure service representatives have the required access to the case and related entities that the AI agent updates. Learn more in [Manage Dataverse auditing](/power-platform/admin/manage-dataverse-auditing).

### Update field and lookup descriptions in Power Apps

To help the AI agent make better predictions for lookup fields, add descriptive information to your lookup records. Do the following steps in Power Apps:

- Add meaningful field descriptions in your table columns to help the AI understand the context. For example, in the **Account Number** column of the **Account** table, add a description like: "This is an account number. Account numbers start with ACC."
-  Do the following steps to improve the AI agent's prediction accuracy with lookup fields:
    - For the required lookup entity, add a new optional text field to contain a description of the record if a description field doesn't already exist.
    - Add the meaning and usage for the description fields in the lookup records.
    - Update the **Quick Find** view of the lookup entity to include the new description field as a column. 
    - Save and publish the changes.
    
  For example, consider case categories like "Billing" and "Account Issues". When a customer writes "I can't access my account to pay my bill," it fits both categories. By adding clear descriptions to each lookup record, the AI agent can make more accurate predictions. If you include descriptions to the "Billing" category such as "Questions about charges and invoices, payment processing issues, refund requests," and  "Login problems and password resets, profile updates and settings, account access difficulties" to "Account issues", the AI agent categorizes the customer's message as "Account Issues" because the primary problem relates to account access rather than billing.
   > [!NOTE]
   > The Subject entity includes a description field by default, but we recommend not using these descriptions for lookup predictions because subject lookup views are read-only.

**Best practices for lookup descriptions**

We recommend that you follow these guidelines when you are adding descriptions for lookup fields:

- Use simple, direct language and keep the descriptions under two or three sentences to ensure clarity. Don't add unnecessary information or domain jargon.
- Include typical scenarios, keywords, and phrases that users might use when describing their issue. This helps the AI agent to make semantic connections between user input and the correct record.
- Distinguish between similar records by specifying what makes each record unique, preventing confusion and improving prediction accuracy.
- Don’t repeat the record name unless it adds clarity. Specify what the name doesn't convey about the record's intended use and scope.
- Use labeled sections like "Use when:" or "Not for:" to provide clear boundaries and usage guidelines for the AI agent.
- Provide synonyms, related terms, and specific examples. Avoid terms such as "general" or "miscellaneous" that lack meaningful context.
- Avoid overly generic descriptions, excessive detail, unexplained abbreviations, and assumptions about internal business logic that the AI agent can't access or understand.

## Configure autonomous case updates

In the Copilot Service admin center, configure the AI agent to predict and update case fields after a conversation ends or when processing an incoming email. The rules you specify in this section apply to all channels unless you explicitly configure them to apply to specific channels.

> [!NOTE]
> The AI agent can predict and update fields of the following data types:
>   - Lookup fields. Upto 50 options are supported for each lookup field.
>   - Boolean
>   - Integer
>   - Choice
>   - Option Set
>   - Currency
>   - Multiple Lines of Text
>   - Single line of text
>   - Email

1. In **Customer support**, select **Case settings**.
2. On the **Case settings** page, select **Manage** for **Case Management Agent**.
3. On the **Case Management Agent** page, select **Case creation and update with autonomous AI assistance (preview)**.
1. In the page that appears, in **Case update by AI agent (any channel)**, select **Create**. Specify the following information:
   - A unique name for the rule. 
   - Conditions for the AI agent to apply the rule. If no conditions are defined, the rule applies to all channels.
   - Fields in **Fields for AI prediction** that the agent predicts and updates when the conversation ends or from an incoming email. If you don't specify update rules, the AI agent doesn't autonomously update any fields.
   - Select **Save**.
 For example, if you only specify **Issue description** and **Contact** fields in the **Fields for AI prediction** section, the AI agent updates these fields when the conversation ends or from an incoming email. If you also specify a condition such as live chat status equals Active, then the rule applies only for live chat conversations that are active.
1. The system runs case update rules in the order they're listed. You can select the arrow buttons to reorder the rules as needed.
1. Select **Activate** to activate the rules.
1. Select **Allow AI agent to override human edits during autonomous updates** for the AI agent to automatically overwrite fields. During autonomous case update, the AI agent overwrites fields that were previously edited by service representatives. 

## Configure autonomous case creation

The following actions trigger the case creation process of the Case Management Agent:

- The service representative accepts an incoming conversation request.
- The service representative ends the conversation.

To allow the AI agent to autonomously create cases across all provisioned messaging and voice channels, perform the following steps:

1. Go to **Case creation and update (preview)** > **Case creation by AI agent (from chats and calls)** and select **Make Case Processing Agent available for case creation from conversations**.
1. In **Fields for AI prediction**, specify the fields the agent must predict and populate in the case form using information from the conversation. 

> [!NOTE]
> The fields you configure for case creation aren't mandatory. The AI agent populates only those fields that have sufficient context available.

## Configure AI-assisted case creation for service representatives

Select the channels from which service representatives can create cases with AI assistance. You can select **Email** or **Conversation(chats and calls)**. When a service representative creates a case from a conversation or an email, the AI agent analyzes the conversation or email and predicts and populates the fields available on the case form. Service representatives can then review the predicted values and make any necessary changes before saving the case.

## Enable service representatives to use autonomous Case Management Agent

For service representatives to use the Case Management Agent in Copilot Service workspace, allow the autonomous case creation and update, case follow-up, and closure in **agent experience profiles**.

By default, service representatives added to the out-of-the-box experience profiles can use the autonomous Case Management Agent.

1. Go to **Experience profiles** using one of the following navigation options:
   - **Support experience** > **Workspaces**
   -  Select **Manage** for **Case Management Agent**, and then select **agent experience profiles** in **Case creation and update (preview)** > **Representative access**.
2. Select the required experience profile.
3. In the **Copilot AI features** section do the following actions:
     - Select **From conversations** in **Autonomous case creation and update**.
     - In **Form fill assistance for cases** select **During case creation from conversation** and **During case creation from email** to indicate which channels the AI agent can assist service representatives in creating cases.
  
  
## Record representative interactions with the AI agent

In **Agent experience data from Representative experience data**, you can select **Record transcripts of representative interactions with AI, including representative actions, and their feedback on AI suggestions** to record and understand how representatives are interacting with the AI agent and how the agent is performing in a support organization. Representatives can also share feedback about AI agent actions, which helps Copilot perform better. You can also download and use the data to analyze knowledge sources, and build usage reports.


## Example 

When a customer initiates a chat conversation with the service representative, the AI agent creates if it has enough context to update at least one of the **Issue description** or **Contact** fields.

For the agent to run this scenario, specify the following in the **Case creation and update with autonomous AI assistance (preview)** page:
 
- **Channel**: Chat  
- **Fields for AI prediction**: Issue description, Contact  

When the conversation ends, the AI agent must update the **Issue description** and **Contact** fields, if there are any updates. Additionally, the **Product**, **Priority**, and **Serial number** fields should also be updated if the case category is set to **product defect**. 

For the agent to execute this scenario, in addition to the **Issue description** and **Contact** fields set in **Default list of fields for AI prediction** specify the following in the **Case creation and update with autonomous AI assistance (preview)** page:

- Select **Create** for **Case update rules**. 
- In the **New rule** page, specify the **Rule name** and the following:
  - In **Define conditions**, select **Add** and then specify the following:
    - **Select a field:** Case category  
    - **Operator:** Equals  
    - **Value:** Product defect  
  - Specify fields for AI prediction when this condition is met:  
    - **Product**, **Priority**, **Serial number**

## Next steps

 [Use Case Management Agent to create and update cases (preview)](../use/use-case-creation-agent.md)
