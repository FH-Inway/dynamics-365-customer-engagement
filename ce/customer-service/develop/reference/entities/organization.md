---
title: "Organization table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Organization table/entity with Microsoft Dynamics 365 Customer Service."
ms.topic: generated-reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Organization table/entity reference (Microsoft Dynamics 365 Customer Service)

Top level of the Microsoft Dynamics 365 business hierarchy. The organization can be a specific business, holding company, or corporation.

> [!NOTE]
> The Microsoft Dynamics 365 Customer Service Organization table extends the [Microsoft Dynamics 365 Organization table](/dynamics365/developer/reference/entities/organization).



## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

### <a name="BKMK_IsComputerUseInMCSEnabled"></a> IsComputerUseInMCSEnabled

|Property|Value|
|---|---|
|Description|**Indicates whether Computer Use in MCS feature is enabled in this organization.**|
|DisplayName|**Enable Computer Use in MCS feature for this organization**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`iscomputeruseinmcsenabled`|
|RequiredLevel|SystemRequired|
|Type|Boolean|
|GlobalChoiceName|`organization_featureenabled`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|


## Customized columns/attributes

Microsoft Dynamics 365 Customer Service modifies the definition of columns/attributes defined in other solutions. Listed by **SchemaName**.

- [EnableEnvironmentSettingsApp](#BKMK_EnableEnvironmentSettingsApp)
- [IsDesktopFlowVanillaImageSharingEnabled](#BKMK_IsDesktopFlowVanillaImageSharingEnabled)
- [SchedulingEngine](#BKMK_SchedulingEngine)

### <a name="BKMK_EnableEnvironmentSettingsApp"></a> EnableEnvironmentSettingsApp

Changes from [EnableEnvironmentSettingsApp (Microsoft Dataverse)](/power-apps/developer/data-platform/reference/entities/organization#BKMK_EnableEnvironmentSettingsApp)

|Property|Value|
|---|---|
|RequiredLevel|SystemRequired|


### <a name="BKMK_IsDesktopFlowVanillaImageSharingEnabled"></a> IsDesktopFlowVanillaImageSharingEnabled

Changes from [IsDesktopFlowVanillaImageSharingEnabled (Microsoft Dataverse)](/power-apps/developer/data-platform/reference/entities/organization#BKMK_IsDesktopFlowVanillaImageSharingEnabled)

|Property|Value|
|---|---|
|RequiredLevel|SystemRequired|


### <a name="BKMK_SchedulingEngine"></a> SchedulingEngine

Changes from [SchedulingEngine (Microsoft Dynamics 365)](/dynamics365/developer/reference/entities/organization#BKMK_SchedulingEngine)

#### SchedulingEngine Choices/Options

|Value|Label|
|---|---|
|192350000|**(Deprecated) Universal Resource Scheduling**|

## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [organization_msdyn_localizedsurveyquestion](#BKMK_organization_msdyn_localizedsurveyquestion)
- [organization_msdyn_ocsmschannelsetting](#BKMK_organization_msdyn_ocsmschannelsetting)
- [organization_msdyn_organizationalunit](#BKMK_organization_msdyn_organizationalunit)
- [organization_msdyn_schedulingparameter](#BKMK_organization_msdyn_schedulingparameter)

### <a name="BKMK_organization_msdyn_localizedsurveyquestion"></a> organization_msdyn_localizedsurveyquestion

Many-To-One Relationship: [msdyn_localizedsurveyquestion organization_msdyn_localizedsurveyquestion](msdyn_localizedsurveyquestion.md#BKMK_organization_msdyn_localizedsurveyquestion)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_localizedsurveyquestion`|
|ReferencingAttribute|`organizationid`|
|ReferencedEntityNavigationPropertyName|`organization_msdyn_localizedsurveyquestion`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_organization_msdyn_ocsmschannelsetting"></a> organization_msdyn_ocsmschannelsetting

Many-To-One Relationship: [msdyn_ocsmschannelsetting organization_msdyn_ocsmschannelsetting](msdyn_ocsmschannelsetting.md#BKMK_organization_msdyn_ocsmschannelsetting)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocsmschannelsetting`|
|ReferencingAttribute|`organizationid`|
|ReferencedEntityNavigationPropertyName|`organization_msdyn_ocsmschannelsetting`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_organization_msdyn_organizationalunit"></a> organization_msdyn_organizationalunit

Many-To-One Relationship: [msdyn_organizationalunit organization_msdyn_organizationalunit](msdyn_organizationalunit.md#BKMK_organization_msdyn_organizationalunit)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_organizationalunit`|
|ReferencingAttribute|`organizationid`|
|ReferencedEntityNavigationPropertyName|`organization_msdyn_organizationalunit`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_organization_msdyn_schedulingparameter"></a> organization_msdyn_schedulingparameter

Many-To-One Relationship: [msdyn_schedulingparameter organization_msdyn_schedulingparameter](msdyn_schedulingparameter.md#BKMK_organization_msdyn_schedulingparameter)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_schedulingparameter`|
|ReferencingAttribute|`organizationid`|
|ReferencedEntityNavigationPropertyName|`organization_msdyn_schedulingparameter`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.organization?displayProperty=fullName>
