# Auto-Encryption Feature

Overview of FenixPyre's auto-encryption for OneDrive and SharePoint, including setup and management.


# Auto-Encryption Feature

**Why it matters:** Auto-encryption automates file protection in shared environments, ensuring all data is secured without user intervention and adapting to real-time changes.

### Overview
Auto-encryption in OneDrive/SharePoint automatically encrypts files in designated folders or sites. Once enabled, it scans, encrypts, and monitors files for ongoing security.

### Pre-requisites
- Only admins can enable this feature.
- For folders over 100,000 files, check storage capacity and wait 24 hours for new datasets.
- Contact support for folders exceeding 500,000 files.

### Process Details
Enabling auto-encryption scans and encrypts all files, storing encrypted versions. Track progress in the Admin Dashboard under the OneDrive section.

### How to Enable Auto-Encryption
1. Right-click the folder and select "Add to Auto-Encryption" via your organization name.

<!-- IMG: ./media/07-features/auto-encryption/image.png | Alt: Right-click menu for auto-encryption -->

2. A browser window opens for confirmation; ensure you're logged in.

<!-- IMG: ./media/07-features/auto-encryption/screenshot.png | Alt: Auto-encryption confirmation window -->

### Managing Auto-Encryption
#### Enabling from Dashboard
1. Log in and go to **Integrations > SharePoint > Auto-Encryption**.
2. Click the action button to enable.

<!-- IMG: ./media/07-features/auto-encryption/enable-dashboard.png | Alt: Dashboard enable button -->

#### Disabling from Dashboard
1. Follow the same path and click to disable; confirm the action.

<!-- IMG: ./media/07-features/auto-encryption/disable-dashboard.png | Alt: Dashboard disable warning -->

### FAQ
- **Encrypt entire OneDrive?** Contact support.
- **Decrypt files?** Reach out to support.
- **Scanning status?** Indicates initial file processing.
- **Monitoring status?** Actively encrypts new files.
- **Disabling effects?** Stops processes but doesn't decrypt; re-enable to resume.

**Known Limitations:** Files over 300MB may not encrypt reliably; contact support for assistance.

## Next Steps / Related Topics
Explore [managing folders](../07-features/manage-auto-encryption-folders.md) or visit the [admin guide](../04-admin-guide/index.md).