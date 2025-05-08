---
title: "Managing Admin Approved Applications"
description: "Learn how to add and manage admin approved applications in FenixPyre to control access to plain text data."
slug: /04-admin-guide/admin-approved-applications
keywords: [fenixpyre, admin, applications, security]
last_updated: 2023-10-01
---

## Why It Matters
Admin approved applications allow organizations to securely permit non-certified apps to handle plain text, enhancing control and reducing risks in data environments.

This guide explains how to add and manage these applications in the FenixPyre Admin Dashboard.

### Steps to Add Admin Approved Applications
1. **Access the Dashboard:**
   - Open the FenixPyre dashboard.

2. **Navigate to Settings:**
   - Go to **Settings > User Roles**.

3. **Edit User Role:**
   - Select the action icon (three vertical dots) and choose **Edit**.
   <!-- IMG: ./media/admin-guide/edit-user-role.png | Alt: Editing user role in dashboard -->

4. **Select Applications Section:**
   - Under **FenixPyre By Folder**, choose **Applications**.
   <!-- IMG: ./media/admin-guide/applications-section.png | Alt: Applications settings page -->

5. **Add New Application:**
   - Click **New Admin Approved Application**.
   - Enter the application name and full executable path (e.g., Notepad: C:\Windows\System32\notepad.exe).
   - Click **Add**.
   <!-- IMG: ./media/admin-guide/add-application.png | Alt: Adding a new admin approved application -->

6. **Save Changes:**
   - Click the **Update** button.

> **Warning:** Application names must contain only letters and spaces, no periods or special characters. Files created by non-approved applications in protected folders won't be encrypted automatically.

## Next Steps / Related Topics
Explore [user roles](04-admin-guide/index.md) or learn about [protected folders](03-setup-&-installation/protected-folders.md).