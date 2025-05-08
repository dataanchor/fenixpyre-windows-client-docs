---
title: "Automatic Encryption Service"
description: "How FenixPyre's automatic encryption service secures files added to protected folders."
slug: /07-features/automatic-encryption
keywords: [fenixpyre, encryption, automatic-encryption]
last_updated: 2023-10-01
---

## Why it matters
Automatic encryption protects files in real-time, reducing the risk of data exposure when files are created or added to protected folders.

The automatic encryption service encrypts any new file added to or created within a protected folder.

### Enabling or Disabling Automatic Encryption
To manage this feature:

1. Log in to the FenixPyre admin dashboard.
2. Go to **Settings** > **User Roles**.
3. Select a user role and click **Edit**.
   <!-- IMG:     ./media/07-features/screenshot-user-roles.jpg | Alt: FenixPyre admin dashboard user roles -->

4. Expand **User Component Settings**.
5. Toggle the **Automatic Encryption Service** option; it is enabled by default.
   <!-- IMG:     ./media/07-features/screenshot-toggle-encryption.jpg | Alt: Toggle for automatic encryption -->

### Adjusting the Encryption Delay
> **Note:** Available in FenixPyre Agent versions 5.3.3 and above.

#### Why Use a Delay?
A delay prevents disruptions to workflows by allowing time for other processes to complete before encryption.

#### How to Set the Delay:
1. In **User Component Settings**, enable Automatic Encryption if needed.
2. Enter a delay time in milliseconds (e.g., 1000 for 1 second).
   <!-- IMG:     ./media/07-features/screenshot-delay-settings.jpg | Alt: Input field for encryption delay -->
3. The default is 0 for immediate encryption; keep it under 60000 ms.

### Known Limitations
- Does not encrypt zero-byte files.
- May miss files in use by other applications.
- Ignores placeholder files.
- Processes multiple files sequentially with delay applied to each.

### Next Steps / Related Topics
Learn more about encryption in [Core Concepts](/02-core-concepts/encryption-model) or manage user roles in [Admin Guide](/04-admin-guide/index).
