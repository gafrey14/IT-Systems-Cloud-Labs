# Group Policy Management — Restricting Control Panel Access

## Objective
Create and configure a Group Policy Object (GPO) in an Active Directory lab to restrict users' access to Windows Control Panel, link the GPO to the Amsterdam organizational unit (OU), and verify the restriction.

## Lab environment
- **Platform:** Windows Server / Active Directory Domain Services (AD DS), VMware
- **Domain:** `firstlab.local`
- **Target OU:** `Europe > Amsterdam`
- **Tool:** Group Policy Management Console (GPMC)

## Procedure
1. Opened **Group Policy Management** and created a new GPO to restrict Control Panel access.
2. Opened the Group Policy Management Editor and navigated to **User Configuration > Policies > Administrative Templates > Control Panel**.
3. Set **Prohibit access to Control Panel and PC settings** to **Enabled**.
4. Linked the GPO to the **Amsterdam** OU.
5. Tested the policy and observed that access to Control Panel was restricted.

## Results
The Control Panel restriction was configured and a screenshot was captured showing restricted access. This demonstrates creating, configuring, linking, and testing a user-based Group Policy in an Active Directory environment.

## Screenshots (pending upload)
The following screenshots were captured during the lab but have **not yet been uploaded to this repository**:

- **Policy configuration:** The Control Panel restriction setting shown as **Enabled**.
- **Restriction test:** The message or screen showing Control Panel access was restricted.

Once the screenshots are uploaded, place them in a `screenshots/` folder alongside this README and add relative Markdown image links here. A screenshot of the GPO link to Amsterdam can also be added if available.

## Skills demonstrated
- Group Policy Object (GPO) creation and configuration
- Linking a GPO to an organizational unit
- Centralized user configuration and access restrictions
- Verifying policy behavior in an Active Directory lab

> **Note:** This is a practice lab. Do not publish actual passwords or other credentials in screenshots or files.
