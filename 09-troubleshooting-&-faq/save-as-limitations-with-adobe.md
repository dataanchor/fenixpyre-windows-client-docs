# Save-As Limitations with Adobe Applications

Learn about potential issues when using Save-As in Adobe apps with FenixPyre and how to mitigate them.


## Why it matters
This limitation could lead to unprotected files, so understanding mitigations helps maintain encryption integrity in shared environments.

### Known Issue and Mitigations
Files saved via Save-As in Adobe Acrobat may lose encryption when overwriting in protected folders.

1. **Local Folders:** Rely on FenixPyre scanner to encrypt after saving.
2. **Network Share:** Install FenixPyre server agent for automatic encryption.

> **Note:** For OneDrive or Egnyte, enable auto-encryption on the web interface.

### Next Steps / Related Topics
Refer to [encryption-model.md](../02-core-concepts/encryption-model.md) for details. See [troubleshooting-common-issues.md](./troubleshooting-common-issues.md) for more.