---
title: Set up a pay-as-you-go plan)
description: Learn how to set up a pay-as-you-go plan for the autonomous case management agent.
author: gandhamm
ms.author: mgandham
ms.reviewer: mgandham
ms.topic: how-to 
ms.collection: 
ms.date: 03/04/2025
ms.custom: bap-template
---

# Set up a pay-as-you-go plan

The autonomous case management agent uses the Data Entry Agent in the background. The [Power Platform pay-as-you-go](/power-platform/admin/pay-as-you-go-overview) plan mandates the usage of an Azure subscription the system charges when the agent runs. This topic describes how the charges are calculated in such scenarios.

## Consumption-based billing

Selected Copilot and agent capabilities in Dynamics 365 use consumption-based billing, charging per use. These capabilities use Microsoft Copilot Studio messages for AI interactions and tasks, like retrieving information and responding to prompts. Messages are the billing units that measure usage. The number of messages per event depends on its complexity. Learn more about messages in [Message scenarios](/microsoft-copilot-studio/requirements-messages-management#message-scenarios).  

Learn more about billing and rates in [Power Platform Licensing Guide](https://go.microsoft.com/fwlink/?LinkId=2085130).

### Set up billing model

Dynamics 365 supports two billing models: prepaid capacity and pay-as-you-go. The prepaid capacity model uses Copilot Studio message pack subscriptions, which are a licensing option for Microsoft Copilot Studio that you purchase in advance. The pay-as-you-go model charges for the actual number of messages consumed by agents during the month. Learn more in [Copilot licensing](/microsoft-copilot-studio/billing-licensing).

Both models require that you link your Dynamics 365 environment to a Power Platform environment.

> [!NOTE]
> Both billing models can be used on the Dynamics 365 environment. Prepaid capacity is consumed first.
> Message capacity on the Power Platform environment is consumed by Dynamics 365 environments and other Microsoft services on the tenant.

### Set up prepaid capacity

Complete these tasks to set up the Dynamics 365 environment for prepaid capacity.

1. Purchase a Copilot message pack subscription using the Microsoft 365 admin center.

   Learn more in [Manage self-service purchases and trials (for users)](/microsoft-365/commerce/subscriptions/manage-self-service-purchases-users) or [Manage self-service purchases and trials (for admin)](/microsoft-365/commerce/subscriptions/manage-self-service-purchases-admins).

1. Assign prepaid capacity to the Power Platform environment using the Power Platform admin center.

   Learn more in [Manage Capacity](/power-platform/admin/manage-copilot-studio-messages-capacity?tabs=new#manage-capacity).


### Set up pay-as-you-go

Complete these tasks to set up the Dynamics 365 environment for pay-as-you-go.

 Set up pay-as-you-go on the Power Platform tenant:

   To set up pay-as-you-go billing, you first need an active Azure subscription. Then, you link the subscription to your Power Platform environment using the [Power Platform admin center](https://admin.powerplatform.microsoft.com/) or within [Power Apps](https://make.powerapps.com/).

Learn more in [Set up pay-as-you-go](/power-platform/admin/pay-as-you-go-set-up).

## Manage capacity and usage

You can view Copilot Studio message capacity and usage for prepaid capacity and pay-as-you-go in the Power Platform admin center. Learn more in [Manage Copilot Studio messages and capacity](/power-platform/admin/manage-copilot-studio-messages-capacity).

Dynamics 365 regularly checks the available capacity (quota) of Copilot Studio messages. If your organization's quota is low or depleted, users receive in-app notifications about the status and necessary actions. It's important to take timely action on these notifications by reallocating existing capacity or purchasing more capacity.

- For prepaid capacity, use the Power Platform admin center to allocate more capacity to the environment from the total available on the tenant. Learn more in [Manage capacity](/power-platform/admin/manage-copilot-studio-messages-capacity#manage-capacity). If there's no quantity to allocate, purchase more.
- For pay-as-you-go, use Microsoft Cost Management in the Azure portal to view detailed usage and adjust spending limits (budgets) to free up more capacity. Learn more in [View usage and billing information](/power-platform/admin/pay-as-you-go-usage-costs). If there's no quantity to allocate, purchase more.

> [!IMPORTANT]
> When the quota is depleted, the AI capability is unavailable until more capacity is added.

## Related information

- [Assign licenses and manage access to Copilot Studio](/microsoft-copilot-studio/requirements-licensing?tabs=web)  
- [Copilot Studio licensing](/microsoft-copilot-studio/billing-licensing)  
- [Disable or limit sharing of agents](/microsoft-copilot-studio/admin-sharing-controls-limits)  
- [Orchestrate copilot topics and actions with generative AI](/microsoft-copilot-studio/advanced-generative-actions)  
- [Work with Power Platform environments in Copilot Studio](/microsoft-copilot-studio/environments-first-run-experience)  
- [Pay-as-you-go plan](/power-platform/admin/pay-as-you-go-overview)  
