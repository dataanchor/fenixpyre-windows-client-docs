---
title: "Uninstalling the FenixPyre Agent"
description: "Guide to uninstalling the FenixPyre Agent via command line for secure and efficient removal."
slug: /03-setup-&-installation/uninstalling-agent
keywords: [fenixpyre, agent, uninstall, command-line]
last_updated: 2023-07-09
---

## Why it matters
Properly uninstalling the FenixPyre Agent ensures system cleanliness and prevents potential conflicts, maintaining optimal security posture.

### Command Line Operations
The FenixPyre Agent setup executable supports install, uninstall, and plugin operations. Use the following syntax:

```
DAtAnchorSetup_v4.0.0.exe {--install --org-id <org-id> | --uninstall | --plugin-install} [options...]
```

**Key Points:**
- Parameters are mutually exclusive and case-sensitive.
- Run commands in non-silent mode first to catch errors.

#### Available Parameters
- `--uninstall`: Removes the agent.
- `--silent`: Runs without prompts; system reboots automatically unless combined with `--reboot-prompt`.
- `--reboot-prompt`: Prompts user before rebooting.
- `--setup-logs <folder-path>`: Redirects logs to the specified folder.
- `--skip-unregister`: Allows uninstall without internet; use with `--uninstall`.
- `--help`: Displays help and ignores other parameters.

### Frequently Used Commands
1. Uninstall with user confirmation: `DAtAnchorSetup_v4.0.0.exe --uninstall`
2. Silent uninstall: `DAtAnchorSetup_v4.0.0.exe --uninstall --silent`
3. Silent uninstall with reboot prompt: `DAtAnchorSetup_v4.0.0.exe --uninstall --reboot-prompt`

> **Warning:** All parameters are case-sensitive; verify before use.

## Next Steps / Related Topics
After uninstalling, check [03-setup-&-installation/install-windows-agent.md] for reinstallation or visit [09-troubleshooting-&-faq/index.md] for common issues.
