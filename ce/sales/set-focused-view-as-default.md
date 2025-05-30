---
title: Configure focused view
description: Configure focused view manually for entities other than contact, account, lead, and opportunity and set it as the default view for any entity and allow a record automatically refresh when updated.
author: udaykirang
ms.author: udag
ms.reviewer: udag
ms.topic: how-to 
ms.date: 01/31/2025
ms.custom: bap-template 
---

# Configure focused view

In focused view, sellers can view and manage their CRM records and their associated activities on one page. This view makes it easier for sellers to stay focused on their tasks, saving time by eliminating the need to navigate through multiple screens. It also allows sellers to better organize and prioritize their tasks.

> [!NOTE]
>
> - Focused view is now available for the **Activities** entity. However, you must [opt in for early access features](/power-platform/admin/opt-in-early-access-updates).  
> - Focused view is not available for the **Queue** entity.

Configuring the focused view as default is allowed only for the contact, lead, account, and opportunity entities. Also, if you want to configure focused view as default for custom and other entities, see [Configure as default for other entities](#configure-as-default-for-other-entities).

Also, you can configure to automatically refresh a record at specified time intervals when it is updated. For more information, see [Automatically refresh records](#refresh-records-automatically)

## Prerequisites

- You must have the **System Administrator** or similar security role to perform these configurations.  
- Ensure that the [focused view is enabled for your organization](enable-focused-view.md).  

## Configure as default for contact, account, lead, and opportunity entities

> [!NOTE]
> To view the **Default view** option, ensure that you have opted in for [early access features](/power-platform/admin/opt-in-early-access-updates).

By default, focused view is enabled for the lead entity. However, to improve the experience and eliminate the need for manual switching to the focused view, you can configure focused view as the default view for contact, account, and opportunity entities for all users. 

To configure focused view as default, follow these steps:

1. Open the contact, lead, account, or opportunity grid.  
1. Change to focused view and in the work item section, select **More options** > **Settings**.
1. On the **Settings** pane, select **Default view**.

    :::image type="content" source="media/fv-settings-set-as-default.png" alt-text="Screenshot of configuring focused view as default.":::

1. Turn on the toggle to enable focused view as default for the required entities.  
1. Save and close the settings pane.

   Focused view is now set as the default view for the selected entities.  

## Configure as default for other entities

To configure and enable focused view as default for custom and other entities, follow these steps:

1. In the sales app, go to **Settings** > **Advanced Settings**.  

    :::image type="content" source="media/advanced-settings-option.png" alt-text="Screenshot of the Advanced Settings option on the Settings menu.":::

1. Go to **Customization** > **Customizations** > **Customize the System**.  
1. In the left pane, expand **Tables** and then the entity you want, and select **Forms**.  

    >[!NOTE]
    >If you are using the classic view, under **Components**, expand **Entities**, and then the entity you want, and select **Forms**. Go to the **Controls** tab and then add **Focused view**.

1. Open the entity form of type **Main** and then select **Components** on the tool bar.

1. In the **Components** section, search for **Focused view** and then drag it to the desired location on the form.  

    >[!NOTE]
    >If you don't see the **Focused view** control in the **Components** section, select **Get more components** to add it.

1. In the **Add focused view** dialog box, configure the following properties:  
    - **Table**: Select the entity for which you want to configure focused view as default.  
    - **View**: Select the view that you want to set as default.  

1. Select **Done**.  
1. Save and publish the configurations.  

Focused view is now set as the default view for the selected entity.

## Refresh records automatically

Records aren't updated automatically in focused view. However, you can configure focused view to automatically refresh records at specified time intervals. To configure automatic refresh for a record, follow these steps:

1. Open the contact, lead, account, or opportunity grid.  
1. Change to focused view and in the work item section, select **More options** > **Settings**.
1. On the **Settings** pane, select **Auto-refresh**.

    :::image type="content" source="media/fv-settings-enable-auto-refresh.png" alt-text="Screenshot of configuring focused view to auto refresh a record when updated.":::  
1. Turn on the **Auto-refresh** toggle to enable automatic refresh of the grid.
1. Select the time interval for the records in the view to refresh. The time interval can be set to 15, 18, or 20 minutes.
1. Save and close the **Settings** pane.

Records will now automatically refresh at the specified time interval.

## Related information

[View and manage records in focused view](focused-view.md)  
[Focused view FAQs](faq-focused-view.md)

