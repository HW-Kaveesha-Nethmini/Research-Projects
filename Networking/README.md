# Enterprise Network Engineering & Infrastructure Security Portfolio
**Researcher:** H.W. Kaveesha Nethmini  
#### **Focus:** Full-Stack Network Administration, Directory Services, and Infrastructure Hardening.

## Executive Summary
This repository documents a massive, 228-page deep-dive into enterprise-grade networking. Instead of just theoretical study, this project showcases the successful deployment of a 10+ server architecture, simulating a high-availability corporate environment. It covers everything from core Active Directory services to automated deployment and cloud integration.


## Technical Infrastructure (The "Lab" Build)
I designed and managed a multi-server ecosystem using **VMware Workstation Pro**, featuring a redundant and scalable architecture:

* **Directory Services:** Deployed **Primary & Additional Domain Controllers (DC/ADC)** to ensure zero downtime for identity management.
* **Core Network Services:** * **DNS & DHCP:** Centralized name resolution and dynamic IP management for the entire enterprise.
    * **SQL Database Server:** Configured dedicated database backends for corporate applications.
* **Deployment & Maintenance:** * **WDS (Windows Deployment Services):** Automated PXE-boot OS installation to reduce manual setup time.
    * **WSUS (Windows Server Update Services):** Centralized patching to defend against "Day 1" exploits.
* **Enterprise Management:** Integrated **ManageEngine Desktop Central** for unified endpoint management (UEM) and automated software distribution.

---

## Security & Resilience Strategy
As an aspiring pentester, I built this infrastructure with a **Defense-in-Depth** mindset:

* **Endpoint Security:** Configured **Kaspersky Endpoint Security Cloud** for behavioral analysis and malware prevention across all workstations.
* **Business Continuity:** Implemented a **Disaster Recovery (DR)** plan involving FSMO role transfer, site-to-site backup strategies, and failover testing.
* **Connectivity & Privacy:** Established secure remote access using **VPN (IPSec/OpenVPN)** tunnels and configured internal messaging via **Windows Exchange Server**.
* **Cloud Integration:** Bridged on-premises assets with **Microsoft 365** and **Azure**, managing licensing, compliance, and hybrid identity.

---

## Technical Toolkit & Skills
| Category | Tools & Technologies |
| :--- | :--- |
| **Server OS** | Windows Server 2019/2022, Ubuntu Server |
| **Directory Services** | Active Directory (AD DS), GPO, FSMO Roles, DNS, DHCP |
| **Virtualization** | VMware Workstation Pro, Hyper-V |
| **Infrastructure** | WDS, WSUS, SQL Server, Exchange Server |
| **Management** | ManageEngine Desktop Central, SCCM (MECM) |
| **Security** | Kaspersky Cloud, VPN Tunnels, Disaster Recovery Planning |
| **Cloud** | Microsoft 365, Azure AD, SaaS Administration |

---

## Repository Contents
* **[Full Technical Project Book](./Networking_project_book.pdf):** A 228-page manual detailing every configuration and laboratory result.
* **Network Diagrams:** Logical and physical topology maps of the 10-server enterprise lab.
* **Configuration Backups:** Exported Group Policy (GPO) reports and server hardening checklists.

---

## ⚖️ Legal & Ethical Statement
All research and deployments were conducted within a strictly controlled virtual laboratory. This project adheres to the **Computer Crimes Act, No. 24 of 2007 (Sri Lanka)** and professional ethical standards.
