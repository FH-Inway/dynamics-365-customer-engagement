---
title: Apply authentication for search providers
description: Apply OAuth 2.0 authentication for search providers using Microsoft Entra ID with resource, client IDs, and client secret configurations.
author: Soumyasd27
ms.author: sdas
ms.reviewer: sdas
ms.topic: how-to
ms.date: 05/09/2025
ms.custom:
  - bap-template
  - ai-gen-docs-bap
  - ai-gen-desc
  - ai-seo-date:04/09/2025
---

# Apply authentication for search providers

[!INCLUDE[azure-ad-rename](../../includes/cc-azure-ad-rename.md)]

Apply authentication for your search providers as required by your organization. If you authenticate using OAuth 2.0 with Microsoft Entra ID, you need the resource ID, client ID, and client secret from your configuration of Microsoft Entra ID authentication for your website. OAuth 2.0 only works with cloud mode.

The values of the resource ID, client ID, and client secret depend on your scenario.

- **Scenario 1:** You're using the same application for the identity provider and the client app to access the website.
  - The client ID and the resource ID are the application's application ID.
  - The client secret is the secret that you generated in the app.
  - After you configure the client app, make sure to create a new client secret in the app's **Certificates and secrets** settings.

- **Scenario 2:** You're using different applications for the identity provider and the client app.
  - The client ID is the application ID of the client app.
  - The client secret is the secret that you generated in the client app.
  - The resource ID is the application ID of the identity provider app.

## Apply OAuth 2.0 authentication

1. Go to https://ms.portal.azure.com/.
1. From the site map, go to **All services** > **App registrations** > **Owned applications** and select yours.
1. In the **Branding & properties** tab, enter the **Home page URL**.

    :::image type="content" source="../media/homepageurl.png" alt-text="Screenshot of the Branding & properties tab, with the Home page URL highlighted.":::

1. In the **Authentication** tab, select **Add a platform**.
1. Select **Web**.

    :::image type="content" source="../media/configure-web_new.png" alt-text="Screenshot of web platform settings.":::

1. If you use the user token that's sent by Azure for authentication, enter the **Redirect URIs**. Otherwise, this field is optional.

1. Select **ID tokens (used for implicit and hybrid flows)**.
1. Select **Configure**.
1. In the **Overview** tab, copy the **Application (client) ID**.
1. In the **Certificates & secrets** tab, either enter the client secret provided in the **Generated by App Service** field or select **New client secret** to create one.

    If you selected **New client secret**, enter the **Description** and select an expiration period in **Expires**.

1. Select **Add**.

## Next steps

[Manage integrated search providers](add-search-provider.md#manage-integrated-search-providers)
