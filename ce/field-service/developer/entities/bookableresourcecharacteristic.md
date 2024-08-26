---
title: "Bookable Resource Characteristic (BookableResourceCharacteristic) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Bookable Resource Characteristic (BookableResourceCharacteristic) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Bookable Resource Characteristic (BookableResourceCharacteristic) table/entity reference (Microsoft Dynamics 365 Field Service)

Associates resources with their characteristics and specifies the proficiency level of a resource for that characteristic.

> [!NOTE]
> The Microsoft Dynamics 365 Field Service Bookable Resource Characteristic (BookableResourceCharacteristic) table extends the [Microsoft Dynamics 365 Bookable Resource Characteristic (BookableResourceCharacteristic) table](/dynamics365/developer/entities/bookableresourcecharacteristic).



## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [msdyn_CharacteristicSupportingInfoId](#BKMK_msdyn_CharacteristicSupportingInfoId)
- [msdyn_Description](#BKMK_msdyn_Description)
- [msdyn_ExpirationDate](#BKMK_msdyn_ExpirationDate)
- [msdyn_IssueDate](#BKMK_msdyn_IssueDate)

### <a name="BKMK_msdyn_CharacteristicSupportingInfoId"></a> msdyn_CharacteristicSupportingInfoId

|Property|Value|
|---|---|
|Description|**Identifier of the characteristic**|
|DisplayName|**ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_characteristicsupportinginfoid`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_Description"></a> msdyn_Description

|Property|Value|
|---|---|
|Description|**Description of the characteristic**|
|DisplayName|**Description**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_description`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2000|

### <a name="BKMK_msdyn_ExpirationDate"></a> msdyn_ExpirationDate

|Property|Value|
|---|---|
|Description|**Expiration date for the characteristic.**|
|DisplayName|**Expiration Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_expirationdate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|TimeZoneIndependent|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_msdyn_IssueDate"></a> msdyn_IssueDate

|Property|Value|
|---|---|
|Description|**Issue date for the characteristic.**|
|DisplayName|**Issue Date**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_issuedate`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|True|
|DateTimeBehavior|TimeZoneIndependent|
|Format|DateOnly|
|ImeMode|Auto|
|SourceTypeMask|0|


## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

### <a name="BKMK_TransactionCurrency_bookableresourcecharacteristic"></a> TransactionCurrency_bookableresourcecharacteristic

One-To-Many Relationship: [transactioncurrency TransactionCurrency_bookableresourcecharacteristic](transactioncurrency.md#BKMK_TransactionCurrency_bookableresourcecharacteristic)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

