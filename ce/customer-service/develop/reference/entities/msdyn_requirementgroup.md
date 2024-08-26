---
title: "Requirement Group (msdyn_requirementgroup) table/entity reference (Microsoft Dynamics 365 Customer Service)"
description: "Includes schema information and supported messages for the Requirement Group (msdyn_requirementgroup) table/entity with Microsoft Dynamics 365 Customer Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: gandhamm
ms.author: mgandham
search.audienceType: 
  - developer
---

# Requirement Group (msdyn_requirementgroup) table/entity reference

Service which has resource requirement offering periods

## Messages

The following table lists the messages for the Requirement Group (msdyn_requirementgroup) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_requirementgroups(*msdyn_requirementgroupid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_requirementgroups<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_requirementgroups(*msdyn_requirementgroupid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `msdyn_BookRequirementGroup`<br />Event: True |**msdyn_BookRequirementGroup action** |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `msdyn_RequirementGroupOverview`<br />Event: False |**msdyn_RequirementGroupOverview action** |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `msdyn_ScheduleRequirementGroup`<br />Event: True |**msdyn_ScheduleRequirementGroup action** |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_requirementgroups(*msdyn_requirementgroupid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_requirementgroups<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_requirementgroups(*msdyn_requirementgroupid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_requirementgroups(*msdyn_requirementgroupid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_requirementgroups(*msdyn_requirementgroupid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Requirement Group (msdyn_requirementgroup) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Requirement Group (msdyn_requirementgroup) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Requirement Group** |
| **DisplayCollectionName** | **Requirement Groups** |
| **SchemaName** | `msdyn_requirementgroup` |
| **CollectionSchemaName** | `msdyn_requirementgroups` |
| **EntitySetName** | `msdyn_requirementgroups`|
| **LogicalName** | `msdyn_requirementgroup` |
| **LogicalCollectionName** | `msdyn_requirementgroups` |
| **PrimaryIdAttribute** | `msdyn_requirementgroupid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_autogrouptype](#BKMK_msdyn_autogrouptype)
- [msdyn_istemplate](#BKMK_msdyn_istemplate)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_requirementgroupId](#BKMK_msdyn_requirementgroupId)
- [msdyn_requirementgrouptemplateid](#BKMK_msdyn_requirementgrouptemplateid)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)

### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|---|---|
|Description|**Sequence number of the import that created this record.**|
|DisplayName|**Import Sequence Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`importsequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_autogrouptype"></a> msdyn_autogrouptype

|Property|Value|
|---|---|
|Description|**Auto Group Type**|
|DisplayName|**Auto Group Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_autogrouptype`|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`msdyn_requirementgroup_msdyn_autogrouptype`|

#### msdyn_autogrouptype Choices/Options

|Value|Label|
|---|---|
|0|**None**|
|1|**Crew**|

### <a name="BKMK_msdyn_istemplate"></a> msdyn_istemplate

|Property|Value|
|---|---|
|Description|**Whether this offering is a template or not.**|
|DisplayName|**Is Template**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_istemplate`|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|
|GlobalChoiceName|`msdyn_requirementgroup_msdyn_istemplate`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description|**The name of the custom entity.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_name`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_requirementgroupId"></a> msdyn_requirementgroupId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Requirement Group**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_requirementgroupid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_requirementgrouptemplateid"></a> msdyn_requirementgrouptemplateid

|Property|Value|
|---|---|
|Description|**Requirement Group Template Reference**|
|DisplayName|**Requirement Group Template**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_requirementgrouptemplateid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_requirementgroup|

### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|---|---|
|Description|**Date and time that the record was migrated.**|
|DisplayName|**Record Created On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overriddencreatedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|---|---|
|Description|**Owner Id**|
|DisplayName|**Owner**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`ownerid`|
|RequiredLevel|SystemRequired|
|Type|Owner|
|Targets|systemuser, team|

### <a name="BKMK_OwnerIdType"></a> OwnerIdType

|Property|Value|
|---|---|
|Description|**Owner Id Type**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridtype`|
|RequiredLevel|SystemRequired|
|Type|EntityName|

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the Requirement Group**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_requirementgroup_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Requirement Group**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_requirementgroup_statuscode`|

#### statuscode Choices/Options

|Value|Details|
|---|---|
|1|Label: **Active**<br />State:0<br />TransitionData: None|
|2|Label: **Inactive**<br />State:1<br />TransitionData: None|

### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Time Zone Rule Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`timezoneruleversionnumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|

### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|---|---|
|Description|**Time zone code that was in use when the record was created.**|
|DisplayName|**UTC Conversion Time Zone Code**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`utcconversiontimezonecode`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|


## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** and **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)

### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who created the record.**|
|DisplayName|**Created By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|---|---|
|Description|**Date and time when the record was created.**|
|DisplayName|**Created On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who created the record.**|
|DisplayName|**Created By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who modified the record.**|
|DisplayName|**Modified By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|---|---|
|Description|**Date and time when the record was modified.**|
|DisplayName|**Modified On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who modified the record.**|
|DisplayName|**Modified By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_OwnerIdName"></a> OwnerIdName

|Property|Value|
|---|---|
|Description|**Name of the owner**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridname`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

|Property|Value|
|---|---|
|Description|**Yomi name of the owner**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridyominame`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

|Property|Value|
|---|---|
|Description|**Unique identifier for the business unit that owns the record**|
|DisplayName|**Owning Business Unit**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`owningbusinessunit`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|businessunit|

### <a name="BKMK_OwningTeam"></a> OwningTeam

|Property|Value|
|---|---|
|Description|**Unique identifier for the team that owns the record.**|
|DisplayName|**Owning Team**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owningteam`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|team|

### <a name="BKMK_OwningUser"></a> OwningUser

|Property|Value|
|---|---|
|Description|**Unique identifier for the user that owns the record.**|
|DisplayName|**Owning User**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owninguser`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|---|---|
|Description|**Version Number**|
|DisplayName|**Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`versionnumber`|
|RequiredLevel|None|
|Type|BigInt|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [business_unit_msdyn_requirementgroup](#BKMK_business_unit_msdyn_requirementgroup)
- [lk_msdyn_requirementgroup_createdby](#BKMK_lk_msdyn_requirementgroup_createdby)
- [lk_msdyn_requirementgroup_createdonbehalfby](#BKMK_lk_msdyn_requirementgroup_createdonbehalfby)
- [lk_msdyn_requirementgroup_modifiedby](#BKMK_lk_msdyn_requirementgroup_modifiedby)
- [lk_msdyn_requirementgroup_modifiedonbehalfby](#BKMK_lk_msdyn_requirementgroup_modifiedonbehalfby)
- [msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid](#BKMK_msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid-many-to-one)
- [owner_msdyn_requirementgroup](#BKMK_owner_msdyn_requirementgroup)
- [team_msdyn_requirementgroup](#BKMK_team_msdyn_requirementgroup)
- [user_msdyn_requirementgroup](#BKMK_user_msdyn_requirementgroup)

### <a name="BKMK_business_unit_msdyn_requirementgroup"></a> business_unit_msdyn_requirementgroup

One-To-Many Relationship: [businessunit business_unit_msdyn_requirementgroup](businessunit.md#BKMK_business_unit_msdyn_requirementgroup)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_requirementgroup_createdby"></a> lk_msdyn_requirementgroup_createdby

One-To-Many Relationship: [systemuser lk_msdyn_requirementgroup_createdby](systemuser.md#BKMK_lk_msdyn_requirementgroup_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_requirementgroup_createdonbehalfby"></a> lk_msdyn_requirementgroup_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_requirementgroup_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_requirementgroup_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_requirementgroup_modifiedby"></a> lk_msdyn_requirementgroup_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_requirementgroup_modifiedby](systemuser.md#BKMK_lk_msdyn_requirementgroup_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_requirementgroup_modifiedonbehalfby"></a> lk_msdyn_requirementgroup_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_requirementgroup_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_requirementgroup_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid-many-to-one"></a> msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid

One-To-Many Relationship: [msdyn_requirementgroup msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid](#BKMK_msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid-one-to-many)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_requirementgroup`|
|ReferencedAttribute|`msdyn_requirementgroupid`|
|ReferencingAttribute|`msdyn_requirementgrouptemplateid`|
|ReferencingEntityNavigationPropertyName|`msdyn_requirementgrouptemplateid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_requirementgroup"></a> owner_msdyn_requirementgroup

One-To-Many Relationship: [owner owner_msdyn_requirementgroup](owner.md#BKMK_owner_msdyn_requirementgroup)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_requirementgroup"></a> team_msdyn_requirementgroup

One-To-Many Relationship: [team team_msdyn_requirementgroup](team.md#BKMK_team_msdyn_requirementgroup)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_requirementgroup"></a> user_msdyn_requirementgroup

One-To-Many Relationship: [systemuser user_msdyn_requirementgroup](systemuser.md#BKMK_user_msdyn_requirementgroup)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`owninguser`|
|ReferencingEntityNavigationPropertyName|`owninguser`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_requirementgroup_AsyncOperations](#BKMK_msdyn_requirementgroup_AsyncOperations)
- [msdyn_requirementgroup_bookableresourcebooking_requirementgroupid](#BKMK_msdyn_requirementgroup_bookableresourcebooking_requirementgroupid)
- [msdyn_requirementgroup_BulkDeleteFailures](#BKMK_msdyn_requirementgroup_BulkDeleteFailures)
- [msdyn_requirementgroup_DuplicateBaseRecord](#BKMK_msdyn_requirementgroup_DuplicateBaseRecord)
- [msdyn_requirementgroup_DuplicateMatchingRecord](#BKMK_msdyn_requirementgroup_DuplicateMatchingRecord)
- [msdyn_requirementgroup_MailboxTrackingFolders](#BKMK_msdyn_requirementgroup_MailboxTrackingFolders)
- [msdyn_requirementgroup_PrincipalObjectAttributeAccesses](#BKMK_msdyn_requirementgroup_PrincipalObjectAttributeAccesses)
- [msdyn_requirementgroup_ProcessSession](#BKMK_msdyn_requirementgroup_ProcessSession)
- [msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid](#BKMK_msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid-one-to-many)
- [msdyn_requirementgroup_requirementrelationship_requirementgroupid](#BKMK_msdyn_requirementgroup_requirementrelationship_requirementgroupid)
- [msdyn_requirementgroup_resourcerequirement_requirementgroupid](#BKMK_msdyn_requirementgroup_resourcerequirement_requirementgroupid)
- [msdyn_requirementgroup_service](#BKMK_msdyn_requirementgroup_service)
- [msdyn_requirementgroup_SyncErrors](#BKMK_msdyn_requirementgroup_SyncErrors)

### <a name="BKMK_msdyn_requirementgroup_AsyncOperations"></a> msdyn_requirementgroup_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_requirementgroup_AsyncOperations](asyncoperation.md#BKMK_msdyn_requirementgroup_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_bookableresourcebooking_requirementgroupid"></a> msdyn_requirementgroup_bookableresourcebooking_requirementgroupid

Many-To-One Relationship: [bookableresourcebooking msdyn_requirementgroup_bookableresourcebooking_requirementgroupid](bookableresourcebooking.md#BKMK_msdyn_requirementgroup_bookableresourcebooking_requirementgroupid)

|Property|Value|
|---|---|
|ReferencingEntity|`bookableresourcebooking`|
|ReferencingAttribute|`msdyn_requirementgroupid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_bookableresourcebooking_requirementgroupid`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_BulkDeleteFailures"></a> msdyn_requirementgroup_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_requirementgroup_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_requirementgroup_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_DuplicateBaseRecord"></a> msdyn_requirementgroup_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_requirementgroup_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_requirementgroup_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_DuplicateMatchingRecord"></a> msdyn_requirementgroup_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_requirementgroup_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_requirementgroup_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_MailboxTrackingFolders"></a> msdyn_requirementgroup_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_requirementgroup_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_requirementgroup_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_PrincipalObjectAttributeAccesses"></a> msdyn_requirementgroup_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_requirementgroup_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_requirementgroup_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_ProcessSession"></a> msdyn_requirementgroup_ProcessSession

Many-To-One Relationship: [processsession msdyn_requirementgroup_ProcessSession](processsession.md#BKMK_msdyn_requirementgroup_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid-one-to-many"></a> msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid

Many-To-One Relationship: [msdyn_requirementgroup msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid](#BKMK_msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid-many-to-one)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_requirementgroup`|
|ReferencingAttribute|`msdyn_requirementgrouptemplateid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_requirementgroup_requirementgrouptemplateid`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_requirementrelationship_requirementgroupid"></a> msdyn_requirementgroup_requirementrelationship_requirementgroupid

Many-To-One Relationship: [msdyn_requirementrelationship msdyn_requirementgroup_requirementrelationship_requirementgroupid](msdyn_requirementrelationship.md#BKMK_msdyn_requirementgroup_requirementrelationship_requirementgroupid)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_requirementrelationship`|
|ReferencingAttribute|`msdyn_requirementgroupid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_requirementrelationship_requirementgroupid`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_resourcerequirement_requirementgroupid"></a> msdyn_requirementgroup_resourcerequirement_requirementgroupid

Many-To-One Relationship: [msdyn_resourcerequirement msdyn_requirementgroup_resourcerequirement_requirementgroupid](msdyn_resourcerequirement.md#BKMK_msdyn_requirementgroup_resourcerequirement_requirementgroupid)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_resourcerequirement`|
|ReferencingAttribute|`msdyn_requirementgroupid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_resourcerequirement_requirementgroupid`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_service"></a> msdyn_requirementgroup_service

Many-To-One Relationship: [service msdyn_requirementgroup_service](service.md#BKMK_msdyn_requirementgroup_service)

|Property|Value|
|---|---|
|ReferencingEntity|`service`|
|ReferencingAttribute|`msdyn_requirementgroupid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_service`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_requirementgroup_SyncErrors"></a> msdyn_requirementgroup_SyncErrors

Many-To-One Relationship: [syncerror msdyn_requirementgroup_SyncErrors](syncerror.md#BKMK_msdyn_requirementgroup_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_requirementgroup_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

