---
title: Copilot in Dynamics 365 Sales overview
description: Learn how to use Copilot in Dynamics 365 Sales to get quick summaries of opportunities and leads, prepare for meetings, compose emails, and stay up-to-date with news.
ms.date: 05/02/2024
ms.topic: overview
ms.service: dynamics-365-sales
content_well_notification:
  - AI-contribution
ms.custom:
  - bap-template
  - ai-gen-docs-bap
  - ai-gen-desc
  - ai-seo-date:10/02/2023
search.app: salescopilot-docs
ms.collection: bap-ai-copilot
author: lavanyakr01
ms.author: lavanyakr
ms.reviewer: lavanyakr
ai-usage: ai-assisted
---

# Copilot in Dynamics 365 Sales overview

Copilot is an AI assistant in Dynamics 365 Sales that helps sales teams be more productive and efficient in their daily work. It has a chat interface that sellers can use to get a quick summary of their opportunity and lead records, catch up on recent changes to their records, prepare for meetings, and read the latest news about their accounts. Sellers can chat with Copilot in natural language or use predefined prompts to get the information they need. [Learn more about how to use Copilot in Dynamics 365 Sales](use-sales-copilot.md)

Copilot is also available as an add-in in Outlook and an integrated app in Teams. With it, sellers can capture, view, and update their customer account data in the apps they use every day. The add-in and Teams app have generative AI capabilities such as record summarization and email content generation. Learn more about [Microsoft Copilot for Sales](/microsoft-sales-copilot/introduction)(formerly known as Microsoft Sales Copilot) and its [generative AI capabilities](/microsoft-sales-copilot/ai-sales-copilot).


## Copilot in Dynamics 365 Sales capabilities

Copilot offers the following capabilities:

- [Record summarization](#record-summarization)
- [Recent changes](#recent-changes)
- [Information assistance](#information-assistance)
- [Meeting preparation](#meeting-preparation)
- [Email assistance](#email-assistance)
- [News updates](#news-updates)

### Record summarization

Record summarization gives you a quick summary of your opportunity and lead records. Copilot generates the summary from predefined fields. Your administrator can change the fields that Copilot uses to generate the summary. Ensure that your entire sales team agrees on the top 10 fields that are most relevant for your business.

Learn more:

- [Summarize a lead or opportunity](copilot-get-information.md#summarize-a-lead-or-opportunity)
- [Change the fields in the record summary](enable-setup-copilot.md#configure-fields-for-generating-summaries-and-recent-changes-list)

### Recent changes

To help you stay on top of your sales records, Copilot summarizes any changes that were made to your lead, opportunity, and account records. Copilot generates the list of recent changes from the records' audit history. Your administrator can change the fields that are included in the recent changes list. Ensure that your entire sales team agrees on the top 10 fields that are most relevant for your business.

Learn more:

- [View recent changes to your lead or opportunity](copilot-ask-questions.md#get-recent-changes-to-a-lead-or-opportunity)
- [Get a list of recently updated sales records](copilot-ask-questions.md#whats-new-with-my-sales-records)
- [View the leads and opportunities assigned to you recently](copilot-ask-questions.md#whats-newly-assigned-to-me)
- [Change the fields you want to view in the recent changes list](enable-setup-copilot.md#configure-fields-for-generating-summaries-and-recent-changes-list)

### Information assistance

With Copilot, you can get information at your fingertips. You don't have to switch between apps to find the information you need. Copilot can get product-related documents and fetch answers to sales-related questions from documents stored in SharePoint.

Learn more:

- [Get content recommendations from SharePoint](copilot-get-doc-suggestions.md#copilot-content-recommendation)
- [Get answers from SharePoint documents](copilot-get-doc-suggestions.md#get-answers-from-sharepoint-documents)


### Meeting preparation

Copilot helps you prepare for your upcoming meetings effortlessly, summarizing relevant information from the opportunity or lead records that are associated with the meeting.

[Learn more about preparing for upcoming sales appointments](copilot-stay-ahead.md#prepare-for-upcoming-sales-appointments).

### Email assistance

Copilot can help you compose professional-looking emails, summarize email conversations to add to your customer notes, and give you reminders to follow up on emails you haven't replied to.

Learn more:

- [Compose and send email messages using Copilot (preview)](compose-send-email-copilot.md)  
- [View and copy an email summary](view-copy-email-summary.md)  
- [Display unanswered emails](copilot-stay-ahead.md#display-unanswered-emails)


### News updates

Copilot can help you stay current with the latest news about your accounts. News updates can be great conversation starters and help you understand the dynamics of your customers' organizations. Ask Copilot to get you the latest news related to an account and it returns a list of articles that feature or mention the account, curated by Bing. As with any content that's provided by AI, make sure you read the news articles thoroughly and confirm that they're from an authentic source and are indeed about the customer.

[Learn how to get the latest news about an account](copilot-get-information.md#show-the-latest-news-about-an-account).

## Region availability and languages supported

Copilot in Dynamics 365 Sales is available only in English language and is supported only in specific regions. For a list of regions where Copilot in Dynamics 365 Sales isn't supported, see [this FAQ](sales-copilot-faq.md#is-copilot-in-dynamics-365-sales-available-in-all-regions). 

Effective April 1, 2024, Copilot in Dynamics 365 Sales is turned on by default for tenants in North America and other regions where an Open AI Service endpoint is available. If your tenant is in a region where Copilot is supported but an Azure Open AI Service endpoint isn't available, an admin needs to opt in to share some data with the Azure OpenAI Service outside of your default geography. [Learn more about regions where Azure Open AI Service endpoints are available](/power-platform/admin/geographical-availability-copilot#how-data-movement-across-regions-works).