**Active Directory Home Lab**
## Overview

This repository will be used for me to document the entire process of me creating a enterprise-style Active Directory environment hosted in Microsoft Azure.

## Configuration

Cloud Provider: Microsoft Azure

Image/OS: Windows 2022 Datacenter Azure edition

Purpose: Future active directory domain controller

Access method: Accessed via bastion to safely connect to server without exposing RDP to the public.

## Lab Progress

### Infrastructure Setup

1. Created an Azure Resource Group.
2. Created an Azure Virtual Network (VNet).
3. Deployed a Windows Server 2022 Virtual Machine.
4. Created a local administrator account for the server.
5. Configured the VM's network interface with a static private IP address.
6. Enabled Azure Bastion for secure remote access.
7. Connected to the server using Azure Bastion.
8. Installed the following Windows Server roles:

   * Active Directory Domain Services (AD DS)
   * DNS Server
   * DHCP Server
   * Group Policy Management
   * Print and Document Services
9. Promoted the server to a Domain Controller.
10. Created test users and Organizational Units (OUs) in Active Directory Users and Computers (ADUC).

## Lab Exercises

1. Simulated a help desk password reset request by locating and using the password reset functionality in Active Directory Users and Computers (ADUC).
2. Created Organizational Units (OUs) to represent multiple company locations and departments.
3. Created additional user accounts and organized them into the appropriate OUs.
4. Created security groups to represent departments and assigned users to the appropriate groups.
5. Practiced copying an existing user account to quickly provision a new employee with similar account settings and group memberships.
6. Explored Active Directory object properties using the Attribute Editor.
7. Gained familiarity with the layout and day-to-day administration of Active Directory Users and Computers.


