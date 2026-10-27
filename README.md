Joe's IT Portfolio and Engineering Lab

## Feature Project: Active Directory Enterprise Engineering Lab
*October 2026*

### Project Executive Summary
Simulation of real-world corporate environment, engineered isolated virtual network test lab from scratch using Oracle VirtualBox. Mapped out secure departmental identity directory, automated employee provisioning via scripting, successfully executed emergency disaster recovery protocols.

### Technical Environment Topology
**Hypervisor:** Oracle VM VirtualBox (Isolated Internal Network)
**Domain Controller:** Windows Server 2022 (Static IP: 192.168.10.10)
**Workstation Client:** Windows 11 Enterprise (Static IP: 192.168.10.20)

##Lab Implementation Milestones

### 1. Active Directory Identity Design (IAM)
Built clean, logical Organizational Unit (OU) structure mirroring corporate layout (Corporate-Headquarters -> IT, HR, Finance). Bypassed generic default containers to ensure high-granularity administrative control.

### 2. Share vs. NTFS Permissions Architecture
Provisioned central network storage folder structures. Implemented strict access controls using custom Active Directory Security Groups ('SG-Finance-RW'), granting necessary data modification paths while hardening directories against unauthorized domain accounts.

### 3. Automation via Powershell scripting
Scripting of a custom Powershell program that reads employee '.csv' matrices, converts strings into unique naming formats, and builds configured active accounts across respective OUs.

### 4. Disaster Recovery & DSRM Override
Simulation of a worst-case scenario involving a domain lockout. Utilized Directory Services Restore Mode (DSRM) safe-boot flags and command-line diagnostics to safely interface with offline Windows SAM registry, bypassing credential locks to securely reset global domain controller administrative profile.

---
### Technical Certifications
**Google IT Support Certification (Coursera) - COMPLETE**
**Google Cybersecurity Certification (Coursera) - COMPLETE**

feat: add initial portfolio profile and ad lab Writeup
