# Automatic File Locking and Unlocking

Understand how FenixPyre automates file locking for Office files to prevent conflicts and ensure data integrity.


# Why it matters

Automatic file locking ensures that only one user can edit an encrypted Office file at a time, preventing data conflicts and maintaining security during collaboration.

## How It Works

FenixPyre locks files when opened from OneDrive or SharePoint, making them read-only for others, and unlocks them upon closing.

### Benefits

- **Preventing Data Leaks:** Avoids conflicts in hybrid environments by controlling access.
- **Enhancing User Experience:** Streamlines workflows and ensures data integrity with clear notifications.

### Limitations

- Applies only to Word, Excel, and PowerPoint files.
- Works for files synced from OneDrive/SharePoint and encrypted with FenixPyre.
- Requires OneDrive collaboration to be disabled in the admin dashboard.

### Frequently Asked Questions

- **Can multiple users edit simultaneously?** No; files lock to one user to avoid conflicts.
- **How to check if a file is locked?** Look for lock indicators in the interface or notifications when opening.
- **Why is a file read-only?** It may be locked by another user; wait for unlocking to edit.

## Next Steps / Related Topics

Learn more about key management in [Key Management](../02-core-concepts/key-mgmt.md).