# File Server Resource Manager (FSRM)

## Objective

Configure File Server Resource Manager (FSRM) to manage storage utilization through quotas and file screening policies.

## Environment

- Windows Server 2022
- File Server Resource Manager (FSRM)

## Features Implemented

### Quota Management

Created quota templates to limit storage usage for shared folders.

Example:

```
Quota Type: Soft Quota

Storage Limit: 1 GB

Notification Threshold: 85%
```

### File Screening

Configured file screening templates to block unwanted file types.

Blocked Extensions:

```
*.mp3
*.mp4
*.exe
*.iso
```

## Steps

1. Install File Server Resource Manager.
2. Open the FSRM console.
3. Create a Quota Template.
4. Apply the quota to a shared folder.
5. Create a File Screen Template.
6. Apply the template to selected folders.
7. Verify storage and file restrictions.

## Benefits

- Prevents excessive storage consumption
- Enforces organizational file policies
- Improves storage management
- Enhances file server security

## Skills Demonstrated

- File Server Resource Manager
- Quota Management
- File Screening
- Windows Server Administration

## Result

Successfully configured FSRM quota and file screening policies to efficiently manage file storage and enforce organizational standards.
