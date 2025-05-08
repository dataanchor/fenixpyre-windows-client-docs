# Primary Domains

Learn how to manage email domains for secure access to FenixPyre admin dashboard and encrypted files (≤160-char SEO summary).


## Why it Matters
Effective domain management ensures that only authorized users can access the FenixPyre admin dashboard and encrypted files, safeguarding sensitive data from unauthorized entry.

Domain management settings allow an admin to manage email domains that are allowed to access FenixPyre admin dashboard, sharing web application, and control access to encrypted files.

### What are Primary Domains?

Primary domains are email domains that can sign in and access FenixPyre admin dashboard (if the user is an admin), sharing web application, and install the desktop agents.

By default, one primary domain is added to an organization when the tenant is created. This is usually the email domain of the admin user. Only admins can add, remove, or update a primary domain.

### Adding a New Primary Domain

Follow these steps to add a new primary domain:

1. Sign in to the FenixPyre admin dashboard at [https://admin.fenixpyre.com](https://admin.fenixpyre.com).
2. Navigate to Settings > Security > Identity & Provisioning > Domains.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-domains.png | Alt: FenixPyre Domains page overview -->

3. Under **Primary Domains**, click the **Add Domain** button.
4. Enter your domain, for example: contoso.com.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-add-domain.png | Alt: Add domain input field -->

5. Click **Add**. To cancel, click **Cancel**.
6. If successful, you will receive a success notification in the top right corner.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-success-notification.png | Alt: Success notification for domain addition -->

#### Watch Tutorial

<!-- VIDEO:   ./media/04-admin-guide/primary-domains/add-domain-tutorial.mp4 | Alt: Tutorial for adding a primary domain | Duration: 45s -->

### Deleting an Existing Primary Domain

1. Sign in to the FenixPyre admin dashboard at [https://admin.fenixpyre.com](https://admin.fenixpyre.com).
2. Go to Settings > Security > Identity & Provisioning > Domains.
3. Click the delete icon next to the domain you want to remove.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-delete-domain.png | Alt: Delete icon on domains page -->

4. In the confirmation dialog, enter **DELETE** (all uppercase) and click **Delete**. To cancel, click **Cancel**.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-confirm-delete.png | Alt: Confirmation dialog for domain deletion -->

5. If successful, you will receive a notification in the top right corner.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-deletion-notification.png | Alt: Success notification for domain deletion -->

#### Watch Tutorial

<!-- VIDEO:   ./media/04-admin-guide/primary-domains/delete-domain-tutorial.mp4 | Alt: Tutorial for deleting a primary domain | Duration: 30s -->

### What Happens if I Delete a Primary Domain?

Deleting a primary domain deactivates all users with emails associated with that domain. Deactivated users are blocked from signing in to the FenixPyre admin dashboard, user sharing portal, accessing encrypted files, or using shared links.

### Editing an Existing Primary Domain

1. Sign in to the FenixPyre admin dashboard at [https://admin.fenixpyre.com](https://admin.fenixpyre.com).
2. Go to Settings > Security > Identity & Provisioning > Domains.
3. Click the edit icon next to the domain you want to change.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-edit-domain.png | Alt: Edit icon on domains page -->

4. Edit the domain in the text box.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-editing-field.png | Alt: Editable text box for domain -->

5. Click the done icon to save. To cancel, click the cancel icon.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-save-changes.png | Alt: Save and cancel icons -->

6. In the confirmation dialog, click **Change** to confirm or **Cancel** to abort.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-confirm-edit.png | Alt: Confirmation dialog for domain edit -->

7. If successful, you will receive a success notification in the top right corner.

<!-- IMG:     ./media/04-admin-guide/primary-domains/screenshot-edit-notification.png | Alt: Success notification for domain edit -->

#### Watch Tutorial

<!-- VIDEO:   ./media/04-admin-guide/primary-domains/edit-domain-tutorial.mp4 | Alt: Tutorial for editing a primary domain | Duration: 40s -->

### What Happens if I Edit a Primary Domain?

Editing a primary domain deactivates all users with emails associated with the original domain. Deactivated users are blocked from signing in to the FenixPyre admin dashboard, user sharing portal, accessing encrypted files, or using shared links. For example, changing from contoso.com to contoso.xyz deactivates all contoso.com users.

## Next Steps / Related Topics
For more on admin tasks, see [Invite Team](/04-admin-guide/invite-team) or [Configure SSO](/03-setup-&-installation/configure-sso).