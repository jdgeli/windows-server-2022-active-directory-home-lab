# File Services

## Objective

Configure File Services to provide centralized storage with appropriate Share and NTFS permissions for domain users.

## Environment

- Windows Server 2022
- File and Storage Services
- Active Directory Domain Environment

## Shared Folder Structure

```
D:\Shares

├── IT
├── Accounting
├── HR
└── Agents
```

## Steps

1. Install the File Server role.
2. Create departmental folders.
3. Enable folder sharing.
4. Configure Share Permissions.
5. Configure NTFS Permissions.
6. Assign access based on Active Directory security groups.
7. Test access using domain user accounts.

## Sample Permissions

| Department | Permission |
|------------|------------|
| IT | Full Control |
| HR | Modify |
| Accounting | Modify |
| Agents | Read |
| Domain Users | Read |

## Skills Demonstrated

- File Server Administration
- NTFS Permissions
- Share Permissions
- Access Control
- Windows Server Management

## Result

Successfully deployed a centralized file sharing solution with department-based access control using Share and NTFS permissions.
