---
title: "Find FenixPyre Agent Version Silently"
description: "Use a PowerShell script to silently check the installed version of the FenixPyre Agent on user machines."
slug: /09-troubleshooting-&-faq/agent-version-check
keywords: [fenixpyre, agent, version-check, powershell]
last_updated: 2023-10-01
---

## Why it matters
Verifying the agent version ensures compatibility and helps apply updates for optimal security and performance.

### Checking Agent Version via PowerShell
This guide demonstrates how to determine the FenixPyre Agent version installed on a machine.

#### Step-by-Step Guide
**Step 1:** Search for "PowerShell" in the Windows search bar and open it.

**Step 2:** Paste and run the following script:

```powershell
$json = Get-Content 'C:\Program Files\FenixPyre Agent\FenixPyreSetupManifest' | Out-String | ConvertFrom-Json
$json.versions.FenixPyre
```

**Step 3:** The script will return the agent version, e.g., 4.0.0.

<!-- IMG:     ./media/09-troubleshooting-&-faq/agent-version-output.png | Alt: Screenshot of PowerShell output showing agent version -->

### Next Steps / Related Topics
If issues arise, check [install-windows-agent.md](../03-setup-&-installation/install-windows-agent.md). For more FAQs, see [index.md](./index.md).