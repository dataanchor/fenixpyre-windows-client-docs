# FenixPyre Integration with Egnyte

How FenixPyre enforces access policies for Egnyte-stored encrypted content to maintain data security.


Why it matters: This integration ensures consistent policy enforcement on Egnyte, protecting sensitive data through defined user roles and access controls.

### Policy Enforcement
FenixPyre enforces dashboard-defined policies on Egnyte, requiring valid sessions and user permissions for actions like encrypting or sharing files.

- Valid users can access files in protected folders like `\\\\egnytedrive\\fenixpyre\\shared\\documents`.
- Manage users and folders via the dashboard.
- External sharing bypasses roles for third-party access.

### Common Errors
- Access denied for non-protected folders.
- Permission errors for unauthorized actions.
- Issues with unauthorized extensions or disabled users.

Next Steps / Related Topics: For setup, see [03-setup-&-installation/index.md].