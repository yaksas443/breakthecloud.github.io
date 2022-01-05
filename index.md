---
layout: default
title: Home
nav_order: 1
description: Resources to attack and defend cloud environments. 

permalink: /
---
# Introduction

Welcome to Break The Cloud.

Here you will find resources (books, articles, tools, commands, attacks, defenses etc.) to protect cloud environments. This website is a work in progress so keep checking in every now and then. To contribute please send a direct message via twitter to [@yaksas443](https://twitter.com/yaksas443) 

## Cloud Security Standards and Frameworks
- [CSA Cloud Controls Matrix (CCM)](https://cloudsecurityalliance.org/research/cloud-controls-matrix/)
- [OWASP Cloud Top 10 2017](https://web.archive.org/web/20170903023808/https://www.owasp.org/index.php/Category:OWASP_Cloud_%E2%80%90_10_Project)
- [OWASP Cloud Native Security Top 10](https://owasp.org/www-project-cloud-native-application-security-top-10/)
- [ISO/IEC 27017:2015](https://infostore.saiglobal.com/en-au/Standards/ISO-IEC-27017-2015-605835_SAIG_ISO_ISO_1388396/)

## Books

### General cloud security

- [Practical Cloud Security by Chris Dotson](https://www.oreilly.com/library/view/practical-cloud-security/9781492037507/)
- [Enterprise Cloud Security and Governance by Zeal Vora](https://www.packtpub.com/product/enterprise-cloud-security-and-governance/9781788299558)
- [Cloud Native Security by Chris Binnie, Rory McCune](https://www.oreilly.com/library/view/cloud-native-security/9781119782230/)
- [Cloud Security Automation by Prashant Priyam](https://www.packtpub.com/product/cloud-security-automation/9781788627863)
- [CCSP Certified Cloud Security Professional All-in-One Exam Guide by Daniel Carter](https://www.oreilly.com/library/view/ccsp-certified-cloud/9781260456936/)
- [CCSK Certificate of Cloud Security Knowledge All-in-One Exam Guide by Graham Thompson ](https://www.oreilly.com/library/view/ccsk-certificate-of/9781260460094/)

### Azure security

- [Penetration Testing Azure for Ethical Hackers](https://www.packtpub.com/product/penetration-testing-azure-for-ethical-hackers/9781839212932) - [Book Review](https://yaksas.in/ycscblog/book-review-penetration-testing-azure-for-ethical-hackers/)
- [Pentesting Azure Applications by Matt Burrough](https://nostarch.com/azure) - [Book Review](https://yaksas.in/ycscblog/book-review-pentesting-azure-applications/)

### AWS Security

- [Hands-On AWS Penetration Testing with Kali Linux by Karl Gilbert, Benjamin Caudill](https://www.oreilly.com/library/view/hands-on-aws-penetration/9781789136722/)
- [AWS Penetration Testing by Jonathan Helmus](https://www.packtpub.com/product/aws-penetration-testing/9781839216923)

## Trainings

### Azure
- [Introduction to Azure Penetration Testing](https://azure.enterprisesecurity.io/) - Free (Registration required)

## Articles

### Azure
- [Azure AD introduction for red teamers](https://www.synacktiv.com/en/publications/azure-ad-introduction-for-red-teamers.html) - Exploiting PHS
- [Azure AD Connect for Red Teamers](https://blog.xpnsec.com/azuread-connect-for-redteam/) - Exploiting PHS and PTA
- [Azure AD Pass The Certificate](https://medium.com/@mor2464/azure-ad-pass-the-certificate-d0c5de624597) - Exploiting Azure P2P Certificates
- [Detecting privilege escalation with Azure AD service principals in Microsoft Sentinel](https://learnsentinel.blog/2022/01/04/azuread-privesc-sentinel/) - Talks about Azure Service principals privilege escalation techniques and defenses.
- [Lateral Movement with Managed Identities of Azure Virtual Machines](https://m365internals.com/2021/11/30/lateral-movement-with-managed-identities-of-azure-virtual-machines/) - Azure Managed Identities deep-dive and lateral movement to Key Vaults, Storage accounts and Azure VMs
- [What I have learned from doing a year of Cloud Forensics in Azure AD](https://m365internals.com/2021/07/13/what-ive-learned-from-doing-a-year-of-cloud-forensics-in-azure-ad/) - Threat hunting in Azure and Microsoft 365
- [Exfiltrating data by transfering it to the cloud with Azcopy](https://m365internals.com/2021/06/11/exfiltrating-data-by-transfering-it-to-the-cloud-with-azcopy/) - Using Azure Storage accounts for data exfiltration

## Blogs

### Azure
- [M365 Internals](https://m365internals.com/)

## Tools

### Multi-cloud

#### Information Gathering
- [CloudBrute](https://github.com/0xsha/CloudBrute)
- [cloud_enum](https://github.com/initstring/cloud_enum)

### Azure

#### Information Gathering
- [o365Creeper](https://github.com/LMGsec/o365creeper)
- [Blob Hunter](https://github.com/cyberark/blobhunter)
- [Get-MsolRolesAndMembers.ps1](https://gist.github.com/ciphertxt/2036e614edf4bf920796059017fbbc3d)
- [AzureHound](https://bloodhound.readthedocs.io/en/latest/data-collection/azurehound.html)
- [o365Recon](https://github.com/nyxgeek/o365recon)
- [CrowdStrike Reporting Tool for Azure](https://github.com/CrowdStrike/CRT)
- [MFASweep](https://github.com/dafthack/MFASweep)
- [Storm Spotter](https://github.com/Azure/Stormspotter)

#### Enumeration and Exploitation
- [Azure PowerShell Module](https://docs.microsoft.com/en-us/powershell/azure/install-az-ps?view=azps-7.0.0)
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- [Azure Active Directory Module](https://www.powershellgallery.com/packages/AzureAD/2.0.2.140)
- [Microburst](https://github.com/NetSPI/MicroBurst)
- [ROADTools](https://github.com/dirkjanm/ROADtools)
- [PowerZure](https://github.com/hausec/PowerZure)

#### Credential Attacks
- [MSOLSpray](https://github.com/dafthack/MSOLSpray)
- [o365Spray](https://github.com/0xZDH/o365spray)

## Other Resources
- [Awesome Azure Penetration Testing](https://github.com/Kyuu-Ji/Awesome-Azure-Pentest#lists-and-cheat-sheets)
