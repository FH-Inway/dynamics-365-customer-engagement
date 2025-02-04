---
title: msdyn_ConnectSequence Action
description: How to assigns a lead and opportunity entity record to a sequence.
ms.date: 12/04/2024
ms.custom: 
ms.topic: article
author: udaykirang
ms.author: udag
ms.reviewer: udag
---

# msdyn_ConnectSequence Action

This action is used to assign a lead and opportunity entity record to a sequence.

## Parameters

|Name |Description |
|-----|-----|
|`RegardingEntityId`|Unique identifier of the entity record that is to be connected to the sequence.|
|`RegardingEntityName`|Logical name of the entity|
|`SequenceId`|Unique identifier of the sequence|

## Example

```json
POST [Organization URI]/api/data/v9.1/msdyn_ConnectSequence

{
    "RegardingEntityId":"11bb11bb-cc22-dd33-ee44-55ff55ff55ff",
    "RegardingEntityName":"lead",
    "SequenceId":"aaaaaaaa-0000-1111-2222-bbbbbbbbbbbb"
}
```

## Related information

[Enable and configure the Sales accelerator](../../enable-configure-sales-accelerator.md)
