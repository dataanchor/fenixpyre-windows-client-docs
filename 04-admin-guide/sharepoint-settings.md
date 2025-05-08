---
title: "Configuring SharePoint Settings in FenixPyre Admin Dashboard"
description: "Learn how to securely configure SharePoint integration in the FenixPyre Admin Dashboard for encrypted file management."
slug: /04-admin-guide/sharepoint-settings
keywords: [fenixpyre, encryption, sharepoint, admin]
last_updated: 2023-10-01
---

# Configuring SharePoint Settings in FenixPyre Admin Dashboard

**Why it matters:** Proper configuration of SharePoint settings ensures seamless encryption and protection of files in collaborative environments, preventing unauthorized access and maintaining data security.

This guide explains how to configure SharePoint settings in the FenixPyre Admin Dashboard. It builds on previous setup steps; for reference, see the [FenixPyre Add-in Setup guide](../setup-&-installation/install-add-in.md).

Before proceeding, ensure the File Collaboration feature is disabled, as it can interfere with encryption. FenixPyre disables this during agent installation, but if needed, follow instructions in the [disabling File Collaboration guide](../09-troubleshooting-&-faq/disable-file-collab.md).

## Entering Settings in the Admin Dashboard

In the FenixPyre Admin Dashboard, navigate to **Integrations > SharePoint > Settings** and input the following:

1. **Application (Client) ID:** Found on the app's overview page.
2. **Client Secret Value:** Saved from a previous step (refer to the setup guide).
3. **Directory (Tenant) ID:** Found on the app's overview page.

<!-- IMG: ./media/04-admin-guide/sharepoint-settings/screenshot.png | Alt: FenixPyre Admin Dashboard SharePoint settings page -->

### Step 1: Log in and Enter Your SharePoint Domain
Log in to the Admin Dashboard and enter your SharePoint domain in the first field, such as `yourcompany.sharepoint.com`. Do not use the SharePoint admin center URL.

- **Correct:** yourcompany.sharepoint.com
- **Incorrect:** yourcompany-admin.sharepoint.com

<!-- IMG: ./media/04-admin-guide/sharepoint-settings/azure.png | Alt: Example of correct SharePoint domain entry -->

### Step 2: Verify Integration in a Private Browser Window

1. Open a browser in incognito or private mode.
2. Log in to your SharePoint account.
3. Open a SharePoint site.
4. Navigate to `Documents`.
5. Select a file, right-click, and confirm `FenixPyre` options appear in the menu.

<!-- IMG: ./media/04-admin-guide/sharepoint-settings/documents.png | Alt: SharePoint documents view with FenixPyre options -->

<!-- IMG: ./media/04-admin-guide/sharepoint-settings/right-click-menu.png | Alt: Right-click menu showing FenixPyre encrypt options -->

**Note:** It may take up to 24 hours for changes to reflect in your SharePoint environment. If issues persist, try logging out and back in, or access via private mode. Folders must be added as protected under user roles to use FenixPyre actions.

For adding protected folders, see the [Adding Protected Folders guide](../04-admin-guide/protected-folders.md).

## Next Steps / Related Topics
After configuration, explore [managing user roles](../04-admin-guide/user-roles.md) or troubleshoot common issues in the [Troubleshooting section](../09-troubleshooting-&-faq/index.md).