# Enable Auto-Encryption for Folders

Learn how to set up auto-encryption for folders in FenixPyre Admin Dashboard to protect your data seamlessly.


## Why it Matters
Auto-encryption ensures that new files added to specified folders are automatically encrypted, safeguarding sensitive data without manual intervention.

### Setting Up Auto-Encryption

Follow these steps to enable auto-encryption for folders in FenixPyre.

#### Step 1: Access the Dashboard
Log in to the FenixPyre Admin Dashboard and navigate to **Integrations > Egnyte**.

<!-- IMG: ./media/04-admin-guide/enable-auto-encryption/screenshot1.png | Alt: FenixPyre dashboard showing Integrations section -->

#### Step 2: Configure Auto-Encryption
Select **Setup Auto-Encryption**. Note that this requires an Egnyte Admin account.

> **Warning:** Ensure you have the necessary permissions before proceeding.

#### Step 3: Add Folders for Auto-Encryption
Select **Add a folder for Auto-Encryption** and enter the Egnyte folder path in this format: /Shared/<folder name>/<Folder name>.

<!-- IMG: ./media/04-admin-guide/enable-auto-encryption/screenshot2.png | Alt: Add folder interface in FenixPyre -->

> **Note:** FenixPyre only encrypts new files added to the folder after setup. We recommend encrypting all existing files in the folder immediately after configuration.

### Next Steps / Related Topics
For more on managing integrations, see [Integrations in Admin Guide](/04-admin-guide/integrations-overview).