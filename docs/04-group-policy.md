# Group Policy Management

## Objective

Configure and manage Group Policy Objects (GPOs) to centrally administer security settings, desktop configurations, and user restrictions across the Active Directory environment.

## Environment

- Windows Server 2022
- Group Policy Management Console (GPMC)
- Windows 11 Domain Client

## Implemented Group Policies

### Desktop Wallpaper

Configured a standard desktop wallpaper for domain users.

### Disable Command Prompt

Restricted access to Command Prompt for standard users.

### Password Policy

Configured:

- Password complexity enabled
- Minimum password length: 8 characters
- Maximum password age: 90 days

### Drive Mapping

Automatically mapped shared network drives for users.

Example:

```
Z: -> \\SERVER\FileShare
```

### USB Restriction

Configured removable storage policies to prevent unauthorized USB access.

### Remote Desktop Restriction

Configured User Rights Assignment to allow Remote Desktop access only to authorized administrators.

## Steps

1. Open **Group Policy Management Console (GPMC)**.
2. Create a new GPO.
3. Edit the policy settings.
4. Link the GPO to the appropriate Organizational Unit.
5. Run:

```
gpupdate /force
```

6. Verify using:

```
gpresult /r
```

## Skills Demonstrated

- Group Policy Management
- User Rights Assignment
- Security Policy Configuration
- Windows Administration

## Result

Successfully implemented multiple Group Policy Objects to standardize configuration, improve security, and simplify user administration across the domain.
