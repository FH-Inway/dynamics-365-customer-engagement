---
title: "Sentiment analysis (msdyn_sentimentanalysis) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Sentiment analysis (msdyn_sentimentanalysis) table/entity with Microsoft Dynamics 365."
ms.topic: generated-reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# Sentiment analysis (msdyn_sentimentanalysis) table/entity reference (Microsoft Dynamics 365)

Sentiment analysis configuration

## Messages

The following table lists the messages for the Sentiment analysis (msdyn_sentimentanalysis) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Associate`<br />Event: True |[Associate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Associate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-associate-method-or-associaterequest)|
| `BulkRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Create`<br />Event: True |`POST` /msdyn_sentimentanalysises<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_sentimentanalysises(*msdyn_sentimentanalysisid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Disassociate`<br />Event: True |[Disassociate records](/power-apps/developer/data-platform/webapi/associate-disassociate-entities-using-web-api) |[Disassociate records](/power-apps/developer/data-platform/org-service/entity-operations-associate-disassociate#use-the-disassociate-method-or-disassociaterequest)|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `PurgeRetainedContent`<br />Event: True |<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_sentimentanalysises(*msdyn_sentimentanalysisid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_sentimentanalysises<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RollbackRetain`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `SetState`<br />Event: True |`PATCH` /msdyn_sentimentanalysises(*msdyn_sentimentanalysisid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_sentimentanalysises(*msdyn_sentimentanalysisid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_sentimentanalysises(*msdyn_sentimentanalysisid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|
| `ValidateRetentionConfig`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Sentiment analysis (msdyn_sentimentanalysis) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Sentiment analysis** |
| **DisplayCollectionName** | **Sentiment analysis** |
| **SchemaName** | `msdyn_sentimentanalysis` |
| **CollectionSchemaName** | `msdyn_sentimentanalysises` |
| **EntitySetName** | `msdyn_sentimentanalysises`|
| **LogicalName** | `msdyn_sentimentanalysis` |
| **LogicalCollectionName** | `msdyn_sentimentanalysises` |
| **PrimaryIdAttribute** | `msdyn_sentimentanalysisid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IsCustomizable](#BKMK_IsCustomizable)
- [msdyn_additionallanguagesenabled](#BKMK_msdyn_additionallanguagesenabled)
- [msdyn_agentthreshold](#BKMK_msdyn_agentthreshold)
- [msdyn_driversenabled](#BKMK_msdyn_driversenabled)
- [msdyn_enabled](#BKMK_msdyn_enabled)
- [msdyn_enableur](#BKMK_msdyn_enableur)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_sentimentanalysisId](#BKMK_msdyn_sentimentanalysisId)
- [msdyn_supervisorthreshold](#BKMK_msdyn_supervisorthreshold)
- [msdyn_supervisorthresholdalerttimeoutseconds](#BKMK_msdyn_supervisorthresholdalerttimeoutseconds)
- [msdyn_thresholdalertsenabled](#BKMK_msdyn_thresholdalertsenabled)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
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

### <a name="BKMK_msdyn_additionallanguagesenabled"></a> msdyn_additionallanguagesenabled

|Property|Value|
|---|---|
|Description|**(Deprecated) Whether multi-language support is enabled**|
|DisplayName|**(Deprecated) Multi-language support enabled**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_additionallanguagesenabled`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_sentimentanalysis_msdyn_additionallanguagesenabled`|
|DefaultValue|True|
|True Label|(Deprecated) Yes|
|False Label|(Deprecated) No|

### <a name="BKMK_msdyn_agentthreshold"></a> msdyn_agentthreshold

|Property|Value|
|---|---|
|Description|**The agent threshold for sentiment threshold alerts**|
|DisplayName|**Agent alert threshold**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_agentthreshold`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`msdyn_sentimentanalysis_msdyn_agentthreshold`|

#### msdyn_agentthreshold Choices/Options

|Value|Label|
|---|---|
|0|**Don't show alerts**|
|7|**Very negative**|
|8|**Negative**|
|9|**Slightly negative**|

### <a name="BKMK_msdyn_driversenabled"></a> msdyn_driversenabled

|Property|Value|
|---|---|
|Description|**This field is deprecated**|
|DisplayName|**(Deprecated) Report sentiment drivers in Omnichannel Insights**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_driversenabled`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_driversenabled`|
|DefaultValue|False|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_enabled"></a> msdyn_enabled

|Property|Value|
|---|---|
|Description|**Whether real-time customer sentiment monitoring is enabled**|
|DisplayName|**Monitor real-time customer sentiment**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_enabled`|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|
|GlobalChoiceName|`msdyn_sentimentanalysis_msdyn_enabled`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_enableur"></a> msdyn_enableur

|Property|Value|
|---|---|
|Description|**Enable Unified Routing**|
|DisplayName|**Enable Unified Routing**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_enableur`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`new_msdyn_sentimentanalysis_msdyn_enableur`|
|DefaultValue|True|
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
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_sentimentanalysisId"></a> msdyn_sentimentanalysisId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Sentiment analysis**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_sentimentanalysisid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_supervisorthreshold"></a> msdyn_supervisorthreshold

|Property|Value|
|---|---|
|Description|**The supervisor threshold for sentiment threshold alerts**|
|DisplayName|**Supervisor alert threshold**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_supervisorthreshold`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`msdyn_sentimentanalysis_msdyn_supervisorthreshold`|

#### msdyn_supervisorthreshold Choices/Options

|Value|Label|
|---|---|
|0|**Don't send notifications**|
|7|**Very negative**|
|8|**Negative**|
|9|**Slightly negative**|

### <a name="BKMK_msdyn_supervisorthresholdalerttimeoutseconds"></a> msdyn_supervisorthresholdalerttimeoutseconds

|Property|Value|
|---|---|
|Description|**This field is deprecated**|
|DisplayName|**(Deprecated) Supervisor alert timeout in seconds**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_supervisorthresholdalerttimeoutseconds`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|500|
|MinValue|1|

### <a name="BKMK_msdyn_thresholdalertsenabled"></a> msdyn_thresholdalertsenabled

|Property|Value|
|---|---|
|Description|**This field is deprecated**|
|DisplayName|**(Deprecated) Threshold alerts enabled**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_thresholdalertsenabled`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_sentimentanalysis_msdyn_thresholdalertsenabled`|
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

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the sentiment analysis**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_sentimentanalysis_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Sentiment Analysis**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_sentimentanalysis_statuscode`|

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
- [OrganizationId](#BKMK_OrganizationId)
- [OverwriteTime](#BKMK_OverwriteTime)
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

### <a name="BKMK_OrganizationId"></a> OrganizationId

|Property|Value|
|---|---|
|Description|**Unique identifier for the organization**|
|DisplayName|**Organization Id**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`organizationid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|organization|

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

- [lk_msdyn_sentimentanalysis_createdby](#BKMK_lk_msdyn_sentimentanalysis_createdby)
- [lk_msdyn_sentimentanalysis_createdonbehalfby](#BKMK_lk_msdyn_sentimentanalysis_createdonbehalfby)
- [lk_msdyn_sentimentanalysis_modifiedby](#BKMK_lk_msdyn_sentimentanalysis_modifiedby)
- [lk_msdyn_sentimentanalysis_modifiedonbehalfby](#BKMK_lk_msdyn_sentimentanalysis_modifiedonbehalfby)
- [organization_msdyn_sentimentanalysis](#BKMK_organization_msdyn_sentimentanalysis)

### <a name="BKMK_lk_msdyn_sentimentanalysis_createdby"></a> lk_msdyn_sentimentanalysis_createdby

One-To-Many Relationship: [systemuser lk_msdyn_sentimentanalysis_createdby](systemuser.md#BKMK_lk_msdyn_sentimentanalysis_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_sentimentanalysis_createdonbehalfby"></a> lk_msdyn_sentimentanalysis_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_sentimentanalysis_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_sentimentanalysis_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_sentimentanalysis_modifiedby"></a> lk_msdyn_sentimentanalysis_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_sentimentanalysis_modifiedby](systemuser.md#BKMK_lk_msdyn_sentimentanalysis_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_sentimentanalysis_modifiedonbehalfby"></a> lk_msdyn_sentimentanalysis_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_sentimentanalysis_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_sentimentanalysis_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_organization_msdyn_sentimentanalysis"></a> organization_msdyn_sentimentanalysis

One-To-Many Relationship: [organization organization_msdyn_sentimentanalysis](organization.md#BKMK_organization_msdyn_sentimentanalysis)

|Property|Value|
|---|---|
|ReferencedEntity|`organization`|
|ReferencedAttribute|`organizationid`|
|ReferencingAttribute|`organizationid`|
|ReferencingEntityNavigationPropertyName|`organizationid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_sentimentanalysis_AsyncOperations](#BKMK_msdyn_sentimentanalysis_AsyncOperations)
- [msdyn_sentimentanalysis_BulkDeleteFailures](#BKMK_msdyn_sentimentanalysis_BulkDeleteFailures)
- [msdyn_sentimentanalysis_DuplicateBaseRecord](#BKMK_msdyn_sentimentanalysis_DuplicateBaseRecord)
- [msdyn_sentimentanalysis_DuplicateMatchingRecord](#BKMK_msdyn_sentimentanalysis_DuplicateMatchingRecord)
- [msdyn_sentimentanalysis_MailboxTrackingFolders](#BKMK_msdyn_sentimentanalysis_MailboxTrackingFolders)
- [msdyn_sentimentanalysis_PrincipalObjectAttributeAccesses](#BKMK_msdyn_sentimentanalysis_PrincipalObjectAttributeAccesses)
- [msdyn_sentimentanalysis_ProcessSession](#BKMK_msdyn_sentimentanalysis_ProcessSession)
- [msdyn_sentimentanalysis_SyncErrors](#BKMK_msdyn_sentimentanalysis_SyncErrors)

### <a name="BKMK_msdyn_sentimentanalysis_AsyncOperations"></a> msdyn_sentimentanalysis_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_sentimentanalysis_AsyncOperations](asyncoperation.md#BKMK_msdyn_sentimentanalysis_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_sentimentanalysis_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_sentimentanalysis_BulkDeleteFailures"></a> msdyn_sentimentanalysis_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_sentimentanalysis_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_sentimentanalysis_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_sentimentanalysis_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_sentimentanalysis_DuplicateBaseRecord"></a> msdyn_sentimentanalysis_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_sentimentanalysis_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_sentimentanalysis_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_sentimentanalysis_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_sentimentanalysis_DuplicateMatchingRecord"></a> msdyn_sentimentanalysis_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_sentimentanalysis_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_sentimentanalysis_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_sentimentanalysis_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_sentimentanalysis_MailboxTrackingFolders"></a> msdyn_sentimentanalysis_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_sentimentanalysis_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_sentimentanalysis_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_sentimentanalysis_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_sentimentanalysis_PrincipalObjectAttributeAccesses"></a> msdyn_sentimentanalysis_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_sentimentanalysis_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_sentimentanalysis_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_sentimentanalysis_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_sentimentanalysis_ProcessSession"></a> msdyn_sentimentanalysis_ProcessSession

Many-To-One Relationship: [processsession msdyn_sentimentanalysis_ProcessSession](processsession.md#BKMK_msdyn_sentimentanalysis_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_sentimentanalysis_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_sentimentanalysis_SyncErrors"></a> msdyn_sentimentanalysis_SyncErrors

Many-To-One Relationship: [syncerror msdyn_sentimentanalysis_SyncErrors](syncerror.md#BKMK_msdyn_sentimentanalysis_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_sentimentanalysis_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](/power-apps/developer/data-platform/reference/about-entity-reference)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

