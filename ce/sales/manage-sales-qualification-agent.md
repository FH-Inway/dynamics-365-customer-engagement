---
title: Manage the Sales Qualification Agent
description: Learn how to manage such as stop or edit the sales qualification settings in Dynamics 365 Sales.
ms.topic: how-to 
ms.date: 07/31/2025
ms.service: dynamics-365-sales
content_well_notification:
  - AI-contribution
ms.custom: bap-template
author: udaykirang
ms.author: udag
ms.reviewer: udag
search.app: salescopilot-docs
ms.collection: bap-ai-copilot
ai-usage: ai-assisted
---

# Manage the Sales Qualification Agent

[!INCLUDE [preview-banner](~/../shared-content/shared/preview-includes/preview-banner.md)]

[!INCLUDE [preview-banner](~/../shared-content/shared/preview-includes/preview-note-d365.md)]

As an administrator, you can manage the Sales Qualification Agent in your organization by editing or stopping the agent.

## Edit the Sales Qualification Agent

Lead qualification is an evolving process which requires experimentation, continuous monitoring, and iterative refinement. Edit the agent configurations to fine-tune the settings based on real-world insights, ensuring a more accurate, and efficient qualification process.

>[!NOTE]
>Once an agent is published, we recommend only a few select fields to be edited. Sections that have tag "Avoid edits" should not be edited as it can lead to the agent giving different results.

**Follow these steps**:

1. [Go to the agent settings page](open-sales-qualification-agent-settings.md).  
1. Edit the sections as required and then select **Apply changes**.  

    :::image type="content" source="media/sqa-settings-edit-page.png" alt-text="Screenshot of editing the Sales Qualification Agent in settings page.":::

1. On the confirmation dialog, select **Apply changes** to confirm the changes.

    Applying the changes might take a few seconds to update the settings, you can continue working while the changes are being applied.  

The updated agent is active, and new leads are processed based on the updated settings. However, leads that are already processed based on the previous agent configurations will not be reprocessed.

## Stop the Sales Qualification Agent

Stop the agent when you don’t want to use it in your organization. Stopping the agent doesn’t delete it and retains the configuration settings.

**Follow these steps**:

1. [Go to the agent settings page](open-sales-qualification-agent-settings.md).  
1. On the agent settings page, select **Stop agent**.  

    :::image type="content" source="media/sqa-settings-stop-agent-page.png" alt-text="Screenshot of stopping the Sales Qualification Agent in settings page.":::

1. On the confirmation message select **Stop agent**.  

    The agent is stopped, and a confirmation message is displayed on the top of the page.

Leads under process before stopping the agent will be stopped for further processing. However, leads that are already processed will not be affected and will continue to be available in the application.

> [!NOTE]
>
> Once you configure and start an agent, it can’t be deleted. If you want to delete the agent, contact Microsoft Support.

## Related information

- [Start the Sales Qualification Agent](start-sales-qualification-agent.md)  
- [Configure the Sales Qualification Agent](configure-sales-qualification-agent.md)
