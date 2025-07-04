---
title: Customize the side panel to view record details during a meeting
description: Learn how to customize the side panel to view record details during a meeting.
ms.date: 06/26/2025
ms.topic: how-to
ms.service: dynamics-365-sales
author: sbmjais
ms.author: shjais
ms.reviewer: shjais 
---

# Customize record details in the side panel (preview)

[!INCLUDE [cc-beta-prerelease-disclaimer](../../includes/cc-beta-prerelease-disclaimer.md)]

[!INCLUDE [preview-disclaimer](../../includes/preview-disclaimer.md)]

Sellers can use the side panel to quickly view and update details of a record during a Teams meeting. It displays notes, tasks, and activities associated with the record.

## Customize the record side panel

As an administrator, you can customize record details that should be displayed within the side panel to meet the needs of your users.

> [!NOTE]
> - To customize record details in the side panel, edit a table's **In Context Form** form. 
> - The side panel supports the Contact, Opportunity, Lead, Account, and Case tables.

The following customizations are supported:

- Add or remove fields in the **(table) info** section.
- Change a field label.
- Set a field requirement (for example, read-only).

The following customizations are not supported:

- Enable or disable tabs.
- Rearrange tabs.
- Add custom tabs or sections.
- Add sections other than (table) info, Contacts, Notes, Tasks, Collaboration, and Recent Opportunities.
- Add a web resource.
- Add a subgrid.
- Change the format or layout of headers, tabs, sections, and fields.
- Change certain properties of headers, tabs, sections, and fields.

**To customize record details in the side panel:**

1. Sign in to Power Apps.

2. Select the environment, and then select **Tables** > **All**.

    :::image type="content" source="./media/tmi-select-all-tables.png" alt-text="Select all tables.":::
    
3. Search for and select the table.

4. Select the **Forms** tab, and then select the **In Context Form** form.

5. Edit the form to choose the fields you want to show in the side panel.

    By default, all the fields in the form are editable. To make a field read-only, select it and turn on the **Read-only** property.

## Related information

[Enable Microsoft Teams meeting integration](enable-teams-meeting-integration.md)    
[Integrate Dynamics 365 and Microsoft Teams meetings](teams-meeting-integration.md)
