---
title: Select a template to configure forecasting
description: Select a template to define the hierarchy to use in a forecast in Dynamics 365 Sales.
ms.date: 01/03/2025
ms.topic: concept-article
author: lavanyakr01
ms.author: lavanyakr
ms.reviewer: lavanyakr
ms.custom: 
  - dyn365-sales
---
# Select a forecasting template

Select a template to define how a forecast structures your organization's data and projections. If you prefer to create a forecast based on your own rollup and hierarchy entities, select **Create from scratch** instead.

## Select a template  

The fastest way to create a forecast is to use a template. The template that you select defines how the forecast groups data.

On the **Forecast configurations** page, select one of the following templates:

- **Org chart forecast**: Rollup columns and projections are based on your organization's reporting structure. This template uses the **Manager** field of the **User** entity for the hierarchy.
- **Product forecast**: Rollup columns and projections are based on the product hierarchy.
- **Territory forecast**: Rollup columns and projections are based on the sales territory hierarchy.

:::image type="content" source="./media/forecast-ce-template-selection.png" alt-text="A screenshot of the Forecast configuration page with the three templates shown.":::

[!INCLUDE[cant-find-option](../includes/cant-find-option.md)]

<table>
<tr><td>

> [!div class="nextstepaction"]
> [Next step: Define general properties and scheduling](define-general-properties-scheduling-forecast.md)
</td></tr>
</table>

## Related information

[Configure forecasts in your organization](configure-forecast.md)

[Configure forecast using custom rollup entity](configure-forecast-using-custom-rollup-entity.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
