---
title: "Managing Authorized Applications in FenixPyre"
description: "Guide for admins to add and manage authorized applications for FenixPyre encryption."
slug: /04-admin-guide/authorized-applications
keywords: [fenixpyre, admin-guide, authorized-apps]
last_updated: 2023-10-01
---

## Why it matters
Authorized applications ensure that only approved tools can access decrypted data, enhancing security without disrupting workflows.

Admins can maintain a list of authorized applications, which are not FenixPyre-certified but approved for your organization.

### Adding Authorized Applications
1. Open the FenixPyre dashboard.
2. Navigate to **Settings > User Roles > Encrypt by Folder > Applications**.
3. Select the action icon (three vertical dots) and choose **Edit**.

   <!-- IMG: ./media/04-admin-guide/edit-applications.png | Alt: Edit button for applications -->

4. Go to **Encrypt by Folder > Applications**.
5. Click **New Authorized Application**, enter the name and full executable path (e.g., C:\Windows\System32\notepad.exe), then click **Add**.

   <!-- IMG: ./media/04-admin-guide/add-app-path.png | Alt: Form for adding application path -->

6. Click **Update** to save changes.

> **Warning:** Application names must contain only letters and spaces, no periods or special characters.

## Next Steps / Related Topics
Explore more admin tasks in [Automatic Account Creation](/04-admin-guide/automatic-account-creation) or [User Guide Overview](/05-user-guide/index).