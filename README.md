# IT-Systems-Cloud-Labs

Hands-on labs and documentation from my IT Systems engineering and cloud administration studies.

## Active Directory and Windows Server Administration Lab

**Environment:** VMware, Windows Server, Active Directory Domain Services (AD DS), DNS, Windows client, PowerShell.

**Lab domain:** `firstlab.local`

### Lab activities

- Installed AD DS and promoted a Windows Server to a domain controller.
- Configured DNS and joined a Windows client to the domain.
- Organized domain resources into a Europe OU with city OUs, including Amsterdam, Brussels, Antwerp, and Rome.
- Created user accounts and security groups, and practiced delegation of administrative permissions.
- Practiced importing a CSV with PowerShell to manage bulk Active Directory user creation.

### Group Policy Management — Restricting Control Panel Access

**Objective:** Use Group Policy to centrally restrict access to Windows Control Panel for targeted domain users.

**Steps performed:**

1. Opened Group Policy Management and created a new Group Policy Object (GPO).
2. Edited the GPO under **User Configuration → Policies → Administrative Templates → Control Panel**.
3. Enabled **Prohibit access to Control Panel and PC settings**.
4. Linked the GPO to the **Amsterdam** organizational unit.
5. Tested access to Control Panel and observed the restriction in effect.

**Evidence captured during the lab:**

- Screenshot showing the Control Panel restriction policy set to **Enabled**.
- Screenshot showing the restricted access to Control Panel.

> **Screenshot upload pending:** Screenshots were captured locally but have not yet been added to this repository. Once uploaded, link the images here as evidence of configuration and testing.

**Skills demonstrated:** Group Policy Object creation and configuration, OU-level GPO linking, centralized Windows configuration, Active Directory administration, and policy validation.

### Documentation notes

This repository documents a practice lab environment, not a production deployment. Lab account passwords and other credentials should not be committed to GitHub.
