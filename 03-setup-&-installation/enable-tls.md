---
title: "Enabling TLS 1.2 for FenixPyre Agent Installation"
description: "Steps to enable TLS 1.2 on Windows to ensure secure FenixPyre Agent installation."
slug: /03-setup-&-installation/enable-tls
keywords: [fenixpyre, tls, security, installation]
last_updated: 2023-10-01
---

## Why It Matters

Enabling TLS 1.2 prevents installation errors and maintains encryption security in FenixPyre.

### How to Enable TLS 1.2 on Windows

1. Open Registry Editor by typing `regedit` in the Start menu.
2. Navigate to `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\SecurityProviders\SCHANNEL\Protocols`.
3. Create a new key named `TLS 1.2`.
4. Inside `TLS 1.2`, create a sub-key named `Client`.
5. In the `Client` key, create and set DWORD values:
   - `Enabled` to `1`.
   - `DisabledByDefault` to `0`.
6. Restart your computer.

> **Note:** Refer to Microsoft's documentation for more details.

## Next Steps / Related Topics

Proceed to [install the FenixPyre Windows Agent](/03-setup-&-installation/install-windows-agent.md).