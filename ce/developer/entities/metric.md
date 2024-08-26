---
title: "Goal Metric (Metric) table/entity reference (Microsoft Dynamics 365)"
description: "Includes schema information and supported messages for the Goal Metric (Metric) table/entity with Microsoft Dynamics 365."
ms.date: 08/26/2024
ms.service: powerapps
ms.topic: reference
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer
---

# Goal Metric (Metric) table/entity reference (Microsoft Dynamics 365)

Type of measurement for a goal, such as money amount or count.

> [!NOTE]
> The Microsoft Dynamics 365 Goal Metric (Metric) table extends the [Microsoft Dataverse Goal Metric (Metric) table](/power-apps/developer/data-platform/reference/entities/metric).


## Messages

The following table lists the messages for the Goal Metric (Metric) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Restore`<br />Event: True |<xref:Microsoft.Dynamics.CRM.Restore?displayProperty=nameWithType /> |[Learn to use messages with the SDK for .NET](/power-apps/developer/data-platform/org-service/use-messages)|



## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

### <a name="BKMK_msdyn_metric_msdyn_forecastdefinition_metricid"></a> msdyn_metric_msdyn_forecastdefinition_metricid

Many-To-One Relationship: [msdyn_forecastdefinition msdyn_metric_msdyn_forecastdefinition_metricid](msdyn_forecastdefinition.md#BKMK_msdyn_metric_msdyn_forecastdefinition_metricid)

|Property|Value|
|---|---|
|ReferencingEntity|`msdyn_forecastdefinition`|
|ReferencingAttribute|`msdyn_metricid`|
|ReferencedEntityNavigationPropertyName|`msdyn_metric_msdyn_forecastdefinition_metricid`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.metric?displayProperty=fullName>
