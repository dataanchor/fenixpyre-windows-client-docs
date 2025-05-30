# Minimum Permissions for FenixPyre on Distributed File Systems

Required share and NTFS permissions for using FenixPyre on DFS environments.


## Why it matters
Proper permissions ensure FenixPyre can encrypt and decrypt files on distributed systems without access issues, maintaining data integrity.

### Network Share and NTFS Permissions
FenixPyre requires specific permissions for operations on shared resources.

#### Common Permissions
- **Full Control:** Allows complete access.
- **Change/Modify:** Permits modifications but not permission changes.
- **Read:** Enables viewing only.

When combining share and NTFS permissions, the most restrictive applies.

For FenixPyre:
- Grant **Full Control** on both share and NTFS for the user executing actions like encrypting or decrypting files.

> **Note:** Ensure non-admin users have at least Read & Execute on NTFS and Change on shares for UNC or DFS paths.

<!-- DIAGRAM: ./media/03-setup-&-installation/permissions-diagram.svg | Alt: Overview of required permissions for FenixPyre on DFS -->

## Next Steps / Related Topics
After setting permissions, proceed to [03-setup-&-installation/install-windows-agent.md] or troubleshoot in [09-troubleshooting-&-faq/index.md].
