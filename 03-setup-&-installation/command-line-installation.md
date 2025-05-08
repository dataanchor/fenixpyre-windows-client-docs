---
title: "Command-Line Installation for FenixPyre Agent"
description: "Instructions for installing the FenixPyre Agent via command line on Windows."
slug: /03-setup-&-installation/command-line-installation
keywords: [fenixpyre, installation, command-line, agent]
last_updated: 2023-10-01
---

# Why it matters: Command-line installation enables automated, script-based deployment of the FenixPyre Agent, ideal for enterprise environments.

## Command Line Usage

Use the following syntax: `FenixPyreSetup_v4.0.0.exe {--install --org-id <org-id> | --uninstall | --plugin-install} [options...]`

### Key Parameters

- `--org-id <org-id>`: Required for install.
- `--silent`: Silent mode without prompts.
- `--skip-os-check`: For unsupported systems like Windows Server.

> **Tip:** All parameters are case-sensitive; test in non-silent mode first.

## Examples

- Regular install: `FenixPyreSetup_v4.0.0.exe --install --org-id <org-id>`
- Silent install: `FenixPyreSetup_v4.0.0.exe --install --org-id <org-id> --silent`

## Next Steps / Related Topics
Check [Prerequisites](/03-setup-&-installation/prerequisites.md) before proceeding.
