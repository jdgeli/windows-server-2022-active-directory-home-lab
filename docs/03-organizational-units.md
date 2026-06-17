# Organizational Units (OUs)

## Objective

Create a logical Organizational Unit (OU) structure to organize users, computers, and servers while preparing the environment for Group Policy deployment and delegated administration.

## Environment

- Domain: company.local
- Active Directory Users and Computers (ADUC)

## OU Structure

```
G6depot.local
├── G6_Depot
├── Cavite
└── Laguna
    ├── Users
    │   ├── IT
    │   ├── Accounting
    │   ├── HR
    │   ├── Agents
    │
    ├── Computers
    └── Servers

```

## Steps

1. Open **Active Directory Users and Computers**.
2. Right-click the domain.
3. Select **New > Organizational Unit**.
4. Create the following OUs:
   - G6_Depot
   - Cavite
   - Laguna
5. Inside the regional OU, create:
   - Users
   - Computers
   - Servers
6. Under Users, create department OUs:
   - IT
   - Accounting
   - HR
   - Agents
7. Create three sample users for each department.

## Benefits

- Organized Active Directory structure
- Easier Group Policy management
- Simplified administration
- Supports delegated permissions

## Result

A structured Active Directory environment was successfully created with regional and departmental Organizational Units for efficient management and policy application.
