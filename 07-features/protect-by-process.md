# Protect by Process Feature

How to configure Protect by Process in FenixPyre to automate file encryption for specific applications.


## Why it Matters
Protect by Process automates encryption for files created by designated applications, enhancing security in non-standard workflows.

### Configuring Protect by Process

Follow these steps to set up Protect by Process:

1. **Select a User Role:** In the FenixPyre Admin Dashboard, go to **Settings > User Roles** and edit the desired role.

2. **Add a New Collection:** Navigate to **Protect by Process > Collections > Add New**.
   <!-- IMG: ./media/07-features/pxp-collection.png | Alt: Adding a new Protect by Process collection -->

3. **Configure Process Rules:** Specify processes by name or folder and define file extensions to protect or ignore.

4. **Set Additional Rules:** Enable options like compliance mode or enforce protection outside protected folders.

> **Note:** After configuration, users will receive a notification when launching the application.

### Known Limitations
- Revoked access takes effect after closing the file.
- Certain extensions like .dll are not automatically encrypted.

### Next Steps / Related Topics
Explore other features in the [FenixPyre features index](/07-features/index.md).
