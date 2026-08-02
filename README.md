**Active Directory Home Lab**
## Overview

This repository will be used for me to document the entire process of me creating a enterprise-style Active Directory environment hosted in Microsoft Azure.

## Configuration

Cloud Provider: Microsoft Azure

Image/OS: Windows 2022 Datacenter Azure edition

Purpose: Future active directory domain controller

Access method: Accessed via bastion to safely connect to server without exposing RDP to the public.

## Deployment Steps

1. Created Azure resource group
2. Created virtual network
3. Created windows server VM
4. Created Admin Account
5. Changed network settings for Network Interface to ensure a static IP address
6. Enable Azure Bastion
7. Connected to server via Bastion
8. Installed Active Directory, DHCP, DNS, Group Policy Management, and print server
9. Promoted Server to Domain Controller and made some test users in ADUC

## Lab Exercises
1. Simulated user calling in because they forgot password to get familiar with where password reset was located within ADUC.
2. Created multiple groups simulating different branch locations and different departments within each branch.
3. Created more users and adding them to the different Organizational Groups.
4. Learned about copying user from known group when making a new user that will be in that same group. Doing this automatically assigns that user the same GPOs as copied user. This makes the process of creating a new user much faster and easier.


