---
title: Enable session restore to automatically reopen browser sessions and tabs (preview)
description: Learn how to enable session restore to automatically reload sessions and tabs in Customer Service workspace.
author: lalexms 
ms.author: laalexan
ms.reviewer: laalexan
ms.topic: how-to 
ms.date: 03/27/2025 
ms.custom: bap-template 
---

# Enable session restore to automatically reopen sessions and tabs (preview)

[!INCLUDE [preview-banner](../../../shared-content/shared/preview-includes/preview-note.md)]

By default, when a browser is refreshed or reconnected in the Customer Service workspace app, only the home page reloads. Service representatives must manually reopen all their sessions and application tabs, such as calls, cases, chats, and messages. Common reasons a browser might close include browser memory issues, microphone or headset problems, network instability, or accidental browser closures.

As an administrator, you can enable session restore, which automatically restores sessions when the browser refreshes. Session restore ensures that service representatives can promptly resume their work without having to manually reconstruct their workspaces. Key entities, such as cases, accounts, and their associated application tabs are reopened, and focus restores to the last session or application tab in view. After the presence is loaded, conversations, including calls and chats, are reinstated.

## Enable session restore for service representatives

1. In the site map of Customer Service admin center or Contact Center admin center, select **Miscellaneous**.
1. In **New and upcoming features**, select **Manage**.
1. Select the **Session restore** checkbox, and then select **Save**.

## Definitions and considerations

Before you enable the session restore feature, review the following definitions and considerations.

### Definitions

- Generic sessions: All sessions that were created using generic session templates.  
- Last updated browser tab: A browser tab where the service representative most recently created or closed a session or tab. Switching of sessions or tabs by representatives doesn't qualify as "last updated browser tab".

### Considerations

- When a representative uses multiple browser sessions or tabs, the system can't restore the session properly for channel-specific sessions, such as for chat and voice. The system restores the latest updated browser tab or session only.
- The order of session tabs might change.
- Cross-browser restoration, such as from Microsoft Edge to Google Chrome, isn't supported.
- While the productivity pane state and focus are restored, the system doesn't restore the state of the productivity tools.
- The system restores chats, calls, and other conversations after presence is reestablished. There's a slight delay when compared to other sessions.
- Sessions that are initiated by third-party providers via Dynamics 365 Channel Integration Framework aren't restored.
- The system doesn't restore panels that are loaded using the Xrm.pane API. Only panels that the system loads using the custom productivity tools feature are restored.
- The system can't restore generic sessions in browser tabs that were reopened using the Ctrl+Shift+T function. Generic sessions can be restored by refreshing the current browser tab only.
- Consult conversations restoration isn't supported.
- Sessions with the new record form open (and saved later) are restored in the new state only.

### Related information

[Overview of Customer Service workspace](../implement/csw-overview.md)  
[Overview of the productivity pane](../use/csw-productivity-pane.md)  
