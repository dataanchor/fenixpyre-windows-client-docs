---
title: "FenixPyreUpdater.exe Command Line Usage"
description: "Advanced guide for using FenixPyreUpdater.exe via command line, intended for administrators managing updates programmatically."
slug: /03-setup-&-installation/command-line-usage
keywords: [fenixpyre, encryption, command-line, agent-update]
last_updated: 2023-10-01
---

## Why it matters
Command-line usage enables automated, script-based updates, ideal for large-scale deployments to maintain consistent encryption security.

*Note: This is for administrative use only.*

### Basic Usage
Run: `FenixPyreUpdater.exe [--silent]`
- `--silent`: Optional; performs updates without UI prompts.

### Service Specification
Run: `FenixPyreUpdater.exe [--service --org-id <org-id>]`
- `--service`: Installs and starts the service with the specified org ID.

> **Warning:** These arguments are mutually exclusive; do not combine `--silent` and `--service`.

## Next Steps / Related Topics
Refer to the full update guide in [03-setup-&-installation/update-agent.md](./update-agent.md) or explore core concepts in [02-core-concepts/index.md](../02-core-concepts/index.md).