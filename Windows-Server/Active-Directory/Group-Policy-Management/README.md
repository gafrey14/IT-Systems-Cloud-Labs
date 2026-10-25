# Group Policy Management — Restricting Control Panel Access

## Objective
Create and configure a Group Policy Object (GPO) in an Active Directory lab to restrict users' access to Windows Control Panel, link the GPO to the Amsterdam organizational unit (OU), and verify the restriction.

## Lab environment
- **Platform:** Windows Server / Active Directory Domain Services (AD DS), VMware
- **Domain:** `firstlab.local`
- **Target OU:** `Europe > Amsterdam`
- **Tool:** Group Policy Management Console (GPMC)

## Procedure and screenshot evidence

### 1. Create the Group Policy Object
Opened **Group Policy Management** and created a new GPO for restricting access to Control Panel.

![Creating the Group Policy Object](screenshots/Creating%20the%20policy.png)

### 2. Enable the Control Panel restriction
In the Group Policy Management Editor, navigated to **User Configuration > Policies > Administrative Templates > Control Panel** and enabled **Prohibit access to Control Panel and PC settings**.

![Enabling the Control Panel restriction policy](screenshots/Enabling%20the%20policy.png)

### 3. Link the GPO to the Amsterdam OU
Linked the configured GPO to the **Amsterdam** organizational unit within **Europe**.

![Linking the Group Policy Object](screenshots/Linking%20the%20policy.png)

### 4. Verify restricted access
Tested access to Control Panel and observed that access was denied, confirming the restriction was applied in the lab.

![Denied access to Control Panel](screenshots/Denied%20Access%20to%20control%20panel.png)

## Results
Created, configured, linked, and tested a user-based Group Policy Object that restricts access to Windows Control Panel. The screenshots above document each stage of the exercise.

## Skills demonstrated
- Group Policy Object (GPO) creation and configuration
- Linking a GPO to an organizational unit
- Centralized user configuration and access restrictions
- Verifying policy behavior in an Active Directory lab


