# Default Access Rules

Understand and manage access rules in FenixPyre to control encrypted file access dynamically.


## Why it Matters
Access rules define conditions for accessing encrypted files, ensuring only authorized users comply with organizational policies.

### What Are Access Rules?
Access rules are conditions that must be met to access encrypted data. They apply dynamically to files and require the machine to be part of the data-owning organization.

All files are assigned global default access rules upon encryption.

### Editing Access Rules in the Admin Dashboard

**Step 1:** Log in to the FenixPyre Admin Dashboard.

**Step 2:** Navigate to **Settings > Global Policies > Admin Configurations**.

**Step 3:** Edit the access rules and click **Update**.

<!-- IMG: ./media/02-core-concepts/access-rules-edit.png | Alt: FenixPyre Admin Dashboard access rules section -->

### Verifying File Context
1. Right-click the file.
2. Select **FenixPyre** and choose **Show Access Rules**.
3. Verify the file's context matches the rules.

<!-- IMG: ./media/02-core-concepts/file-access-rules.png | Alt: Right-click menu showing access rules -->

> **Warning:** Ensure files are in the correct context to avoid access issues.

### Next Steps / Related Topics
For more on key management, see [Key Management](/02-core-concepts/key-mgmt.md).