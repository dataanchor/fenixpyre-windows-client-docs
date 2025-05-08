# Managing Auto-Updates in FenixPyre

Guide for FenixPyre administrators on controlling auto-updates for the agent software to ensure secure and controlled deployments.


## Why It Matters
Auto-update management allows administrators to test and deploy software updates safely, maintaining control over system integrity and minimizing disruptions.

### Auto-Update Overview
Starting with FenixPyre version 5.3.3, the FenixPyre Agent on Windows can automatically check for and apply updates.

#### Key Concepts
- Administrators must mark a new installer as default on the Installers page before it becomes available for auto-updates.
- This feature enables testing new versions before widespread rollout.

#### Installer Properties
- Only the default installer is used for auto-updates.
- FenixPyre Agents will not detect new versions until marked as default.

<!-- DIAGRAM: ./media/04-admin-guide/installers-flow.svg | Alt: Flow diagram for installer selection and updates -->

#### Examples and Behavior
In a scenario with multiple installers listed, only the default one (e.g., FenixPyre_v6.0.0) is selected for updates.

#### Installer Types
- **Minor releases:** No reboot required for updates on existing installations.
- **Major releases:** Reboot may be needed due to driver updates.

#### Downloading and Changing Defaults
To download non-default installers or change the default:
1. Click the down arrow or anywhere on the installer entry to expand details.
2. For changing defaults, click the more information icon (three dots), select "Set as default", and confirm.

<!-- GIF: ./media/04-admin-guide/change-default-installer.gif | Alt: Demonstration of changing the default installer -->

#### Additional Notes
- Only one installer can be default at a time.
- Agents ignore older default versions if already on a newer one.

## Next Steps / Related Topics
Explore [prerequisites.md] in the 03-setup-and-installation section for initial setup requirements.
