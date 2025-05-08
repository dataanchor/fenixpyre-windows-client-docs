
## Why It Matters
Integrating FenixPyre with tools like GIT ensures that sensitive code and files are encrypted, protecting intellectual property during development and collaboration.

This article outlines the process to enable FenixPyre for GIT, Matlab, and Visual Studio.

### Steps
1. **Install the FenixPyre Agent:**
   - Run the installation command in admin mode: `FenixPyreSetup_v4.0.0.exe --install --org-id <ORGANIZATION ID> --disable-update-header --enable-key-local-db --skip-os-check --disable-ignore-extensions`.

2. **Add Protected Folders:**
   - Add folders via the Admin Dashboard or manually by right-clicking and selecting **FenixPyre > Encrypt My Data > Add Protection**.

3. **Add Approved Applications:**
   - In the Admin Dashboard, add executable paths for GIT, Matlab, and Visual Studio as approved applications.
   - For GIT: Add paths like C:\Program Files\Git\bin\git.exe.
   - For Matlab: C:\Program Files\MATLAB\R2022a\matlab.exe.
   - For Visual Studio: C:\Users\<USER PROFILE>\AppData\Local\Programs\Microsoft VS Code\code.exe.

4. **Perform Operations:**
   - Run a GIT operation, like cloning, into a protected folder to encrypt files automatically.
   <!-- IMG: ./media/features/git-clone-success.png | Alt: Successful GIT clone operation -->

> **Tip:** GIT operations may take longer due to encryption; monitor with `git status`.

## Next Steps / Related Topics
Check out [FenixPyre features](07-features/index.md) or [troubleshooting](09-troubleshooting-&-faq/index.md).