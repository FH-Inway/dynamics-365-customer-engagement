---
title: View minutes used in voice calls
description: View the report to see the minutes used in voice calls in Dynamics 365 Contact Center.
author: neeranelli
ms.author: nenellim
ms.date: 06/14/2024
ms.topic: article
ms.collection:
---


# View minutes used in voice calls

[!INCLUDE[cc-feature-availability](../../includes/cc-feature-availability.md)]

The Voice minutes report lets administrators view a Power BI report that helps them to get insights about how many call intelligence minutes and intelligent voicebot minutes from the voice quota have been consumed.

## Prerequisites

- The voice channel should be configured and in use for the report to display data.
- The administrator role for accessing the report.

## View the Voice minutes report

To view the Voice minutes report, in the site map of Customer Service admin center or Contact Center admin center, select **Insights**, and in **Admin reports**, select **View report** for **Voice minutes**. 

> ![The Voice minutes report.](../media/voice-minutes-report.png "The Voice minutes report.")

The following table contains the metrics.

|Metric|Description|
|--------|------|
|Call intelligence minutes| Number of minutes of calls for which call transcription is generated. Number is rounded to a whole number.  |
|Intelligent voicebot minutes|Number of minutes used by voicebot. Number is rounded to a whole number.|
|Total Calls|Number of calls that consumed the minutes.|
|Minutes over time|Overtime trending of call intelligence minutes and intelligent voicebot minutes. |

### View the IVR transcripts

The **Voice details** table in the report provides the following information.

|Attribute|Description|
|----|----|
|Date| Date when the conversation is logged.|
|Conversation ID |Identifier of the conversation record.|
|Type|Type of call, either "Call intelligence" or "Intelligence voicebot". |
|Start|Time when the recording of the minutes starts.|
|End|Time when the recording of the minutes stops.|
|Duration|Total number of minutes consumed for the current row.|
|Phone number|Agent phone number used in the call.|
|Workstream| Workstream through which the call was handled.|
|Call direction| Indicates whether the call was an "Incoming" or "Outgoing" one.|

### Slice metrics by time and time zone

The **Duration** option lets you filter the report details and affects all metrics in the report. More information: [Slice metrics by time](../implement/intraday-insights-dashboard.md#slice-metrics-by-time)

The **Time zone** option lets you filter the report for the selected time zone.

### See also

[Overview of voice channel](voice-channel.md)  
[Intraday conversation insights](../implement/intraday-conversation-insights.md)  
