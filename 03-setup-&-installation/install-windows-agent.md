# Installing FenixPyre Agent on Windows

Step-by-step guide for manually installing the FenixPyre desktop agent on Windows 10, 11, and Server to enhance data security.


## Why It Matters
Proper installation of the FenixPyre Agent ensures that your files are encrypted and protected on Windows systems, safeguarding sensitive data from unauthorized access.

This guide covers the manual installation of the FenixPyre desktop agent version 5.3+ on Windows 10, 11, and Server.

For instructions on installing on Windows Server 2016 and above, refer to the relevant section below.

> **Note:** Watch a demonstration video for visual guidance.
<!-- VIDEO: ./media/install-windows-agent/demo.mp4 | Alt: FenixPyre Agent installation walkthrough | Duration: 45s -->

### Installing FenixPyre 5.3+ on Windows 10 and 11

#### Prerequisites
1. Complete all items in the minimum system requirements guide.

#### Steps
1. **Download the FenixPyre installer:**
   - Go to the admin dashboard and navigate to **installers**.
   - Select the download icon for your desired FenixPyre version (this guide applies to 5.3+; for earlier versions, see the manual installation guide).
   - Extract the downloaded ZIP file to access the `FenixPyreInstaller.exe` executable.
   <!-- IMG: ./media/install-windows-agent/installer-exe.png | Alt: FenixPyreInstaller executable file -->

2. **Launch the installer:**
   - Double-click `FenixPyreInstaller.exe` to start the graphical interface.
   <!-- IMG: ./media/install-windows-agent/splash-screen.png | Alt: FenixPyre Installer splash screen -->

3. **Enter your organization ID:**
   - Type your organization ID in lowercase letters.
   <!-- IMG: ./media/install-windows-agent/enter-org-id.png | Alt: Entering organization ID in lowercase -->

4. **Monitor installation progress:**
   - The installer will show a progress bar during the process.
   <!-- IMG: ./media/install-windows-agent/install-progress.png | Alt: Installation progress bar -->

5. **Complete the installation:**
   - When finished, a prompt will appear to reboot your system. Click the reboot button to finalize the setup. **Rebooting is required for FenixPyre to work properly.**
   <!-- IMG: ./media/install-windows-agent/reboot-prompt.png | Alt: Reboot confirmation screen -->

6. **Sign in:**
   - Sign in to the FenixPyre agent after reboot.

### Installing FenixPyre 5.3+ on Windows Server

#### Steps
1. **Prepare the environment:**
   - Ensure all minimum system requirements are met.

2. **Download the installer:**
   - Go to the admin dashboard and click **installers**.
   - Download the ZIP for your desired FenixPyre version and extract `FenixPyreInstaller.exe`.

3. **Run the installer via command line:**
   - Open Command Prompt or PowerShell with administrator privileges.
   - Navigate to the folder containing `FenixPyreInstaller.exe`.
   - Execute the command: `FenixPyreInstaller.exe --org-id <org-id> --skip-os-check`.

4. **Reboot:**
   - Reboot the computer to complete the installation.

5. **Sign in:**
   - Sign in to the FenixPyre agent.

## Next Steps / Related Topics
For more details, see [prerequisites](prerequisites.md) or explore [FenixPyre Cloud](create-tenant.md).