---
title: Understand how unified routing affects queue items and live work items for routed records
description: Use this article to understand how unified routing affects queue items, live work items, and the corresponding APIs.
ms.date: 11/28/2023
ms.topic: conceptual
author: gandhamm
ms.author: mgandham
ms.custom: bap-template
ms.reviewer:
ms.collection:
---

# Understand how unified routing affects queue items and live work items for routed records

When you route a record using unified routing, a live work item entity record ([`msdyn_ocliveworkitem`](reference/entities/msdyn_ocliveworkitem.md)) is created to track the workstream settings for allowed presence, matched skills, and available capacity. The unified routing engine uses these settings to route records to the appropriate queues based on route-to-queue rules, and to the available agent based on presence, skills, and capacity.

After the record is routed to the queue, a queue item ([`queueitem`](reference/entities/queueitem.md)) is created. The following three fields are updated in the queue item:
- the queue to which the queue item belongs
- the worker ID or agent assigned to the queue items
- the state of the queue item, whether active or inactive
 
Unified routing updates the following details when a record is automatically assigned to an agent or is picked by the agent:
- Agent as the record owner
- Agent in the live work item
- Worker ID in the queue item

Unified routing automatically synchronizes these updates from the queue item to the live work item, but not vice-versa. So, any updates from the live work item aren't automatically reflected in the queue item. If you'd like to make these updates manually, we recommend that you update only the queue item so that the live work item gets updated automatically by the unified routing engine. 

At a time, you can update one field only of the queue item. For example, if you need to update both the queue and the worker ID fields of the queue item, then make sure that you update the queue or the worker ID field, but not both in the same update operation.

> [!NOTE]
> We recommend the following:
> - Don't overwrite or update the ownership. Unified routing automatically sets the record's owner to a user.
> - Don't add any custom logic on live work items because Microsoft uses the live work items in unified routing services.

## How unified routing affects queue items, live work items for routed records

This section describes how queue items and live work items are updated when you change the status of a queue item with unified routing.

### What happens when you change the Queue field

- When you change the **Queue** field from an advanced queue to another advanced queue&mdash;by selecting **Add to Queue** on the record via the [AddToQueue action](/power-apps/developer/data-platform/webapi/reference/addtoqueue?view=dataverse-latest&preserve-view=true&viewFallbackFrom=dynamics-ce-odata-9) or by selecting **Route To** on the queue item via the [RouteTo action](/power-apps/developer/data-platform/webapi/reference/routeto?view=dataverse-latest&preserve-view=true&viewFallbackFrom=dynamics-ce-odata-9), then the associated queue for the live work item ([msdyn_ocliveworkitem](reference/entities/msdyn_ocliveworkitem.md)) also gets updated to the same destination queue. This action then updates the unified routing services that maintain agent presence and capacity with the corresponding changes.

- When you change the **Queue** field from an advanced queue to a basic queue by selecting **Add to Queue** on the record via the [AddToQueue Action](/power-apps/developer/data-platform/webapi/reference/addtoqueue?view=dataverse-latest&preserve-view=true&viewFallbackFrom=dynamics-ce-odata-9) or by selecting **Route To** on the queue item via the [RouteTo action](/power-apps/developer/data-platform/webapi/reference/routeto?view=dataverse-latest&preserve-view=true&viewFallbackFrom=dynamics-ce-odata-9), then the associated live work item ([msdyn_ocliveworkitem](reference/entities/msdyn_ocliveworkitem.md)) and the entity record are closed, and the queue item is no longer considered or picked by the unified routing engine. This action then updates the unified routing services that maintain agent presence and capacity with the corresponding changes.

- When you change the **Queue** field of a queue item from a basic queue to an advanced queue, then you must reroute the queue items using **Save & Route** so that the corresponding live work item can be picked up by the unified routing services. If you change a basic queue to an advanced type of queue while the queue item is still assigned to the basic queue, then the queue item won't be considered for routing by the unified routing engine. 

### What happens when you update the Worked By field 

- When you update the **Worked By** field of queue items by selecting **Route To**/**Pick From Queue** on the queue items list via the [RouteTo action](/power-apps/developer/data-platform/webapi/reference/routeto?view=dataverse-latest&preserve-view=true)/[PickFromQueue Action](/power-apps/developer/data-platform/webapi/reference/pickfromqueue?view=dataverse-latest&preserve-view=true) or by manually updating the **Worked By** field on the QueueItem details form, then the live work item ([`msdyn_ocliveworkitem`](reference/entities/msdyn_ocliveworkitem.md)) also gets assigned to the same agent. With **Route To**/**Pick From Queue**, the owner of the record is also updated to the same agent whereas manual update of **Worked by** doesn't update the owner field in the record.

- When automatic assignment routes and assigns the record to an agent, then the following fields are updated with the agent name:
  - Worked By
  - Agent in the live work item
  - Owner in the record

> [!CAUTION]
> If you run a custom script, flow, or action that updates the queue item, live work item, or record at the same time as the automatic assignment, then you might experience assignment errors. We recommend that you run custom scripts or flows before or after the automatic assignment is complete.

## What happens when you delete or deactivate a queue item

- When you delete a queue item by selecting **Remove** via the [RemoveFromQueue action](/power-apps/developer/data-platform/webapi/reference/removefromqueue?view=dataverse-latest&preserve-view=true&viewFallbackFrom=dynamics-ce-odata-9), or by deleting or closing the underlying record, the associated live work item [`msdyn_ocliveworkitem`](reference/entities/msdyn_ocliveworkitem.md) is also closed. This action then updates the unified routing services that maintain agent presence and capacity with the corresponding changes.

- When you [deactivate a queue item](deactivate-queue-items.md), the associated live work item [`msdyn_ocliveworkitem`](reference/entities/msdyn_ocliveworkitem.md) is also closed. This action then updates the unified routing services that maintain agent presence and capacity with the corresponding changes. If the record needs to be reopened, then you must reroute it using **Save & Route**, and not reactivate the queue item. The rerouting creates a new live work item and a new queue item, ensuring all the information needed for routing is available again.

- When you update a queue item using unified routing, you can't remove it from the queue by selecting **Pick** ([PickFromQueue action](/power-apps/developer/data-platform/webapi/reference/pickfromqueue?view=dataverse-latest&preserve-view=true&viewFallbackFrom=dynamics-ce-odata-9)) or **RouteTo action** on the queue item.

- When you resolve a case, the corresponding queue item that gets deactivated can't be activated again.


> [!Note]
> - Unified routing works upon the underlying entity record for the owner field also. Therefore, make sure that you provide Read privileges to the agents for that entity and any other dependent entity. For information on how to provide the accesses to different roles for the entities, see [Manage user accounts, user licenses, and security roles](/power-platform/admin/security-roles-privileges).
> - To get the capacity released for the agents for entities other than incident (via incident resolution or cancellation), add a custom logic to deactivate the corresponding queue item. More information: [Create and manage capacity profiles](../administer/capacity-profiles.md).
> - For non-case records, we recommend that you deactivate the associated queue item before deleting it.

## Next steps

[Close live work items or deactivate queue items](deactivate-queue-items.md)

### See also

[Overview of unified routing](../administer/overview-unified-routing.md)   
[Set up record routing](../administer/set-up-record-routing.md)   
[Set up unified routing](../administer/set-up-routing-process.md)   


[!INCLUDE[footer-include](../../includes/footer-banner.md)]
