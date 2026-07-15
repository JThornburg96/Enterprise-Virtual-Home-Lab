# Enterprise Home Lab

> A continuously evolving enterprise Windows Server home lab built to develop hands-on experience with Active Directory, Windows Server, networking, PowerShell, and hybrid Microsoft Azure infrastructure.

---

## About This Project

This repository documents the design, implementation, and expansion of an enterprise-style IT environment built using Hyper-V virtualization. The goal is to simulate a production corporate network while developing real-world systems administration and cloud administration skills.

This lab is being built alongside my Microsoft Azure Administrator (AZ-104) studies and serves as both a technical learning environment and a professional portfolio demonstrating infrastructure design, troubleshooting, automation, and documentation.

---

## Current Environment

### Infrastructure

- Hyper-V Virtualization
- Windows Server 2022 VM
- Windows 11 Pro
- pfSense Firewall VM

### Core Services Setup

- ✅ Active Directory Domain Services
- ✅ DNS
- ✅ Organizational Units
- ✅ User Management
- ✅ Internal Virtual Network

### In Progress

- 🚧 Firewall Configuration
- 🚧 Windows Client Deployment
- 🚧 Group Policy
- 🚧 File Server
- 🚧 PowerShell Automation

---

## Current Network

```
                 Internet
                     │
                Home Router
              192.168.1.0/24
                     │
────────────────────────────────────
               Hyper-V Host
                     │
              pfSense Firewall
                     │
            Enterprise LAN Network
               10.10.0.0/16
                     │
      ┌──────────────┼──────────────┐
      │              │              │
    DC01        Windows 11      Future Servers
(Domain/AD)       Client
```

---

## Technologies

### Microsoft

- Windows Server 2022
- Active Directory
- DNS
- Group Policy *(In Progress)*
- PowerShell
- Hyper-V

### Networking

- pfSense
- TCP/IP
- DNS
- Enterprise IP Addressing (10.10.10.1/16)

### Cloud

- Microsoft Azure *(Planned)*
- Microsoft Entra ID *(Planned)*
- Azure Virtual Networks *(Planned)*
- Azure VPN *(Planned)*
- Azure File Sync *(Planned)*

---

# Project Roadmap

## ✅ Phase 1 — Core Infrastructure

- Hyper-V
- Virtual Networking
- pfSense
- Windows Server
- Active Directory
- DNS
- Organizational Units
- User Accounts

## 🚧 Phase 2 — Enterprise Administration

- Domain Join Windows Clients
- Group Policy
- Security Groups
- Password Policies
- Login Scripts
- Network Drive Deployment

## ⏳ Phase 3 — Enterprise Services

- File Server
- NTFS Permissions
- DHCP
- Print Server
- Certificate Services
- WSUS

## ⏳ Phase 4 — Automation

- PowerShell User Provisioning
- Bulk User Creation (tested)
- Health Checks
- Inventory Reports

## ⏳ Phase 5 — Hybrid Azure

- Microsoft Entra ID
- Azure AD Connect
- Azure Virtual Network
- Site-to-Site VPN
- Azure File Sync
- Azure Backup

---

# Repository Documentation

Detailed documentation for each component of the lab can be found in the **docs** folder.

| Document | Description |
|----------|-------------|
| Project Overview | Goals, objectives, and lab design |
| Hyper-V | Virtualization configuration |
| pfSense | Firewall and routing configuration |
| Active Directory | Domain configuration |
| DNS | DNS design and troubleshooting |
| Group Policy | Enterprise policy management |
| File Server | Storage and NTFS permissions |
| Azure Hybrid | Azure integration |
| Troubleshooting | Problems encountered and solutions |

---

# Repository Structure

```
Enterprise-HomeLab
│
├── README.md
│
├── docs/
│
├── diagrams/
│
├── screenshots/
│
├── scripts/
│
└── assets/
```

---

# Skills Demonstrated

- Windows Server Administration
- Active Directory
- DNS Administration
- Enterprise Networking
- Hyper-V Virtualization
- Infrastructure Documentation
- PowerShell
- Troubleshooting
- Hybrid Cloud Planning
- Microsoft Azure Administration

---

# Future Goals

This environment will continue to expand to include:

- Microsoft Entra ID
- Azure Hybrid Identity
- Intune
- Microsoft Defender
- Azure Monitor
- SQL Server
- Automated Infrastructure Deployment
- Disaster Recovery
- Cloud Migration Scenarios

---

## Author

**James Thornburg**

IT Operations Professional | Systems Administration | Azure Administration | Infrastructure Engineering

This repository is actively maintained as my enterprise home lab continues to grow.
