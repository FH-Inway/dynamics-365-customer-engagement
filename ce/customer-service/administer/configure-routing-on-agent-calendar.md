---
title: Configure routing based on shift bookings
description: Learn how to configure routing of work items to representatives based on shift schedules of representatives.
author: neeranelli
ms.author: nenellim
ms.reviewer: nenellim
ms.topic: how-to
ms.collection: 
ms.date: 04/18/2025
ms.custom: bap-template
---

# Configure routing based on shift bookings

Configure assignment rules to route and assign cases and conversations based on customer service representatives' (service representative or representative) shift bookings in workforce management (WFM) system or schedules imported from external systems. By verifying representatives' schedules in advance, organizations can route tasks to only those service representatives who are available, and reduce the risk of delays. 

You can incorporate shift assignments and time-off considerations into the routing process to foster an employee-centric approach, and streamline operational workflows for productivity and improved retention rates.

> [!NOTE]
> Routing based on external schedules isn't supported in the Government Community Cloud (GCC) or sovereign clouds.

With shift bookings, the routing engine considers the shift activity type to determine if a representative can be considered for assignment. If the shift activity type associated with the shift booking is "non assignable", such as training or lunch break, then the representative isn't considered for assignment. Learn how to [configure shift activity types](/dynamics365/contact-center/administer/wfm-shift-activity-types).

## Prerequisites

- [Workforce Management for Customer Service](configure-agent-calendar.md#enable-workforce-management) is enabled in your environment, or a non-Microsoft adapter is configured to import representative schedules from an external system. If you're importing external schedules using the non-Microsoft adapter, opt in every representative ([bookableresource](../develop/reference/entities/bookableresource.md)) into shift-based routing by setting the **msdyn_generatecalendarfromshift** column of the corresponding bookableresource entry to **True**.
- Shift bookings are created in WFM system.
- [Unified routing](provision-unified-routing.md) is enabled and set up.
- [Workstreams](create-workstreams.md) and [advanced queues](queues-omnichannel.md) are set up.
- [Custom assignment method](configure-assignment-rules.md) is configured for the queue and the Calendar schedule attribute is used in custom assignment conditions.

## Enable shift-based routing

Follow the steps in [Enable shift-based routing](/dynamics365/contact-center/administer/wfm-enable-shift-based-routing#enable-shift-based-routing) to turn on the feature.

## Import external schedule data

You can create shift bookings in WFM system. Optionally, if you want to integrate schedules from external WFM systems, you can use a non-Microsoft adapter to import the schedules into Customer Service.

Alternatively, you can use [Organization Service](/power-apps/developer/data-platform/org-service/overview) or [Dataverse OData Web API](/power-apps/developer/data-platform/webapi/overview) to import representative schedules from external systems into Dynamics 365. For a detailed overview of how to import external schedules and the entities in Customer Service that can represent these external schedules, see the [Schedule import integration](https://github.com/microsoft/dynamics365-customerservice-wem-samples/wiki/Schedule-import-integration) guide.

## Configure an assignment rule

1. In the site map of Copilot Service admin center, select **Queues**, and then select **Manage** in the **Advanced queues** area.
1. Select the queue for which you want to configure the assignment rule, select the [custom assignment](configure-assignment-rules.md) method, and select **Edit**.
1. Create a rule or modify an existing rule and do the following:
    1. In **Conditions**, select **Add row**, and then select **Calendar schedule**. The **Is working** value is automatically selected.
    1. Save and close.

       :::image type="content" source="../media/screenshot-of-calendar-schedule-condition.png" alt-text="Screenshot of assignment rule configured on calendar schedule.":::

## View routing diagnostics records

View the [conversation diagnostics in Azure Application Insights](configure-conversation-diagnostics.md) to understand how a work item is routed when routing is configured based on shift bookings.

## How shift-based routing works

The imported schedules from external systems are represented in Dynamics 365 as "bookings". You can also create shift bookings natively in the workforce management system in Customer Service. The [bookableresourcebooking](../develop/reference/entities/bookableresourcebooking.md) entity stores this information. Shift bookings are added as activities to a shift plan that's assigned to a representative. The representative is recorded as a bookable resource and each of them with one or more bookings has a corresponding entry in the [bookableresource](../develop/reference/entities/bookableresource.md) entity.

Shift-based routing is applicable only when booking-based routing is enabled at organization level for all queues.

Unified routing considers the workforce management bookings and not any other bookings out of workforce management like appointments or field service bookings. The booking state must be active, status must be committed, and assignment status as "Assignable" for automatic assignment.

To find a matching representative, the assignment engine performs the regular assignment checks configured in custom assignment method with the check for assignable shift booking.

The booking start time needs to be before or equal to the time when automated assignment is attempted. The booking end time needs to be after the automated assignment attempted time.

If a representative has an assignable shift booking outside their calendar working hours, they are considered for automatic assignment because shift-based routing ignores work hour calendar and considers shift bookings only. 

If a representative has overlapping shift bookings and all of them are assignable, the representative is considered. If there's even one non-assignable shift booking, representative isn't considered for automatic assignment for the duration of non-assignable booking. If all the overlapping bookings are non-assignable, representative won't be considered for automatic assignment for the combined duration of the overlapping bookings.

If representative doesn't have a booking when assignment is attempted, no work is assigned automatically. The representatives can pick up work manually or supervisors can assign work to them.

### Related information

[Use Customer Service workspace](../implement/csw-overview.md)  
[View the agent calendar](../use/use-agent-calendar.md)  
