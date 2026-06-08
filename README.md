# Home SOC and Azure Security Lab

## Overview

This repository documents my home SOC and Azure security lab. The lab is designed to demonstrate practical skills in Microsoft infrastructure, Azure security, SOC operations, vulnerability management, networking, endpoint security, incident response and security testing.

The environment is built around Proxmox, OPNsense, Active Directory, Windows clients, Wazuh, Kali Linux, vulnerable targets, OpenVAS/Greenbone and Microsoft cloud security tooling such as Entra ID, Intune, Defender and Sentinel.

## Lab Goals

The purpose of this lab is to build practical, hands-on experience in:

- Proxmox virtualisation and lab infrastructure
- Network segmentation, firewalling and routing
- Active Directory, DNS, Group Policy and Windows administration
- Microsoft 365, Entra ID, Intune and Defender security concepts
- SIEM deployment, log collection and alert investigation
- Vulnerability scanning, reporting and remediation
- Attack simulation in an isolated lab environment
- Incident response documentation and evidence handling
- Hybrid cloud and Azure security learning

## Current Lab Structure

| Area | Purpose |
|---|---|
| Infrastructure | Proxmox, OPNsense, VPN, DNS, monitoring and core services |
| Microsoft Lab | Active Directory, Windows Server, Windows clients, Group Policy and identity testing |
| SIEM / SOC | Wazuh, syslog, log forwarding, dashboards and alert investigation |
| Attack Platform | Kali Linux, Parrot OS, REMnux and controlled security testing |
| Vulnerable Targets | Metasploitable, OWASP Juice Shop, DVWA and vulnerable Windows/Linux systems |
| Vulnerability Management | OpenVAS/Greenbone, Nessus Essentials, Security Onion, Zeek and Suricata |
| Cloud & Hybrid | Azure Arc, Entra ID, Sentinel, Defender and hybrid identity testing |
| Training / Experiments | Docker, Kubernetes, Linux testing, AI testing and sandbox systems |

## Core Technologies

- Proxmox VE
- OPNsense
- Windows Server
- Windows 11
- Active Directory
- Group Policy
- Microsoft Entra ID
- Microsoft Intune
- Microsoft Defender
- Microsoft Sentinel
- Wazuh
- Kali Linux
- OpenVAS / Greenbone
- OWASP Juice Shop
- DVWA
- Metasploitable 2

## VMID Plan

The lab uses a structured VMID plan so each area of the environment is clearly separated and has room for future expansion.

| VMID Range | Area |
|---|---|
| 100-113 | Infrastructure |
| 120-133 | Microsoft Lab |
| 140-152 | SIEM / SOC |
| 160-170 | Attack Platform |
| 180-193 | Vulnerable Targets |
| 200-210 | Vulnerability Management |
| 220-230 | Cloud & Hybrid |
| 240-249 | Training / Experiments |

Each section includes five reserved VMIDs for future expansion.

## Build Roadmap

### Phase 1: Foundation

- Proxmox installation and configuration
- Storage planning
- VMID planning
- Network bridge setup
- Backup strategy

### Phase 2: Network Security

- OPNsense firewall deployment
- Lab network segmentation
- Firewall rules
- NAT and port forwarding where required
- VPN testing

### Phase 3: Microsoft Infrastructure

- Windows Server deployment
- Active Directory Domain Services
- DNS and Group Policy
- Windows 11 domain-joined clients
- Basic hardening and security policies

### Phase 4: SOC and Logging

- Wazuh deployment
- Windows and Linux agent configuration
- Log collection
- Alert triage
- Dashboard creation

### Phase 5: Attack Simulation

- Kali Linux setup
- Vulnerable target deployment
- Controlled enumeration and exploitation testing
- Detection validation through SIEM alerts

### Phase 6: Vulnerability Management

- OpenVAS/Greenbone deployment
- Vulnerability scanning
- Risk ranking
- Remediation planning
- Rescan and validation

### Phase 7: Microsoft Cloud Security

- Entra ID learning
- Intune device management
- Defender security testing
- Sentinel integration
- Azure Arc and hybrid cloud testing

### Phase 8: Incident Response

- Alert investigation
- Timeline creation
- Evidence capture
- Root cause analysis
- Remediation notes
- Lessons learned

## Repository Structure

This repository will be organised into the following sections as the lab develops:

```text

home-soc-azure-lab/

├── 00-lab-overview/

├── 01-proxmox-build/

├── 02-network-design/

├── 03-active-directory/

├── 04-microsoft-cloud/

├── 05-siem-and-logging/

├── 06-vulnerability-management/

├── 07-attack-simulation/

├── 08-incident-response/

├── diagrams/

├── screenshots/

└── reports/
