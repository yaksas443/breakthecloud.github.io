---
layout: default
title: Notes
nav_order: 2
description: Notes from my research in cloud security  

permalink: /notes
---
# Azure

## Targets
- Azure Files support the use of only one account for accessing the SMB share, the storage account. The password for the share is the account's primary key.
- VM and Azure App credentials are often stored in Deployment Templates. Checking deployment history may reveal some interesting information.
- If a certificate stored in Azure Key Vault doesn’t have an export policy, it defaults to exportable. 
- Permissions to Azure Key Vaults are assigned at the vault level and not to individual secrets. So if you have access to a vault, you have access to all secrets within it.
- Azure AD Connect creates a synchronisation account to sync on-Prem AD password hashes to Azure AD. This account has replication privileges on the domain. Compromising this account will give the attacker the ability to perform DC Sync attack.
- While hunting for #Azure Storage account keys in configuration files, search for variable names such as StorageAccountKey, StorageServiceKeys or StorageConnectionString.

## Attacks
- An indirect way to compromise Azure VMs is to download the VHD and analyse the disk for stored credentials. This assumes that you have access to the storage account key linked with the VM and VHD is not encrypted.

## Lateral Movement
- A VM hosting a service that connects to an on-premise server, such as a cloud hosted website talking to an on-premise SQL server, can be used to move laterally from cloud to on-prem.
- In Azure, private peering is bidirectional. So access to an Azure VM, using Azure ExpressRoute VPN service, could provide access to on-premises enterprise network. It works the other way round as well, providing lateral movement from on-premise to cloud. 
- Azure hybrid workers enable automation on on-premise systems. It requires a hybrid worker agent to be installed on the system. This agent runs with SYSTEM privileges and executes all tasks with SYSTEM account privileges.

## Persistence
- Azure Automation can help in establishing long term (long-haul) persistence in the target Azure environment. It can also be used to create (short-haul) persistence channels.
