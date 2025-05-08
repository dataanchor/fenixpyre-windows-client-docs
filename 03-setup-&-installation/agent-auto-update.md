---
title: "Auto-Update Feature for FenixPyre Agent"
description: "How the FenixPyre desktop agent automatically checks and applies software updates for seamless security."
slug: /03-setup-&-installation/agent-auto-update
keywords: [fenixpyre, auto-update, agent, installation]
last_updated: 2023-10-01
---

## Why it Matters
The auto-update feature keeps your FenixPyre agent up-to-date, ensuring the latest security enhancements and reducing manual maintenance efforts.

The FenixPyre desktop agent automatically checks for and installs software updates. Updates are categorized as:
- **Minor updates:** No Windows reboots required.
- **Major updates:** May require reboots due to driver changes.

### Frequency of Checks
1. The agent checks for updates once an hour.
2. A check occurs on Windows startup.
3. Subsequent checks happen every 60 minutes.

### Notification and Installation
When an update is available, a notification appears. You can install it immediately or defer by clicking 'Remind me later'.

<!-- IMG: ./media/03-setup-&-installation/screenshot-minor-update.png | Alt: Notification for minor update -->
<!-- IMG: ./media/03-setup-&-installation/screenshot-major-update.png | Alt: Notification for major update -->

> **Note:** Updates are delivered securely with integrity checks. If errors occur, contact support.
> **Warning:** Once installed, updates cannot be rolled back.

## Next Steps / Related Topics
- Proceed to [installing the FenixPyre agent](/03-setup-&-installation/install-windows-agent.md).
- Review [FenixPyre core concepts](/02-core-concepts/master-key.md) for key management.