# Cyber Security Research & Hands-on Lab Portfolio
**Researcher:** Kaveesha Nethmini
**Project Scope:** Comprehensive study of Offensive and Defensive Security Operations.

## Project Overview
This repository documents a deep-dive research project covering the full spectrum of penetration testing, from infrastructure setup to advanced exploit analysis. The project involves building complex virtual environments, performing vulnerability assessments, and implementing defensive controls.

## Technical Skills & Lab Environment
* **Virtualization:** Managed a 10-VM enterprise lab using **VMware Workstation Pro** and **AWS EC2** (Kali Linux Cloud Instance).
* **Networking:** Packet analysis using **Wireshark**, TCP/IP stack deep dives, and subnetting.
* **Offensive Security:** Reconnaissance (OSINT), Network Scanning (Nmap), and Web App Security (DVWA).
* **Defensive Security:** IDS/IPS configuration with **Snort**, Firewall management (iptables), and Digital Forensics.
* **Specialized Tools:** Hak5 Rubber Ducky (DuckyScript), Metasploit (EternalBlue case study), and Autopsy (Forensics).

## Key Modules & Research Areas

### 1. Infrastructure & Cloud Setup
* [cite_start]Deployed a multi-OS environment including Windows Server 2022 (Domain Controller), Kali Linux, Ubuntu, and various "vulnerable by design" targets like Metasploitable 2/3 and OWASP BWA[cite: 4524, 4663].
* [cite_start]Configured custom virtual networks (LAB-ATTACK) to simulate isolated corporate environments[cite: 4629, 4658].

### 2. Reconnaissance & OSINT (Passive/Active)
* [cite_start]Mastered footprinting techniques using `whois`, `dnsrecon`, and `amass`[cite: 6457, 6496].
* [cite_start]Implemented Google Dorking and Shodan queries for surface area discovery[cite: 3894, 3899].

### 3. Vulnerability Assessment & Web Security
* [cite_start]Performed systematic network scanning with Nmap, utilizing NSE scripts and timing templates to avoid detection[cite: 3910, 3923].
* [cite_start]Hands-on exploitation of the **OWASP Top 10** within the DVWA environment, including SQL Injection, XSS, and Broken Access Control[cite: 3993, 4034].

### 4. Detection & Forensics
* [cite_start]Developed custom **Snort rules** to detect malicious file transfers and command-and-control (C2) beaconing[cite: 4103, 4132].
* [cite_start]Practiced forensic data recovery workflows, including disk imaging (FTK Imager) and file carving[cite: 4048, 4055].

### 5. Advanced Exploit Analysis
* [cite_start]**EternalBlue (MS17-010):** Conducted a technical breakdown of the SMBv1 vulnerability, simulating the exploit flow and analyzing the "wormable" impact on Windows environments[cite: 4490, 4496].
* [cite_start]**Wi-Fi Security:** Evaluated WPA2/WPA3 weaknesses and simulated Evil Twin attacks for educational research[cite: 4415, 4459].

## ⚖️ Legal & Ethical Compliance
All research was conducted within an isolated lab environment. [cite_start]This project adheres to the **Computer Crimes Act, No. 24 of 2007** (Sri Lanka) and ethical hacking best practices[cite: 4504, 6436].
