---
title: "Managing Guest Domains"
description: "Learn how to add, delete, or edit guest domains in FenixPyre to control external access to encrypted files."
slug: /04-admin-guide/manage-guest-domains
keywords: [fenixpyre, admin, guest-domains, sharing, security]
last_updated: 2023-10-01
---

## Why It Matters
Guest domains allow controlled sharing of encrypted files with external users, enhancing collaboration while minimizing security risks.

### What Are Guest Domains?
Guest domains are email domains that internal users can share files with. Only added domains can access shared links.

#### Adding a New Guest Domain
1. Sign in to the FenixPyre Admin Dashboard at [https://admin.fenixpyre.com](https://admin.fenixpyre.com).
2. Go to **Settings > Security > Identity & Provisioning > Domains**.

<!-- IMG: ./media/04-admin-guide/domains-page-screenshot.png | Alt: Domains section in Admin Dashboard -->

3. Under **Guest Domains**, click **Add new Domain**.
4. Enter the domain (e.g., contoso.com) and click **Add**.

<!-- IMG: ./media/04-admin-guide/add-domain-screenshot.png | Alt: Add domain form -->

> **Warning:** Deactivation of users may occur if domains are edited or deleted.

#### Deleting a Guest Domain
1. Go to the same **Domains** page.
2. Click the delete icon next to the domain.
3. Confirm deletion in the dialog box.

<!-- IMG: ./media/04-admin-guide/delete-domain-screenshot.png | Alt: Delete domain confirmation -->

#### Editing a Guest Domain
1. Click the edit icon next to the domain.
2. Make changes and confirm.

<!-- IMG: ./media/04-admin-guide/edit-domain-screenshot.png | Alt: Edit domain interface -->

### Next Steps / Related Topics
For user management, refer to [Adding New Users](/04-admin-guide/add-new-user). Explore [Security Settings](/04-admin-guide/security-settings).