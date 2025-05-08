
## Why it matters
Enforcing encryption outside protected folders prevents data leaks by ensuring files from specific processes are always secured, regardless of location.

### Enforce FenixPyre Encryption
This feature automatically encrypts files created by protected processes, even if they're not in a protected folder.

- **When Enabled:** Files from processes like AxP are encrypted everywhere except ignored folders. Access is only granted in protected folders.

> **Warning:** Moving files outside protected folders may block access until they're returned.

- **When Disabled:** Files created outside protected folders won't be encrypted, risking security bypass.

> **Tip:** Use this cautiously to maintain strong access controls.

## Next Steps / Related Topics
Explore [key management](../02-core-concepts/key-mgmt.md) or [setup prerequisites](../03-setup-&-installation/prerequisites.md).
