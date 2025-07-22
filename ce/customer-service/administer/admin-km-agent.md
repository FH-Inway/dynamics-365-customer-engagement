---
title: Manage Customer Knowledge Management Agent (preview)
description: Learn how to manage the Customer Knowledge Management Agent to autonomously create knowledge articles from cases and related communications.
author: Soumyasd27
ms.author: sdas
ms.reviewer: Soumyasd27
ms.topic: how-to
ms.collection: 
ms.date: 07/22/2025
ms.custom: bap-template
---

# Manage Customer Knowledge Management Agent (preview)

[!INCLUDE [preview-banner](~/../shared-content/shared/preview-includes/preview-banner.md)]

Customer Knowledge Management Agent lets you autonomously turn cases and case-related conversations, emails, and notes into knowledge articles that can support your contact center operations. 

[!INCLUDE [preview-banner](../../../shared-content/shared/preview-includes/production-ready-preview-dynamics365.md)]

## Prerequisites

- You're using the out-of-the-box case entities.
- [Dynamics 365 knowledge management](set-up-knowledge-management-embedded-knowledge-search.md#configure-knowledge-management) is configured.
- You enabled Copilot to access Dynamics 365 knowledge base. You can utilize the internal knowledge base resources only for generating responses. Learn more in [Configure knowledge sources](copilot-enable-help-pane.md#configure-knowledge-sources).
- For real-time creation, you [configured connection references for Customer Knowledge Management Agent flow (preview)](admin-km-agent-connections.md#configure-connection-references-for-customer-knowledge-management-agent-flow-preview).
- [Manage consumption-based billing and capacity](setup-pay-as-you-go.md).

## Enable Customer Knowledge Management Agent

In Copilot Service admin center, go to **Support experience** > **Knowledge** > **Customer Knowledge Management Agent (preview)**, and then select **Manage**. The **Customer Knowledge Management Agent (preview)** page appears.

You can harvest from cases, associated conversation summaries, emails, notes, and conversations. For cases and conversations, select from the following options as required for Customer Knowledge Management Agent.

## Enable real-time knowledge creation

From the **Case** or **Conversations** tab, in the **Real-time creation** section, select the **Let Copilot use information from current case to create knowledge articles** option for cases or **Let Copilot use information from current chat and messaging conversations to create knowledge articles** option for conversations.

Real-time knowledge creation is triggered when a customer service representative (service representative) resolves a case or closes a conversation. It determines whether a new knowledge article is needed by comparing the content of the case or conversation with the existing knowledge articles in Dynamics 365 knowledge base. If an article is needed, the Customer Knowledge Management Agent creates the article using the case or conversation content.  

### Control which cases or conversations real-time creation should create articles from 

You can create multiple rules to control which conditions must be met for a resolved case or conversation to be processed by Customer Knowledge Management Agent in real time. For example, you might limit this process to cases or conversations owned by a certain user, or any other fields on the case or conversation.  

1. From either the **Case** or **Conversations** tab, in the **Real-time creation** section, select **Manage rules**. 
1. In the **Manage rules** dialog, select **New** to add a new rule.
1. In the **New knowledge creation rules** dialog, enter a rule name, condition name, and then add your conditions.
1. Select **Save**.

### Control which case attributes are used to create knowledge articles in historical

Customer Knowledge Management Agent uses **Case Title**, **Case Description**, **Product**, **Subject**, **Email Content**, **Conversation Summary**, and **Case Notes** to create an article. You can remap all the fields except **Email Content** and **Conversation Summary** to your own record types and data fields. You can't change the attributes used for conversations.
 
1. In the **Case** section, select **Manage attributes**. The **Manage data** page appears. 
You can map which record types and data fields are used for each element. You can choose to include and exclude data.
1. Select **Save and Close**.
1. Select **Save** on the **Customer Knowledge Management Agent (preview)** settings page.

> [!NOTE]
> If you encounter issues during historical creation, try enabling **Track changes** for the mapped entities and adding them to the **Entity Analytics Config** table.

To enable track changes:
 
1. Sign in to [Power Apps](https://make.powerapps.com). 
2. Search and select the table you want to configure from **Dataverse** > **Tables**.
3. Select **More commands**  (…) > **Properties**. 
5. On the **Edit table** dialog, expand **Advanced options**. 
6. Turn on **Track changes** and then select **Save**. 

To add mapped entities to the **Entity Analytics Config** table:

1. Open the model-driven app ( `https://<org>.crm.dynamics.com/...` ).   
2. Press **F12** to open the browser’s **Developer Tools**, and then select the **Console** tab.   
3. Copy the following script snippet, update **ENTITY_NAME**, and paste it into the console.
4. Press **Enter** to run the script.

```javascript

Xrm.WebApi.createRecord('entityanalyticsconfig', {'parententitylogicalname':'{ENTITY_NAME}','isenabledforadls': true})

 ``` 

## Enable historical knowledge creation

When enabled, the agent looks at all the cases that meet the conditions specified, and then determines if new articles are needed by comparing the content of the cases or conversations with the existing Dynamics 365 knowledge base. If a new article is needed, it creates a new article by using the content of one or more historical cases that meet the configured conditions.  

1. Select the **Cases** or the **Conversations** tab.

    ### [Case](#tab/case)
    a. In the **Creation from historical cases** section, select the **Let copilot use information from historical cases to create knowledge articles** option.
    ### [Conversations](#tab/conversations)
    a. In the **Creation from historical conversations** section, select the **Let copilot use information from historical chat and messaging conversations to create knowledge articles** option.

1. Select **Manage rules** to configure the conditions for the harvest.
1. On the **Default rule** dialog, enter a rule name, condition name, and then add your conditions to filter historical articles.
1. Select **Save**.
1. Select **Save** on the **Customer Knowledge Management Agent** settings page.
1. Select **Start** on the **Creation from historical cases or conversations** section. 
Once you select start, you see that the article creation is in progress. You can see the creation process log by selecting the **View creation process log** link.

Creation from historical cases or conversations is a long-running process, which can't be stopped once it starts. The process can create articles from a maximum of 100,000 cases or conversations and runs until all the 100,000 cases or conversations are processed. We recommend that you perform historical knowledge creation in batches. 

## Set the default compliance state of created articles

You can control the default compliance state of the articles created by Customer Knowledge Management Agent. For example, to ensure articles are compliant, set their default state to **Pending** and ask the knowledge reviewers to mark them as compliant before publishing.  

To set the default compliance state of articles created by Customer Knowledge Management Agent, on the **Customer Knowledge Management Agent (preview)** page, **Compliance** section, select your default compliance state from the available options.

Articles with the **Non Compliant** status can't be published.

> [!NOTE]
> Customer Knowledge Management Agent removes personal data from the case data before drafting articles. However, the agent might not detect all instances of sensitive information.

## Auto publish articles

You can control whether the AI agent can automatically publish articles that comply with the **Compliance Status** you set. You can also select the target audience that can view the published articles.

To set the auto-publishing of articles created by Customer Knowledge Management Agent, on the **Customer Knowledge Management Agent (preview)** page, **Auto publishing** section, select the **Automatically publish compliant articles as soon as they’re created** option.

- Select **Internal target audiences**, if you want articles to be available to your service representatives and Copilot internally. 
- Select **Internal and external target audiences**, if you want these articles to be published to external portals.

## Set up the agent review draft experience

If you’re not configuring the AI agent to automatically publish articles, you can configure an agent review experience where service representatives can review and publish articles.

To enable this editor: 

- Enable in-app notifications for service representatives to be notified when their cases are considered for publishing.
- Ensure that your service representatives have the permission to edit articles.
- Make sure that your cases have **Timeline** and **Timeline highlights** enabled.

Service representatives can see whether they have knowledge articles to review by opening a resolved case. Learn more in [Review knowledge articles created by the Customer Knowledge Management Agent (preview)](../use/admin-km-agent-review.md#review-knowledge-articles-created-by-the-customer-knowledge-management-agent-preview).

## Use knowledge insights for Customer Knowledge Management Agent

You can get analytics reports on Customer Knowledge Management Agent and collect analytics data for your own custom reporting. Learn more in [Use knowledge insights for Customer Knowledge Management Agent (preview)](../use/admin-km-agent-insights.md#use-knowledge-insights-for-customer-knowledge-management-agent-preview).

## Related information

[Use knowledge insights for Customer Knowledge Management Agent (preview)](../use/admin-km-agent-insights.md#use-knowledge-insights-for-customer-knowledge-management-agent-preview)




