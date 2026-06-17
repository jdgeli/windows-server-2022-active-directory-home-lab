# Active Directory Domain Services (AD DS)

## Objective

Install and configure Active Directory Domain Services (AD DS) to create a centralized domain environment for managing users, computers, groups, and network resources.

## Environment

- Hypervisor: VMware Workstation
- Server OS: Windows Server 2022 Standard
- Client OS: Windows 11 Pro
- Role Installed: Active Directory Domain Services (AD DS)
- DNS: Installed Automatically

## Steps

1. Open **Server Manager**.
2. Click **Add Roles and Features**.
3. Select **Active Directory Domain Services (AD DS)**.
4. Complete the installation wizard.
5. Click **Promote this server to a domain controller**.
6. Select **Add a new forest**.
7. Enter the domain name G6depot.local.
8. Configure the Directory Services Restore Mode (DSRM) password.
9. Complete the installation and restart the server.
10. Verify the installation using:
    - Active Directory Users and Computers
    - DNS Manager
    - Group Policy Management Console

## Features Configured

- Active Directory Domain Services
- Domain Controller
- DNS Server
- Group Policy Management

## Result

The Windows Server 2022 virtual machine was successfully promoted to a Domain Controller and is now managing authentication, authorization, and directory services for the lab environment.
