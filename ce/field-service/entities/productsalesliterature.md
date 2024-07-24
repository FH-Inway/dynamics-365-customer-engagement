---
title: "ProductSalesLiterature table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the ProductSalesLiterature table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 07.24.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# ProductSalesLiterature table/entity reference



## Messages

The following table lists the messages for the ProductSalesLiterature table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `RetrieveMultiple`<br />Event: True |`GET` /productsalesliteratures<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|

## Properties

The following table lists selected properties for the ProductSalesLiterature table.

|Property|Value|
| --- | --- |
| **DisplayName** | **ProductSalesLiterature** |
| **DisplayCollectionName** | **ProductSalesLiterature** |
| **SchemaName** | `ProductSalesLiterature` |
| **EntitySetName** | `productsalesliteratures`|
| **LogicalName** | `productsalesliterature` |
| **PrimaryIdAttribute** | `productsalesliteratureid` |
| **PrimaryNameAttribute** |`name` |
| **TableType** | `Standard` |
| **OwnershipType** | `None` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [Name](#BKMK_Name)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [ProductSalesLiteratureId](#BKMK_ProductSalesLiteratureId)
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

### <a name="BKMK_ProductSalesLiteratureId"></a> ProductSalesLiteratureId

|Property|Value|
|---|---|
|Description|**Unique identifier of the product sales literature associated with this price list.**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`productsalesliteratureid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

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

- [ProductId](#BKMK_ProductId)
- [SalesLiteratureId](#BKMK_SalesLiteratureId)
- [VersionNumber](#BKMK_VersionNumber)

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

### <a name="BKMK_SalesLiteratureId"></a> SalesLiteratureId

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`salesliteratureid`|
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

- [productsalesliterature_AsyncOperations](#BKMK_productsalesliterature_AsyncOperations)
- [productsalesliterature_BulkDeleteFailures](#BKMK_productsalesliterature_BulkDeleteFailures)
- [productsalesliterature_MailboxTrackingFolders](#BKMK_productsalesliterature_MailboxTrackingFolders)
- [productsalesliterature_PrincipalObjectAttributeAccesses](#BKMK_productsalesliterature_PrincipalObjectAttributeAccesses)

### <a name="BKMK_productsalesliterature_AsyncOperations"></a> productsalesliterature_AsyncOperations

Many-To-One Relationship: [asyncoperation productsalesliterature_AsyncOperations](asyncoperation.md#BKMK_productsalesliterature_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`productsalesliterature_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_productsalesliterature_BulkDeleteFailures"></a> productsalesliterature_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure productsalesliterature_BulkDeleteFailures](bulkdeletefailure.md#BKMK_productsalesliterature_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`productsalesliterature_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_productsalesliterature_MailboxTrackingFolders"></a> productsalesliterature_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder productsalesliterature_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_productsalesliterature_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`productsalesliterature_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_productsalesliterature_PrincipalObjectAttributeAccesses"></a> productsalesliterature_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess productsalesliterature_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_productsalesliterature_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`productsalesliterature_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|


## Many-to-Many relationships

These relationships are many-to-many. Listed by **SchemaName**.

### <a name="BKMK_productsalesliterature_association"></a> productsalesliterature_association


|Property|Value|
|---|---|
|IntersectEntityName|`productsalesliterature`|
|IsCustomizable|False|
|SchemaName|`productsalesliterature_association`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

