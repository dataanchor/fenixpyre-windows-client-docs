---
title: "Configure FenixPyre by Process"
description: "How to set up automated encryption for files created by specific applications."
slug: /04-admin-guide/configure-anchor-by-process
keywords: [fenixpyre, encryption, by-process]
last_updated: 2023-10-01
---

## Why it matters
FenixPyre by Process automates encryption for designated applications, enhancing security for non-office workflows.

### Overview
FenixPyre by Process allows administrators to control encryption for files created by specific processes.

### Configuration Steps
1. Go to **Settings > User Roles > FenixPyre by Process > Collections** in the Admin Dashboard.
2. Select **Add New** to create a collection.
3. Configure options:
   - **Enforce Encryption outside protected folders**: Automatically encrypt files even outside protected folders.
   - **Process selection type**: Choose **By Name** for specific processes or **By Folder** for processes in a path.
   - **Process Path(s)**: Enter paths, e.g., `c:\program files\acad\acad.exe` (supports wildcards like `%username%`).
   - **Handle data by extensions**: Select **Protect** or **Ignore** specific extensions.

> **Warning:** If ignored extensions are in authorized lists, they may still encrypt in protected folders.

## Next Steps / Related Topics
Check [policies-roles.md](/02-core-concepts/policies-roles) for role-based configurations.
