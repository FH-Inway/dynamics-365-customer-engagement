---
title: "LeadProduct table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the LeadProduct table/entity with Microsoft Dynamics 365."
ms.date: 08.01.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# LeadProduct table/entity reference



## Messages

The following table lists the messages for the LeadProduct table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `RetrieveMultiple`<br />Event: True |`GET` /leadproducts<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|

## Properties

The following table lists selected properties for the LeadProduct table.

|Property|Value|
| --- | --- |
| **DisplayName** | **LeadProduct** |
| **DisplayCollectionName** | **LeadProduct** |
| **SchemaName** | `LeadProduct` |
| **EntitySetName** | `leadproducts`|
| **LogicalName** | `leadproduct` |
| **PrimaryIdAttribute** | `leadproductid` |
| **PrimaryNameAttribute** |`name` |
| **TableType** | `Standard` |
| **OwnershipType** | `None` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [LeadProductId](#BKMK_LeadProductId)
- [Name](#BKMK_Name)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
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

### <a name="BKMK_LeadProductId"></a> LeadProductId

|Property|Value|
|---|---|
|Description|**Unique identifier of the lead product.**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`leadproductid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_Name"></a> Name

|Property|Value|
|---|---|
|Description|**name**|
|DisplayName|**name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`name`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

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

- [LeadId](#BKMK_LeadId)
- [ProductId](#BKMK_ProductId)
- [VersionNumber](#BKMK_VersionNumber)

### <a name="BKMK_LeadId"></a> LeadId

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`leadid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_ProductId"></a> ProductId

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`productid`|
|RequiredLevel|SystemRequired|
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

## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [leadproduct_AsyncOperations](#BKMK_leadproduct_AsyncOperations)
- [leadproduct_BulkDeleteFailures](#BKMK_leadproduct_BulkDeleteFailures)
- [leadproduct_MailboxTrackingFolders](#BKMK_leadproduct_MailboxTrackingFolders)
- [leadproduct_PrincipalObjectAttributeAccesses](#BKMK_leadproduct_PrincipalObjectAttributeAccesses)

### <a name="BKMK_leadproduct_AsyncOperations"></a> leadproduct_AsyncOperations

Many-To-One Relationship: [asyncoperation leadproduct_AsyncOperations](asyncoperation.md#BKMK_leadproduct_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`leadproduct_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_leadproduct_BulkDeleteFailures"></a> leadproduct_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure leadproduct_BulkDeleteFailures](bulkdeletefailure.md#BKMK_leadproduct_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`leadproduct_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_leadproduct_MailboxTrackingFolders"></a> leadproduct_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder leadproduct_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_leadproduct_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`leadproduct_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_leadproduct_PrincipalObjectAttributeAccesses"></a> leadproduct_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess leadproduct_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_leadproduct_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`leadproduct_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|


## Many-to-Many relationships

These relationships are many-to-many. Listed by **SchemaName**.

### <a name="BKMK_leadproduct_association"></a> leadproduct_association


|Property|Value|
|---|---|
|IntersectEntityName|`leadproduct`|
|IsCustomizable|False|
|SchemaName|`leadproduct_association`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

