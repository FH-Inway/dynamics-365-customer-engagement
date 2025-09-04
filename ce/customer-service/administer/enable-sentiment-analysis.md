---
title: Enable real-time customer sentiment with sentiment analysis
description: Analyze real-time customer sentiment to improve team performance and customer satisfaction.
ms.date: 6/30/2025
ms.topic: how-to
author: lalexms
ms.author: laalexan
ms.reviewer: laalexan
feedback_product_url: https //experience.dynamics.com/ideas/categories/list/?category=a7f4a807-de3b-eb11-a813-000d3a579c38&forum=b68e50a6-88d9-e811-a96b-000d3a1be7ad
ms.custom:
  - ai-gen-docs-bap
  - ai-gen-title
  - ai-seo-date:12/21/2023
  - ai-gen-desc
---

# Analyze real-time customer sentiment

[!INCLUDE[cc-feature-availability-embedded-yes](../../includes/cc-feature-availability.md)]

Sentiment analysis provides customer service representatives (service representatives or representatives) and supervisors with real-time insights into customer interactions with service representatives during conversations.

> [!IMPORTANT]
> This feature is intended to help customer service managers or supervisors enhance their team's performance and improve customer satisfaction. This feature isn't intended for use in making, and customers shouldn't use it to make, decisions that affect the employment of an employee or group of employees, including compensation, rewards, seniority, or other rights or entitlements. Customers are solely responsible for using Dynamics 365 Customer Service, this feature, and any associated feature or service in compliance with all applicable laws. This responsibility includes laws that relate to accessing individual employee analytics and monitoring, recording, and storing communications with end users. This responsibility also includes the requirement that customers adequately notify end users that their communications with customer service representatives might be monitored, recorded, or stored and, as required by applicable laws, and obtain consent from end users before they use the feature with them. Customers are also encouraged to have a mechanism in place to inform their customer service representatives that their communications with end users may be monitored, recorded, or stored.

> [!NOTE]
> Supervisor and service representatives sentiment notifications aren't available in Omnichannel for Customer Service on Unified Service Desk.

## Sentiment analysis

To let service representatives and supervisors see the customer's satisfaction levels instantly during customer communication, you must enable sentiment analysis.

> [!NOTE]
> Sentiment analysis is enabled by default.

### Enable sentiment analysis

You can enable the sentiment analysis feature in the Copilot Service admin center app.

1. In the site map, select **Insights** in **Operations**. The **Insights** page appears.
1. In the **Sentiment analysis** section, select **Manage**.
1. In the **Sentiment analysis** section, set the **Monitor real-time customer sentiment** toggle to **Yes**, and then select **Save**.

    > [!div class=mx-imgBorder]
    > ![Enable sentiment analysis.](../media/monitor-real-time.png "Enable sentiment analysis")

After you enable real-time customer sentiment, you can view scores in the [Omnichannel Insights dashboards](../implement/configure-historical-sentiment-dashboard-supervisor.md).

## Service representative settings

Service representatives can view the customer sentiment in the communication panel for a conversation session that is active and in focus. For a session that isn't in focus, the alert is shown on the session panel.

You can show alerts to the service representatives when a customer's sentiment decreases to or lowers to a particular value. You can set the customer's sentiment to any of the following values:

- Don't show alerts
- Slightly negative
- Negative
- Very negative

For example, you set the threshold value as **Slightly negative**. When the customer's sentiment reaches **Slightly negative** or any other sentiment value lower than this level, an alert is displayed to the service representative.

1. Navigate to the **Sentiment analysis** page.
2. In the **Agent settings** section, select a value from the **Show alerts when a customer's sentiment decreases to or below** list. The options are:

    - Don't show alerts
    - Slightly negative
    - Negative
    - Negative

      > [!div class=mx-imgBorder]
      > ![Show alerts when a customer's sentiment decreases to or lower than level.](../media/monitor-real-time-agent.png "Show alerts when a customer's sentiment decreases to falls lower than a value")

To turn off service representative alerts, select **Don't show alerts**.

## Supervisor settings

Supervisors can use the [**Ongoing conversations**](../use/realtime-ongoing.md) report to view customer sentiment during conversations between customers and service representatives.

You can show notifications to the supervisors when a customer's sentiment decreases to or falls lower than a particular value. The supervisor can receive sentiment threshold alerts only when their presence is Available or Busy and they're assigned to a queue.

You can set the sentiment threshold to any of the following values:

- Don't show notifications
- Slightly negative
- Negative
- Very negative

For example, you set the threshold value as **Slightly negative**. When the customer's sentiment reaches **Slightly negative** or any other sentiment value lesser than **Slightly negative**, a notification is displayed to the supervisor.

1. Navigate to the **Sentiment analysis** page.
2. In the **Supervisor settings** section, select a value from the **Send notifications when a customer's sentiment decreases to or below** list. The options are:

    - Don't send notifications
    - Slightly negative
    - Negative
    - Very negative

    > [!div class=mx-imgBorder]
    > ![Send notifications when a customer's sentiment decreases to or falls lower.](../media/monitor-real-time-supervisor.png "Send notifications when a customer's sentiment decreases to or falls lower")

To turn off supervisor notifications, select **Don't send notifications**.

## Multilingual sentiment

Multilingual sentiment scoring is enabled by default. Conversations in more than 40 languages are scored. The languages listed in the following table are supported in the analytics features.

<table>
<tbody>
<colgroup span = "3">
<col width = "34%"></col>
<col width = "33%"></col>
<col width = "33%"></col>
</colgroup>
<tr>
<td>Arabic<br>
Bulgarian<br>
Chinese (Hong Kong SAR)<br>
Catalan<br>
Chinese Simplified<br>
Chinese Traditional<br>
Croatian<br>
Czech<br>
Danish<br>
Dutch<br>
English<br>
Estonian<br>
Finnish<br>
French<br>
</td>
<td>German<br>
Greek<br>
Hebrew<br>
Hindi<br>
Hungarian<br>
Indonesian<br>
Italian<br>
Japanese<br>
Korean<br>
Latvian<br>
Lithuanian<br>
Malay<br>
Norwegian<br>
Polish<br>
</td>
<td>Portuguese<br>
Romanian<br>
Russian<br>
Serbian (Cyrillic)<br>
Serbian (Latin)<br>
Slovak<br>
Slovenian<br>
Spanish<br>
Swedish<br>
Thai<br>
Turkish<br>
Ukrainian<br>
Vietnamese<br>
</td>
</tbody>
</table>

> [!NOTE]
> For languages supported in the product user interface (UI), see [Language availability](../implement/international-availability.md).

### Related information

[Monitor, assign, and transfer conversations](../use/monitor-conversations.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]
