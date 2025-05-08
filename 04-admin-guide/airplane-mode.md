# Airplane Mode for Offline Access

Enable offline access to encrypted files in FenixPyre while maintaining control, including time-limited access for authorized users.


## Why it Matters
Airplane mode allows secure offline work with encrypted files, ensuring organizational control and protection even without internet connectivity.

FenixPyre requires an internet connection for access to encrypted files, but Airplane mode enables offline access for specified users with a configurable time limit up to 90 days.

### Enabling or Disabling Airplane Mode

**Step 1:**
1. In the FenixPyre Admin Dashboard, go to **Settings > User Roles**.
2. Under **Actions**, click the three vertical dots and select **View**.

<!-- IMG: ./media/04-admin-guide/user-roles-view.png | Alt: FenixPyre Admin Dashboard User Roles section -->

**Step 2:**
1. Click **General Settings**, then expand **User Component Settings**.
2. Toggle **Enable Airplane Mode** on or off.
3. Set the duration in days for offline access.

<!-- IMG: ./media/04-admin-guide/airplane-mode-settings.png | Alt: FenixPyre Airplane Mode configuration options -->

### File Access Logs in Offline Mode
FenixPyre logs file actions during offline mode and uploads them once online. Key logs include:
- ADD-OFFLINE: Marking a folder for offline use.
- REMOVE-OFFLINE: Removing a folder from offline use.
- GO-OFFLINE: Entering offline mode.
- GO-ONLINE: Returning to online mode.
- OFFLINE_ENCRYPT: Encrypting a new file offline.
- OFFLINE_OPEN: Opening an encrypted file offline.
- OFFLINE_EDIT: Editing an encrypted file offline.
- OFFLINE_DENY: Denying access to an encrypted file offline.
- OFFLINE_REVOKE: Revoking access when offline time expires.

> **Warning:** Users receive a notification if offline access expires while files are open or accessed.

<!-- IMG: ./media/04-admin-guide/offline-notification.png | Alt: Example of offline mode expiration notification -->

### Next Steps / Related Topics
Explore more user role settings in [User Roles Management](/04-admin-guide/user-roles.md).