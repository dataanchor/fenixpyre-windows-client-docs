---
title: "Managing Ignored Folders"
description: "Guide for admins to manage folders that are not monitored by FenixPyre for encryption."
slug: /04-admin-guide/managing-ignored-folders
keywords: [fenixpyre, encryption, admin-guide, ignored-folders]
last_updated: 2023-09-01
---

## Why it matters
Ignored folders prevent unintended encryption of files in system directories, ensuring application compatibility and smooth operations.

### What is an Ignored Folder?
An ignored folder is a location where files are not encrypted by the FenixPyre Agent by default.

> **Warning:** Do not encrypt files in default ignored folders, as it may cause applications to malfunction.

### Step-by-Step Guide

**Step 1:** Log in to the FenixPyre Admin Dashboard and navigate to **Settings > Global Policies > Advanced Settings**.

<!-- IMG: ./media/04-admin-guide/advanced-settings.png | Alt: Admin dashboard advanced settings page -->

**Step 2:** Add the folder path under **Filters > Unmonitored**.

Default ignored folders include: \Program Files (x86)\, \Program Files\, \ProgramData\, \Windows\.

> **Note:** Enter the full path for custom folders.

### Next Steps / Related Topics
For more admin tasks, refer to [FenixPyre Admin Guide Index](/docs-v4/04-admin-guide/index.md).
