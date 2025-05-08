# Install FenixPyre Agent via Command Line

Learn how to install the FenixPyre Agent using command-line options for automated deployment.


## Why it matters
Efficient command-line installation allows for seamless, unattended deployment of the FenixPyre Agent, ensuring secure encryption capabilities across environments.

### Command Line Installation Overview

There are three primary and mutually exclusive modes of operation: install, uninstall, and plugin-install for FenixPyreSetup_v4.0.0.exe. Use the following syntax: `FenixPyreSetup_v4.0.0.exe {--install --org-id <org-id> | --uninstall | --plugin-install} [options...]`

**Critical points to observe:**
- Ensure you have completed all items in the [prerequisites](/03-setup-&-installation/prerequisites).
- The parameters for these modes may not be combined.
- Specify an org-id for installations.
- If installation is unresponsive, verify the org-id is valid and not empty.
- Run commands in non-silent mode first to identify errors before using silent mode for unattended operations.
- **Note:** All parameters are case-sensitive and must be entered exactly as shown.

### Parameters

- `--org-id <org-id>`: Required for `--install`. Use only with `--install`. The org-id and domain-name are case-sensitive.
- `--silent`: Use with `--install` or `--uninstall` for no user prompts or progress bars. The system reboots automatically unless `--reboot-prompt` is specified.
- `--setup-logs <folder-path>`: Redirect logs to the specified folder. If it doesn't exist, it will be created. Default location: `C:\Users\Public\FenixPyreSetupLogs`.
- `--disable-NWShares`: Use with `--install` for environments with Distributed File Systems (DFS) on Windows servers. Disables encrypting/decrypting operations on network share folders for Windows 10 and Windows 11.
- `--reboot-prompt`: Use with `--silent` to prompt the user before rebooting.
- `--plugin-install`: Installs Microsoft Office plugins only.
- `--skip-reboot`: Prevents prompting for a system reboot after installation.
- `--help`: Displays help window; ignores other parameters.
- `--skip-os-check`: Allows installation on unsupported systems like Windows Server 2016 and above.
- `--skip-vcredist-check`: Use only with `--install`.
- `--disable-ignore-extensions`: Sets registry to exclude certain files (e.g., hex, DLL) from encryption.
- `--disable-update-header`: Disables the update header feature, recommended for OneDrive/SharePoint use.
- `--enable-key-local-db`: Enables Git support.

### Examples

**Perform regular install with reboot prompt:**
Note: Setup logs are stored in `C:\Users\Public\FenixPyreSetupLogs`.

```
FenixPyreSetup_v4.0.0.exe --install --org-id <org-id>
```

**Perform silent install:**
Note: Setup logs are stored in `C:\Users\Public\FenixPyreSetupLogs`.

```
FenixPyreSetup_v4.0.0.exe --install --org-id <org-id> --silent
```

**Perform silent install with custom logs folder:**

```
FenixPyreSetup_v4.0.0.exe --install --org-id <org-id> --silent --setup-logs "C:\\Users\\Public\\FenixPyre Setup Logs"
```

**Perform silent install and disable network share operations:**

```
FenixPyreSetup_v4.0.0.exe --install --org-id <org-id> --silent --setup-logs "C:\\Users\\Public\\FenixPyre Setup Logs" --disable-NWShares
```

**Install on Windows Server 2016 and above:**
Note: Ensure Wireless Lan service is enabled.

```
FenixPyreSetup_v4.0.0.exe --install --org-id <org-id> --skip-os-check
```

## Next Steps / Related Topics
For further configuration, see [configure-sso.md](/03-setup-&-installation/configure-sso). Explore [prerequisites.md](/03-setup-&-installation/prerequisites) if needed.
