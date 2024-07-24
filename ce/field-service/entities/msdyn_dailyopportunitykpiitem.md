---
title: "Daily kpis for Opportunity (msdyn_dailyopportunitykpiitem) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Daily kpis for Opportunity (msdyn_dailyopportunitykpiitem) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 07.24.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Daily kpis for Opportunity (msdyn_dailyopportunitykpiitem) table/entity reference



## Messages

The following table lists the messages for the Daily kpis for Opportunity (msdyn_dailyopportunitykpiitem) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Create`<br />Event: True |`POST` /msdyn_dailyopportunitykpiitems<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_dailyopportunitykpiitems(*msdyn_dailyopportunitykpiitemid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retrieve`<br />Event: True |`GET` /msdyn_dailyopportunitykpiitems(*msdyn_dailyopportunitykpiitemid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_dailyopportunitykpiitems<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `SetState`<br />Event: True |`PATCH` /msdyn_dailyopportunitykpiitems(*msdyn_dailyopportunitykpiitemid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_dailyopportunitykpiitems(*msdyn_dailyopportunitykpiitemid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_dailyopportunitykpiitems(*msdyn_dailyopportunitykpiitemid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Daily kpis for Opportunity (msdyn_dailyopportunitykpiitem) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Daily kpis for Opportunity (msdyn_dailyopportunitykpiitem) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Daily kpis for Opportunity** |
| **DisplayCollectionName** | **dailyopportunitykpiitems** |
| **SchemaName** | `msdyn_dailyopportunitykpiitem` |
| **CollectionSchemaName** | `msdyn_dailyopportunitykpiitems` |
| **EntitySetName** | `msdyn_dailyopportunitykpiitems`|
| **LogicalName** | `msdyn_dailyopportunitykpiitem` |
| **LogicalCollectionName** | `msdyn_dailyopportunitykpiitems` |
| **PrimaryIdAttribute** | `msdyn_dailyopportunitykpiitemid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_computationaccuracy](#BKMK_msdyn_computationaccuracy)
- [msdyn_dailyopportunitykpiitemId](#BKMK_msdyn_dailyopportunitykpiitemId)
- [msdyn_date](#BKMK_msdyn_date)
- [msdyn_emailsreceived](#BKMK_msdyn_emailsreceived)
- [msdyn_emailssent](#BKMK_msdyn_emailssent)
- [msdyn_entityid](#BKMK_msdyn_entityid)
- [msdyn_liemailssent](#BKMK_msdyn_liemailssent)
- [msdyn_meetingsreceived](#BKMK_msdyn_meetingsreceived)
- [msdyn_meetingssent](#BKMK_msdyn_meetingssent)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_opportunityId](#BKMK_msdyn_opportunityId)
- [msdyn_phonecallsmade](#BKMK_msdyn_phonecallsmade)
- [msdyn_phonecallsreceived](#BKMK_msdyn_phonecallsreceived)
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

### <a name="BKMK_msdyn_computationaccuracy"></a> msdyn_computationaccuracy

|Property|Value|
|---|---|
|Description||
|DisplayName|**Computation Accuracy**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_computationaccuracy`|
|RequiredLevel|None|
|Type|Picklist|
|DefaultFormValue|100000000|
|GlobalChoiceName|`msdyn_kpicomputationaccuracy`|

#### msdyn_computationaccuracy Choices/Options

|Value|Label|
|---|---|
|100000000|**Complete**|
|100000001|**Partial**|

### <a name="BKMK_msdyn_dailyopportunitykpiitemId"></a> msdyn_dailyopportunitykpiitemId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Daily kpis for Opportunity**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_dailyopportunitykpiitemid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_date"></a> msdyn_date

|Property|Value|
|---|---|
|Description||
|DisplayName|**Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_date`|
|RequiredLevel|ApplicationRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_emailsreceived"></a> msdyn_emailsreceived

|Property|Value|
|---|---|
|Description||
|DisplayName|**emails received**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_emailsreceived`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

### <a name="BKMK_msdyn_emailssent"></a> msdyn_emailssent

|Property|Value|
|---|---|
|Description||
|DisplayName|**Emails sent**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_emailssent`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

### <a name="BKMK_msdyn_entityid"></a> msdyn_entityid

|Property|Value|
|---|---|
|Description||
|DisplayName|**Opportunity ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_entityid`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|opportunity|

### <a name="BKMK_msdyn_liemailssent"></a> msdyn_liemailssent

|Property|Value|
|---|---|
|Description||
|DisplayName|**LinkedIn emails sent**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_liemailssent`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

### <a name="BKMK_msdyn_meetingsreceived"></a> msdyn_meetingsreceived

|Property|Value|
|---|---|
|Description||
|DisplayName|**meetings received**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_meetingsreceived`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

### <a name="BKMK_msdyn_meetingssent"></a> msdyn_meetingssent

|Property|Value|
|---|---|
|Description||
|DisplayName|**meetings sent**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_meetingssent`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

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

### <a name="BKMK_msdyn_opportunityId"></a> msdyn_opportunityId

|Property|Value|
|---|---|
|Description||
|DisplayName|**OpportunityId**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_opportunityid`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_phonecallsmade"></a> msdyn_phonecallsmade

|Property|Value|
|---|---|
|Description||
|DisplayName|**phone calls made**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_phonecallsmade`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

### <a name="BKMK_msdyn_phonecallsreceived"></a> msdyn_phonecallsreceived

|Property|Value|
|---|---|
|Description||
|DisplayName|**phone calls received**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_phonecallsreceived`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|0|

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
|Description|**Status of the Daily kpis for Opportunity**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_dailyopportunitykpiitem_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Daily kpis for Opportunity**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_dailyopportunitykpiitem_statuscode`|

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
- [OrganizationId](#BKMK_OrganizationId)
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

- [lk_msdyn_dailyopportunitykpiitem_createdby](#BKMK_lk_msdyn_dailyopportunitykpiitem_createdby)
- [lk_msdyn_dailyopportunitykpiitem_createdonbehalfby](#BKMK_lk_msdyn_dailyopportunitykpiitem_createdonbehalfby)
- [lk_msdyn_dailyopportunitykpiitem_modifiedby](#BKMK_lk_msdyn_dailyopportunitykpiitem_modifiedby)
- [lk_msdyn_dailyopportunitykpiitem_modifiedonbehalfby](#BKMK_lk_msdyn_dailyopportunitykpiitem_modifiedonbehalfby)
- [msdyn_opportunity_dailyopportunitykpiitem_entityid](#BKMK_msdyn_opportunity_dailyopportunitykpiitem_entityid)
- [organization_msdyn_dailyopportunitykpiitem](#BKMK_organization_msdyn_dailyopportunitykpiitem)

### <a name="BKMK_lk_msdyn_dailyopportunitykpiitem_createdby"></a> lk_msdyn_dailyopportunitykpiitem_createdby

One-To-Many Relationship: [systemuser lk_msdyn_dailyopportunitykpiitem_createdby](systemuser.md#BKMK_lk_msdyn_dailyopportunitykpiitem_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_dailyopportunitykpiitem_createdonbehalfby"></a> lk_msdyn_dailyopportunitykpiitem_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_dailyopportunitykpiitem_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_dailyopportunitykpiitem_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_dailyopportunitykpiitem_modifiedby"></a> lk_msdyn_dailyopportunitykpiitem_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_dailyopportunitykpiitem_modifiedby](systemuser.md#BKMK_lk_msdyn_dailyopportunitykpiitem_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_dailyopportunitykpiitem_modifiedonbehalfby"></a> lk_msdyn_dailyopportunitykpiitem_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_dailyopportunitykpiitem_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_dailyopportunitykpiitem_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_opportunity_dailyopportunitykpiitem_entityid"></a> msdyn_opportunity_dailyopportunitykpiitem_entityid

One-To-Many Relationship: [opportunity msdyn_opportunity_dailyopportunitykpiitem_entityid](opportunity.md#BKMK_msdyn_opportunity_dailyopportunitykpiitem_entityid)

|Property|Value|
|---|---|
|ReferencedEntity|`opportunity`|
|ReferencedAttribute|`opportunityid`|
|ReferencingAttribute|`msdyn_entityid`|
|ReferencingEntityNavigationPropertyName|`msdyn_entityid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_organization_msdyn_dailyopportunitykpiitem"></a> organization_msdyn_dailyopportunitykpiitem

One-To-Many Relationship: [organization organization_msdyn_dailyopportunitykpiitem](organization.md#BKMK_organization_msdyn_dailyopportunitykpiitem)

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

- [msdyn_dailyopportunitykpiitem_AsyncOperations](#BKMK_msdyn_dailyopportunitykpiitem_AsyncOperations)
- [msdyn_dailyopportunitykpiitem_BulkDeleteFailures](#BKMK_msdyn_dailyopportunitykpiitem_BulkDeleteFailures)
- [msdyn_dailyopportunitykpiitem_MailboxTrackingFolders](#BKMK_msdyn_dailyopportunitykpiitem_MailboxTrackingFolders)
- [msdyn_dailyopportunitykpiitem_PrincipalObjectAttributeAccesses](#BKMK_msdyn_dailyopportunitykpiitem_PrincipalObjectAttributeAccesses)
- [msdyn_dailyopportunitykpiitem_ProcessSession](#BKMK_msdyn_dailyopportunitykpiitem_ProcessSession)
- [msdyn_dailyopportunitykpiitem_SyncErrors](#BKMK_msdyn_dailyopportunitykpiitem_SyncErrors)

### <a name="BKMK_msdyn_dailyopportunitykpiitem_AsyncOperations"></a> msdyn_dailyopportunitykpiitem_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_dailyopportunitykpiitem_AsyncOperations](asyncoperation.md#BKMK_msdyn_dailyopportunitykpiitem_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dailyopportunitykpiitem_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dailyopportunitykpiitem_BulkDeleteFailures"></a> msdyn_dailyopportunitykpiitem_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_dailyopportunitykpiitem_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_dailyopportunitykpiitem_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dailyopportunitykpiitem_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dailyopportunitykpiitem_MailboxTrackingFolders"></a> msdyn_dailyopportunitykpiitem_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_dailyopportunitykpiitem_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_dailyopportunitykpiitem_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dailyopportunitykpiitem_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dailyopportunitykpiitem_PrincipalObjectAttributeAccesses"></a> msdyn_dailyopportunitykpiitem_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_dailyopportunitykpiitem_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_dailyopportunitykpiitem_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dailyopportunitykpiitem_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dailyopportunitykpiitem_ProcessSession"></a> msdyn_dailyopportunitykpiitem_ProcessSession

Many-To-One Relationship: [processsession msdyn_dailyopportunitykpiitem_ProcessSession](processsession.md#BKMK_msdyn_dailyopportunitykpiitem_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dailyopportunitykpiitem_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_dailyopportunitykpiitem_SyncErrors"></a> msdyn_dailyopportunitykpiitem_SyncErrors

Many-To-One Relationship: [syncerror msdyn_dailyopportunitykpiitem_SyncErrors](syncerror.md#BKMK_msdyn_dailyopportunitykpiitem_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_dailyopportunitykpiitem_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

