---
title: "Custom API Ruleset Configuration (msdyn_customapirulesetconfiguration) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Custom API Ruleset Configuration (msdyn_customapirulesetconfiguration) table/entity with Microsoft Dynamics 365."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# Custom API Ruleset Configuration (msdyn_customapirulesetconfiguration) table/entity reference (Microsoft Dynamics 365)

Configuration table for setting up custom APIs for usage inside the Unified routing system

## Messages

The following table lists the messages for the Custom API Ruleset Configuration (msdyn_customapirulesetconfiguration) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_customapirulesetconfigurations(*msdyn_customapirulesetconfigurationid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_customapirulesetconfigurations<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_customapirulesetconfigurations(*msdyn_customapirulesetconfigurationid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Retrieve`<br />Event: True |`GET` /msdyn_customapirulesetconfigurations(*msdyn_customapirulesetconfigurationid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_customapirulesetconfigurations<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_customapirulesetconfigurations(*msdyn_customapirulesetconfigurationid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_customapirulesetconfigurations(*msdyn_customapirulesetconfigurationid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_customapirulesetconfigurations(*msdyn_customapirulesetconfigurationid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Custom API Ruleset Configuration (msdyn_customapirulesetconfiguration) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Custom API Ruleset Configuration (msdyn_customapirulesetconfiguration) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Custom API Ruleset Configuration** |
| **DisplayCollectionName** | **Custom API Ruleset Configurations** |
| **SchemaName** | `msdyn_customapirulesetconfiguration` |
| **CollectionSchemaName** | `msdyn_customapirulesetconfigurations` |
| **EntitySetName** | `msdyn_customapirulesetconfigurations`|
| **LogicalName** | `msdyn_customapirulesetconfiguration` |
| **LogicalCollectionName** | `msdyn_customapirulesetconfigurations` |
| **PrimaryIdAttribute** | `msdyn_customapirulesetconfigurationid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IsCustomizable](#BKMK_IsCustomizable)
- [msdyn_CustomAPI](#BKMK_msdyn_CustomAPI)
- [msdyn_CustomAPIRequestParameter](#BKMK_msdyn_CustomAPIRequestParameter)
- [msdyn_CustomAPIResponseProperty](#BKMK_msdyn_CustomAPIResponseProperty)
- [msdyn_customapirulesetconfigurationId](#BKMK_msdyn_customapirulesetconfigurationId)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_PersistOutputData](#BKMK_msdyn_PersistOutputData)
- [msdyn_RefreshInputData](#BKMK_msdyn_RefreshInputData)
- [msdyn_UniqueName](#BKMK_msdyn_UniqueName)
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

### <a name="BKMK_IsCustomizable"></a> IsCustomizable

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Is Customizable**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`iscustomizable`|
|RequiredLevel|SystemRequired|
|Type|ManagedProperty|

### <a name="BKMK_msdyn_CustomAPI"></a> msdyn_CustomAPI

|Property|Value|
|---|---|
|Description|**Select the Custom API registered in dataverse**|
|DisplayName|**Custom API**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_customapi`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|customapi|

### <a name="BKMK_msdyn_CustomAPIRequestParameter"></a> msdyn_CustomAPIRequestParameter

|Property|Value|
|---|---|
|Description|**Select the request parameter of the Custom API that should contain the input from Unified Routing**|
|DisplayName|**Custom API request parameter**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_customapirequestparameter`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|customapirequestparameter|

### <a name="BKMK_msdyn_CustomAPIResponseProperty"></a> msdyn_CustomAPIResponseProperty

|Property|Value|
|---|---|
|Description|**Select the response property of the Custom API which will contain the output that needs to be parsed by Unified Routing**|
|DisplayName|**Custom API response property**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_customapiresponseproperty`|
|RequiredLevel|Recommended|
|Type|Lookup|
|Targets|customapiresponseproperty|

### <a name="BKMK_msdyn_customapirulesetconfigurationId"></a> msdyn_customapirulesetconfigurationId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Custom API Ruleset Configuration**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_customapirulesetconfigurationid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description|**Name of the Custom API record that can be selected in routing rules**|
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

### <a name="BKMK_msdyn_PersistOutputData"></a> msdyn_PersistOutputData

|Property|Value|
|---|---|
|Description|**Persist the output data from the Custom API to be used in further rules**|
|DisplayName|**Persist output data**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_persistoutputdata`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_customapirulesetconfiguration_msdyn_persistoutputdata`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_RefreshInputData"></a> msdyn_RefreshInputData

|Property|Value|
|---|---|
|Description|**Refresh the work items details before invoking the Custom API**|
|DisplayName|**Refresh input data**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_refreshinputdata`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_customapirulesetconfiguration_msdyn_refreshinputdata`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_UniqueName"></a> msdyn_UniqueName

|Property|Value|
|---|---|
|Description|**Unique Name for the entity.**|
|DisplayName|**Unique Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_uniquename`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|128|

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
|Description|**Status of the Custom API Ruleset Configuration**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_customapirulesetconfiguration_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Custom API Ruleset Configuration**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_customapirulesetconfiguration_statuscode`|

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

- [ComponentIdUnique](#BKMK_ComponentIdUnique)
- [ComponentState](#BKMK_ComponentState)
- [CreatedBy](#BKMK_CreatedBy)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [IsManaged](#BKMK_IsManaged)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [OverwriteTime](#BKMK_OverwriteTime)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [SolutionId](#BKMK_SolutionId)
- [SupportingSolutionId](#BKMK_SupportingSolutionId)
- [VersionNumber](#BKMK_VersionNumber)

### <a name="BKMK_ComponentIdUnique"></a> ComponentIdUnique

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Row id unique**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`componentidunique`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_ComponentState"></a> ComponentState

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Component State**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`componentstate`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue||
|GlobalChoiceName|`componentstate`|

#### ComponentState Choices/Options

|Value|Label|
|---|---|
|0|**Published**|
|1|**Unpublished**|
|2|**Deleted**|
|3|**Deleted Unpublished**|

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

### <a name="BKMK_IsManaged"></a> IsManaged

|Property|Value|
|---|---|
|Description|**Indicates whether the solution component is part of a managed solution.**|
|DisplayName|**Is Managed**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`ismanaged`|
|RequiredLevel|SystemRequired|
|Type|Boolean|
|GlobalChoiceName|`ismanaged`|
|DefaultValue|False|
|True Label|Managed|
|False Label|Unmanaged|

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

### <a name="BKMK_OverwriteTime"></a> OverwriteTime

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Record Overwrite Time**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overwritetime`|
|RequiredLevel|SystemRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

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

### <a name="BKMK_SolutionId"></a> SolutionId

|Property|Value|
|---|---|
|Description|**Unique identifier of the associated solution.**|
|DisplayName|**Solution**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`solutionid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_SupportingSolutionId"></a> SupportingSolutionId

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Solution**|
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|`supportingsolutionid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

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

- [business_unit_msdyn_customapirulesetconfiguration](#BKMK_business_unit_msdyn_customapirulesetconfiguration)
- [lk_msdyn_customapirulesetconfiguration_createdby](#BKMK_lk_msdyn_customapirulesetconfiguration_createdby)
- [lk_msdyn_customapirulesetconfiguration_createdonbehalfby](#BKMK_lk_msdyn_customapirulesetconfiguration_createdonbehalfby)
- [lk_msdyn_customapirulesetconfiguration_modifiedby](#BKMK_lk_msdyn_customapirulesetconfiguration_modifiedby)
- [lk_msdyn_customapirulesetconfiguration_modifiedonbehalfby](#BKMK_lk_msdyn_customapirulesetconfiguration_modifiedonbehalfby)
- [msdyn_customapi_msdyn_customapirulesetconfiguration_CustomAPI](#BKMK_msdyn_customapi_msdyn_customapirulesetconfiguration_CustomAPI)
- [msdyn_customapirequestparameter_msdyn_customapirulesetconfiguration_CustomAPIRequestParameter](#BKMK_msdyn_customapirequestparameter_msdyn_customapirulesetconfiguration_CustomAPIRequestParameter)
- [msdyn_customapiresponseproperty_msdyn_customapirulesetconfiguration_CustomAPIResponseProperty](#BKMK_msdyn_customapiresponseproperty_msdyn_customapirulesetconfiguration_CustomAPIResponseProperty)
- [owner_msdyn_customapirulesetconfiguration](#BKMK_owner_msdyn_customapirulesetconfiguration)
- [team_msdyn_customapirulesetconfiguration](#BKMK_team_msdyn_customapirulesetconfiguration)
- [user_msdyn_customapirulesetconfiguration](#BKMK_user_msdyn_customapirulesetconfiguration)

### <a name="BKMK_business_unit_msdyn_customapirulesetconfiguration"></a> business_unit_msdyn_customapirulesetconfiguration

One-To-Many Relationship: [businessunit business_unit_msdyn_customapirulesetconfiguration](businessunit.md#BKMK_business_unit_msdyn_customapirulesetconfiguration)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_customapirulesetconfiguration_createdby"></a> lk_msdyn_customapirulesetconfiguration_createdby

One-To-Many Relationship: [systemuser lk_msdyn_customapirulesetconfiguration_createdby](systemuser.md#BKMK_lk_msdyn_customapirulesetconfiguration_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_customapirulesetconfiguration_createdonbehalfby"></a> lk_msdyn_customapirulesetconfiguration_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_customapirulesetconfiguration_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_customapirulesetconfiguration_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_customapirulesetconfiguration_modifiedby"></a> lk_msdyn_customapirulesetconfiguration_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_customapirulesetconfiguration_modifiedby](systemuser.md#BKMK_lk_msdyn_customapirulesetconfiguration_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_customapirulesetconfiguration_modifiedonbehalfby"></a> lk_msdyn_customapirulesetconfiguration_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_customapirulesetconfiguration_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_customapirulesetconfiguration_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_customapi_msdyn_customapirulesetconfiguration_CustomAPI"></a> msdyn_customapi_msdyn_customapirulesetconfiguration_CustomAPI

One-To-Many Relationship: [customapi msdyn_customapi_msdyn_customapirulesetconfiguration_CustomAPI](customapi.md#BKMK_msdyn_customapi_msdyn_customapirulesetconfiguration_CustomAPI)

|Property|Value|
|---|---|
|ReferencedEntity|`customapi`|
|ReferencedAttribute|`customapiid`|
|ReferencingAttribute|`msdyn_customapi`|
|ReferencingEntityNavigationPropertyName|`msdyn_CustomAPI`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_customapirequestparameter_msdyn_customapirulesetconfiguration_CustomAPIRequestParameter"></a> msdyn_customapirequestparameter_msdyn_customapirulesetconfiguration_CustomAPIRequestParameter

One-To-Many Relationship: [customapirequestparameter msdyn_customapirequestparameter_msdyn_customapirulesetconfiguration_CustomAPIRequestParameter](customapirequestparameter.md#BKMK_msdyn_customapirequestparameter_msdyn_customapirulesetconfiguration_CustomAPIRequestParameter)

|Property|Value|
|---|---|
|ReferencedEntity|`customapirequestparameter`|
|ReferencedAttribute|`customapirequestparameterid`|
|ReferencingAttribute|`msdyn_customapirequestparameter`|
|ReferencingEntityNavigationPropertyName|`msdyn_CustomAPIRequestParameter`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_customapiresponseproperty_msdyn_customapirulesetconfiguration_CustomAPIResponseProperty"></a> msdyn_customapiresponseproperty_msdyn_customapirulesetconfiguration_CustomAPIResponseProperty

One-To-Many Relationship: [customapiresponseproperty msdyn_customapiresponseproperty_msdyn_customapirulesetconfiguration_CustomAPIResponseProperty](customapiresponseproperty.md#BKMK_msdyn_customapiresponseproperty_msdyn_customapirulesetconfiguration_CustomAPIResponseProperty)

|Property|Value|
|---|---|
|ReferencedEntity|`customapiresponseproperty`|
|ReferencedAttribute|`customapiresponsepropertyid`|
|ReferencingAttribute|`msdyn_customapiresponseproperty`|
|ReferencingEntityNavigationPropertyName|`msdyn_CustomAPIResponseProperty`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_customapirulesetconfiguration"></a> owner_msdyn_customapirulesetconfiguration

One-To-Many Relationship: [owner owner_msdyn_customapirulesetconfiguration](owner.md#BKMK_owner_msdyn_customapirulesetconfiguration)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_customapirulesetconfiguration"></a> team_msdyn_customapirulesetconfiguration

One-To-Many Relationship: [team team_msdyn_customapirulesetconfiguration](team.md#BKMK_team_msdyn_customapirulesetconfiguration)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_customapirulesetconfiguration"></a> user_msdyn_customapirulesetconfiguration

One-To-Many Relationship: [systemuser user_msdyn_customapirulesetconfiguration](systemuser.md#BKMK_user_msdyn_customapirulesetconfiguration)

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

- [msdyn_customapirulesetconfiguration_AsyncOperations](#BKMK_msdyn_customapirulesetconfiguration_AsyncOperations)
- [msdyn_customapirulesetconfiguration_BulkDeleteFailures](#BKMK_msdyn_customapirulesetconfiguration_BulkDeleteFailures)
- [msdyn_customapirulesetconfiguration_DuplicateBaseRecord](#BKMK_msdyn_customapirulesetconfiguration_DuplicateBaseRecord)
- [msdyn_customapirulesetconfiguration_DuplicateMatchingRecord](#BKMK_msdyn_customapirulesetconfiguration_DuplicateMatchingRecord)
- [msdyn_customapirulesetconfiguration_MailboxTrackingFolders](#BKMK_msdyn_customapirulesetconfiguration_MailboxTrackingFolders)
- [msdyn_customapirulesetconfiguration_PrincipalObjectAttributeAccesses](#BKMK_msdyn_customapirulesetconfiguration_PrincipalObjectAttributeAccesses)
- [msdyn_customapirulesetconfiguration_ProcessSession](#BKMK_msdyn_customapirulesetconfiguration_ProcessSession)
- [msdyn_customapirulesetconfiguration_SyncErrors](#BKMK_msdyn_customapirulesetconfiguration_SyncErrors)
- [msdyn_rulesetdependencymapping_msdyn_customapirulesetconfig_msdyn_referencedpolymorphicentityid](#BKMK_msdyn_rulesetdependencymapping_msdyn_customapirulesetconfig_msdyn_referencedpolymorphicentityid)

### <a name="BKMK_msdyn_customapirulesetconfiguration_AsyncOperations"></a> msdyn_customapirulesetconfiguration_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_customapirulesetconfiguration_AsyncOperations](asyncoperation.md#BKMK_msdyn_customapirulesetconfiguration_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfiguration_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_customapirulesetconfiguration_BulkDeleteFailures"></a> msdyn_customapirulesetconfiguration_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_customapirulesetconfiguration_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_customapirulesetconfiguration_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfiguration_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_customapirulesetconfiguration_DuplicateBaseRecord"></a> msdyn_customapirulesetconfiguration_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_customapirulesetconfiguration_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_customapirulesetconfiguration_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfiguration_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_customapirulesetconfiguration_DuplicateMatchingRecord"></a> msdyn_customapirulesetconfiguration_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_customapirulesetconfiguration_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_customapirulesetconfiguration_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfiguration_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_customapirulesetconfiguration_MailboxTrackingFolders"></a> msdyn_customapirulesetconfiguration_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_customapirulesetconfiguration_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_customapirulesetconfiguration_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfiguration_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_customapirulesetconfiguration_PrincipalObjectAttributeAccesses"></a> msdyn_customapirulesetconfiguration_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_customapirulesetconfiguration_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_customapirulesetconfiguration_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfiguration_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_customapirulesetconfiguration_ProcessSession"></a> msdyn_customapirulesetconfiguration_ProcessSession

Many-To-One Relationship: [processsession msdyn_customapirulesetconfiguration_ProcessSession](processsession.md#BKMK_msdyn_customapirulesetconfiguration_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfiguration_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_customapirulesetconfiguration_SyncErrors"></a> msdyn_customapirulesetconfiguration_SyncErrors

Many-To-One Relationship: [syncerror msdyn_customapirulesetconfiguration_SyncErrors](syncerror.md#BKMK_msdyn_customapirulesetconfiguration_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfiguration_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_rulesetdependencymapping_msdyn_customapirulesetconfig_msdyn_referencedpolymorphicentityid"></a> msdyn_rulesetdependencymapping_msdyn_customapirulesetconfig_msdyn_referencedpolymorphicentityid

Many-To-One Relationship: [msdyn_rulesetdependencymapping msdyn_rulesetdependencymapping_msdyn_customapirulesetconfig_msdyn_referencedpolymorphicentityid](msdyn_rulesetdependencymapping.md#BKMK_msdyn_rulesetdependencymapping_msdyn_customapirulesetconfig_msdyn_referencedpolymorphicentityid)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_rulesetdependencymapping`|
|ReferencingAttribute|`msdyn_referencedpolymorphicentityid`|
|ReferencedEntityNavigationPropertyName|`msdyn_customapirulesetconfig_msdyn_rulesetdependencymapping_msdyn_referencedpolymorphicentityid`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

