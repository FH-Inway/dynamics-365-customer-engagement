---
title: "Plug-in Type (PluginType) table/entity reference (Microsoft Dynamics 365 Field Service)"
description: "Includes schema information and supported messages for the Plug-in Type (PluginType) table/entity with Microsoft Dynamics 365 Field Service."
ms.date: 08/21/2024
ms.service: powerapps
ms.topic: reference
author: m-hartmann
ms.author: mhart
search.audienceType: 
  - developer
---

# Plug-in Type (PluginType) table/entity reference

Type that inherits from the IPlugin interface and is contained within a plug-in assembly.

> [!NOTE]
> The Microsoft Dynamics 365 Field Service Plug-in Type (PluginType) table extends the [Microsoft Dynamics 365 Plug-in Type (PluginType) table](/dynamics365/developer/entities/plugintype).




## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

### <a name="BKMK_plugin_type_service"></a> plugin_type_service

Many-To-One Relationship: [service plugin_type_service](service.md#BKMK_plugin_type_service)

|Property|Value|
|---|---|
|ReferencingEntity|`service`|
|ReferencingAttribute|`strategyid`|
|ReferencedEntityNavigationPropertyName|`plugin_type_service`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.plugintype?displayProperty=fullName>
