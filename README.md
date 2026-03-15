# Research-Projects

# Integrated Cyber Security & Enterprise Networking Portfolio
**Researcher:** H.W. Kaveesha Nethmini  

#### Focus: Full-Stack Infrastructure Security, Offensive Operations, and Defensive Hardening.

## Project Overview
This repository documents an extensive research-based exploration into the dual worlds of Enterprise Networking and Offensive Security. The goal was to build a "Gold Standard" corporate environment and then systematically audit, exploit, and secure it using professional penetration testing frameworks.


## Phase 1: Enterprise Infrastructure & Networking
I designed and deployed a complex, 10-server virtualized environment to simulate a modern corporate network.

* **Active Directory Ecosystem:** Configured Primary and Additional Domain Controllers (DC/ADC) for high availability and redundancy.
* **Automated Services:** * **WDS (Windows Deployment Services):** For rapid, automated OS deployment across the network.
    * **WSUS (Windows Server Update Services):** Centralized patching to mitigate vulnerabilities across all endpoints.
* **Infrastructure Roles:** Deployed and managed dedicated DNS, DHCP, SQL Database, and Windows Exchange servers.
* **Endpoint Management:** Integrated **ManageEngine Desktop Central** for unified device control and automated software distribution.
* **Disaster Recovery:** Established 3-2-1 backup strategies and FSMO role transfer protocols to ensure business continuity.

---

## Phase 2: Offensive Security & Penetration Testing
Using the infrastructure built in Phase 1, I performed rigorous security auditing following the **PTES (Penetration Testing Execution Standard)**.

### Reconnaissance & Enumeration
* **OSINT & Footprinting:** Utilized `whois`, `nslookup`, and `theHarvester` to map attack surfaces.
* **Advanced Scanning:** Mastered **Nmap** for service discovery and script-based vulnerability scanning (`-sC -sV`).
* **Packet Analysis:** Used **Wireshark** to perform deep-dive analysis of TCP 3-way handshakes and protocol headers to identify anomalies.

### Exploitation & Web Security
* **Vulnerability Analysis:** Conducted technical research into **MS17-010 (EternalBlue)** and simulated exploitation flows in unpatched environments.
* **Web App Auditing:** Tested the **OWASP Top 10** within DVWA (Damn Vulnerable Web Application), focusing on SQL Injection, Cross-Site Scripting (XSS), and Broken Authentication.
* **Metasploit Framework:** Utilized MSF for payload generation, listener configuration, and post-exploitation privilege escalation.

---

## Phase 3: Defensive Operations (Blue Teaming)
True security requires building resilient systems that can detect and withstand attacks.

* **Intrusion Detection (NIDS):** Configured **Snort** with custom rules to monitor network traffic for malicious patterns like ICMP sweeps and C2 beaconing.
* **Digital Forensics:** Utilized **Autopsy** and **FTK Imager** for file carving and analyzing disk images to identify indicators of compromise (IOCs).
* **Hardening:** Applied Group Policy Objects (GPOs) to disable LLMNR/NBT-NS and enforce enterprise-grade password policies.

---

## Technical Toolkit
| Category | Tools & Technologies |
| :--- | :--- |
| **Operating Systems** | Kali Linux (Cloud & Local), Windows Server 2022, Ubuntu, Metasploitable |
| **Networking** | Wireshark, TCP/IP, DNS, DHCP, VPN (IPSec), WDS, WSUS |
| **Offensive Tools** | Nmap, Metasploit, Burp Suite, SQLmap, Responder |
| **Defensive/Forensics** | Snort, Autopsy, FTK Imager, ManageEngine Desktop Central |
| **Methodologies** | Scrum/Agile, PTES, OWASP Top 10 |

---

## Legal & Ethical Statement
All activities documented here were conducted in a strictly controlled, authorized lab environment. This project complies with the **Computer Crimes Act, No. 24 of 2007 (Sri Lanka)**. These skills are used exclusively for building defensive resilience and professional security auditing.

---
