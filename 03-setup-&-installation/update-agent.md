---
title: "How to Update FenixPyre Agent"
description: "Guide to updating the FenixPyre Agent using the updater tool for seamless encryption management and security enhancements."
slug: /03-setup-&-installation/update-agent
keywords: [fenixpyre, encryption, agent-update, installation]
last_updated: 2023-10-01
---

## Why it matters
Keeping the FenixPyre Agent updated ensures you have the latest security features and fixes, protecting your data from vulnerabilities.

The FenixPyre Agent updater (`FenixPyreUpdater.exe`) simplifies updates for versions 5.3 and later, handling restarts and supporting silent modes for managed environments.

### Key Changes in Updater File Names
For versions 5.3+, file names have been updated; update your scripts if using older versions.

| Package Description                  | v5.2.1 and earlier       | v5.3 and later          |
| ------------------------------------| -------------------------| ------------------------|
| Update from previous versions       | N/A                      | `FenixPyreUpdater.exe`  |
| UI-based installation               | `InstallerApp.exe`       | `FenixPyreInstaller.exe`|
| Command-line installation           | `DAtAnchorSetup_v<versionNumber>.exe` | `FenixPyreSetup_v<versionNumber>.exe` |

### Download the Updater
1. Go to the FenixPyre Admin Dashboard and click **Installers**.
2. Download your desired version and unzip to access `FenixPyreUpdater.exe`.

### Update in Regular Mode
1. Download `FenixPyreUpdater.exe` to the target computer.
2. Double-click to run it.
3. Confirm the dialog for two reboots.
4. Wait for completion and reboot if prompted.

<!-- IMG: ./media/03-setup-&-installation/agent-login.png | Alt: FenixPyre Agent login screen after update -->

### Update in Silent Mode
1. Download the file.
2. Open an admin Command Prompt and navigate to the file.
3. Run `FenixPyreUpdater.exe --silent`.

> **Note:** Monitor progress via the Windows registry key `HKLM\Software\DAtAnchor\FullUpdateStatus` (values: 0=Idle, 1=UninstallStarted, etc.).

### What Happens During Update
- Stops FenixPyre services.
- Uninstalls and reinstalls components.
- Reboots as needed.

## Next Steps / Related Topics
For command-line details, see [03-setup-&-installation/command-line-usage.md](./command-line-usage.md), or start with [03-setup-&-installation/index.md](../index.md).