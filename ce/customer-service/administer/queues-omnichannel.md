---
title: Create and manage queues for unified routing
description: Create and manage advanced queues, know how fallback and default queues work in unified routing in Customer Service.
author: neeranelli
ms.author: nenellim
ms.reviewer: nenellim
ms.topic: how-to
ms.date: 05/27/2025
ms.custom: bap-template
ms.collection:
searchScope:
- D365-App-customerservice
- D365-Entity-queueitem
- D365-UI-*
- Customer Engagement
- Dynamics 365
- Customer Service
---

# Create and manage queues for unified routing

[!INCLUDE[cc-feature-availability-embedded-yes](../../includes/cc-feature-availability-embedded-yes.md)]

Queues are used to collect and distribute workload among customer service representatives (service representatives or representatives). Workload includes records such as cases, and conversations such as chat or SMS. Service representatives are added as members to the queues and the workload is distributed among them based on assignment methods.

## How work items are routed to queues

You can create separate queues for each line of business such as billing, investment, and products. When a customer query is raised for any of the areas, it's routed to the corresponding designated queue based on how you define route to queues in the classification. You can also set up a customer support availability matrix by using a combination of queues, operating hour schedules, and routing rules.

In an enterprise scenario, you can have various supervisors handling different issues, and therefore, different types of queues are required to handle the various scenarios. Accordingly, routing rules are set up based on the complexity of issues that need to be handled.

To simplify the routing experience for administrators and supervisors, queues are categorized based on the channel types as follows:

- **Messaging**: To route all messaging conversations pertaining to the live chat, SMS, and social channels.
- **Records**: To route work items pertaining to records, such as cases and emails.
- **Voice**: To route calls made to support phone numbers listed on the customer portal.

The queue types allow issues to be routed correctly and help avoid cross-queue assignments. When you configure workstreams and routing rule items, the queues that are available for selection are based on the channel type for the workstream. For example, for routing rules for a live chat workstream, only messaging type queues are shown for selection. Similarly, you can transfer a chat conversation only to a messaging queue, and a case only to a record queue.

## Create a queue for unified routing

1. In the site map of Copilot Service admin center, select **Queues** in **Customer support**.
    
1. On the **Queues** page, select **Manage** for **Advanced queues**.
    
1. On the **Queues** page, do the following steps:

    1. Select **New**.
    1. In the **Create a queue** dialog, enter the following details:
       - **Name**: A name for the queue.
       - **Type**: Select **Messaging**, **Record**, or **Voice**.
       - **Queue priority**: A number to [prioritize the queue](#configure-queue-prioritization).
    1. Select **Create**. The queue that you created is displayed.

       :::image type="content" source="../media/queue-summary-ur.png" alt-text="A screenshot of an advanced queue in admin center.":::


1. Select **Add users**, and in the flyout menu, select the users who should be part of the queue, and then select **Add**. The users are added to the queue.

1. In **Assignment method**, select any of the following options:
   - **Highest capacity**: Assigns a work item to a service representative with the highest available capacity. The representative has skills identified during the classification stage and presence that matches one of the allowed presences in the workstream.
   - **Advanced round robin**: Assigns a work item to the representative who matches the criteria for skills, presence, and capacity. The initial order is based on when a user is added to the queue. Then, the order is updated based on assignments.
   - **Least active**: Assigns a work item to the representative who has been least active among all those who match skills, presence, and capacity.
   - **Create new**: Lets you create a custom assignment method. The custom assignment method lets you use your own rulesets and rules to configure priority, severity, and capacity for choosing the queues to which work items need to be routed by setting up the rulesets for prioritization and assignment. Learn more about the custom assignment method in [Create custom assignment method](assignment-methods.md).

1. To manage overflow of queues, in **Overflow management**, select **Set overflow conditions**, and perform the steps described in [Manage overflow of queues](manage-overflow.md).

1. To set the operating hours, in **Operation hours**, select **Set operation hours**. If you don't set operation hours, the queue is considered to be available round the clock. You must configure the operating hour record before you can set it for the queue. Learn more in [Configure operating hour record](create-operating-hours.md).

1. On the **Set operation hours** dialog that appears, select an operating hour record in the **Name** list.

1. Select **Save and close**. The operating hour record that you selected is configured for the queue.

## Configure queue prioritization

You can assign a priority to the queue that helps you prioritize assignment of work. Queues are ordered from highest to lowest priority when work items are assigned. Unified routing prioritizes a queue with a smaller number over a queue with a larger number. For example, if you need to prioritize conversations over cases, you can assign queue priority numbers to the corresponding queues accordingly. For the queues that handle conversations, you can assign a number 1 and for the queues that handle cases, you can assign 2 as the priority number. Similarly, you can prioritize one type of work over another. Assign priority number 1 to the queue with premium customer chats for higher priority and priority number 2 to the queue that handles general customer questions to give it lower priority. Learn more in [How unified routing prioritizes work items](assignment-methods.md#how-unified-routing-prioritizes-work-items).

### Manage queues for unified routing

You can manage queues on the **Queues** page, and perform operations such as search, edit, copy, and delete the queues.

- Select a queue to edit the users, assignment methods, or operating hour record.

- Select a queue on the **Queues** page, select **Copy** on the command menu, and then select **Copy** in the *<queue_name>* dialog. The queue is copied and inherits the settings of the queue you copied from, including its name, prefixed with **Copy of**.
- Select a queue and then select **Share** to share with users or teams in your organization. In the **Share records** dialog that appears, select the users or teams. You can also set the permissions for each user or team. When you share a record permission, it doesn't automatically grant privileges to all the records of the related tables. You need to create a custom plugin to set permissions for the related tables listed for the queue when you set permissions for the parent table record.

> [!IMPORTANT]
> If unified routing is enabled, make sure that the **Queue** form, which is the default form, exists and hasn't been removed through customization. Otherwise, you aren't able to create a basic queue in Customer Service Hub.

### How fallback queues work

To efficiently manage the work items, you can configure a fallback queue per workstream that acts as a safety net. You can set an existing queue as the fallback queue or create a fallback queue with the required settings when you're creating a workstream.

For existing workstreams, you can configure the fallback queue on the workstream page. If you choose to create a queue, you need to add users. By default, the assignment method for the fallback queue is highest capacity.

If any overflow settings exist, they are overruled and work items are routed to the fallback queues in the following scenarios:

- Work item encounters an error during classification.
- Work item encounters an error when running a route-to-queue rule.
- Work item doesn't match any route-to-queue rules.

### How default queues work

Default queues are a finite set of system-defined queues that help you manage work items when other queues aren't available for routing them. All service representatives who have the Omnichannel agent role are a part of the default queues. Out of the box, the following default queues are available:

- **Default entity queue** for routing entity records.
- **Default messaging queue** for routing all messaging conversations pertaining to live chat, SMS, Microsoft Teams, and social channels.
- **Default voice queue** for routing all voice calls.

For a workstream, you can set any queue as a fallback queue, including a default queue but vice versa isn't possible. You can update the assignment method only for the default queues. However, we recommend that you always create advanced queues and define the assignment strategy instead of using the default queues. No other settings are available to edit.

### Related information

[Create and manage workstreams](create-workstreams.md)  
[Create and manage assignment methods](configure-assignment-rules.md#create-an-assignment-method-and-configure-rules)  
[Create and manage operating hours](create-operating-hours.md)  
[Configure the voice queues](../voice-channel-route-queues.md)  
[FAQ about time taken by configuration changes in unified routing](faqs.md#how-long-does-a-configuration-change-to-the-omnichannel-for-customer-service-and-unified-routing-settings-take-to-update)

[!INCLUDE[footer-include](../../includes/footer-banner.md)]
