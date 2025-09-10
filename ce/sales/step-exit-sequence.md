---
title: "Define criteria to exit a sequence during the flow"
description: "Exit a sequence during the flow when the defined criteria is met."
ms.date: 12/31/2024
ms.topic: how-to
author: udaykirang
ms.author: udag
ms.reviewer: udag
---

# Exit a sequence during the flow

By enabling the option to exit a sequence, you disconnect the sequence from its records when the criteria is met. For example, if the flow includes an email reply from the customer, the record will be disconnected from the sequence.

## Prerequisites

Review the following requirements before you configure the exit criteria:

- At least one email activity step is created in the sequence. 
- The sequence must be in inactive or revision state.
- [Configure the email engagement feature](configure-email-engagement.md) in your organization before you start using this option for the email activity.

## Configure the exit sequence criteria

1.	Open the sequence and then on the designer page, select **Exit criteria**.

    :::image type="Select exit criteria in the sequence designer" source="media/sequence-designer-select-options.png" alt-text="Select exit criteria in the sequence designer":::

2.	On the **Sequence Options** pane, turn on the **Exit a sequence** toggle to exit a sequence when a customer replies to any email in the sequence.  

    :::image type="Enable exiting a sequence on the Sequence Options pane" source="media/sequence-sequence-options-pane.png" alt-text="Enable exiting a sequence on the Sequence Options pane":::

3.	Select **Save**.

[!INCLUDE[cant-find-option](../includes/cant-find-option.md)]

## Related information

[Create and activate a sequence](create-and-activate-a-sequence.md)      
[Add steps to sequence](steps-sequence.md)  
[Add condition steps to sequences](adaptive-sequence.md)   
[Add command steps to sequences](command-sequence.md)     
[Add LinkedIn activities to sequence](linkedin-activities-sequence.md)
