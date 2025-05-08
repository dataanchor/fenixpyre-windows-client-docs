# Getting Started with Okta SSO

Guide for admins to set up Single Sign-On (SSO) with Okta for secure access to FenixPyre.


## Why it Matters
Configuring Okta SSO streamlines user authentication, enhancing security and reducing the risk of credential-based attacks in FenixPyre environments.

### Steps to Set Up Okta SSO
1. **Prerequisites:** Ensure your primary email domain is added in FenixPyre settings.

2. **Sign in to Okta:** Go to your Okta admin portal and navigate to the Applications tab.

3. **Create App Integration:** Select SAML 2.0 and follow the setup wizard.

   <!-- IMG: ./media/configure-okta-sso/okta-setup.png | Alt: Okta SAML integration creation -->

4. **Gather FenixPyre Details:** From the FenixPyre Admin Dashboard, copy the Single Sign-On URL and Audience Restriction.

5. **Configure Attributes:** Add required attribute and group statements in Okta.

6. **Finish and Assign Users:** Complete the setup and assign users to the app.

   <!-- VIDEO: ./media/configure-okta-sso/sso-walkthrough.mp4 | Alt: Okta SSO setup walkthrough | Duration: 3m -->

> **Warning:** Verify user assignments to avoid access issues.

Next Steps / Related Topics: After setup, refer to [Inviting Your Team](/setup-and-installation/invite-team).