
## Why it matters
FenixPyre Compliance Mode ensures consistent encryption policies for sensitive data, helping organizations meet CMMC guidelines and protect against unauthorized access.

FenixPyre Compliance Mode enables administrators to enforce encryption policies for specific users and applications, safeguarding data in line with CMMC standards. This mode automatically encrypts files opened and saved by designated applications, providing robust control over data management.

### Enabling Compliance Mode for an Application

Administrators can enable Compliance Mode by adding an application as a Protect By Process (PxP) application and selecting the Compliance Mode option in user role configurations. For more details on Protect By Process, refer to the relevant documentation.

<!-- IMG:     ./media/07-features/compliance-mode/screenshot.png | Alt: Compliance Mode configuration interface -->

**When Compliance Mode is Enabled:**  
All files, whether encrypted or not, opened by designated applications will be automatically encrypted upon saving, regardless of the folder location, ensuring adherence to CMMC guidelines.

**When Compliance Mode is Disabled:**  
Designated applications cannot open encrypted files from any folder, though unencrypted files remain accessible without automatic encryption.

### Windows Endpoint Settings
After an administrator enables Compliance Mode for specific Protect By Process collections in the Admin Dashboard, assigned users can toggle it via the FenixPyre system tray application.

<!-- IMG:     ./media/07-features/compliance-mode/agent-screenshot.png | Alt: FenixPyre system tray options -->

### FAQs

Q1: Who can enable or disable FenixPyre Compliance Mode?  
A: Admins enable it via the Admin Dashboard for user roles; assigned users can then toggle it on their endpoints.

Q2: What happens if Compliance Mode is disabled and a user tries to open an encrypted file?  
A: Access is denied for PxP applications, protecting sensitive data, though files can be opened via approved applications in protected folders.

Q3: Does this mode encrypt all file types?  
A: Yes, it applies to all files handled by specified applications.

Q4: Can unencrypted files be accessed when Compliance Mode is enabled?  
A: Yes, but they will be encrypted automatically after editing and saving.

## Next Steps / Related Topics  
For more on encryption features, see [Protect By Process in 07-features/protect-by-process.md].
