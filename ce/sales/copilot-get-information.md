---
title: Get information from Copilot
description: Learn how to use Copilot in Dynamics 365 Sales to get information about your pipeline, summarize leads and opportunities, and get the latest news about your accounts.
ms.date: 04/26/2024
ms.topic: how-to
ms.service: dynamics-365-sales
ms.custom:
  - ai-gen-docs-bap
  - ai-gen-desc
  - ai-seo-date:10/04/2023
  - bap-template
author: lavanyakr01
ms.author: lavanyakr
ms.reviewer: lavanyakr
search.app: salescopilot-docs
ms.collection: bap-ai-copilot
---

# Get information from Copilot

Use Copilot to get information about your pipeline, summarize your opportunities and leads, and get the latest news about your accounts. You can either use predefined prompts or ask questions in natural language. This article describes some of the predefined prompts you can use to get information from Copilot. [Learn more about chatting with Copilot in natural language](use-sales-copilot.md#chat-with-copilot-in-NL).

## Show my pipeline

Copilot can provide a list of open opportunities assigned to you, sorted by the estimated close date.

[Open Copilot](use-sales-copilot.md#open-copilot), select the sparkle icon (:::image type="icon" source="media/sparkle-icon.png" border="false":::), select **Get info** > **Show my pipeline**, and select **Enter**.

## Summarize a lead or opportunity

1. [Open Copilot](use-sales-copilot.md#open-copilot).  
1. Select the sparkle icon (:::image type="icon" source="media/sparkle-icon.png" border="false":::), select **Get info** > **Summarize lead** or **Summarize opportunity**, and then select **Enter**.

    - When a record is opened, Copilot summarizes it.
    - When in grid view, Copilot lists the records for which you have read access. Hover over a record and select **Summarize**.

1. To get a list of changes for a specific lead or opportunity, type **/** after the prompt, and then start typing the name of the opportunity or lead.

    :::image type="content" source="media/copilot-opportunity-summary.png" alt-text="Screenshot of a Copilot opportunity summary.":::

### Would you like to view a summary of different fields?

Copilot generates the summary from a set of predefined fields. Other fields might be more important to you, however. For example, estimated revenue, close date, contact, pipeline stage, and proposed solution might be the first things you look for in an opportunity. Work with your Dynamics 365 Sales administrator to [add those fields to the configuration](enable-setup-copilot.md#configure-fields-for-generating-summaries-and-recent-changes-list).

Keep in mind that the summary fields are configured at the organization level. Make sure that your entire sales team agrees on the **top 10** fields that are most relevant for your business.

### Enrich leads with related information

Copilot can enrich your leads with information from Dynamics 365 Sales, Dynamics 365 Customer Insights, LinkedIn, and Bing, such as:

- Possible contacts, based on the lead name, phone number, email address, and company name

- Insights about customer sentiment, behavior, and interest generated based on unified activity data in Dynamics 365 Customer Insights, if configured. [Learn more](/dynamics365/customer-insights/data/lead-profile-summary)  

- The latest news about the account, curated by Bing

- Suggested LinkedIn profiles for the contact, if you have the LinkedIn Sales Navigator license

After you select a lead, Copilot suggests other records that might be associated with the lead and from which it can glean more information.

1. [Ask Copilot to summarize a lead](#summarize-a-lead-or-opportunity).

    If Copilot finds possible matching contact records, it lists them after the summary. [How does Copilot match leads with contacts and can I customize the matching fields?](sales-copilot-faq.md#how-does-copilot-match-leads-with-contacts-and-can-i-customize-the-matching-fields)

1. Select **Connect** to connect the lead with a matching record.

    :::image type="content" source="media/copilot-lead-enrichment.png" alt-text="Screenshot of a lead card in the Copilot chat, with a matching account highlighted.":::

1. After Copilot connects the records, select **Get updated lead summary** to generate a new summary that includes information from the connected record.

    Copilot also lists the fields that can be updated with information from the connected record, such as the city, state, phone numbers, and postal code.

1. To update the lead record with the suggested values, select **Update all**.

<a name="copilot-doc-summarization"></a>
## Summarize proposals associated with a record (preview)

[!INCLUDE [preview-banner-section](~/../shared-content/shared/preview-includes/preview-banner-section.md)]

[!INCLUDE [preview-note](~/../shared-content/shared/preview-includes/preview-note.md)]

Often, you might have documents such as proposals and contracts associated with your records. Copilot can summarize the content of these documents and help you understand the key points. For example, you can ask Copilot to summarize a proposal document to understand the budget, authority (decision maker), need, and timeline (BANT) of the opportunity.

> [!NOTE]
>- This feature is available only if your administrator has opted in to the [Copilot preview features](copilot-preview-features.md).
>- Currently, Copilot can summarize only PDF and Word documents.

1. Open a record, such as an opportunity, lead, account, or contact, that has documents associated with it.

1. In the Copilot side pane, enter the prompt **Summarize document /** and then enter the name of the document you want summarized.

   A minimum of three characters is required to start the search. You can search by the file name. For example,
    - Enter **Summarize document /contract** to get a list of documents that has **contract** in the file name.
    - Enter **Summarize document /pdf** to get a list of documents that has **pdf** in the file name or extension.

   Depending on the size of the document, it might take a few seconds to summarize the document.


## Show the latest news about an account

Copilot can get the latest news that features or mentions your accounts, curated by Bing. These news articles can be great conversation starters and help you understand the dynamics in your customers' organizations.

As always when you're working with AI-sourced content, read articles thoroughly to confirm they're from authentic sources and are indeed about your customer.

1. [Open Copilot](use-sales-copilot.md#open-copilot).

1. Select the sparkle icon (:::image type="icon" source="media/sparkle-icon.png" border="false":::), select **Get info** > **Get latest news for account**, and select Enter.

    - If you have a record open, Copilot lists the news articles related to that account.
    - If you're in the grid view, Copilot lists news articles for the top 10 accounts you work with, sorted by the revenue associated with them.

1. To get the news articles for a specific account, type **/** and then start typing the name of the account.

### See also

- [Copilot overview](copilot-overview.md)
- [Enable and set up Copilot](enable-setup-copilot.md)
- [Chat with Copilot in natural language (preview)](use-sales-copilot.md#chat-with-copilot-in-natural-language-preview)
- [Get document recommendations from SharePoint](copilot-get-doc-suggestions.md#get-document-recommendations-from-sharepoint)
