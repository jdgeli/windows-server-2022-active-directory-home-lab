Active Directory Domain Services (AD DS)
Overview

Active Directory Domain Services (AD DS) is a Microsoft directory service that provides centralized authentication, authorization, and management of users, computers, groups, and network resources within an organization.

This lab demonstrates the deployment and basic administration of an Active Directory environment using Windows Server 2022.

Objectives
Install Active Directory Domain Services
Promote the server to a Domain Controller
Create a new Active Directory domain
Verify DNS integration
Test domain authentication
Lab Environment
Component	Configuration
Server OS	Windows Server 2022
Client OS	Windows 11 Pro
Hypervisor	VMware Workstation
Role Installed	Active Directory Domain Services (AD DS)
Implementation Steps
Step 1 - Install AD DS
Open Server Manager.
Select Add Roles and Features.
Install Active Directory Domain Services.
Wait for the installation to complete.
Step 2 - Promote Server to Domain Controller

After installing AD DS:

Click Promote this server to a domain controller
Create a new forest
Configure the domain name
Set Directory Services Restore Mode (DSRM) password
Step 3 - Restart the Server

The server automatically restarts after promotion.

Validation

The following items were verified:

Active Directory Users and Computers
DNS Manager
Group Policy Management Console
Domain Controller status
Skills Demonstrated
Windows Server Administration
Active Directory Deployment
Domain Controller Configuration
DNS Integration
Authentication Services
Result

Successfully deployed a Windows Server 2022 Domain Controller and created a fully functional Active Directory environment for user and resource management.
