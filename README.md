# Home SOC and Azure Security Lab

## Overview

This repository documents my home SOC and Azure security lab. I am using this project to build and document hands-on experience with Microsoft infrastructure, Azure security, SOC operations, vulnerability management, networking, endpoint security and incident response.

The lab is built around Proxmox and will include OPNsense, Active Directory, Windows clients, Wazuh, Kali Linux, vulnerable lab targets, OpenVAS/Greenbone and Microsoft cloud security tools such as Entra ID, Intune, Microsoft Defender and Microsoft Sentinel.

My aim is to create a realistic lab environment that I can use for learning, testing, troubleshooting and building evidence of the work I have completed.

## Lab Goals

The main goals of this lab are to practise and document:

- Proxmox virtualisation and lab infrastructure
- Network segmentation, firewalling and routing
- Active Directory, DNS, Group Policy and Windows administration
- Microsoft 365, Entra ID, Intune and Defender security concepts
- SIEM deployment, log collection and alert investigation
- Vulnerability scanning, reporting and remediation
- Attack simulation in an isolated lab environment
- Incident response notes, timelines and evidence handling
- Hybrid cloud and Azure security learning
- Technical documentation and GitHub portfolio development

## Current Lab Structure

| Area | Purpose |
|---|---|
| Infrastructure | Proxmox, OPNsense, VPN, DNS, monitoring and core services |
| Microsoft Lab | Active Directory, Windows Server, Windows clients, Group Policy and identity testing |
| SIEM / SOC | Wazuh, syslog, log forwarding, dashboards and alert investigation |
| Attack Platform | Kali Linux, Parrot OS, REMnux and controlled security testing |
| Vulnerable Targets | Metasploitable, OWASP Juice Shop, DVWA and vulnerable Windows/Linux systems |
| Vulnerability Management | OpenVAS/Greenbone, Nessus Essentials, vulnerability reporting and remediation tracking |
| Cloud Security | Microsoft Entra ID, Intune, Defender, Sentinel and Azure security learning |

## Planned Learning Phases

This lab will be built in stages:

1. Infrastructure foundation
2. Networking and firewall configuration
3. Windows Server and Active Directory
4. Azure and Microsoft 365 security
5. AWS fundamentals and cloud security
6. DevOps and platform engineering
7. Automation and scripting
8. Monitoring and operations
9. Enterprise capstone and professional portfolio
10. Infrastructure as Code and GitOps
11. Containers and Kubernetes
12. Advanced security engineering
13. Certification companion and career study planning

## Repository Structure

| Folder | Purpose |
|---|---|
| `00-lab-overview` | Lab overview, design decisions, VMID plan, VM inventory and general planning |
| `01-proxmox-build` | Proxmox setup, storage, networking and VM build notes |
| `02-network-design` | IP addressing, VLANs, firewall rules and routing notes |
| `03-active-directory` | Windows Server, Active Directory, DNS, users, groups and Group Policy |
| `04-microsoft-cloud` | Azure, Microsoft 365, Entra ID, Intune, Defender and Sentinel notes |
| `05-siem-and-logging` | Wazuh, syslog, log forwarding, dashboards and alert investigation |
| `06-vulnerability-management` | Vulnerability scanning, reporting and remediation evidence |
| `07-attack-simulation` | Kali Linux, controlled attack simulation and isolated security testing |
| `08-incident-response` | Investigation notes, timelines, evidence handling and response documentation |
| `09-automation-and-scripting` | PowerShell, Bash, Python and automation tasks |
| `10-monitoring-and-operations` | Monitoring, alerting, maintenance checks and operational documentation |
| `11-devops-and-iac` | GitHub Actions, Terraform, CI/CD, Infrastructure as Code and GitOps |
| `12-containers-and-kubernetes` | Docker, container security, Kubernetes and orchestration notes |
| `13-advanced-security` | Advanced detection engineering, threat hunting and security hardening |
| `14-capstone-and-portfolio` | Final projects, portfolio write-ups, reports and career evidence |
| `diagrams` | Network diagrams and architecture diagrams |
| `reports` | Lab reports, investigation summaries and vulnerability reports |
| `screenshots` | Evidence screenshots for each stage |
| `scripts` | Reusable PowerShell, Bash and Python scripts |
| `templates` | Reusable documentation templates, report formats and investigation notes |

## Security Notice

This repository is for learning and portfolio purposes only.

No passwords, API keys, licence keys, private certificates, tenant IDs, recovery keys, public IP addresses or sensitive personal information will be stored in this repository.

All attack simulation and vulnerability testing will be carried out only inside isolated lab environments that I own and control.
