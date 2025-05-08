# OneDrive File Collaboration with FenixPyre

How FenixPyre handles file collaboration in OneDrive, including limitations and configurations.


## Why it Matters
File collaboration in OneDrive enables real-time teamwork, but FenixPyre manages encryption to prevent data exposure during sessions.

OneDrive collaboration allows multiple users to edit files simultaneously. FenixPyre disables this by default to protect encrypted files.

**Impact on FenixPyre:** Encrypted files may decrypt temporarily during collaboration, potentially leading to issues. Admins can enable it via the dashboard.

**Known Limitations:** Users can't open encrypted files from OneDrive if collaboration is enabled.

> **Tip:** Use whitelisted apps like Excel for better compatibility.

### Next Steps / Related Topics
Enable collaboration in the [Admin Dashboard](/04-admin-guide/index.md) or review [file protection basics](/05-user-guide/add-protected-folders.md).
