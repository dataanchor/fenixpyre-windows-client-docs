
## Why it matters
Automatic account creation simplifies user access via SAML SSO, reducing administrative overhead while maintaining security.

### Just-in-Time (JIT) Provisioning
FenixPyre supports JIT provisioning for SAML SSO, allowing users to join automatically.

To enable:
1. Go to **Settings > Security > Identity & Provisioning > SAML SSO**.
2. Ensure Automatic account creation is enabled.

<!-- VIDEO: ./media/04-admin-guide/jit-provisioning.mp4 | Alt: Video walkthrough of enabling JIT provisioning | Duration: 45s -->

> **Warning:** Do not enable if using SCIM; use allowed email domains instead. JIT is unavailable for OTP or username-password auth.

## Next Steps / Related Topics
Continue with [Authorized Applications](/04-admin-guide/authorized-applications) or [Setup Prerequisites](/03-setup-&-installation/prerequisites).