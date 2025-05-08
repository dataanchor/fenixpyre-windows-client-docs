
## Why it matters
Protecting folders in DFS ensures data security across networked environments, preventing unauthorized access via UNC or mapped drives.

### Adding Protected Folders
#### For UNC Paths
1. Log into the FenixPyre admin dashboard and go to **Settings > User Roles**.
2. Edit the desired role and add the UNC path (e.g., \\server\share\folder).

<!-- IMG:     ./media/04-admin-guide/unc-path-add.png | Alt: Adding UNC path in admin dashboard -->

#### For DFS Paths
1. Follow similar steps and enter the DFS path (e.g., \\domain\dfsroot\folder).

> **Warning:** Ensure proper permissions are set as per FenixPyre requirements.

### Next Steps / Related Topics
For more configurations, see [invite-team.md](../03-setup-&-installation/invite-team.md). Check [protected-folders.md](./protected-folders.md) for best practices.