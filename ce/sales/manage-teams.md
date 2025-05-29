---
title: "Create or manage teams in Dynamics 365 Sales | MicrosoftDocs"
description: "Create a team with a group of users so they can share and collaborate on business records in Dynamics 365 Sales."
ms.date: 01/28/2025
ms.topic: how-to
author: lavanyakr01
ms.author: lavanyakr
ms.reviewer: lavanyakr
ms.custom: 
  - "dyn365-sales"
---

# Create or manage teams

A team is a group of users who share and collaborate on business records. A user can be associated with multiple teams.

## Create a team

Depending on the Dynamics 365 Sales license you have, select one of the following tabs for specific information:

# [Sales Premium or Sales Enterprise](#tab/sales)

Follow the instructions in [Microsoft Dataverse teams management](/power-platform/admin/manage-teams) to create and manage teams.

# [Sales Professional](#tab/salespro)

**To create a team**:

1.  In the site map, select **Sales settings**.

2.  Under **Advanced settings**, select **Team management**.

3.  Select **Create a team**.

4.  In the **Add New Team** pane, enter the following details, and then select **Add**.

    -   **Team Name**: Name of the team.

    -   **Business Unit Name**: This defaults to your organization name.

    -   **Team Description**: Enter a description of what the team has been created for.

    -   **Select Team Administrator**: Select the person who will do the team administration, such as adding members to or removing members from the team.

      :::image type="content" source="media/add-new-team-dialog-box.png" alt-text="Add New Team pane":::

### Add members to the team

1. On the **Team management** page, select the team you want to add members to.

2. In the **Team members** section, select **Add Existing User**.

3. In the **Lookup Records** panel, search for and select the required members, and then select **Add**.

### Remove members from the team

1. On the **Team Management** page, select the team you want to remove the members from.

2. In the **Team members** section, select the members you want to remove, and then select **Remove**.

### Manage security roles

When a team is assigned a role, the team members are assigned the set of privileges associated with that role.

1. In your app, select **Settings** ![Settings.](media/settings-icon.png), and then select **Advanced Settings**.

2. Select **Settings** > **Security** > **Teams**.

3.  Select a team you want to assign a role to, and then on the command bar, select **Manage security roles**.

4.  In the **Manage security roles** pane, select the security role you want for the team, and then select **Save**.

---

[!INCLUDE [cant-find-option](../includes/cant-find-option.md)]


## Related information

[Admin settings overview](admin-settings-overview.md)


[!INCLUDE[footer-include](../includes/footer-banner.md)]

