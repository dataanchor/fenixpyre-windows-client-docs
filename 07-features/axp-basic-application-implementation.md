# FenixPyre by Process: Basic Application Implementation

Learn how to implement FenixPyre by Process for securing files created by specific applications, ensuring encrypted protection for sensitive data.


Why it matters: Implementing FenixPyre by Process ensures that files created by designated applications are automatically encrypted, enhancing data security without disrupting workflows.

### Steps to Add Basic Applications for FenixPyre by Process

Follow these steps to add basic applications as protected by FenixPyre through process applications:

1. Navigate to **Settings > User Roles > FenixPyre by Process > Collections**.
2. To add a new process or collection, select **Add New**.
3. Configure the collection as needed and select **Add New Process**.
   - **Enforce Encrypting Outside Protected Folders**: Enable this option to automatically encrypt anything created by the processes in your collection, even if it's in a non-protected folder.

### Process Selection Type

4. Select the **Process Selection Type**:
   - **By Name**: Add the executable name in Process Paths. Anything created by the specified processes will be automatically encrypted.
     - **Note**: Admins can only add one process path at a time.
     - Examples:
       - To encrypt files from Notepad++: Add `C:\Program Files\Notepad++\notepad++.exe` in Process Path.
       - To encrypt files from Windows Media Player: Add `C:\Program Files (x86)\Windows Media Player\wmplayer.exe` in Process Path.
       - To encrypt files from Paint: Add `C:\Windows\System32\mspaint.exe` in Process Path.
       - To encrypt files from WordPad: Add `C:\Program Files\Windows NT\Accessories\wordpad.exe` in Process Path.

### FenixPyre by Process Mode

5. Select **FenixPyre by Process Mode**:
   - **Protect**: Encrypts only files created, saved, or exported by these processes that end with specified extensions.
   - **Ignore**: Encrypts all files created, saved, or exported by these processes except those ending with specified extensions.

### Adding Extensions

6. Add extensions:
   - Type extensions to protect or ignore based on your mode. Do not include the "." (e.g., txt).
   - For multiple extensions: Use format like `txt, docx, rtf, xlsx`.
   - For files without extensions: Use a period, e.g., `txt, docx, ., xlsx`.
   - **Note**: If ignored extensions are in authorized extensions, FenixPyre will encrypt them in protected folders.

Next Steps / Related Topics: For more on user roles, see [04-admin-guide/user-roles.md].