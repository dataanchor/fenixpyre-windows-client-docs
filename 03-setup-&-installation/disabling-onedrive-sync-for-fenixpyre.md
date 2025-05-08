---
title: "Disabling OneDrive File Collaboration for FenixPyre"
description: "Steps to disable automatic syncing in OneDrive to ensure proper FenixPyre encryption functionality."
slug: /03-setup-&-installation/disabling-onedrive-sync
keywords: [fenixpyre, encryption, onedrive, setup, installation]
last_updated: 2023-10-01
---

## Why it matters
Disabling OneDrive's automatic sync prevents conflicts with FenixPyre encryption, ensuring files are properly secured during setup.

OneDrive may automatically sync Office files, which can interfere with FenixPyre's encryption. Follow these steps to disable this feature.

### Disabling Sync on Your Computer
**Step 1:** Open OneDrive settings.

**Step 2:** In the Office tab, uncheck the option "Use Office applications to sync Office files that I open".

<!-- IMG: ./media/03-setup-&-installation/onedrive-settings-screenshot.png | Alt: OneDrive settings screen with sync option unchecked -->

**Step 3:** Click **OK** to save changes.

> **Note:** After this, Office files will no longer auto-sync to OneDrive.

### For OneDrive Admins
To block syncing of temporary FenixPyre files:

**Step 1:** Go to [https://admin.onedrive.com/?v=SyncSettings](https://admin.onedrive.com/?v=SyncSettings).

**Step 2:** Enable "Block syncing of specific file types".

**Step 3:** Add the file extensions (datcmd, datuh, datbkp, datanchor) to the block list.

<!-- IMG: ./media/03-setup-&-installation/block-file-types-screenshot.png | Alt: OneDrive admin screen blocking specific file extensions -->

### Next Steps / Related Topics
Once configured, proceed to [Installing FenixPyre Agent](/03-setup-&-installation/install-windows-agent). For troubleshooting, refer to [Troubleshooting & FAQ](/09-troubleshooting-&-faq).