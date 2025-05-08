
# Handling Hybrid Block Notifications

**Why it matters:** Hybrid blocking prevents mixing of protected and plain text content, avoiding data leaks and maintaining encryption integrity during file operations.

This guide covers hybrid blocking, which ensures protected files remain secure by blocking access when non-protected content is open.

### Key Scenarios
1. **Opening a non-protected file while a protected file is open:** Protected data becomes unreadable to prevent exposure. Close the non-protected file to access protected content.
2. **Opening a protected file while a non-protected file is open:** The system blocks this to enforce security.

<!-- IMG: ./media/09-troubleshooting-&-faq/hybrid-block-notification/screenshot.jpg | Alt: Example of hybrid block notification -->

**Warning:** Always close non-protected files before working with encrypted ones to avoid disruptions.

## Next Steps / Related Topics
For more troubleshooting, see the [FAQ section](../09-troubleshooting-&-faq/index.md) or learn about [encryption best practices](../02-core-concepts/encryption-model.md).