---
title: Insights generated from Microsoft 365 data
description: Dynamics 365 Sales can generate insights based on email interactions and meetings information from Microsoft 365. 
ms.date: 05/07/2024
ms.topic: concept-article
author: lavanyakr01
ms.author: lavanyakr
ms.reviewer: lavanyakr
---

# Insights generated from Microsoft 365 data

If you admin has [enabled server-side synchronization](configure-email.md), then Dynamics 365 Sales uses your emails and meeting information from Exchange to generate the following relationship insights:

- [Relationship analytics and health](#relationship-analytics-and-health)
- [Who knows whom](#who-knows-whom)

> [!NOTE]
> If your organization is using Dynamics 365 Customer Insights, then your Exchange data will be used to enrich customer data. For more information, see [Enrich customer profiles with data from Microsoft Office 365](/dynamics365/customer-insights/enrichment-office).


## Relationship analytics and health

Relationship analytics provides a comprehensive view of the overall health and trend of your business relationships based on your sellers interactions with your customers through emails and activities in Dynamics 365 and Exchange. It calculates the KPIs and activity histories for any contact, opportunity, lead, or account. With these insights, you can identify critical opportunities and customer relationships that need your attention.

The following screenshot is an example of how relationship analytics data appears for open opportunities:

:::image type="content" source="media/relationship-health-details-grid-view.png" alt-text="Screenshot of relationship health details for open opportunities in a grid view.":::

Learn more about how to set up and use this feature in [Enable relationship intelligence](enable-ri.md) and [Use relationship analytics to gather KPIs](relationship-analytics.md).

## Who knows whom

Who knows whom helps you identify colleagues who can introduce you to a lead or contact based on their email interactions with the lead. An introduction can increase the chances of a positive outcome. This feature provides you with details such as the names and email addresses of your colleagues and the strength of their connection to the lead.

The following screenshot is an example of the **Who Knows Whom** widget on a lead page:

:::image type="content" source="media/wkw_connection.png" alt-text="Screenshot of the Who Knows Whom connection widget showing contact details and connection strength.":::

Learn more about how to set up and use this feature in [Enable relationship intelligence](enable-ri.md) and [How to get introduced to leads or contacts](who-knows-whom.md).
