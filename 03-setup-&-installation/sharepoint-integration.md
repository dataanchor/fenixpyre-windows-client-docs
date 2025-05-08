# Setting Up FenixPyre Add-in for SharePoint

Guide to configure FenixPyre integration with SharePoint for seamless encryption.


## Why it Matters
Integrating FenixPyre with SharePoint protects your data with encryption while enabling secure collaboration in Microsoft environments.

### Creating an Azure App
Follow these steps to set up the integration:

**Step 1:** Go to [https://portal.azure.com/](https://portal.azure.com/).

**Step 2:** Click **Azure Active Directory**.

**Step 3:** Select **App Registrations** and click **New registration**.

**Step 4:** Name the app (e.g., "FenixPyre"), select account type, and set redirect URI.

**Step 5-14:** Complete app configuration as detailed in the legacy documentation, including creating a client secret and adding permissions.

> **Note:** Replace all instances of legacy terms with FenixPyre equivalents.

<!-- IMG: ./media/03-setup-&-installation/azure-app-setup.png | Alt: Azure portal app registration steps -->

### Next Steps / Related Topics
After setup, refer to [FenixPyre Agent Installation](/03-setup-&-installation/install-windows-agent.md).