---
title: "Case (Incident) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Case (Incident) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Case (Incident) table/entity reference (Microsoft Dynamics 365 Field Service)

Service request case associated with a contract.

> [!NOTE]
> The Microsoft Dynamics 365 Field Service Case (Incident) table extends the [Microsoft Dynamics 365 Case (Incident) table](/dynamics365/developer/entities/incident).



## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [msdyn_FunctionalLocation](#BKMK_msdyn_FunctionalLocation)
- [msdyn_IncidentType](#BKMK_msdyn_IncidentType)

### <a name="BKMK_msdyn_FunctionalLocation"></a> msdyn_FunctionalLocation

|Property|Value|
|---|---|
|Description|**Case's functional location**|
|DisplayName|**Functional Location**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_functionallocation`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_functionallocation|

### <a name="BKMK_msdyn_IncidentType"></a> msdyn_IncidentType

|Property|Value|
|---|---|
|Description|**Unique identifier for Incident Type associated with Case.**|
|DisplayName|**Incident Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_incidenttype`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_incidenttype|


## Customized columns/attributes

Microsoft Dynamics 365 Field Service modifies the definition of columns/attributes defined in other solutions. Listed by **SchemaName**.

### <a name="BKMK_ExchangeRate"></a> ExchangeRate

Changes from [ExchangeRate (Microsoft Dynamics 365)](/dynamics365/developer/entities/incident#BKMK_ExchangeRate)

|Property|Value|
|---|---|
|MinValue|1E-12|
|Precision|12|


## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [msdyn_msdyn_functionallocation_incident_FunctionalLocation](#BKMK_msdyn_msdyn_functionallocation_incident_FunctionalLocation)
- [msdyn_msdyn_incidenttype_incident_IncidentType](#BKMK_msdyn_msdyn_incidenttype_incident_IncidentType)
- [TransactionCurrency_Incident](#BKMK_TransactionCurrency_Incident)

### <a name="BKMK_msdyn_msdyn_functionallocation_incident_FunctionalLocation"></a> msdyn_msdyn_functionallocation_incident_FunctionalLocation

One-To-Many Relationship: [msdyn_functionallocation msdyn_msdyn_functionallocation_incident_FunctionalLocation](msdyn_functionallocation.md#BKMK_msdyn_msdyn_functionallocation_incident_FunctionalLocation)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_functionallocation`|
|ReferencedAttribute|`msdyn_functionallocationid`|
|ReferencingAttribute|`msdyn_functionallocation`|
|ReferencingEntityNavigationPropertyName|`msdyn_FunctionalLocation`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_incidenttype_incident_IncidentType"></a> msdyn_msdyn_incidenttype_incident_IncidentType

One-To-Many Relationship: [msdyn_incidenttype msdyn_msdyn_incidenttype_incident_IncidentType](msdyn_incidenttype.md#BKMK_msdyn_msdyn_incidenttype_incident_IncidentType)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_incidenttype`|
|ReferencedAttribute|`msdyn_incidenttypeid`|
|ReferencingAttribute|`msdyn_incidenttype`|
|ReferencingEntityNavigationPropertyName|`msdyn_incidenttype`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_TransactionCurrency_Incident"></a> TransactionCurrency_Incident

One-To-Many Relationship: [transactioncurrency TransactionCurrency_Incident](transactioncurrency.md#BKMK_TransactionCurrency_Incident)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [bpf_incident_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b](#BKMK_bpf_incident_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b)
- [bpf_incident_msdyn_bpf_989e9b1857e24af18787d5143b67523b](#BKMK_bpf_incident_msdyn_bpf_989e9b1857e24af18787d5143b67523b)
- [incident_msdyn_bookingalerts](#BKMK_incident_msdyn_bookingalerts)
- [msdyn_incident_msdyn_inspectioninstance_CaseId](#BKMK_msdyn_incident_msdyn_inspectioninstance_CaseId)
- [msdyn_incident_msdyn_workorder_ServiceRequest](#BKMK_msdyn_incident_msdyn_workorder_ServiceRequest)

### <a name="BKMK_bpf_incident_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b"></a> bpf_incident_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b

Many-To-One Relationship: [msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b bpf_incident_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b](msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b.md#BKMK_bpf_incident_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b`|
|ReferencingAttribute|`bpf_incidentid`|
|ReferencedEntityNavigationPropertyName|`bpf_incident_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseLabel`<br />Group: `Details`<br />Label: incident<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_bpf_incident_msdyn_bpf_989e9b1857e24af18787d5143b67523b"></a> bpf_incident_msdyn_bpf_989e9b1857e24af18787d5143b67523b

Many-To-One Relationship: [msdyn_bpf_989e9b1857e24af18787d5143b67523b bpf_incident_msdyn_bpf_989e9b1857e24af18787d5143b67523b](msdyn_bpf_989e9b1857e24af18787d5143b67523b.md#BKMK_bpf_incident_msdyn_bpf_989e9b1857e24af18787d5143b67523b)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bpf_989e9b1857e24af18787d5143b67523b`|
|ReferencingAttribute|`bpf_incidentid`|
|ReferencedEntityNavigationPropertyName|`bpf_incident_msdyn_bpf_989e9b1857e24af18787d5143b67523b`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseLabel`<br />Group: `Details`<br />Label: incident<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_incident_msdyn_bookingalerts"></a> incident_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert incident_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_incident_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`incident_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: `CRMActivity.RetrieveByObject`<br />ViewId: `00000000-0000-0000-00aa-000010001903`|

### <a name="BKMK_msdyn_incident_msdyn_inspectioninstance_CaseId"></a> msdyn_incident_msdyn_inspectioninstance_CaseId

Many-To-One Relationship: [msdyn_inspectioninstance msdyn_incident_msdyn_inspectioninstance_CaseId](msdyn_inspectioninstance.md#BKMK_msdyn_incident_msdyn_inspectioninstance_CaseId)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_inspectioninstance`|
|ReferencingAttribute|`msdyn_caseid`|
|ReferencedEntityNavigationPropertyName|`msdyn_incident_msdyn_inspectioninstance_CaseId`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_incident_msdyn_workorder_ServiceRequest"></a> msdyn_incident_msdyn_workorder_ServiceRequest

Many-To-One Relationship: [msdyn_workorder msdyn_incident_msdyn_workorder_ServiceRequest](msdyn_workorder.md#BKMK_msdyn_incident_msdyn_workorder_ServiceRequest)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_workorder`|
|ReferencingAttribute|`msdyn_servicerequest`|
|ReferencedEntityNavigationPropertyName|`msdyn_incident_msdyn_workorder_ServiceRequest`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|


## Customized relationships

### Customized One-to-Many relationships

#### <a name="BKMK_msdyn_incident_msdyn_originatingqueue_createdincidentid"></a> msdyn_incident_msdyn_originatingqueue_createdincidentid

Changes from [msdyn_incident_msdyn_originatingqueue_createdincidentid (Microsoft Dynamics 365)](/dynamics365/developer/entities/incident#BKMK_msdyn_incident_msdyn_originatingqueue_createdincidentid)

|Property|Value|
|---|---|
|AssociatedMenuConfiguration|Label: ``|


### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

