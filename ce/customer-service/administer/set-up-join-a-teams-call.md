---
title: Set up Join a Teams call for customer service representatives
description: Learn how to set up Join a Teams call in Dynamics 365 Customer Service.
ms.date: 05/16/2025
ms.topic: how-to
author: lalexms
ms.author: laalexan
ms.reviewer: laalexan
ms.custom: bap-template
---

# Set up Join a Teams call for customer service representatives

[!INCLUDE[cc-feature-availability-embedded-yes](../../includes/cc-feature-availability.md)]

Join a Teams call is a feature that helps customer service representatives (service representatives or representatives) in your organization give their customers a more personalized support experience by using Teams to share their screen, connect through video, and offer remote control assistance. Customers don’t need to have a Teams license or previous experience using Teams.

This feature is turned on by default in Copilot Service workspace.

## Prerequisites

Ensure that the following prerequisites are met:

- In Power Platform admin center, go to **Settings** > **Product** > **Collaboration**, and then turn on the setting for **End users can join Teams meetings from appointments**. 
- Representatives in your organization must be able to access and use Teams.
- Representatives must be able to access the productivity pane to see the Join a Teams call app. Learn more in [Assign templates and enable the productivity pane and channels](create-agent-experience-profile.md#assign-users-templates-configure-productivity-pane-channels)
- If you want representatives to be able to invite their customers to Teams meetings via email, representative email must be configured for outbound email.

## Set up the ability for representatives to invite customers to join Teams calls

By default, the Join a Teams call feature is turned on out of the box in Copilot Service workspace for agent profiles that have Omnichannel for Customer Service enabled.  

If you previously disabled it and need to turn it back on, start with Step 1.  

If you want to complete the configuration for custom agent profiles, start with Step 4. 
   
1. In Copilot Service admin center, go to **Support experience** > **Collaboration**.
	
1. In **Join a Teams call**, select **Manage**.

1. On the **Join a Teams call** page, turn on the setting for **Join a Teams call**.

1. If you want to enable custom agent profiles that aren't set by default to invite customers to join Teams calls, you must manually enable it for those profiles. Select **Manage** next to **Turn on for specific multisession users.** Learn more in [Add the Teams chat setting page for specific multisession users](configure-teams-chat.md#add-the-teams-chat-settings-page-for-specific-multisession-users)

1. Save the changes. The Join a Teams call feature is now enabled for users in Copilot Service workspace.

### Related information

[Configure Teams ](../use/oc-customer-summary.md) <br>
[Use Join a Teams call](../use/join-a-teams-call.md) <br>
[Configure Teams chat in Customer Service](configure-teams-chat.md)
