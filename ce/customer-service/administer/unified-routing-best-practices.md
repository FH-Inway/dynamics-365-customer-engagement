---
title: Use best practices to set up unified routing in Customer Service
description: Use this article to learn about the best practices to set up unified routing in Customer Service and Dynamics 365 Contact Center and what to do for a successful implementation.
author: neeranelli
ms.author: nenellim
ms.reviewer: nenellim
ms.topic: how-to
ms.date: 09/16/2025
ms.custom: bap-template
---

# Use best practices to set up unified routing in Customer Service

[!INCLUDE[cc-feature-availability-embedded-yes](../../includes/cc-feature-availability-embedded-yes.md)]

This article discusses some of the important aspects to successfully deploy and manage unified routing and focuses on the most common areas where you might have questions.

## Set up unified routing

### Verify service limits and default quotas

Dynamics 365 Customer Service relies on shared cloud resources for data and processing. You must check the service limits and default quotas for the resources before you provision unified routing. If you need a higher limit on an adjustable measure, contact Microsoft Support to check whether the limit can be increased. More information: [Service quotas](../implement/service-quotas.md)

## Manage users

Use the following guidance to set up users in bulk:

- Follow a specific sequence to set up users in bulk using Dataverse API calls.
- Limit the number of change requests when setting up users in bulk using Dataverse API calls.

### Follow a specific sequence to set up users in bulk using Dataverse API calls

To manage the users in bulk, follow these steps:

1. Create or import users to enable them.
1. Add the users to queues. More information: [Create and manage queues](queues-omnichannel.md)
1. Create bookable resources. More information: [Manage users](users-user-profiles.md#manage-users-using-the-classic-experience)
1. Add skills. More information: [Set up skills](setup-skills-assign-agents.md)
1. Assign capacity profiles. More information: [Create and manage capacity profiles](capacity-profiles.md)
1. Assign required roles. More information: [Assign roles](../implement/add-users-assign-roles.md)

If you don't follow the recommended order, inconsistencies in the user information might occur, such as missing users or missing skills and capacity profiles.

### Limit number of change requests when setting up users in bulk using Dataverse API calls

Customer Service lets you make API calls to set up users in bulk. A single change request is any add or update operation like defining a single skill, capacity profile, or role per user.

We recommend that you make 500 change requests every 15 minutes for the system to process the changes optimally without getting throttled. Beyond this recommended rate for bulk updates, you might notice inconsistencies in user data, such as skills not updated as expected, after the update is over.

For example, in a contact center with 1,000 customer service representative (service representative or representative), you need to set up each representative with two skills, one capacity profile, and one role. The total number of requests to configure these settings is 4,000.

Based on our recommendation of 500 requests per 15 minutes, make these requests in eight batches as follows:

|Change request type|Number of requests|Number of batches|
|-----------|---------|------------|
|Two skills per service representative|250 requests per batch|Four|
|One capacity profile per service representative|500 requests per batch|Two|
|One role per service representative |500 requests per batch|Two|

Learn about using the API in [Use the Microsoft Dataverse Web API](/power-apps/developer/data-platform/webapi/overview).

### Monitor service representative capacity

You can view details such as the representative's presence, current conversations, and the sentiments of those conversations, and the available capacity across different capacity profiles. You can use the **Agents insights** report to monitor the representative's capacity. You can choose to reset capacity at the end of the workday or immediately after a work item is closed. Learn more in [Create and manage capacity profiles](capacity-profiles.md).

You can choose the following relevant entities for representative status and status history based on your implementation of capacity.

- **Capacity profiles**
  - [Agent capacity update history (msdyn_agentcapacityupdatehistory) table](../../developer/reference/entities/msdyn_agentcapacityupdatehistory.md)
  - [Agent Capacity Profile Unit (msdyn_agentcapacityprofileunit) table](../../developer/reference/entities/msdyn_agentcapacityprofileunit.md)

- **Unit-based capacity profiles**
  - [Agent Status (msdyn_agentstatus) table](../../developer/reference/entities/msdyn_agentstatus.md)
  - [Agent Status history (msdyn_agentstatushistory) table](../../developer/reference/entities/msdyn_agentstatushistory.md)

### Use representative attributes to optimize workload

To set up your service representatives for success:

- Make sure that the default presence status is set up for them when they start their work day, helping to manage their availability and workload effectively. Learn more in [Create and manage users and user profiles](users-user-profiles.md).
- If no default presence is set, the system automatically sets the presence to **Available** when they sign in.
- Make sure that the representatives and supervisors don't manually change the presence status so that the assignment cycles run uninterrupted.
- Configure assignment rules to route and assign cases and conversations based on shift schedules imported from external workforce management (WFM) systems. By verifying the schedules in advance, you can avoid routing tasks to off-duty representatives, and reduce the risk of delays. Learn more in [Configure routing based on external schedules](configure-routing-on-agent-calendar.md).

## Manage queues

- Manage automatic assignment if the top 100 work items have extended wait times.
- Use skill-based routing to distribute work items to the most qualified service representatives.
- Set up single or multiple queues with skill-matching to manage different types of work.

### Use classification rules for enhanced assignment performance

Complex rules and conditions in prioritization rulesets add latency to the prioritization and assignment cycles. These assignment cycles are iterative and run until the system finds a service representative and assigns the work item. To simplify manageability and reduce assignment latency, we recommend that you use the classification rules in the workstream to check for static values and categorize the conversation. For example, checks on whether the conversation is from a VIP customer or an urgent query that requires immediate attention, can be evaluated only once during classification. By setting an attribute in the classification rule, you can use it downstream in route-to-queue and prioritization rules.

### Manage auto-assignment if work items have extended wait times

The auto-assignment process in unified routing matches incoming work items with the best-suited service representatives based on the configured assignment rules. This continuous process is made up of multiple assignment cycles. Learn about the auto-assignment process in [How automated assignment works](assignment-methods.md#how-automated-assignment-works).

If you have a scenario in which representatives aren't available to be assigned the work items for an extended time, we recommend the following options:

- To minimize the wait time, use features like overflow management to manage high load or custom assignment rules to gradually relax rules to expand the eligible representatives pool.
- Review representative availability and schedules to evaluate staffing more representatives.

### Use skill-based routing to distribute work items to the most qualified representatives

Skill-based routing lets your contact center distribute work items (conversations) to the service representative who is most qualified to solve the issue. However, the need to use skill-based routing is determined by your business scenario.  

For example, to address the following scenario in your contact center, we recommend that you configure skill-based matching to assign work items to the service representative who has the necessary skills to handle the cases:

- My service team supports two types of work items&mdash;order delivery issues and refund requests. However, most of the users will have the skills for one type only.
- During standard operations, the team has two subgroups, and each group handles one type of incoming work items.
- During peak load, certain users can handle work items from both types.

Skill-based routing helps reduce the number of queues to be managed in your organization.

## Next steps

[Overview of unified routing](overview-unified-routing.md)  
[FAQ about unified routing](unified-routing-faqs.md)  

### Related information

[Provision unified routing](provision-unified-routing.md)  
[Set up skill-based routing](set-up-skill-based-routing.md)  
