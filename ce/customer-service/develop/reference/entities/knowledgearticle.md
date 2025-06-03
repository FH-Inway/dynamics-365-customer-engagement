---
title: "Knowledge Article (KnowledgeArticle) table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Knowledge Article (KnowledgeArticle) table/entity with Microsoft Dynamics 365 Customer Service."
ms.topic: generated-reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Knowledge Article (KnowledgeArticle) table/entity reference (Microsoft Dynamics 365 Customer Service)

Organizational knowledge for internal and external use.

> [!NOTE]
> The Microsoft Dynamics 365 Customer Service Knowledge Article (KnowledgeArticle) table extends the [Microsoft Dynamics 365 Knowledge Article (KnowledgeArticle) table](/dynamics365/developer/reference/entities/knowledgearticle).




## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [knowledgearticle_msdyn_bookingalerts](#BKMK_knowledgearticle_msdyn_bookingalerts)
- [knowledgearticle_msdyn_ocoutboundmessages](#BKMK_knowledgearticle_msdyn_ocoutboundmessages)

### <a name="BKMK_knowledgearticle_msdyn_bookingalerts"></a> knowledgearticle_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert knowledgearticle_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_knowledgearticle_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`knowledgearticle_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: `CRMActivity.RetrieveByObject`<br />ViewId: `00000000-0000-0000-00aa-000010001903`|

### <a name="BKMK_knowledgearticle_msdyn_ocoutboundmessages"></a> knowledgearticle_msdyn_ocoutboundmessages

Many-To-One Relationship: [msdyn_ocoutboundmessage knowledgearticle_msdyn_ocoutboundmessages](msdyn_ocoutboundmessage.md#BKMK_knowledgearticle_msdyn_ocoutboundmessages)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocoutboundmessage`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`knowledgearticle_msdyn_ocoutboundmessages`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: `CRMActivity.RetrieveByObject`<br />ViewId: `00000000-0000-0000-00aa-000010001903`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.knowledgearticle?displayProperty=fullName>
