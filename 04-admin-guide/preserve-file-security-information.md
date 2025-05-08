---
title: "How to Preserve File Security Information"
description: "Instructions for preserving file timestamps and security info in FenixPyre."
slug: /04-admin-guide/preserve-file-security-information
keywords: [fenixpyre, encryption, admin-guide, file-security]
last_updated: 2023-10-01
---

## Why it matters
Preserving file security information ensures accurate metadata and access controls, preventing issues with cloud sync and compliance.

### Preserve File Timestamps

By default, FenixPyre updates file timestamps during encryption or decryption. To preserve them:

1. Log in to the FenixPyre Admin Dashboard.
2. Go to **Settings > Global Policies > Admin Configurations**.
3. Scroll to **Agent File Properties** and toggle **Preserve File Timestamps** on.

> **Warning:** Enabling this may affect cloud services like OneDrive; test thoroughly.

<!-- IMG: ./media/04-admin-guide/preserve-timestamps.png | Alt: Preserve file timestamps toggle -->

### Definitions

| Term            | Definition                          |
|-----------------|-------------------------------------|
| Creation Date  | Date and time when the file was created. |
| Last Accessed Date | Date and time when the file was last accessed. |
| Last Modified Date | Date and time when the file was last modified. |

### Preserving File Security Information

1. In the Admin Dashboard, under **Agent File Properties**, toggle **Preserve File Security Info** on.

<!-- IMG: ./media/04-admin-guide/preserve-security-info.png | Alt: Preserve file security info toggle -->

## Next Steps / Related Topics
For additional admin settings, see [Key Management](/02-core-concepts/key-mgmt). Explore [Policies and Roles](/02-core-concepts/policies-roles).
