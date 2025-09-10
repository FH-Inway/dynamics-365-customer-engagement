---
title: "Insight (msdyn_salessuggestion) table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Insight (msdyn_salessuggestion) table/entity with Microsoft Dynamics 365 Customer Service."
ms.topic: generated-reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Insight (msdyn_salessuggestion) table/entity reference (Microsoft Dynamics 365 Customer Service)



> [!NOTE]
> The Microsoft Dynamics 365 Customer Service Insight (msdyn_salessuggestion) table extends the [Microsoft Dynamics 365 Insight (msdyn_salessuggestion) table](/dynamics365/developer/reference/entities/msdyn_salessuggestion).




## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_salessuggestion_msdyn_bookingalerts](#BKMK_msdyn_salessuggestion_msdyn_bookingalerts)
- [msdyn_salessuggestion_msdyn_ocoutboundmessages](#BKMK_msdyn_salessuggestion_msdyn_ocoutboundmessages)
- [msdyn_salessuggestion_msdyn_ocvoicemails](#BKMK_msdyn_salessuggestion_msdyn_ocvoicemails)

### <a name="BKMK_msdyn_salessuggestion_msdyn_bookingalerts"></a> msdyn_salessuggestion_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert msdyn_salessuggestion_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_msdyn_salessuggestion_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_salessuggestion_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_salessuggestion_msdyn_ocoutboundmessages"></a> msdyn_salessuggestion_msdyn_ocoutboundmessages

Many-To-One Relationship: [msdyn_ocoutboundmessage msdyn_salessuggestion_msdyn_ocoutboundmessages](msdyn_ocoutboundmessage.md#BKMK_msdyn_salessuggestion_msdyn_ocoutboundmessages)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocoutboundmessage`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_salessuggestion_msdyn_ocoutboundmessages`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_salessuggestion_msdyn_ocvoicemails"></a> msdyn_salessuggestion_msdyn_ocvoicemails

Many-To-One Relationship: [msdyn_ocvoicemail msdyn_salessuggestion_msdyn_ocvoicemails](msdyn_ocvoicemail.md#BKMK_msdyn_salessuggestion_msdyn_ocvoicemails)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocvoicemail`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_salessuggestion_msdyn_ocvoicemails`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

