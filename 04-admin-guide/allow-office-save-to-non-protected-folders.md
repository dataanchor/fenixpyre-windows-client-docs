# Allow Office Applications to Save Files to Non-Protected Folders

Configure FenixPyre to enable Office applications and Adobe Acrobat to save files to non-protected folders for seamless workflow integration.


## Why it matters
Enabling this feature ensures that users can work efficiently with Office applications and Adobe Acrobat while maintaining data security, preventing accidental restrictions on file saving.

### Enabling the Feature
Follow these steps to configure the setting in the FenixPyre admin dashboard:

1. Ensure all relevant applications are added as Protect by Process (PxP) applications. This is essential for the feature to function correctly.
2. In the FenixPyre admin dashboard, navigate to **Settings > User Roles**.
3. For the desired user role, click the three vertical dots under **Actions** and select **Edit**.

<!-- IMG:     ./media/04-admin-guide/user-roles-screenshot.png | Alt: User roles interface in FenixPyre admin dashboard -->

4. Expand the **MS Office Add-In Settings** section.
5. Scroll to the **Save as** setting and toggle it on to allow saving to non-protected folders.

<!-- IMG:     ./media/04-admin-guide/save-as-setting.png | Alt: Save as toggle in MS Office settings -->

> **Warning:** Only enable this after configuring PxP applications to avoid security gaps.

### Next Steps / Related Topics
For more on user roles, see [configure-sso.md](../03-setup-&-installation/configure-sso.md). To learn about protected folders, check [protected-folders.md](./protected-folders.md).