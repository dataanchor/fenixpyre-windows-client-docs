# Configuring Network Shared Folders as Protected in FenixPyre

Steps to set up and manage protected network folders for secure data access.


## Why it matters
Protected folders ensure files are only accessible in secure locations, reducing data exposure risks.

### Step-by-Step Procedure

**Step 1:** Install the FenixPyre Agent on your Windows server.

**Step 2:** Right-click the folder and select **FenixPyre > FenixPyre My Data** to protect it.

<!-- IMG: ./media/04-admin-guide/protect-folder.png | Alt: Protecting a network folder -->

**Step 3:** In the Admin Dashboard, go to User Roles, edit the role, and add the folder's UNC path under Protected Folders.

<!-- IMG: ./media/04-admin-guide/add-protected-folder.png | Alt: Adding protected folders in Admin Dashboard -->

**Step 4:** Save changes.

### Next Steps / Related Topics
For user management, see [Adding a New Admin](/04-admin-guide/adding-new-admin).
