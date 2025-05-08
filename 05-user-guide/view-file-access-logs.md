# View File Access Logs in OneDrive/SharePoint

Learn how to view access logs for encrypted files to monitor user activity and ensure data security.


## Why it Matters
Viewing file access logs helps maintain compliance and detect unauthorized access to encrypted files, ensuring your organization's data remains secure.

### Prerequisites
Before viewing file access logs, ensure the user has a valid FenixPyre account in the Admin Dashboard. Users can be added to a user role, and their email domain must be verified. For more on adding users, see the [related guide](#).

### Step-by-Step Guide

#### Step 1: Access the File
Right-click the desired encrypted file in OneDrive or SharePoint and select **FenixPyre > Show File Access Logs**.

<!-- IMG:     ./media/05-user-guide/screenshot-access-logs.png | Alt: Right-click menu showing FenixPyre options -->

#### Step 2: View the Logs
A new browser tab will open displaying the file's access logs. Note that locations are based on the user's public IP address. Users must be logged into FenixPyre to access this; if not, they will be redirected to log in.

<!-- IMG:     ./media/05-user-guide/screenshot-logs-view.png | Alt: Browser view of file access logs -->

> **Warning:** Access logs provide approximate locations and should not be used as precise tracking.

### Next Steps / Related Topics
For more on managing user roles, check the [Admin Guide](/04-admin-guide/index.md). Learn about [logging into FenixPyre](/05-user-guide/how-to-login.md) for full access.
