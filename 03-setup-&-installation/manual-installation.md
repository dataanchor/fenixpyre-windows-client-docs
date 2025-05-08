---
title: "Manual Installation of FenixPyre Agent"
description: "Guide to manually installing the FenixPyre Agent on Windows 10/11 and servers."
slug: /03-setup-&-installation/manual-installation
keywords: [fenixpyre, installation, agent, windows]
last_updated: 2023-10-01
---

## Why it matters
Proper agent installation is essential for encrypting files and integrating FenixPyre with your environment.

### Installation Steps for Windows 10/11

**Step 1:** Meet all [prerequisites](/03-setup-&-installation/prerequisites).

**Step 2:** Unzip the installer and run **InstallerApp.exe**, entering your organization name.

<!-- IMG: ./media/03-setup-&-installation/installer-app.png | Alt: FenixPyre Installer interface -->

**Step 3:** Follow the prompts and reboot as required.

### Installation on Windows Server

**Step 1:** Enable Wireless LAN service.

**Step 2:** Use command-line installation: `DAtAnchorSetup_v4.0.0.exe --install --org-id <org-id> --skip-os-check`.

**Step 3:** Reboot and sign in.

> **Warning:** A reboot is mandatory for full functionality.

### Next Steps / Related Topics
Proceed to [Configuring Protected Folders](/04-admin-guide/configure-network-shared-folder).
