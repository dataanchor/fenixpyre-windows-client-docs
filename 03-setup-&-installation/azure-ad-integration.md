---
title: "Azure AD Integration with FenixPyre"
description: "Step-by-step process to set up Azure Active Directory integration for FenixPyre authentication."
slug: /03-setup-&-installation/azure-ad-integration
keywords: [fenixpyre, azure-ad, integration]
last_updated: 2023-10-01
---

## Why it Matters
Integrating with Azure AD streamlines user authentication and authorization, enhancing security for FenixPyre deployments.

This guide demonstrates how to set up Azure Active Directory integration with FenixPyre.

### Setup

1. Log in to your Azure Portal with admin credentials.

2. Navigate to the Azure Active Directory window.

<!-- IMG: ./media/azure-ad-integration/screenshot1.png | Alt: Azure Active Directory page -->

3. Select **Enterprise Applications** and then **New Application**.

4. Create your own application and register it.

5. Input the name and select the option to integrate with Azure AD.

6. Add the redirect URI as https://fenixpyre.us.auth0.com/login/callback and register.

7. Note the Client ID and Tenant ID.

8. Create a new client secret and share it with support along with IDs.

9. Add necessary API permissions for Microsoft Graph.

<!-- IMG: ./media/azure-ad-integration/screenshot2.png | Alt: API permissions setup -->

## Next Steps / Related Topics
Proceed to [User Management](/04-admin-guide/index.md) after integration.
