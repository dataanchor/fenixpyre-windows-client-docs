
# Preserve File Properties

## Why it Matters
Preserving file timestamps and security information ensures that metadata remains accurate after encryption or decryption, maintaining integrity and avoiding issues with cloud synchronization services.

By default, FenixPyre does not preserve file timestamps when encrypting and decrypting files. When a file is encrypted or decrypted, FenixPyre updates the file's "last modified date," as well as other metadata like "last access date" and "last write date." You can override this to reflect the file's actual change history rather than the operation timestamp.

> **Warning:** FenixPyre's default configuration avoids preserving timestamps to prevent unexpected behavior in cloud storage services like OneDrive or DropBox, which use these dates for syncing. Enabling this feature could lead to sync failures; test it in your environment before widespread deployment.

In FenixPyre version 5.2.0 and later, you can configure this behavior as follows:

### Configure File Timestamps

**Step 1:** Log in to the FenixPyre Admin Dashboard and navigate to **Settings > Global Policies > Admin Configurations.**

<!-- IMG: ./media/04-admin-guide/admin-dashboard.png | Alt: FenixPyre Admin Dashboard overview -->

**Step 2:** Scroll to the **Agent File Properties** section. Toggle the switch labeled **Preserve File Timestamps** to on if you want to prevent encryption/decryption operations from changing the last modified date. Leave it off to record operations as file changes (default behavior).

<!-- IMG: ./media/04-admin-guide/global-policies.png | Alt: Global Policies in FenixPyre Admin Dashboard -->

### Preserve File Security Information

With FenixPyre version 5.2.0 and later, you can also preserve security information, such as discretionary access control lists (DACLs), after encrypting or decrypting files.

**Step 1:** Log in to the FenixPyre Admin Dashboard and go to **Settings > Global Policies > Admin Configurations.**

<!-- IMG: ./media/04-admin-guide/global-policies-security.png | Alt: Global Policies for security settings -->

**Step 2:** In the **Agent File Properties** section, toggle the switch labeled **Preserve File Security Info** to enable it.

<!-- IMG: ./media/04-admin-guide/preserve-security-info.png | Alt: Preserve File Security Info toggle -->

### Definitions

| Term            | Definition                          |
| --------------- | ----------------------------------- |
| Creation Date   | The date and time when the file was created. |
| Last Accessed Date | The date and time when the file was last accessed. |
| Last Modified Date | The date and time when the file was last modified. |
| Last Write Date | The date and time when the file was last written to (often the same as last modified date). |

## Next Steps / Related Topics
For more on configuration, see [04-admin-guide/index.md](./index.md). Or explore [02-core-concepts/key-mgmt.md](../02-core-concepts/key-mgmt.md) for key management details.
