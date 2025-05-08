# Getting Started as an Admin

Step-by-step guide for administrators to set up FenixPyre, including SCIM integration.


## Why it matters
Proper admin setup ensures secure user management and integration, safeguarding organizational data from the start.

### Steps for Admin Setup

1. **Sign in to FenixPyre Dashboard:** Visit [https://admin.fenixpyre.com](https://admin.fenixpyre.com).

2. **Access Security Settings:** Go to **Settings** > **Security** > **Identity & Provisioning** > **SCIM** tab.
   - <!-- IMG: ./media/04-admin-guide/scim-tab.png | Alt: SCIM settings in FenixPyre dashboard -->

3. **Set Up SCIM:** FenixPyre uses WorkOS; click **Setup SCIM** to redirect.
   - <!-- IMG: ./media/04-admin-guide/workos-setup.png | Alt: WorkOS setup page -->

4. **Select Identity Provider:** Choose **Okta** on the WorkOS page.
   - > **Note:** Do not follow outdated steps on the Configure Directory Sync page.

5. **Configure in Okta:** Sign in to your Okta admin portal and edit the SAML SSO application.
   - <!-- IMG: ./media/04-admin-guide/okta-app.png | Alt: Okta application settings -->

6. **Enable Provisioning:** In the **General** tab, edit App Settings and enable SCIM in the **Provisioning** section.
   - <!-- IMG: ./media/04-admin-guide/provisioning.png | Alt: SCIM provisioning in Okta -->

7. **Finalize Provisioning:** Go to the **Provisioning** tab in Okta.

### Next Steps / Related Topics
Once set up, review [User Management](/04-admin-guide/index.md) or [Configure SSO](/03-setup-and-installation/configure-sso.md).
