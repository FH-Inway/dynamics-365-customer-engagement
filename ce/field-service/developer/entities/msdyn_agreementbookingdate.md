---
title: "Agreement Booking Date (msdyn_agreementbookingdate) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Agreement Booking Date (msdyn_agreementbookingdate) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Agreement Booking Date (msdyn_agreementbookingdate) table/entity reference (Microsoft Dynamics 365 Field Service)

Specify the maintenance booking dates for the agreement.

## Messages

The following table lists the messages for the Agreement Booking Date (msdyn_agreementbookingdate) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_agreementbookingdates(*msdyn_agreementbookingdateid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_agreementbookingdates<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_agreementbookingdates(*msdyn_agreementbookingdateid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `DeleteMultiple`<br />Event: True | |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Retrieve`<br />Event: True |`GET` /msdyn_agreementbookingdates(*msdyn_agreementbookingdateid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_agreementbookingdates<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_agreementbookingdates(*msdyn_agreementbookingdateid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_agreementbookingdates(*msdyn_agreementbookingdateid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_agreementbookingdates(*msdyn_agreementbookingdateid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|


## Events

The following table lists the events for the Agreement Booking Date (msdyn_agreementbookingdate) table.
Events are messages that exist so that you can subscribe to them. Unless you added the event, you shouldn't invoke the message, only subscribe to it.

|Name|Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `BulkRetain`|<xref:Microsoft.Dynamics.CRM.BulkRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `PurgeRetainedContent`|<xref:Microsoft.Dynamics.CRM.PurgeRetainedContent?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `Retain`|<xref:Microsoft.Dynamics.CRM.Retain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `RollbackRetain`|<xref:Microsoft.Dynamics.CRM.RollbackRetain?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|
| `ValidateRetentionConfig`|<xref:Microsoft.Dynamics.CRM.ValidateRetentionConfig?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|

## Properties

The following table lists selected properties for the Agreement Booking Date (msdyn_agreementbookingdate) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Agreement Booking Date** |
| **DisplayCollectionName** | **Agreement Booking Dates** |
| **SchemaName** | `msdyn_agreementbookingdate` |
| **CollectionSchemaName** | `msdyn_agreementbookingdates` |
| **EntitySetName** | `msdyn_agreementbookingdates`|
| **LogicalName** | `msdyn_agreementbookingdate` |
| **LogicalCollectionName** | `msdyn_agreementbookingdates` |
| **PrimaryIdAttribute** | `msdyn_agreementbookingdateid` |
| **PrimaryNameAttribute** |`msdyn_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_Agreement](#BKMK_msdyn_Agreement)
- [msdyn_agreementbookingdateId](#BKMK_msdyn_agreementbookingdateId)
- [msdyn_BookingDate](#BKMK_msdyn_BookingDate)
- [msdyn_BookingSetup](#BKMK_msdyn_BookingSetup)
- [msdyn_EarliestDate](#BKMK_msdyn_EarliestDate)
- [msdyn_InternalFlags](#BKMK_msdyn_InternalFlags)
- [msdyn_LatestDate](#BKMK_msdyn_LatestDate)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_PostponeGenerationUntil](#BKMK_msdyn_PostponeGenerationUntil)
- [msdyn_ProcessStartedOn](#BKMK_msdyn_ProcessStartedOn)
- [msdyn_Resource](#BKMK_msdyn_Resource)
- [msdyn_Revision](#BKMK_msdyn_Revision)
- [msdyn_Status](#BKMK_msdyn_Status)
- [msdyn_WorkOrder](#BKMK_msdyn_WorkOrder)
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
|Description|**Shows the sequence number of the import that created this record.**|
|DisplayName|**Import Sequence Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`importsequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_Agreement"></a> msdyn_Agreement

|Property|Value|
|---|---|
|Description|**Agreement this Booking Date relates to**|
|DisplayName|**Agreement**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_agreement`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_agreement|

### <a name="BKMK_msdyn_agreementbookingdateId"></a> msdyn_agreementbookingdateId

|Property|Value|
|---|---|
|Description|**Shows the entity instances.**|
|DisplayName|**Agreement Booking Date**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_agreementbookingdateid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_msdyn_BookingDate"></a> msdyn_BookingDate

|Property|Value|
|---|---|
|Description|**Enter the date and time to be booked.**|
|DisplayName|**Booking Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_bookingdate`|
|RequiredLevel|ApplicationRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_BookingSetup"></a> msdyn_BookingSetup

|Property|Value|
|---|---|
|Description|**Booking Setup this Booking Date relates to**|
|DisplayName|**Booking Setup**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_bookingsetup`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_agreementbookingsetup|

### <a name="BKMK_msdyn_EarliestDate"></a> msdyn_EarliestDate

|Property|Value|
|---|---|
|Description|**Enter the earliest date this can be booked.**|
|DisplayName|**Earliest Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_earliestdate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_InternalFlags"></a> msdyn_InternalFlags

|Property|Value|
|---|---|
|Description||
|DisplayName|**Internal Flags**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_internalflags`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1048576|

### <a name="BKMK_msdyn_LatestDate"></a> msdyn_LatestDate

|Property|Value|
|---|---|
|Description|**Enter the latest date this can be booked.**|
|DisplayName|**Latest Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_latestdate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|---|---|
|Description|**Enter the name of the custom entity.**|
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

### <a name="BKMK_msdyn_PostponeGenerationUntil"></a> msdyn_PostponeGenerationUntil

|Property|Value|
|---|---|
|Description|**Intended for internal use. Manipulating values in this field is not supported and can lead to unexpected system behavior.**|
|DisplayName|**Postpone Generation Until**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_postponegenerationuntil`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|TimeZoneIndependent|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_ProcessStartedOn"></a> msdyn_ProcessStartedOn

|Property|Value|
|---|---|
|Description|**For internal use only**|
|DisplayName|**Process Started On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_processstartedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|TimeZoneIndependent|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_Resource"></a> msdyn_Resource

|Property|Value|
|---|---|
|Description|**Resource to be booked**|
|DisplayName|**Resource**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_resource`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|bookableresource|

### <a name="BKMK_msdyn_Revision"></a> msdyn_Revision

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Revision**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_revision`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|1|

### <a name="BKMK_msdyn_Status"></a> msdyn_Status

|Property|Value|
|---|---|
|Description|**Enter the status of this Booking Date**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_status`|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|
|DefaultFormValue|690970000|
|GlobalChoiceName|`msdyn_agreementbookingstatus`|

#### msdyn_Status Choices/Options

|Value|Label|
|---|---|
|690970000|**Active**|
|690970001|**Processed**|
|690970002|**Canceled**|

### <a name="BKMK_msdyn_WorkOrder"></a> msdyn_WorkOrder

|Property|Value|
|---|---|
|Description|**Work Order which was generated by this record**|
|DisplayName|**Work Order**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_workorder`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|msdyn_workorder|

### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|---|---|
|Description|**Shows the date and time that the record was migrated.**|
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
|Description|**Status of the Agreement Booking Date**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_agreementbookingdate_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Agreement Booking Date**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_agreementbookingdate_statuscode`|

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
|Description|**Shows the time zone code that was in use when the record was created.**|
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
|Description|**Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.**|
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
|Description|**Shows who created the record on behalf of another user.**|
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
|Description|**Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.**|
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
|Description|**Shows who last updated the record on behalf of another user.**|
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

- [business_unit_msdyn_agreementbookingdate](#BKMK_business_unit_msdyn_agreementbookingdate)
- [lk_msdyn_agreementbookingdate_createdby](#BKMK_lk_msdyn_agreementbookingdate_createdby)
- [lk_msdyn_agreementbookingdate_createdonbehalfby](#BKMK_lk_msdyn_agreementbookingdate_createdonbehalfby)
- [lk_msdyn_agreementbookingdate_modifiedby](#BKMK_lk_msdyn_agreementbookingdate_modifiedby)
- [lk_msdyn_agreementbookingdate_modifiedonbehalfby](#BKMK_lk_msdyn_agreementbookingdate_modifiedonbehalfby)
- [msdyn_bookableresource_msdyn_agreementbookingdate_Resource](#BKMK_msdyn_bookableresource_msdyn_agreementbookingdate_Resource)
- [msdyn_msdyn_agreement_msdyn_agreementbookingdate_Agreement](#BKMK_msdyn_msdyn_agreement_msdyn_agreementbookingdate_Agreement)
- [msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingdate_BookingSetup](#BKMK_msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingdate_BookingSetup)
- [msdyn_msdyn_workorder_msdyn_agreementbookingdate_WorkOrder](#BKMK_msdyn_msdyn_workorder_msdyn_agreementbookingdate_WorkOrder)
- [owner_msdyn_agreementbookingdate](#BKMK_owner_msdyn_agreementbookingdate)
- [team_msdyn_agreementbookingdate](#BKMK_team_msdyn_agreementbookingdate)
- [user_msdyn_agreementbookingdate](#BKMK_user_msdyn_agreementbookingdate)

### <a name="BKMK_business_unit_msdyn_agreementbookingdate"></a> business_unit_msdyn_agreementbookingdate

One-To-Many Relationship: [businessunit business_unit_msdyn_agreementbookingdate](businessunit.md#BKMK_business_unit_msdyn_agreementbookingdate)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_agreementbookingdate_createdby"></a> lk_msdyn_agreementbookingdate_createdby

One-To-Many Relationship: [systemuser lk_msdyn_agreementbookingdate_createdby](systemuser.md#BKMK_lk_msdyn_agreementbookingdate_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_agreementbookingdate_createdonbehalfby"></a> lk_msdyn_agreementbookingdate_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_agreementbookingdate_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_agreementbookingdate_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_agreementbookingdate_modifiedby"></a> lk_msdyn_agreementbookingdate_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_agreementbookingdate_modifiedby](systemuser.md#BKMK_lk_msdyn_agreementbookingdate_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_agreementbookingdate_modifiedonbehalfby"></a> lk_msdyn_agreementbookingdate_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_agreementbookingdate_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_agreementbookingdate_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_bookableresource_msdyn_agreementbookingdate_Resource"></a> msdyn_bookableresource_msdyn_agreementbookingdate_Resource

One-To-Many Relationship: [bookableresource msdyn_bookableresource_msdyn_agreementbookingdate_Resource](bookableresource.md#BKMK_msdyn_bookableresource_msdyn_agreementbookingdate_Resource)

|Property|Value|
|---|---|
|ReferencedEntity|`bookableresource`|
|ReferencedAttribute|`bookableresourceid`|
|ReferencingAttribute|`msdyn_resource`|
|ReferencingEntityNavigationPropertyName|`msdyn_resource`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_agreement_msdyn_agreementbookingdate_Agreement"></a> msdyn_msdyn_agreement_msdyn_agreementbookingdate_Agreement

One-To-Many Relationship: [msdyn_agreement msdyn_msdyn_agreement_msdyn_agreementbookingdate_Agreement](msdyn_agreement.md#BKMK_msdyn_msdyn_agreement_msdyn_agreementbookingdate_Agreement)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_agreement`|
|ReferencedAttribute|`msdyn_agreementid`|
|ReferencingAttribute|`msdyn_agreement`|
|ReferencingEntityNavigationPropertyName|`msdyn_agreement`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingdate_BookingSetup"></a> msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingdate_BookingSetup

One-To-Many Relationship: [msdyn_agreementbookingsetup msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingdate_BookingSetup](msdyn_agreementbookingsetup.md#BKMK_msdyn_msdyn_agreementbookingsetup_msdyn_agreementbookingdate_BookingSetup)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_agreementbookingsetup`|
|ReferencedAttribute|`msdyn_agreementbookingsetupid`|
|ReferencingAttribute|`msdyn_bookingsetup`|
|ReferencingEntityNavigationPropertyName|`msdyn_bookingsetup`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `Cascade`<br />Delete: `Cascade`<br />Merge: `NoCascade`<br />Reparent: `Cascade`<br />RollupView: `NoCascade`<br />Share: `Cascade`<br />Unshare: `Cascade`|

### <a name="BKMK_msdyn_msdyn_workorder_msdyn_agreementbookingdate_WorkOrder"></a> msdyn_msdyn_workorder_msdyn_agreementbookingdate_WorkOrder

One-To-Many Relationship: [msdyn_workorder msdyn_msdyn_workorder_msdyn_agreementbookingdate_WorkOrder](msdyn_workorder.md#BKMK_msdyn_msdyn_workorder_msdyn_agreementbookingdate_WorkOrder)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_workorder`|
|ReferencedAttribute|`msdyn_workorderid`|
|ReferencingAttribute|`msdyn_workorder`|
|ReferencingEntityNavigationPropertyName|`msdyn_workorder`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_agreementbookingdate"></a> owner_msdyn_agreementbookingdate

One-To-Many Relationship: [owner owner_msdyn_agreementbookingdate](owner.md#BKMK_owner_msdyn_agreementbookingdate)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_agreementbookingdate"></a> team_msdyn_agreementbookingdate

One-To-Many Relationship: [team team_msdyn_agreementbookingdate](team.md#BKMK_team_msdyn_agreementbookingdate)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_agreementbookingdate"></a> user_msdyn_agreementbookingdate

One-To-Many Relationship: [systemuser user_msdyn_agreementbookingdate](systemuser.md#BKMK_user_msdyn_agreementbookingdate)

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

- [msdyn_agreementbookingdate_ActivityPointers](#BKMK_msdyn_agreementbookingdate_ActivityPointers)
- [msdyn_agreementbookingdate_adx_inviteredemptions](#BKMK_msdyn_agreementbookingdate_adx_inviteredemptions)
- [msdyn_agreementbookingdate_adx_portalcomments](#BKMK_msdyn_agreementbookingdate_adx_portalcomments)
- [msdyn_agreementbookingdate_Annotations](#BKMK_msdyn_agreementbookingdate_Annotations)
- [msdyn_agreementbookingdate_Appointments](#BKMK_msdyn_agreementbookingdate_Appointments)
- [msdyn_agreementbookingdate_AsyncOperations](#BKMK_msdyn_agreementbookingdate_AsyncOperations)
- [msdyn_agreementbookingdate_BulkDeleteFailures](#BKMK_msdyn_agreementbookingdate_BulkDeleteFailures)
- [msdyn_agreementbookingdate_chats](#BKMK_msdyn_agreementbookingdate_chats)
- [msdyn_agreementbookingdate_connections1](#BKMK_msdyn_agreementbookingdate_connections1)
- [msdyn_agreementbookingdate_connections2](#BKMK_msdyn_agreementbookingdate_connections2)
- [msdyn_agreementbookingdate_DuplicateBaseRecord](#BKMK_msdyn_agreementbookingdate_DuplicateBaseRecord)
- [msdyn_agreementbookingdate_DuplicateMatchingRecord](#BKMK_msdyn_agreementbookingdate_DuplicateMatchingRecord)
- [msdyn_agreementbookingdate_Emails](#BKMK_msdyn_agreementbookingdate_Emails)
- [msdyn_agreementbookingdate_Faxes](#BKMK_msdyn_agreementbookingdate_Faxes)
- [msdyn_agreementbookingdate_Letters](#BKMK_msdyn_agreementbookingdate_Letters)
- [msdyn_agreementbookingdate_MailboxTrackingFolders](#BKMK_msdyn_agreementbookingdate_MailboxTrackingFolders)
- [msdyn_agreementbookingdate_msdyn_bookingalerts](#BKMK_msdyn_agreementbookingdate_msdyn_bookingalerts)
- [msdyn_agreementbookingdate_msdyn_copilottranscripts](#BKMK_msdyn_agreementbookingdate_msdyn_copilottranscripts)
- [msdyn_agreementbookingdate_msdyn_ocliveworkitems](#BKMK_msdyn_agreementbookingdate_msdyn_ocliveworkitems)
- [msdyn_agreementbookingdate_msdyn_ocsessions](#BKMK_msdyn_agreementbookingdate_msdyn_ocsessions)
- [msdyn_agreementbookingdate_msfp_alerts](#BKMK_msdyn_agreementbookingdate_msfp_alerts)
- [msdyn_agreementbookingdate_msfp_surveyinvites](#BKMK_msdyn_agreementbookingdate_msfp_surveyinvites)
- [msdyn_agreementbookingdate_msfp_surveyresponses](#BKMK_msdyn_agreementbookingdate_msfp_surveyresponses)
- [msdyn_agreementbookingdate_PhoneCalls](#BKMK_msdyn_agreementbookingdate_PhoneCalls)
- [msdyn_agreementbookingdate_PrincipalObjectAttributeAccesses](#BKMK_msdyn_agreementbookingdate_PrincipalObjectAttributeAccesses)
- [msdyn_agreementbookingdate_ProcessSession](#BKMK_msdyn_agreementbookingdate_ProcessSession)
- [msdyn_agreementbookingdate_QueueItems](#BKMK_msdyn_agreementbookingdate_QueueItems)
- [msdyn_agreementbookingdate_RecurringAppointmentMasters](#BKMK_msdyn_agreementbookingdate_RecurringAppointmentMasters)
- [msdyn_agreementbookingdate_ServiceAppointments](#BKMK_msdyn_agreementbookingdate_ServiceAppointments)
- [msdyn_agreementbookingdate_SharePointDocumentLocations](#BKMK_msdyn_agreementbookingdate_SharePointDocumentLocations)
- [msdyn_agreementbookingdate_SocialActivities](#BKMK_msdyn_agreementbookingdate_SocialActivities)
- [msdyn_agreementbookingdate_SyncErrors](#BKMK_msdyn_agreementbookingdate_SyncErrors)
- [msdyn_agreementbookingdate_Tasks](#BKMK_msdyn_agreementbookingdate_Tasks)
- [msdyn_msdyn_agreementbookingdate_bookableresourcebooking_AgreementBookingDate](#BKMK_msdyn_msdyn_agreementbookingdate_bookableresourcebooking_AgreementBookingDate)

### <a name="BKMK_msdyn_agreementbookingdate_ActivityPointers"></a> msdyn_agreementbookingdate_ActivityPointers

Many-To-One Relationship: [activitypointer msdyn_agreementbookingdate_ActivityPointers](activitypointer.md#BKMK_msdyn_agreementbookingdate_ActivityPointers)

|Property|Value|
|---|---|
|ReferencingEntity|`activitypointer`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_ActivityPointers`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_adx_inviteredemptions"></a> msdyn_agreementbookingdate_adx_inviteredemptions

Many-To-One Relationship: [adx_inviteredemption msdyn_agreementbookingdate_adx_inviteredemptions](adx_inviteredemption.md#BKMK_msdyn_agreementbookingdate_adx_inviteredemptions)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_inviteredemption`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_adx_inviteredemptions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_adx_portalcomments"></a> msdyn_agreementbookingdate_adx_portalcomments

Many-To-One Relationship: [adx_portalcomment msdyn_agreementbookingdate_adx_portalcomments](adx_portalcomment.md#BKMK_msdyn_agreementbookingdate_adx_portalcomments)

|Property|Value|
|---|---|
|ReferencingEntity|`adx_portalcomment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_adx_portalcomments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_Annotations"></a> msdyn_agreementbookingdate_Annotations

Many-To-One Relationship: [annotation msdyn_agreementbookingdate_Annotations](annotation.md#BKMK_msdyn_agreementbookingdate_Annotations)

|Property|Value|
|---|---|
|ReferencingEntity|`annotation`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_Annotations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_Appointments"></a> msdyn_agreementbookingdate_Appointments

Many-To-One Relationship: [appointment msdyn_agreementbookingdate_Appointments](appointment.md#BKMK_msdyn_agreementbookingdate_Appointments)

|Property|Value|
|---|---|
|ReferencingEntity|`appointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_Appointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_AsyncOperations"></a> msdyn_agreementbookingdate_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_agreementbookingdate_AsyncOperations](asyncoperation.md#BKMK_msdyn_agreementbookingdate_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_BulkDeleteFailures"></a> msdyn_agreementbookingdate_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_agreementbookingdate_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_agreementbookingdate_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_chats"></a> msdyn_agreementbookingdate_chats

Many-To-One Relationship: [chat msdyn_agreementbookingdate_chats](chat.md#BKMK_msdyn_agreementbookingdate_chats)

|Property|Value|
|---|---|
|ReferencingEntity|`chat`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_chats`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_connections1"></a> msdyn_agreementbookingdate_connections1

Many-To-One Relationship: [connection msdyn_agreementbookingdate_connections1](connection.md#BKMK_msdyn_agreementbookingdate_connections1)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record1id`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_connections1`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 100<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_connections2"></a> msdyn_agreementbookingdate_connections2

Many-To-One Relationship: [connection msdyn_agreementbookingdate_connections2](connection.md#BKMK_msdyn_agreementbookingdate_connections2)

|Property|Value|
|---|---|
|ReferencingEntity|`connection`|
|ReferencingAttribute|`record2id`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_connections2`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_DuplicateBaseRecord"></a> msdyn_agreementbookingdate_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_agreementbookingdate_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_agreementbookingdate_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_DuplicateMatchingRecord"></a> msdyn_agreementbookingdate_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_agreementbookingdate_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_agreementbookingdate_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_Emails"></a> msdyn_agreementbookingdate_Emails

Many-To-One Relationship: [email msdyn_agreementbookingdate_Emails](email.md#BKMK_msdyn_agreementbookingdate_Emails)

|Property|Value|
|---|---|
|ReferencingEntity|`email`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_Emails`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_Faxes"></a> msdyn_agreementbookingdate_Faxes

Many-To-One Relationship: [fax msdyn_agreementbookingdate_Faxes](fax.md#BKMK_msdyn_agreementbookingdate_Faxes)

|Property|Value|
|---|---|
|ReferencingEntity|`fax`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_Faxes`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_Letters"></a> msdyn_agreementbookingdate_Letters

Many-To-One Relationship: [letter msdyn_agreementbookingdate_Letters](letter.md#BKMK_msdyn_agreementbookingdate_Letters)

|Property|Value|
|---|---|
|ReferencingEntity|`letter`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_Letters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_MailboxTrackingFolders"></a> msdyn_agreementbookingdate_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_agreementbookingdate_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_agreementbookingdate_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_msdyn_bookingalerts"></a> msdyn_agreementbookingdate_msdyn_bookingalerts

Many-To-One Relationship: [msdyn_bookingalert msdyn_agreementbookingdate_msdyn_bookingalerts](msdyn_bookingalert.md#BKMK_msdyn_agreementbookingdate_msdyn_bookingalerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_bookingalert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_msdyn_bookingalerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_msdyn_copilottranscripts"></a> msdyn_agreementbookingdate_msdyn_copilottranscripts

Many-To-One Relationship: [msdyn_copilottranscript msdyn_agreementbookingdate_msdyn_copilottranscripts](msdyn_copilottranscript.md#BKMK_msdyn_agreementbookingdate_msdyn_copilottranscripts)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_copilottranscript`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_msdyn_copilottranscripts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_msdyn_ocliveworkitems"></a> msdyn_agreementbookingdate_msdyn_ocliveworkitems

Many-To-One Relationship: [msdyn_ocliveworkitem msdyn_agreementbookingdate_msdyn_ocliveworkitems](msdyn_ocliveworkitem.md#BKMK_msdyn_agreementbookingdate_msdyn_ocliveworkitems)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocliveworkitem`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_msdyn_ocliveworkitems`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_msdyn_ocsessions"></a> msdyn_agreementbookingdate_msdyn_ocsessions

Many-To-One Relationship: [msdyn_ocsession msdyn_agreementbookingdate_msdyn_ocsessions](msdyn_ocsession.md#BKMK_msdyn_agreementbookingdate_msdyn_ocsessions)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_ocsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_msdyn_ocsessions`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_msfp_alerts"></a> msdyn_agreementbookingdate_msfp_alerts

Many-To-One Relationship: [msfp_alert msdyn_agreementbookingdate_msfp_alerts](msfp_alert.md#BKMK_msdyn_agreementbookingdate_msfp_alerts)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_alert`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_msfp_alerts`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_msfp_surveyinvites"></a> msdyn_agreementbookingdate_msfp_surveyinvites

Many-To-One Relationship: [msfp_surveyinvite msdyn_agreementbookingdate_msfp_surveyinvites](msfp_surveyinvite.md#BKMK_msdyn_agreementbookingdate_msfp_surveyinvites)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyinvite`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_msfp_surveyinvites`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_msfp_surveyresponses"></a> msdyn_agreementbookingdate_msfp_surveyresponses

Many-To-One Relationship: [msfp_surveyresponse msdyn_agreementbookingdate_msfp_surveyresponses](msfp_surveyresponse.md#BKMK_msdyn_agreementbookingdate_msfp_surveyresponses)

|Property|Value|
|---|---|
|ReferencingEntity|`msfp_surveyresponse`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_msfp_surveyresponses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_PhoneCalls"></a> msdyn_agreementbookingdate_PhoneCalls

Many-To-One Relationship: [phonecall msdyn_agreementbookingdate_PhoneCalls](phonecall.md#BKMK_msdyn_agreementbookingdate_PhoneCalls)

|Property|Value|
|---|---|
|ReferencingEntity|`phonecall`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_PhoneCalls`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_PrincipalObjectAttributeAccesses"></a> msdyn_agreementbookingdate_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_agreementbookingdate_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_agreementbookingdate_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_ProcessSession"></a> msdyn_agreementbookingdate_ProcessSession

Many-To-One Relationship: [processsession msdyn_agreementbookingdate_ProcessSession](processsession.md#BKMK_msdyn_agreementbookingdate_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_QueueItems"></a> msdyn_agreementbookingdate_QueueItems

Many-To-One Relationship: [queueitem msdyn_agreementbookingdate_QueueItems](queueitem.md#BKMK_msdyn_agreementbookingdate_QueueItems)

|Property|Value|
|---|---|
|ReferencingEntity|`queueitem`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_QueueItems`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_RecurringAppointmentMasters"></a> msdyn_agreementbookingdate_RecurringAppointmentMasters

Many-To-One Relationship: [recurringappointmentmaster msdyn_agreementbookingdate_RecurringAppointmentMasters](recurringappointmentmaster.md#BKMK_msdyn_agreementbookingdate_RecurringAppointmentMasters)

|Property|Value|
|---|---|
|ReferencingEntity|`recurringappointmentmaster`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_RecurringAppointmentMasters`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_ServiceAppointments"></a> msdyn_agreementbookingdate_ServiceAppointments

Many-To-One Relationship: [serviceappointment msdyn_agreementbookingdate_ServiceAppointments](serviceappointment.md#BKMK_msdyn_agreementbookingdate_ServiceAppointments)

|Property|Value|
|---|---|
|ReferencingEntity|`serviceappointment`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_ServiceAppointments`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_SharePointDocumentLocations"></a> msdyn_agreementbookingdate_SharePointDocumentLocations

Many-To-One Relationship: [sharepointdocumentlocation msdyn_agreementbookingdate_SharePointDocumentLocations](sharepointdocumentlocation.md#BKMK_msdyn_agreementbookingdate_SharePointDocumentLocations)

|Property|Value|
|---|---|
|ReferencingEntity|`sharepointdocumentlocation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_SharePointDocumentLocations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_SocialActivities"></a> msdyn_agreementbookingdate_SocialActivities

Many-To-One Relationship: [socialactivity msdyn_agreementbookingdate_SocialActivities](socialactivity.md#BKMK_msdyn_agreementbookingdate_SocialActivities)

|Property|Value|
|---|---|
|ReferencingEntity|`socialactivity`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_SocialActivities`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_SyncErrors"></a> msdyn_agreementbookingdate_SyncErrors

Many-To-One Relationship: [syncerror msdyn_agreementbookingdate_SyncErrors](syncerror.md#BKMK_msdyn_agreementbookingdate_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_agreementbookingdate_Tasks"></a> msdyn_agreementbookingdate_Tasks

Many-To-One Relationship: [task msdyn_agreementbookingdate_Tasks](task.md#BKMK_msdyn_agreementbookingdate_Tasks)

|Property|Value|
|---|---|
|ReferencingEntity|`task`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_agreementbookingdate_Tasks`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_msdyn_agreementbookingdate_bookableresourcebooking_AgreementBookingDate"></a> msdyn_msdyn_agreementbookingdate_bookableresourcebooking_AgreementBookingDate

Many-To-One Relationship: [bookableresourcebooking msdyn_msdyn_agreementbookingdate_bookableresourcebooking_AgreementBookingDate](bookableresourcebooking.md#BKMK_msdyn_msdyn_agreementbookingdate_bookableresourcebooking_AgreementBookingDate)

|Property|Value|
|---|---|
|ReferencingEntity|`bookableresourcebooking`|
|ReferencingAttribute|`msdyn_agreementbookingdate`|
|ReferencedEntityNavigationPropertyName|`msdyn_msdyn_agreementbookingdate_bookableresourcebooking_AgreementBookingDate`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

