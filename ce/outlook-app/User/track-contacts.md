---
title: "Track your Outlook contacts using App for Outlook (Dynamics 365 apps) | MicrosoftDocs"
description: Track your Outlook contacts using App for Outlook.
ms.custom: 
ms.date: 07/11/2025
ms.reviewer: smurkute
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: how-to
applies_to: Dynamics 365 apps
caps.latest.revision: 1
author: bharavar 
ms.author: bharavar 
search.audienceType: 
  - admin
  - customizer
  - enduser
---

# Track contacts

> [!NOTE]
> Starting October 1, 2025, the contact tracking feature in the Dynamics 365 App for Outlook isn't supported in the classic Outlook app. As an alternative, to track contacts, add them to Dynamics 365 Sales manually. Contact tracking isn't available in the new Outlook app. More information: [Deprecation of support for the contact tracking feature](/power-platform/important-changes-coming)

Access your Outlook contacts and Dynamics 365 contacts and see which contacts are tracked. You can also link an Outlook contact to an account in your Dynamics 365 app.

You admin must enable your Dynamics 365 mailbox for appointments, contacts, and tasks to use the track contacts feature. 


   > [!div class="mx-imgBorder"] 
   > ![Viw your contacts.](../media/all-contacts.png)  
 
Legend
1. **Outlook Contacts**: View all your Outlook contacts. The same contacts are displayed in the default contacts view your Dynamics 365 app.
2. **Dynamics 365 Contacts**: View all your Dynamics 365 app contacts.
3. **Tracked**: See whether a contact is tracked or not, or whether the tracking status is pending.
4. **Company**: If the contact is tracked, select to open the row in your app.
5. **Search**: Switch to the **Dynamics 365 Contacts** tab on the top of screen to view the list of all of your active contacts in the Dynamics 365 app. You can search for data stored in the full name, title, department, and business address field. You can’t search for data stored in any of the other fields such as business phone, account, or email. You also can't search for data within the tracking status, business phone, or email field.

## Access contacts

To access your contacts, from the Outlook navigation pane, select More ![Outlook navigation options.](../media/outlook-nav-options.png) and then select **Add-ins**.

   > [!div class="mx-imgBorder"] 
   > ![Select add-in.](../media/access-add-in.png)  


### View contact card

In the contacts list, select **Dynamics 365 Contacts** and then select the checkbox next to a contact's name. The contact details appear on the right side of the screen.

   > [!div class="mx-imgBorder"] 
   > ![View contact details.](../media/view-contact-details.png)  


## Link Outlook contacts to an account 

You can link and track a single or multiple contacts from Outlook to an account row in your Dynamics 365 app. 

   > [!div class="mx-imgBorder"] 
   > ![Demo of how to link a Outlook contact to a row in your app.](../media/link-outlook-contact-3.gif) 

Depending on the server-side synchronization filters, the active contacts that a user owns in the Dynamics 365 app should be synchronized with Outlook after the mailbox is configured. For more information, see [Choose the records to synchronize between customer engagement apps and Exchange](/power-platform/admin/choose-records-synchronize-dynamics-365-outlook-exchange),

Follow the steps below to link and track your Outlook contacts to a row in your app.

1. From the **Outlook Contacts** tab, select a contact(s) that is not already tracked.
2. On the command bar, select **Link**.
 
   > [!div class="mx-imgBorder"] 
   > ![Link an Outlook contact.](../media/link-outlook-contact.png) 
 
3. Choose the account row that you want to link the contact(s) with and then select elect **Link**.

   > [!div class="mx-imgBorder"] 
   > ![Choose a contact in your app to link to.](../media/link-outlook-contact-2.png) 

4.  To avoid issues, until the linking is complete before you navigate away from the page. 

## Track Outlook contacts without linking to an account

You can track a single or multiple contacts from Outlook in your Dynamics 365 app without linking it to an account row.

1. From the **Outlook Contacts** tab, select a contact(s) that is not already tracked.
2. On the command bar, select **Track**.

   > [!div class="mx-imgBorder"] 
   > ![Demo of how to track a Outlook contact in your app.](../media/track-without-linking.gif) 
   
3. To avoid issues, until the tracking is complete before you navigate away from the page. 

## Untrack a contact

You can also untrack a contact and choose to delete the contact's information from your Dynamics 365 app or keep the row by stop tracking it.

1. From the **Outlook Contacts** tab, select a contact(s) that you want to stop tracking
2. On the command bar, select **Untrack**.
3. Then select one of the following:
    - **Untrack & Delete**: Delete the contact row from your app.
    - **Untrack & Keep**: Keep the contact row in your app but stop tracking it.

   > [!div class="mx-imgBorder"] 
   > ![Untrack a contact.](../media/untrack-contact.png) 

## Change views

Use the **Dynamics 365 Contacts** tab, to access the same contact views that you see in your Dynamics 365 app. However, if one of these views includes a column from a related table, then that view won't be displayed.

- From the **Dynamics 365 Contacts** tab, select down arrow and then select a view.

   > [!div class="mx-imgBorder"] 
   > ![Change view.](../media/change-contact-view.png) 


## Filter contacts

You can easily see which contacts are tracked or untracked.

- From the **Outlook Contacts** tab, select down arrow and then select a filter.

   > [!div class="mx-imgBorder"] 
   > ![Filter contacts view.](../media/filter-contacts.png) 


## FAQs

1. When I search in a view, why does it only return 5,000 rows? This current limit is 5,000 when you search a view from in Dynamics 365 App for Outlook.
2. Why can't I track contacts using Outlook on the web? You need Outlook 2016 or later to use the contact tracking feature.
3. What happens when a contact is deleted from the Dynamics 365 app?  If you're not the owner of the contact row, then deleting a contact from Dynamics 365 deletes the tracked contact from Outlook. If you're the owner of the contact row, deleting a contact from your Dynamics 365 does not delete the contact from Outlook.
4. What happens when a contact is deleted from Outlook? Deleting a tracked contact in Outlook doesn't delete the contact row from your Dynamics 365 app. Regardless of ownership of the contact row, if you have delete permissions for the contact and you stop tracking the contact, App for Outlook will ask whether you want to delete the contact row from  your Dynamics 365 app.





