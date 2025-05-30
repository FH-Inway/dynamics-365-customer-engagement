---
title: Default insight cards
description: Discover default insight cards that help you stay updated with your work in Dynamics 365 Sales, providing relevant information for your tasks.
author: udaykirang
ms.author: udag
ms.reviewer: udag
ms.topic: concept-article
ms.date: 04/16/2025
ms.custom:
  - bap-template
  - ai-gen-docs-bap
  - ai-gen-desc
  - ai-seo-date:03/21/2024
---

# Default insight cards

Insight cards help keep you up to date with your work in Dynamics 365 Sales, letting you know when you need to follow up on an email, attend a meeting, and much more. They're displayed throughout the application to provide relevant information for the context you're working in. The cards are generated by the assistant based on data stored in Dynamics 365 Sales and your [!INCLUDE[pn_Exchange](../includes/pn-exchange.md)] inbox and calendar. This topic lists each of the available cards and provides details about what each card does, how it gets generated, and how you can use it. More information: [Use Sales Insights Assistant to guide customer communications](assistant.md)

> [!NOTE]
> - Your system administrator must enable the assistant before you can try it out. For prerequisites, how to enable the feature, and how to set it up, see [Configure Sales Insights Assistant](configure-assistant.md).  
> - Some of the Exchange-based cards are deprecated starting from Sunday, October 1, 2023. [Learn more](deprecations-sales.md#exchange-based-cards-are-deprecated).

The assistant displays cards in the following categories:

- [Upcoming meetings](#upcoming-meetings)   
- [Reminders](#reminders)   
- [Insights](#insights)
  
## Upcoming meetings

The following cards are available under **Upcoming meetings**.

| &nbsp; | &nbsp; | &nbsp; |
|----------|----------|----------|
| [Meeting today](#MeetingToday) | [Upcoming meeting](#UpcomingMeeting)| [Related news](#RelatedNEWS) |
| [Nearby customers](#NearbyCustomers) |||

>[!NOTE]
>The standard insight card types are available to you with the Sales Enterprise license.

|Insight card	| Type | Description | 
|-------------|------|-------------|
|<a name="MeetingToday"></a>**Meeting today** <br/>  ![Insight card for meeting today](media/ActionCard_MeetingToday.png "Insight card for meeting today")| Standard |**Description**:<br>Tells that you have a meeting scheduled for today. <br>The **Meeting Today** card is derived from your appointments in the Dynamics 365 Sales organization.<br>**Features**:<br>Shows the meeting title, with a link to the meeting record. Shows the meeting description, location, start time, and key participants. Open the detailed view to see the regarded entity and a collection of closely related insight cards, including relevant people, companies, opportunities, nearby customers, news, and more.<br>**Actions**: <br>Open Appointment<br>Email Attendees|
| <a name="UpcomingMeeting"></a>**Upcoming Meeting** <br />  ![Insight card for upcoming meeting](media/ActionCard_UpcomingMeeting.png "Insight card for upcoming meeting") | Standard | **Description**: <br>Tells that you have a meeting scheduled to start in 30 minutes or less. When available, this card is given highest priority and appears at the top of the stack. That way, you'll have all of your important meeting information available. <br> The "meeting today" card is similar, but it's shown all day until the meeting ends, provides fewer features, and is given lower priority. <br>**Features**:<br> Shows the meeting title, with a link to the meeting record.<br>Shows the meeting description (shortened for space if needed). <br>Shows the regarding record (with link).<br> Shows a list of attendees (with a link to the full list if there are more than four).<br>Displays a map of the location (if relevant and available; not for online meetings).<br> Open the detailed view to see a collection of closely related insight cards, including relevant people, companies, opportunities, news, and more.<br>**Actions**:<br> Join Meeting <br> Email Attendees |
| <a name="RelatedNEWS"></a>**Related News** <br />  ![Insight card for related news](media/ActionCard_RelevantNews.png "Insight card for related news") | Standard | **Description**: <br>The card displays news headlines related to companies that are **set as regarded** for the meeting. It’s shown in the card details view when you tap a meeting card from the assistant feed.<br>Only news in English is supported. You must have a ticker symbol defined for the company and it is used to fetch the news articles using Microsoft Bing and MSN Money. More information: [Privacy notice for Sales Insights standard features](privacy-notice.md#sales-insights-standard-features) <br> **Features**:<br> Shows the date when the news was last updated.<br> Thumbnail image and headline for each found article. Select to view the full article. |
| <a name="NearbyCustomers"></a>**Nearby Customers** <br />  ![Insight card for nearby customers](media/ActionCard_NearbyCustomers.png "Insight card for nearby customers")| Standard | **Description**: <br>The card finds customers that are located near the meeting location. It's shown in the card details view when you tap a meeting card from the assistant feed.<br> **Features**:<br> Shows the top three nearby customers. <br> Shows basic information about each company.|

## Reminders

The following cards are available under **Reminders**.

| &nbsp; | &nbsp; | &nbsp; |
|----------|----------|----------|
| [{<i>activity</i>} due today](#ActivityDueDate) | [Close date coming soon](#CloseDateComingSoon) | [Missed (opportunity) closed date](#MissedCloseDate)|
| [Email opened](#EmailOpened) | [Email reminder](#EmailReminder) | [No activity with {<i>record type</i>}](#NoActivityWithType) |
| [Recent meeting](#RecentMeeting) | ||

>[!NOTE]
>- The standard insight card types are available to you with the Sales Enterprise license.
>- The premium insight card types are available to you with the Sales Insights license. 

|Insight card	| Type | Description |
|-------------|------|-------------|
| <a name="ActivityDueDate"></a>**{*Activity*} due today** <br />  ![Insight card for task due today](media/ActionCard_TaskDueToday.png "Insight card for task due today") | Standard | **Description**:<br> Tells you that an open activity is due today.<br> **Features**:<br>Indicates the type of activity (email, letter, phone call, task, or custom).<br> **Actions**: <br>Close (for activities, such as phone call and task)<br>Complete|
| <a name="CloseDateComingSoon"></a>**Close date coming soon** <a name="CloseDateComingSoon"></a> <br />  ![Insight card for close date coming soon](media/ActionCard_CloseDateComingSoon.png "Insight card for close date coming soon") | Standard | **Description**: <br>Tells you that an open opportunity will soon reach its estimated close date. <br>**Features**:<br> Identifies the opportunity.<br>Tells how far away the close date is.<br>**Actions**:<br> Open opportunity<br>**Configuration options**:<br> Set how many days before the close date to start showing the card. The default value is set by your administrator.<br>**Note**: When you're viewing a dashboard, you'll only see these cards for opportunities that are assigned to you, but when you view a specific opportunity you'll see this card even if that opportunity is assigned to somebody else. |
| <a name="MissedCloseDate"></a>**Missed (opportunity) close date** <br />  ![Insight card for missed close date](media/ActionCard_CloseDateMissed.png "Insight card for missed close date") | Standard | **Description**:<br> Tells you that an open opportunity has passed its close date. <br>**Features**:<br> Identifies the opportunity.<br>**Actions**:<br> Open opportunity<br>**Note**: When you're viewing a dashboard, you'll only see these cards for opportunities that are assigned to you, but when viewing a specific opportunity you'll see this card even if that opportunity is assigned to somebody else.|
|<a name="EmailOpened"></a>**Email opened** <br />  ![Insight card for email opened](media/ActionCard_OpenedEmail.png "Insight card for email opened") | Standard | **Description**: <br>A followed email was opened by its recipient.<br>**Features**:<br>Names the contact you sent the email to.<br>Provides descriptive text that shows the subject of the email, the time it was opened, and the approximate location where it was opened.<br>**Actions**:<br>Open Email<br>**Prerequisites**:<br>Enable email engagement to use this card. To learn more, see [Configure and enable email engagement](configure-email-engagement.md). |
| <a name="EmailReminder"></a>**Email reminder** <br />  ![Insight card for email reminder](media/ActionCard_EmailReminder.png "Insight card for email reminder") | Standard | **Description**: <br> You set a follow-up reminder for an email you recently sent, and its trigger conditions have just been met. Trigger conditions always include a date but may also include conditionals such as whether the email wasn't opened or replied to by that date.<br>**Features**:<br> Names the contact that you sent the email to.<br>Tells you that you set a follow-up reminder for this email.<br>Provides a description that summarizes the trigger conditions.<br>**Actions**:<br>Open Email<br>**Prerequisites**:<br>Enable email engagement to use this card. To learn more, see [Configure and enable email engagement](configure-email-engagement.md). |
| <a name="NoActivityWithType"></a>**No activity with {*record type*}** <br />  ![Insight card for a lack of activity](media/ActionCard_NoActivity.png "Insight card for no activity") | Standard | **Description**:<br>Allows you to know that a record you own has been inactive for some time. Applies to contact, opportunity, lead, account, and case records.<br>**Features**: <br>Identifies the type and name of the relevant record.<br>Explains why the card was generated.<br>**Actions**:<br>Open {*record type*}<br>Send Email<br>**Configuration options**: <br> Set the number of days of inactivity that must pass before a card is generated. You can set a different value for each type of supported record (contact, opportunity, lead, account, and case). |
| <a name="RecentMeeting"></a>**Recent meeting** <br />![Insight card for a recent meeting](media/ActionCard_RecentMeeting.png "Insight card for recent meeting") | Standard | **Description**:<br> Tells you that a meeting you organized (where you're the record owner) has recently ended, giving you an easy opportunity to document the meeting in Dynamics 365 Sales. The card is displayed for 30 minutes after the scheduled end of the meeting, and then removed.<br>**Features**:<br>Identifies the meeting.<br>**Actions**:<br>Take Notes (Only for recent meeting)<br>Open Appointment |

## Insights

The following cards are available under **Insights**.

| &nbsp; | &nbsp; | &nbsp; |
|----------|----------|----------|
| [Opportunity at risk (sentiment detection)](#OpportunityRiskSentiment) | [Opportunity at risk (phrase detection)](#OpportunityRiskPhrase) | [Competitor mentioned](#CompetitorMentioned) |
| [Meeting requested](#MeetingRequested) | [File requested](#FileRequested) | [Buying intent detected in email](#BuyingIntentDetectedEmail) |
| [Suggested stakeholder](#SuggestedStakeholder) | [Relationship analytics](#RelationshipAnalytics) |[Contact is no longer with the company](#ContactMovedToNewOrg) |
| [Today's top people](#TodaysTopPeople) | [Today's top records](#TodaysTopRecords) | [Upcoming flight](#UpcomingFlight) |

>[!NOTE]
>- The standard insight card types are available to you with the Sales Enterprise license.
>- The premium insight card types are available to you with the Sales Insights license. 
>- The premium insight card types that get data from LinkedIn require the Sales Navigator license.

|Insight card | Type | Description |
|-------------|------|-------------|
|<a name="OpportunityRiskSentiment"></a>**Opportunity at Risk (sentiment detection)** <br />![Insight card for Opportunity at risk sentiment](media/ActionCard_OpportunityRiskSentiment.png "Insight card for Opportunity at Risk sentiment") |  Standard | **Description**: Tells you when an email is received concerning an open opportunity with negative sentiment, which can put the opportunity at risk.<br>**Actions**:<br>Open Email<br>Open opportunity|
|<a name="OpportunityRiskPhrase"></a>**Opportunity at Risk (phrase detection)** <br />![Insight card for Opportunity at risk phrase detection](media/ActionCard_OpportunityRiskPhraseDetection.png "Insight card for Opportunity at Risk phrase detection") | Standard | **Description**: Tells you when an email is received concerning an open opportunity that contains a phrase about legal, delay, or budget issues that can put the opportunity at risk.<br>**Actions**:<br>Open Email<br>Open opportunity|
| <a name="CompetitorMentioned"></a>**Competitor mentioned** <br/>![Insight card for competitor mentioned](media/ActionCard_CompetitorMentioned.png "Insight card for competitor mentioned") |  Standard | **Description**: <br> A tracked email that is set as regarding a sales opportunity appears to refer to a company that is listed as a competitor in your system.<br>**Actions**:<br>Add Competitor<br>Always Add<br>**Configuration options**:<br>Set this feature to add the competitor automatically rather than showing the card.<br>**Note**: This is the same as the configuration setting available for this card type, and you can reset it by going to your Assistant settings. To learn more, see [Assistant](assistant.md). |
| <a name="MeetingRequested"></a>**Meeting requested**<br />![Insight card for meeting request](media/ActionCard_MeetingRequest.png "Insight card for meeting request") | Standard |**Description**: <br>An email from a known contact in your inbox appears to include a meeting request.<br>**Features**:<br>Shows the name of the contact.<br>Tells you that a meeting request has arrived.<br>Displays the sentence from the email that appears to be asking for a meeting.<br>**Actions**:<br>Create Meeting<br>Open Email |
| <a name="FileRequested"></a>**File requested**<br />![Insight card for file request](media/ActionCard_FileRequest.png "Insight card for file request") | Standard | **Description**: <br>An email from a known contact in your inbox appears to include a request for a file.<br>**Features**:<br>Shows the name of the contact.<br>Tells you that a request for a file has arrived.<br>Displays the sentence from the email that appears to be asking for a file.<br>**Actions**:<br>Open Email |
| <a name="BuyingIntentDetectedEmail"></a>**Buying intent detected in email**<br />![Insight card for potential lead or upsell](media/ActionCard_BuyingIntentDetectedEmail.png "Insight card for potential lead or upsell") |  Standard | **Description**: <br>An email received from a known or unknown contact requesting more information about a product. For known contacts, this may be an upsell opportunity. For unknown contacts, this could be a new lead.<br>**Features**:<br>Shows the name of the sender.<br>Tells you that an email has arrived that may represent an upsell or new-lead opportunity.<br>Displays the sentence from the email that is requesting more information about a product.<br>**Actions**:<br>Open email |
| <a name="SuggestedStakeholder"></a>**Suggested stakeholder** <br/>![Insight card for recommended stakeholder](media/ActionCard_RecommendedStakeholder.png "Insight card for recommended stakeholder") |  Standard | **Description**: <br> An email regarding an open opportunity has arrived, and it includes an extra recipient that isn't yet listed as a stakeholder for that opportunity.<br>**Features**:<br>Shows the name of the potential stakeholder.<br>Tells you that this person might be a stakeholder in an open opportunity.<br>Displays a short description that includes the name of the opportunity.<br>**Actions**:<br>Add Stakeholder<br>Always Add<br>**Configuration options**:<br>You can choose to add the stakeholder automatically rather than show the card.<br>**Note**: This  is the same as the configuration setting available for this card type, and you can reset it by going to your Assistant settings. To learn more, see [Assistant](assistant.md).|
| <a name="RelationshipAnalytics"></a>**Relationship analytics** <br/> ![Relationship analytics](media/ActionCard_RelationshipAnalytics.png "Insight card for relationship analytics") |  Premium | **Description**: <br>This card is provided as an alert when you have an opportunity that is similar to deals that were won recently.<br>**Feature**:<br>Indicates that the current opportunity is similar to the opportunities that had been previously won. <br>**Actions**: <br>Open opportunity <br> By selecting the action, you can view comparable information on the KPIs, graphs, activity history, and relationship health with similar deals that had been won. <br>**Prerequisite**: <br> Enable preview to view similar opportunities in Relationship analytics to use this card. To learn more, see [Configure Relationship analytics](configure-relationship-analytics.md). <br> You must purchase a Sales Insights license.|
| <a name="ContactMovedToNewOrg"></a>**Contact is no longer with the company** <br/> ![Contact left the company](media/ActionCard_ContactMovedToNewOrg.png "Insight card for contact left the company") | Premium | **Description**: Tells you that one of your contacts has left the company based on the information LinkedIn has.<br>**Actions**:<br>Open – Opens the contact record<br> **Prerequisite**:<br>Users should have a **LinkedIn Sales Navigator** license to use this card. To learn more, see [Install, enable, and disable default LinkedIn Sales Navigator controls](/dynamics365/linkedin/install-sales-navigator).|
| <a name="TodaysTopPeople"></a>**Today's Top People** <br />![Insight card for top people today](media/ActionCard_TopPeople.png "Insight card for top people today") | Standard | **Description**: <br>The system analyzes your appointments, tasks, and other work for the day and generates this card to show the contacts you're most likely to interact with today.<br>**Features**:<br>Shows each contact's name and portrait.<br>Shows each contact's title and any business they have with you today (such as a meeting, task, or phone call).<br>Click to view full contact details. |
| <a name="TodaysTopRecords"></a>**Today's Top Records**<br />![Insight card for top records today](media/ActionCard_TopRecords.png "Insight card for top records today") | Standard |**Description**:<br> The system analyzes all of the Sales records that are related to you and lists the records that you're most likely to be working with today based on your recent activities and date information (such as a due date or appointment) in each record.<br>**Features**:<br> Shows a thumbnail image and a summary of each found record.<br>Click to view the full record. |
| <a name="UpcomingFlight"></a>**Upcoming Flight** <br />  ![flight](media/ActionCard_Flight.png "Insight card for upcoming flight") | Standard | **Description**: <br>This card is generated when your Exchange inbox includes an email message that contains a flight confirmation. The system then matches the flight dates to upcoming meetings and finds other information related to the location that you're flying to, such as other nearby customers.<br>**Note**: This card doesn't show live or updated flight information, just information from the flight confirmation email message that triggered the card.<br>**Features**: <br>Flight company and flight number, with a link to the flight record.<br>Departure and arrival times, with airport codes.<br>Related meeting record, with link. Up to three meetings may be listed here.<br>List of customer offices near the destination airport, with links. <br>**Actions**:<br>Open Email |

## Related information

[Use the assistant to guide customer communications](use-assistant-guide-customer-communications.md)  
[Turn on or off the insight cards](turn-on-off-insight-cards.md)

