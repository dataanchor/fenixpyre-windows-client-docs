
## Why it Matters
Proper configuration of timing settings ensures real-time enforcement of access rules and user roles, preventing unauthorized access to encrypted files and maintaining data security.

### Accessing Timing Settings

**Step 1:** Log in to the FenixPyre Admin Dashboard, navigate to **Settings > Global Policies > Admin Configurations**, and scroll to the "Timing Settings" section.

**Step 2:** Enter your desired time settings and click **Update**.

### Access Control Heartbeat Rate
This is the interval in seconds for checking and verifying access rules. The default is 10 seconds, meaning compliance checks occur every 10 seconds. Users retain access to encrypted files if compliant; otherwise, access is revoked, and open files are saved and closed until compliance is restored.

<!-- IMG: ./media/04-admin-guide/heartbeat-rate.png | Alt: FenixPyre Admin Dashboard showing Access Control Heartbeat Rate -->

### User Roles Update Rate
This is the interval in seconds for the endpoint agent to check the FenixPyre Cloud for user role changes. The default is 60 seconds, so wait at least 60 seconds after updating roles to test changes.

> **Note:** These settings help balance security with user productivity.

### Next Steps / Related Topics
For more on admin configurations, see [Admin Configurations Overview](/04-admin-guide/index.md).