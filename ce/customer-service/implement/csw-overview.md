---
title: Overview of the Copilot Service workspace application for Dynamics 365 Customer Service
description: Overview of Copilot Service workspace for Dynamics 365 Customer Service.
ms.date: 06/30/2025
ms.topic: overview
author: gandhamm
ms.author: mgandham
ms.reviewer: mgandham
search.audienceType: 
  - admin
  - customizer
  - enduser
ms.custom: 
  - dyn365-customerservice
ms.collection: get-started
---

# Get started with Copilot Service workspace

Copilot Service workspace helps customer service representatives (service representatives or representatives) increase productivity with a browser-like, tabbed experience. Service representatives can use the app to work on multiple cases and conversations. It's a modern, customizable, high-productivity application that allows them to work on multiple sessions at a time in a single workspace.

The application uses artificial intelligence in productivity tools like Smart Assist to identify similar cases and relevant articles, thereby boosting representative productivity. Features such as scripts and macros provide representatives with guidance and resources to automate repetitive tasks to achieve a great customer experience.

Learn more about licensing and system requirements in [Copilot Service workspace system requirements](customer-service-workspace-system-requirements.md).

**Set up Omnichannel in Copilot Service workspace** 

With the Dynamics 365 Customer Service Digital Messaging add-on, the representative who work on cases can also engage with customers via channels like Live Chat, voice, and SMS without leaving the Copilot Service workspace app. Learn more in [Set up Omnichannel for Customer Service channels in Copilot Service workspace](/dynamics365/app-profile-manager/csw-enable-channels).

:::image type="content" source="../media/csw-default-overview.png" alt-text="Screenshot of the enhanced multisession Copilot Service workspace":::

## Copilot Service workspace sessions and tabs

Copilot Service workspace allows representatives to work on multiple sessions at a time in a single app while keeping the work organized.
- Representatives can work on up to nine sessions and within a session, they can open up to 10 tabs.
- A new session starts when a representative opens a case from the **Home** session or accepts an incoming conversation.
- If the representative opens the customer record from a session, a new tab opens in the same session. 
- Representatives can select the hamburger icon to access the site map. 
- When a representative opens a page from the site map, the page loads in the current focused session.

### Navigate sessions and tabs

 The following table gives an overview of the multisession navigation:

| Action | Result |
| ------ | ------ |
| Open a record from the Home session | Record opens in a new session. |
| Open a record from the Global search | Record opens in a new session. |
| Open a record from the retrieved search records | Record opens in a focused session. |
| Open a record using the Quick Create notification | Record opens in a new session. |
| Create a new record | Record opens in a new session. |
| Open a record from the timeline | Record opens in a new tab in the focused session. |
| Open a record from a form lookup | Record opens in a new tab in the focused session. |
| Open a view from the site map | View opens in a new tab in the focused session. |
| Open a dashboard from the site map | Dashboard opens in a new tab in the focused session. |
| Expand **Recent** in the site map | You can see records and views opened from the **anchor** tab only. |


### Session restore (preview)

If your administrator turned on session restore, key entities in Copilot Service workspace reload automatically if your browser refreshes. Without session restore, when a browser refreshes or reconnects, Copilot Service workspace reloads only the home page. 

Session restore automatically restores cases, accounts, and their associated application tabs without requiring you to manually reopen them. Focus is restored to the last session or application tab in view. After the presence is loaded, conversations, including calls and chats, are reinstated. 

Learn more in [Enable session restore to automatically reopen sessions and tabs (preview)](../administer/enable-session-restore.md).


### Use the Inbox

If your administrator turned on the inbox for your profile, you can select the **Inbox** tab to view all the cases, conversations, and activities that are assigned to you. Use the inbox to work on high-velocity tasks. You can also promote inbox sessions to regular sessions when you need more time to resolve a case or complete a conversation.

The asynchronous channels available in the conversation inbox are: 
- SMS
- persistent chat
- Facebook
- WeChat
- LINE
- WhatsApp
- Microsoft Teams

Learn more in [Configure the inbox view](../administer/configure-inbox.md).

### Use the productivity pane with Smart Assist

When you work on a case, the productivity pane on the right side of the Copilot Service workspace displays intelligence-driven suggestions to help you. The productivity pane uses Smart Assist to suggest related cases and knowledge articles that might be relevant to the case you're working on. There are also scripts that guide you through a consistent series of steps with potentially automated actions through macros.

Learn more in [Productivity pane](../use/../use/csw-productivity-pane.md).

## Work with cases, activities, knowledge articles, and email templates

On the Customer Service Representative Dashboard, here are some of the actions you can do:

- View cases and activities assigned to you
- View cases available to work on
- Create, delete, and filter cases and activities from the workspace

### Customize the representative experience with Copilot Service admin center

Experience profiles enable you to create targeted app experiences for representatives and supervisors, and are an alternative to building and maintaining custom apps. With the experience profiles, administrators can create custom profiles with specific session templates, conversation channels, and productivity tools. These profiles can then be assigned to users.

Learn more in [Experience profiles](../administer/overview.md).

## Considerations

Here are a few things to note when you use Copilot Service workspace in your organization:

- We recommend that you have only one browser instance accessing the app.
- `XRM.Navigation.openForm` and `Xrm.Navigation.navigateTo` APIs have a similar navigation as the multisession app. For example:
  - A new session is initiated if you open a form through `XRM.Navigation.openForm` from Home.
  - A new tab in the focused session is initiated if you open a form through `XRM.Navigation.openForm` from a case session.
- Opening a WebResource through `Xrm.Navigation.openWebResource` opens a new browser window but doesn't remove the navigation and command bars. You can programmatically open web resources as session tabs using the `Microsoft.Apm.createTab` method. Learn more in [createTab method](../develop/reference/methods/createTab.md).
- You can open sessions and tabs using Microsoft.Apm APIs. Learn more in [App profile manager JavaScript API Reference](../develop/microsoft-apm.md).
- The multisession capabilities are supported in the Copilot Service workspace and Omnichannel for Customer Service apps only. You won't be able to navigate across multiple sessions in a custom app or a copy of the Copilot Service workspace app in your environment.

### Limitations

The following limitations apply to Copilot Service workspace:
- When you switch between tabs or sessions:
  - Subgrid controls don't retain the filter or sort conditions.
  - Web resources, form components, custom pages, and third-party websites don't retain the state of the page. For example, form components might retain unsaved values for text fields but not for lookup fields.
  - When you change the status record in a tab, the corresponding record that's open in a grid or subgrid of another tab doesn't refresh automatically.
- Copilot Service workspace isn't supported in mobile devices, Unified Service Desk, Microsoft Teams, and with Dynamics 365 Customer Engagement (on-premises).

## Deprecated Customer Service workspace layout

The legacy layout is deprecated and was removed in October 2023.

:::image type="content" source="../media/csw-overview-mini.png" alt-text="Screenshot of the default Copilot Service workspace, with items labeled according to the legend in the table" lightbox="../media/csw-overview.png":::


### Turn off the close session dialog

1. With Copilot Service workspace open, press the F12 key to open the developer tools window.
1. In the console window, enter the following command: `Xrm.Utility.getGlobalContext().saveSettingValue("msdyn_SuppressSessionCloseWarning",true)`
1. Refresh the app page.


### Training resources

Download the [Copilot Service workspace in a day training](https://go.microsoft.com/fwlink/?linkid=2241180). This training provides an overview of the following topics:

  * Get familiar with sessions, tabs, and productivity tools.
  * How to create experience profiles, templates, scripts, and macros.
  * How to assign experience profile based on security roles.
  * How to move experience profiles via solutions.
  * How to use multisession APIs (Microsoft.Apm).

[Migrate from Unified Service Desk to Copilot Service workspace](../../unified-service-desk/admin/migrate-to-csw.md). The Unified Service Desk to Copilot Service workspace Migration Playbook helps you plan and execute the transition from Unified Service Desk to Copilot Service workspace.

### Related information

[Work with cases in Customer Service Hub](../use/customer-service-hub-user-guide-create-a-case.md)  
[Overview of the productivity pane](../use/csw-productivity-pane.md)  
[View the agent calendar](../use/use-agent-calendar.md)  

[!INCLUDE[footer-include](../../includes/footer-banner.md)]
