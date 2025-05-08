
## Why it matters
Restarting OneDrive is essential for applying FenixPyre encryption settings changes, ensuring secure and seamless file collaboration without delays.

If the OneDrive file collaboration setting is toggled from the FenixPyre admin dashboard, a restart of OneDrive is required for the change to take effect. Users will receive a notification via a toast message indicating the need to restart OneDrive.

<!-- IMG:     ./media/05-user-guide/restart-onedrive/screenshot.png | Alt: Toast notification for restarting OneDrive -->

When the user clicks the 'Restart OneDrive' button on the toast notification, FenixPyre will restart OneDrive if it's running, or start it if it's not.

After a restart, OneDrive will automatically display its root folder. This is a standard OneDrive behavior and is not controlled by FenixPyre.

> **Note:** If the toast notification expires or is closed, FenixPyre will track the need for a restart. The next time a user attempts to open an Office file from OneDrive or SharePoint, FenixPyre will check and prompt for a restart if necessary.

### Next Steps / Related Topics
For more details on FenixPyre file collaboration, see [File Collaboration in FenixPyre](../file-collaboration.md).