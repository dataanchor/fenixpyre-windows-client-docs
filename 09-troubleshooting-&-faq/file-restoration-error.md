# Handling File Restoration Errors in FenixPyre

Steps to resolve errors when attempting to restore non-encrypted files in FenixPyre.


## Why it Matters
Properly handling restoration errors prevents data loss and ensures seamless access to encrypted files.

### Error Notification for Non-Encrypted Files

When trying to restore a file that isn't encrypted, FenixPyre displays a notification. Files must be encrypted before restoration is possible.

1. **Identify the Error:** You may see a message indicating the file is not encrypted.
   <!-- IMG: ./media/09-troubleshooting-&-faq/restoration-error.png | Alt: Screenshot of file restoration error notification -->

2. **Encrypt the File:** Right-click the file and select **Encrypt with FenixPyre**.

> **Warning:** Only encrypt files in protected folders to avoid access issues.

Once encrypted, you can restore previous versions if changes have been made.

### Next Steps / Related Topics
Learn more about encryption in the [core concepts section](/02-core-concepts/encryption-model.md).
