
## Why it Matters
Integrating Active Directory streamlines user management and authentication, enhancing security and efficiency in FenixPyre environments.

### Step-by-Step Guide
1. Download and install the latest Auth0 LDAP connector from the official site.
2. Follow the setup instructions, and obtain the TICKET URL from the FenixPyre team.
3. Enter the LDAP Connection String and Base DN (auto-filled or use `dsquery *` in Command Prompt).
4. Provide the Username (e.g., via `dsquery user -name <username>`) and Password for the admin account.
5. Save the configuration and verify by searching for a user in the Search tab.

<!-- IMG:     ./media/04-admin-guide/screenshot-ldap-setup.png | Alt: LDAP connector configuration screen -->

#### Troubleshooting
If searches fail, wait a few minutes, restart the LDAP connector services, or reboot the server.

> **Warning:** Contact support at help@fenixpyre.com if issues persist.

### Next Steps / Related Topics
Move to [user management](/04-admin-guide/index.md) or check [SSO configuration](/03-setup-&-installation/configure-sso.md).
