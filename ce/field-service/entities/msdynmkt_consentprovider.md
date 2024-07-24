---
title: "Consent Provider (msdynmkt_consentprovider) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Consent Provider (msdynmkt_consentprovider) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 07.24.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Consent Provider (msdynmkt_consentprovider) table/entity reference



## Messages

The following table lists the messages for the Consent Provider (msdynmkt_consentprovider) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdynmkt_consentproviders(*msdynmkt_consentproviderid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdynmkt_consentproviders<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdynmkt_consentproviders(*msdynmkt_consentproviderid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Retrieve`<br />Event: True |`GET` /msdynmkt_consentproviders(*msdynmkt_consentproviderid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdynmkt_consentproviders<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdynmkt_consentproviders(*msdynmkt_consentproviderid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdynmkt_consentproviders(*msdynmkt_consentproviderid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdynmkt_consentproviders(*msdynmkt_consentproviderid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Consent Provider (msdynmkt_consentprovider) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Consent Provider (msdynmkt_consentprovider) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Consent Provider** |
| **DisplayCollectionName** | **Consent Providers** |
| **SchemaName** | `msdynmkt_consentprovider` |
| **CollectionSchemaName** | `msdynmkt_consentproviders` |
| **EntitySetName** | `msdynmkt_consentproviders`|
| **LogicalName** | `msdynmkt_consentprovider` |
| **LogicalCollectionName** | `msdynmkt_consentproviders` |
| **PrimaryIdAttribute** | `msdynmkt_consentproviderid` |
| **PrimaryNameAttribute** |`msdynmkt_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IsCustomizable](#BKMK_IsCustomizable)
- [msdynmkt_consentcheckurltemplate](#BKMK_msdynmkt_consentcheckurltemplate)
- [msdynmkt_consentproviderexternalentity](#BKMK_msdynmkt_consentproviderexternalentity)
- [msdynmkt_consentproviderexternalformidentifier](#BKMK_msdynmkt_consentproviderexternalformidentifier)
- [msdynmkt_consentproviderexternalpurposeentity](#BKMK_msdynmkt_consentproviderexternalpurposeentity)
- [msdynmkt_consentproviderexternalpurposeformidentifier](#BKMK_msdynmkt_consentproviderexternalpurposeformidentifier)
- [msdynmkt_consentproviderId](#BKMK_msdynmkt_consentproviderId)
- [msdynmkt_consentresolutionmessageoptions](#BKMK_msdynmkt_consentresolutionmessageoptions)
- [msdynmkt_consentresolutiontrackingoptions](#BKMK_msdynmkt_consentresolutiontrackingoptions)
- [msdynmkt_email_consentresolutionmessageoverride](#BKMK_msdynmkt_email_consentresolutionmessageoverride)
- [msdynmkt_email_consentresolutiontrackingoverride](#BKMK_msdynmkt_email_consentresolutiontrackingoverride)
- [msdynmkt_name](#BKMK_msdynmkt_name)
- [msdynmkt_oneclickunsubscribesupported](#BKMK_msdynmkt_oneclickunsubscribesupported)
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

### <a name="BKMK_msdynmkt_consentcheckurltemplate"></a> msdynmkt_consentcheckurltemplate

|Property|Value|
|---|---|
|Description||
|DisplayName|**Consent Check Url Template**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_consentcheckurltemplate`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdynmkt_consentproviderexternalentity"></a> msdynmkt_consentproviderexternalentity

|Property|Value|
|---|---|
|Description||
|DisplayName|**Consent Provider External Entity**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_consentproviderexternalentity`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdynmkt_consentproviderexternalformidentifier"></a> msdynmkt_consentproviderexternalformidentifier

|Property|Value|
|---|---|
|Description||
|DisplayName|**Consent Provider External Form Identifier**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_consentproviderexternalformidentifier`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|36|

### <a name="BKMK_msdynmkt_consentproviderexternalpurposeentity"></a> msdynmkt_consentproviderexternalpurposeentity

|Property|Value|
|---|---|
|Description||
|DisplayName|**Consent Provider External Purpose Entity**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_consentproviderexternalpurposeentity`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdynmkt_consentproviderexternalpurposeformidentifier"></a> msdynmkt_consentproviderexternalpurposeformidentifier

|Property|Value|
|---|---|
|Description||
|DisplayName|**Consent Provider External Purpose Form Identifier**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_consentproviderexternalpurposeformidentifier`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|36|

### <a name="BKMK_msdynmkt_consentproviderId"></a> msdynmkt_consentproviderId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Consent Provider**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdynmkt_consentproviderid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdynmkt_consentresolutionmessageoptions"></a> msdynmkt_consentresolutionmessageoptions

|Property|Value|
|---|---|
|Description||
|DisplayName|**External consent resolution for messages**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_consentresolutionmessageoptions`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|238550001|
|GlobalChoiceName|`msdynmkt_externalconsentresolutionoptions`|

#### msdynmkt_consentresolutionmessageoptions Choices/Options

|Value|Label|
|---|---|
|238550001|**Use custom api to resolve**|
|238550002|**Always resolve to consent given**|
|238550003|**Always resolve to consent not given**|
|238550004|**Use Real-time journeys default implementation**|

### <a name="BKMK_msdynmkt_consentresolutiontrackingoptions"></a> msdynmkt_consentresolutiontrackingoptions

|Property|Value|
|---|---|
|Description||
|DisplayName|**External consent resolution for messages**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_consentresolutiontrackingoptions`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|238550001|
|GlobalChoiceName|`msdynmkt_externalconsentresolutionoptions`|

#### msdynmkt_consentresolutiontrackingoptions Choices/Options

|Value|Label|
|---|---|
|238550001|**Use custom api to resolve**|
|238550002|**Always resolve to consent given**|
|238550003|**Always resolve to consent not given**|
|238550004|**Use Real-time journeys default implementation**|

### <a name="BKMK_msdynmkt_email_consentresolutionmessageoverride"></a> msdynmkt_email_consentresolutionmessageoverride

|Property|Value|
|---|---|
|Description||
|DisplayName|**Email channel resolution for message override**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_email_consentresolutionmessageoverride`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|238550000|
|GlobalChoiceName|`msdynmkt_channelconsentresolutionoverrides`|

#### msdynmkt_email_consentresolutionmessageoverride Choices/Options

|Value|Label|
|---|---|
|238550000|**No override**|
|238550001|**Use custom api to resolve**|
|238550002|**Always resolve to consent given**|
|238550003|**Always resolve to consent not given**|
|238550004|**Use Real-time journeys default implementation**|

### <a name="BKMK_msdynmkt_email_consentresolutiontrackingoverride"></a> msdynmkt_email_consentresolutiontrackingoverride

|Property|Value|
|---|---|
|Description||
|DisplayName|**External consent resolution for messages**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_email_consentresolutiontrackingoverride`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|238550000|
|GlobalChoiceName|`msdynmkt_channelconsentresolutionoverrides`|

#### msdynmkt_email_consentresolutiontrackingoverride Choices/Options

|Value|Label|
|---|---|
|238550000|**No override**|
|238550001|**Use custom api to resolve**|
|238550002|**Always resolve to consent given**|
|238550003|**Always resolve to consent not given**|
|238550004|**Use Real-time journeys default implementation**|

### <a name="BKMK_msdynmkt_name"></a> msdynmkt_name

|Property|Value|
|---|---|
|Description|**The name of the custom entity.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_name`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdynmkt_oneclickunsubscribesupported"></a> msdynmkt_oneclickunsubscribesupported

|Property|Value|
|---|---|
|Description||
|DisplayName|**One click unsubscribe supported**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdynmkt_oneclickunsubscribesupported`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdynmkt_consentprovider_msdynmkt_oneclickunsubscribesupported`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

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
|Description|**Status of the Consent Provider**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdynmkt_consentprovider_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Consent Provider**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdynmkt_consentprovider_statuscode`|

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

- [business_unit_msdynmkt_consentprovider](#BKMK_business_unit_msdynmkt_consentprovider)
- [lk_msdynmkt_consentprovider_createdby](#BKMK_lk_msdynmkt_consentprovider_createdby)
- [lk_msdynmkt_consentprovider_createdonbehalfby](#BKMK_lk_msdynmkt_consentprovider_createdonbehalfby)
- [lk_msdynmkt_consentprovider_modifiedby](#BKMK_lk_msdynmkt_consentprovider_modifiedby)
- [lk_msdynmkt_consentprovider_modifiedonbehalfby](#BKMK_lk_msdynmkt_consentprovider_modifiedonbehalfby)
- [owner_msdynmkt_consentprovider](#BKMK_owner_msdynmkt_consentprovider)
- [team_msdynmkt_consentprovider](#BKMK_team_msdynmkt_consentprovider)
- [user_msdynmkt_consentprovider](#BKMK_user_msdynmkt_consentprovider)

### <a name="BKMK_business_unit_msdynmkt_consentprovider"></a> business_unit_msdynmkt_consentprovider

One-To-Many Relationship: [businessunit business_unit_msdynmkt_consentprovider](businessunit.md#BKMK_business_unit_msdynmkt_consentprovider)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdynmkt_consentprovider_createdby"></a> lk_msdynmkt_consentprovider_createdby

One-To-Many Relationship: [systemuser lk_msdynmkt_consentprovider_createdby](systemuser.md#BKMK_lk_msdynmkt_consentprovider_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdynmkt_consentprovider_createdonbehalfby"></a> lk_msdynmkt_consentprovider_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdynmkt_consentprovider_createdonbehalfby](systemuser.md#BKMK_lk_msdynmkt_consentprovider_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdynmkt_consentprovider_modifiedby"></a> lk_msdynmkt_consentprovider_modifiedby

One-To-Many Relationship: [systemuser lk_msdynmkt_consentprovider_modifiedby](systemuser.md#BKMK_lk_msdynmkt_consentprovider_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdynmkt_consentprovider_modifiedonbehalfby"></a> lk_msdynmkt_consentprovider_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdynmkt_consentprovider_modifiedonbehalfby](systemuser.md#BKMK_lk_msdynmkt_consentprovider_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdynmkt_consentprovider"></a> owner_msdynmkt_consentprovider

One-To-Many Relationship: [owner owner_msdynmkt_consentprovider](owner.md#BKMK_owner_msdynmkt_consentprovider)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdynmkt_consentprovider"></a> team_msdynmkt_consentprovider

One-To-Many Relationship: [team team_msdynmkt_consentprovider](team.md#BKMK_team_msdynmkt_consentprovider)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdynmkt_consentprovider"></a> user_msdynmkt_consentprovider

One-To-Many Relationship: [systemuser user_msdynmkt_consentprovider](systemuser.md#BKMK_user_msdynmkt_consentprovider)

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

- [msdynmkt_consentprovider_AsyncOperations](#BKMK_msdynmkt_consentprovider_AsyncOperations)
- [msdynmkt_consentprovider_BulkDeleteFailures](#BKMK_msdynmkt_consentprovider_BulkDeleteFailures)
- [msdynmkt_consentprovider_DuplicateBaseRecord](#BKMK_msdynmkt_consentprovider_DuplicateBaseRecord)
- [msdynmkt_consentprovider_DuplicateMatchingRecord](#BKMK_msdynmkt_consentprovider_DuplicateMatchingRecord)
- [msdynmkt_consentprovider_MailboxTrackingFolders](#BKMK_msdynmkt_consentprovider_MailboxTrackingFolders)
- [msdynmkt_consentprovider_PrincipalObjectAttributeAccesses](#BKMK_msdynmkt_consentprovider_PrincipalObjectAttributeAccesses)
- [msdynmkt_consentprovider_ProcessSession](#BKMK_msdynmkt_consentprovider_ProcessSession)
- [msdynmkt_consentprovider_SyncErrors](#BKMK_msdynmkt_consentprovider_SyncErrors)
- [msdynmkt_ConsentproviderLocalization_msdynmk](#BKMK_msdynmkt_ConsentproviderLocalization_msdynmk)
- [msdynmkt_msdynmkt_consentprovider_msdynmkt_complia](#BKMK_msdynmkt_msdynmkt_consentprovider_msdynmkt_complia)

### <a name="BKMK_msdynmkt_consentprovider_AsyncOperations"></a> msdynmkt_consentprovider_AsyncOperations

Many-To-One Relationship: [asyncoperation msdynmkt_consentprovider_AsyncOperations](asyncoperation.md#BKMK_msdynmkt_consentprovider_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_consentprovider_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_consentprovider_BulkDeleteFailures"></a> msdynmkt_consentprovider_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdynmkt_consentprovider_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdynmkt_consentprovider_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_consentprovider_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_consentprovider_DuplicateBaseRecord"></a> msdynmkt_consentprovider_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdynmkt_consentprovider_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdynmkt_consentprovider_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_consentprovider_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_consentprovider_DuplicateMatchingRecord"></a> msdynmkt_consentprovider_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdynmkt_consentprovider_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdynmkt_consentprovider_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_consentprovider_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_consentprovider_MailboxTrackingFolders"></a> msdynmkt_consentprovider_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdynmkt_consentprovider_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdynmkt_consentprovider_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_consentprovider_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_consentprovider_PrincipalObjectAttributeAccesses"></a> msdynmkt_consentprovider_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdynmkt_consentprovider_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdynmkt_consentprovider_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_consentprovider_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_consentprovider_ProcessSession"></a> msdynmkt_consentprovider_ProcessSession

Many-To-One Relationship: [processsession msdynmkt_consentprovider_ProcessSession](processsession.md#BKMK_msdynmkt_consentprovider_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_consentprovider_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_consentprovider_SyncErrors"></a> msdynmkt_consentprovider_SyncErrors

Many-To-One Relationship: [syncerror msdynmkt_consentprovider_SyncErrors](syncerror.md#BKMK_msdynmkt_consentprovider_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_consentprovider_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_ConsentproviderLocalization_msdynmk"></a> msdynmkt_ConsentproviderLocalization_msdynmk

Many-To-One Relationship: [msdynmkt_consentproviderlocalization msdynmkt_ConsentproviderLocalization_msdynmk](msdynmkt_consentproviderlocalization.md#BKMK_msdynmkt_ConsentproviderLocalization_msdynmk)

|Property|Value|
|---|---|
|ReferencingEntity|`msdynmkt_consentproviderlocalization`|
|ReferencingAttribute|`msdynmkt_msdynmkt_consentprovider`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_ConsentproviderLocalization_msdynmk`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdynmkt_msdynmkt_consentprovider_msdynmkt_complia"></a> msdynmkt_msdynmkt_consentprovider_msdynmkt_complia

Many-To-One Relationship: [msdynmkt_compliancesettings4 msdynmkt_msdynmkt_consentprovider_msdynmkt_complia](msdynmkt_compliancesettings4.md#BKMK_msdynmkt_msdynmkt_consentprovider_msdynmkt_complia)

|Property|Value|
|---|---|
|ReferencingEntity|`msdynmkt_compliancesettings4`|
|ReferencingAttribute|`msdynmkt_consentproviderid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_msdynmkt_consentprovider_msdynmkt_complia`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

