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



