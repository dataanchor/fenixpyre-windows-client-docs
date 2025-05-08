---
title: "Getting Started with Azure SSO"
description: "Set up single sign-on with Azure for secure access to FenixPyre."
slug: /03-setup-&-installation/getting-started-azure-sso
keywords: [fenixpyre, azure, sso, setup]
last_updated: 2023-10-01
---

## Why it matters
Integrating Azure SSO ensures seamless and secure authentication, reducing risks and improving efficiency for FenixPyre users.

> **Note:** Before setting up Azure SAML SSO, review the [prerequisites.md in 03-setup-&-installation/](../03-setup-&-installation/prerequisites.md) and add your Azure Microsoft Entra ID primary domain to FenixPyre primary domains.

### Setup Single Sign-On with Azure Enterprise Application

1. Sign in to your Azure admin portal.
2. In the left menu, click on Microsoft Entra ID.
3. Click on **Enterprise applications**.
4. In the Enterprise applications page, click on **New application**.

<!-- IMG: ./media/03-setup-&-installation/azure-new-app.png | Alt: Screenshot of creating a new application in Azure -->

5. In the **Browse Microsoft Entra Gallery** page, click on **Create your own application**.

<!-- IMG: ./media/03-setup-&-installation/azure-gallery.png | Alt: Screenshot of the Azure gallery page -->

6. Enter a name, e.g., **fenixpyre-saml-sso-app**, and select **Integrate any other application you don't find in the gallery**.

<!-- IMG: ./media/03-setup-&-installation/azure-create-app.png | Alt: Screenshot of creating a custom application -->

7. Click **Create**.
8. In the application page, select **Single sign-on**.
9. Select SAML.
10. Edit **Basic SAML Configuration** and add the required values from FenixPyre Admin Dashboard.
11. Sign in to FenixPyre Admin Dashboard, go to Settings > Security > Identity & Provisioning > SAML SSO, and add a new SAML SSO for Azure.

<!-- IMG: ./media/03-setup-&-installation/fenixpyre-saml-setup.png | Alt: Screenshot of SAML SSO setup in FenixPyre -->

12. Copy the Identifier, Reply URL, and Sign-on URL, then paste them into Azure.
13. Save changes in Azure and grant necessary API permissions.
14. Download the Base64 certificate and copy the Login URL, then upload to FenixPyre.

<!-- VIDEO: ./media/03-setup-&-installation/azure-sso-setup.mp4 | Alt: Video of verifying Azure SSO setup | Duration: 60s -->

15. Verify the setup by logging out and signing back in.

### Next Steps / Related Topics
Proceed to [configure-sso.md in 03-setup-&-installation/](../03-setup-&-installation/configure-sso.md) for additional configurations.