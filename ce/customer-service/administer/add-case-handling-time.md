---
title: Add case handling time widget to case forms 
description: Learn how to enable and configure the case handling time widget, which shows the total time customer service representatives spend on a case.
author: gandhamm 
ms.author: mgandham
ms.reviewer: mgandham
ms.topic: how-to 
ms.date: 06/10/2025 
ms.custom: bap-template 
---

# Configure case handling time widget to case forms 

Case handling time is the total time customer service representatives (service representatives or representatives) actively work on a case. It includes activities such as communicating  with customers, troubleshooting, researching, collaborating, or updating case details, like adding notes.

> [!NOTE]
> - Case handling time is supported in both custom and out-of-the-box single session apps, and out-of-the-box multisession apps only, such as Copilot Service workspace.
> - Case handling time and case resolution time are different. For example, a representative works actively on a case for 5 hours. The case is resolved 5 days after it was created. Here, the case handling time is 5 hours, and the case resolution time is 5 days.

## Enable case handling time widget

To display the case handling time widget on a case form, follow these steps:

1. In Copilot Service admin center, select **Customer Support** > **Case settings**.
1. On the **Case settings** page, select **Manage** for **Case handling time**. The **Case handling time** page opens.
1. Select the **Enable case handling time** check box.
1. Select the Power Apps link. The application shows the [**Solutions**](/power-apps/maker/data-platform/solutions-overview#work-with-solutions-in-power-apps) page. 
1. In Power Apps, select the solution that contains your custom case form and then select **Tables**.
1. In the **Tables** page, select **Case** and then select **forms**.
1. Select the required form and [add the **Handling time** component](/power-apps/maker/model-driven-apps/add-move-configure-or-delete-components-on-form#add-components-for-a-column-on-the-form) to the form. The widget always appears on the bottom right of the case form at runtime, regardless of where you add it on the form. We recommend that you add it in an existing section within the viewport. During runtime, you will see a blank space where you added the component to the form.
1.  Configure these properties for the component:

      - **Table**: Set this value to **Time Trackers**.
      - **View**: Set this value to **All Time Trackers**.
      - **Allow users to add time logs**: Set this value to **True** or **False**, depending on whether you want representatives to manually add time on the case. The default is **True**.
      - **Show users only their contributed time**: Set this value to **True** or **False**, depending on whether you want representatives to see only their own time or the total time of all representatives on the case. The default is **False**.
      - **Make CHT widget visible to users**: Set this value to **False** to hide the time tracking widget from representatives. However, the application still tracks time in the background. The default is **True**. 
    1. Select **Show related records**.
    > [!NOTE]
    >  - In Copilot Service workspace, the application tracks the time automatically in the background whenever a representative opens the case and the case form is in focus, even if you don't add the widget to the case form. You can create reports on automatic time tracked per representative for each case.
    > - In Customer Service Hub, you must add the widget to the case form for automatic time to be tracked.
  1. Save and publish the changes.

You can also view the time tracker records in the [msdyn_timetracker](../../developer/reference/entities/msdyn_timetracker.md) table.

## Set the update interval

The update interval is the time between each update of the database and the widget with the automatic tracked time. You can set a value between 10 and 60 min. The default value is 10 min. When you specify a time for the update interval, the application performs the following actions:

- Updates the database with the automatic tracked time in the frequency specified.
- Automatically refreshes the case handling time widget to display the updated time.

For example, if you set 10 min as the update interval, the automatic time tracked on the case is updated to the database and the widget after every 10 min. If two representatives open the same case at the same time, after 10 min, the widget displays 20 mins as the total time tracked on the case.

## Enable case handling time for service representatives

For service representatives to see the case handling time widget on the case form, you must enable the **Case handling time** feature in **Experience profiles**. 

Perform the following steps:

1. In Copilot Service admin center, select **Workspaces** in **Support experience**. The **Workspaces** page appears.
1. Select **Manage** for **Experience profiles**. The **Experience profiles** page appears.
1. Select the required experience profile. 
1. In the **Case Handling Time** section, select **Edit**.
1. Select the **Enable case handling time** checkbox.
1. Select **Save and close**.

> [!NOTE]
> When the **Enable case handling time** checkbox is selected, the service representative sees the case handling widget on the case form even if the **Case handling time** feature isn't enabled in **Case settings**.

## Delete time tracker records

 Automatic time tracker records for each representative for every case are stored in the database according to the update frequency that you set. These records can take up a lot of space over time. To save storage space in the database, you can delete the time tracker records for old resolved cases. Perform the following steps to delete the records:
   1. Select the **Time tracker list** link to view the list of time tracker records.
   1. Select the  required records and then select the **Delete** icon to delete the time tracker records.

> [!NOTE]
> - If you plan to use these records for building reports, we recommend that you don't delete them.
> - When using the legacy case resolution dialog (Standard dialog), the total time displayed may differ from the **Total Time** shown on the widget. This is because the legacy dialog's **Total Time** is based on case activities only. To use the total time from the widget, switch to either Customizable or Quick Create case resolution dialog and include the **Total Time** attribute from Case Handling Time (Time Tracker) table.


### Related information  

[Track your time on cases](../use/case-handling-time.md)
