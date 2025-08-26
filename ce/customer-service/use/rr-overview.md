---
title: Overview of real-time analytics for record routing
description: Monitor contact center performance with real-time analytics for record routing. Access dashboards, view KPIs, and analyze summary, queue, agent, and work item reports to improve productivity.
author: Soumyasd27
ms.author: sdas
ms.reviewer: sdas
ms.topic: overview
ms.date: 08/26/2025
ms.custom:
  - bap-template
  - ai-gen-docs-bap
  - ai-gen-description
  - ai-seo-date:08/13/2025
---

# Overview of real-time analytics for record routing

Real-time analytics for record routing helps you monitor and improve your contact center's performance.

**Key capabilities:**
- Monitor real-time performance metrics and KPIs
- Track service representative productivity and workload distribution
- Analyze queue performance and backlog trends
- [Customize the visual display](customize-reports.md#customize-visual-display) of  reports and save personalized views as [bookmarks](manage-bookmarks.md#manage-bookmarks-for-reports)
- Access detailed insights across summary, queue, agent, and work item reports

## Security roles and permissions

Real-time analytics uses the security permissions defined in Microsoft Dataverse. For example, if your organization has set business unit-level permissions for you, metrics that are computed based on business unit-level data only are shown to you.

As a supervisor, you can view the **Real-time analytics for record routing** dashboards in the Copilot Service workspace app. However, your administrator must provide the required permissions for you. Learn more in [Configure user access to analytics and dashboards](../administer/configure-customer-service-analytics-insights-csh.md#configure-user-access-to-analytics-and-dashboards). To view the real-time analytics for record-routing dashboards, you must have the CSR Manager role.

> [!NOTE]
> If different values are shown to different users in the metrics, you must investigate the permissions for those users.

## Access reports

1. In the Copilot Service workspace app, select **Real-time analytics for record routing** in **Service**.
2. The **Summary** report opens by default.
3. Select the dropdown for **Queue**, **Agent**, **Ongoing work items**, or **Backlog work items** reports.

If you can't view the reports, contact your system administrator. Learn more in [Manage real-time analytics for record routing](../administer/enable-record-routing.md#manage-real-time-analytics-for-record-routing).

## Dashboard details 

Dynamics 365 Unified Routing uses work item (conversation) to track case and record routing and assignment. Case and record conversation states can be open, active, or closed. Learn more in [Understand conversation states](oc-conversation-state.md#understand-conversation-states). 

For example, a case that gets created automatically creates a conversation in the open state. When such a case gets reassigned, a new conversation gets created, and the old one gets closed while the case remains the same. This way, work item lifecycles can be tracked seamlessly.

**Real-time analytics for record routing** consists of the following reports:

- **Summary**: This report provides an overview of your organization in real time.

- **Queue:** This report provides a case and record work item overview, segmented by queue. This report shows entity record type queues only.

- **Agent**: This report provides an overview of the health and KPIs of service representatives in your organization.

- **Ongoing work items**: This report provides information about cases and records that service representatives are handling, and that are in an active or open state.

- **Backlog work items**: This report lists case and record work item conversations that are modified, including work items created within the time range selected.

## Filter information displayed on dashboard 

Use the filters to drill down to KPIs across the dashboard. Adjust the filters based on the insights that you're looking for. The available filters include **Modified on**, **Agent**, **Agent status,** **Agent skill**, **Queue**, **Work item status,** **Work item skill**, and **Time zone**.

> [!NOTE]
> The queues filter shows entity record type queues only.

## Autorefresh 

Summary, queue, and agent reports are autorefreshed continuously to allow for real-time analytics trend insights. This autorefresh can be paused and resumed. Ongoing and backlog work item views need to be manually refreshed, which makes it easier to focus on supervisor tasks without disrupting data refreshes.

> [!NOTE]
> For optimum use of real-time analytics for record routing, use [capacity profiles](../administer/capacity-profiles.md#create-and-manage-capacity-profiles). The use of legacy unit-based capacity or mixed capacity management leads to reduced report actionability.

## Related information

[Manage real-time analytics for record routing](../administer/enable-record-routing.md#manage-real-time-analytics-for-record-routing)  
[Summary report](rr-summary.md#view-and-understand-real-time-analytics-for-record-routing-in-the-summary-report)  
[Queue report](rr-queue.md#view-and-understand-real-time-analytics-for-record-routing-in-the-queue-report)  
[Agent report](rr-agent.md#view-and-understand-real-time-analytics-for-record-routing-in-the-agent-report)  
[Backlog work items report](rr-backlogitems.md#view-and-understand-real-time-analytics-for-record-routing-in-the-backlog-work-items-report)  
[Ongoing work items report](rr-ongoingworkitems.md#view-and-understand-real-time-analytics-for-record-routing-in-the-ongoing-work-items-report) 
