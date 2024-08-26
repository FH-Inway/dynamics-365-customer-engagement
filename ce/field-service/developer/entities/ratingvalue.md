---
title: "Rating Value (RatingValue) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Rating Value (RatingValue) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Rating Value (RatingValue) table/entity reference

A unique value associated with a rating model that allows providing a user friendly rating value.

> [!NOTE]
> The Microsoft Dynamics 365 Field Service Rating Value (RatingValue) table extends the [Microsoft Dynamics 365 Rating Value (RatingValue) table](/dynamics365/developer/entities/ratingvalue).



## Customized columns/attributes

Microsoft Dynamics 365 Field Service modifies the definition of columns/attributes defined in other solutions. Listed by **SchemaName**.

### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

Changes from [OwningBusinessUnit (Microsoft Dynamics 365)](/dynamics365/developer/entities/ratingvalue#BKMK_OwningBusinessUnit)

|Property|Value|
|---|---|
|RequiredLevel|None|


## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

### <a name="BKMK_TransactionCurrency_ratingvalue"></a> TransactionCurrency_ratingvalue

One-To-Many Relationship: [transactioncurrency TransactionCurrency_ratingvalue](transactioncurrency.md#BKMK_TransactionCurrency_ratingvalue)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_ratingvalue_msdyn_incidenttypecharacteristic_RatingValue](#BKMK_msdyn_ratingvalue_msdyn_incidenttypecharacteristic_RatingValue)
- [msdyn_ratingvalue_msdyn_requirementcharacteristic_ratingvalue](#BKMK_msdyn_ratingvalue_msdyn_requirementcharacteristic_ratingvalue)

### <a name="BKMK_msdyn_ratingvalue_msdyn_incidenttypecharacteristic_RatingValue"></a> msdyn_ratingvalue_msdyn_incidenttypecharacteristic_RatingValue

Many-To-One Relationship: [msdyn_incidenttypecharacteristic msdyn_ratingvalue_msdyn_incidenttypecharacteristic_RatingValue](msdyn_incidenttypecharacteristic.md#BKMK_msdyn_ratingvalue_msdyn_incidenttypecharacteristic_RatingValue)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_incidenttypecharacteristic`|
|ReferencingAttribute|`msdyn_ratingvalue`|
|ReferencedEntityNavigationPropertyName|`msdyn_ratingvalue_msdyn_incidenttypecharacteristic_RatingValue`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_ratingvalue_msdyn_requirementcharacteristic_ratingvalue"></a> msdyn_ratingvalue_msdyn_requirementcharacteristic_ratingvalue

Many-To-One Relationship: [msdyn_requirementcharacteristic msdyn_ratingvalue_msdyn_requirementcharacteristic_ratingvalue](msdyn_requirementcharacteristic.md#BKMK_msdyn_ratingvalue_msdyn_requirementcharacteristic_ratingvalue)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_requirementcharacteristic`|
|ReferencingAttribute|`msdyn_ratingvalue`|
|ReferencedEntityNavigationPropertyName|`msdyn_ratingvalue_msdyn_requirementcharacteristic_ratingvalue`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseLabel`<br />Group: `Details`<br />Label: Characteristics<br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

