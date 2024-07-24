---
title: "Catalog table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Catalog table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 07.24.2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Catalog table/entity reference

Entity for cataloging records to make it easier for your customers to find them on portals and through search.

> [!NOTE]
> The Microsoft Dynamics 365 Field Service Catalog table extends the [Microsoft Dataverse Catalog table](/power-apps/developer/data-platform/reference/entities/catalog).




## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

### <a name="BKMK_msdynmkt_catalog_catalogeventstatusconfiguration"></a> msdynmkt_catalog_catalogeventstatusconfiguration

Many-To-One Relationship: [msdynmkt_catalogeventstatusconfiguration msdynmkt_catalog_catalogeventstatusconfiguration](msdynmkt_catalogeventstatusconfiguration.md#BKMK_msdynmkt_catalog_catalogeventstatusconfiguration)

|Property|Value|
|---|---|
|ReferencingEntity|`msdynmkt_catalogeventstatusconfiguration`|
|ReferencingAttribute|`msdynmkt_catalogid`|
|ReferencedEntityNavigationPropertyName|`msdynmkt_catalog_catalogeventstatusconfiguration`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.catalog?displayProperty=fullName>
