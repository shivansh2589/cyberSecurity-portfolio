# Cyber & Cloud Security Portfolio

Welcome to my cybersecurity portfolio.

I am **Laxmikant Sharma**, a Cyber & Cloud Security Professional graduate from Robertson College in Winnipeg, Manitoba. This portfolio documents hands-on work in cybersecurity, network defense, SIEM, cloud security, Windows and Linux administration, firewall configuration, virtualization, and security monitoring.

## Portfolio

This repository contains the source files for my Cyber & Cloud Security portfolio website.

The portfolio includes:

- Hands-on cybersecurity projects
- Cybersecurity home-lab architecture
- pfSense firewall and network-segmentation work
- Proxmox VE virtualization
- Wazuh SIEM/XDR deployment and monitoring
- Windows Server 2022 and Active Directory security monitoring
- Privileged Active Directory group monitoring
- File Integrity Monitoring
- SOC-style event investigation
- Microsoft Sentinel and Azure Arc experience
- Splunk training and security-monitoring skills
- Linux and Windows administration
- Certifications and technical training
- Resume and professional experience

## Featured Projects

### Microsoft 365 Email Security Monitoring

Built and validated a personal Outlook → Microsoft Graph → Python/MSAL → Wazuh home-lab pipeline with delegated Mail.Read, local token reuse, message-ID deduplication, five-minute systemd scheduling, and JSONL ingestion. Custom rules 100500 (level 8), 100501 (level 6), and 100502 (level 7) cover Microsoft account security notifications, high-importance email, and phishing-style subject keywords. A real Gmail-to-Outlook test matched rule 100502 and was verified in Wazuh Threat Hunting.

- [Project evidence page](https://shivansh2589.github.io/cyberSecurity-portfolio/m365-email-security.html)
- [Architecture, setup, sanitized examples, validation, and screenshots](https://github.com/shivansh2589/cybersecurity-home-lab/tree/main/Microsoft-365-Email-Security)

**Achievement:** Automated and validated email-security monitoring in a home lab, including three custom Wazuh rules and real mailbox-to-dashboard testing. These detections support triage; keyword matches do not establish maliciousness.


### Proxmox Cybersecurity Home Lab with Wazuh & Active Directory Monitoring

Built a centralized cybersecurity lab on **Proxmox VE** and integrated it with the existing pfSense-segmented `192.168.10.0/24` network.

The environment includes:

- Wazuh Server
- Windows Server 2022
- Active Directory Domain Services and DNS
- Ubuntu Server
- Kali Linux
- Windows endpoints

Key work completed:

- Deployed and networked Windows and Linux virtual machines in Proxmox
- Diagnosed and repaired a Proxmox Linux bridge failure that made the host unreachable
- Restored `vmbr0` connectivity and verified the repair after reboot
- Validated gateway, Internet, and VM-to-VM communication
- Deployed Wazuh Manager, Indexer, and Dashboard
- Enrolled Windows, Windows Server, Ubuntu, and Kali agents
- Configured and validated real-time Windows File Integrity Monitoring
- Monitored Active Directory authentication and account-management events
- Validated privileged **Domain Admins** membership monitoring with a controlled test account
- Verified Event ID `4728` for adding the test account to Domain Admins and Event ID `4729` for removing it
- Confirmed Wazuh showed the changed member, privileged target group, administrative actor, and domain controller
- Built a reusable Wazuh view for Windows Server / AD security activity
- Correlated repeated failed logons with an account-lockout event in a SOC-style mini investigation

Verified Windows Security events included:

`4624`, `4625`, `4720`, `4722`, `4724`, `4725`, `4726`, `4728`, `4729`, `4740`, and `4767`.

This project demonstrates practical experience with virtualization, Windows Server, Active Directory, privileged-group monitoring, SIEM monitoring, event analysis, FIM, troubleshooting, and basic SOC investigation workflows.

### pfSense Network Segmentation

Built and configured a dedicated cybersecurity lab network protected by pfSense.

Key work includes:

- Configured LAN and WAN interfaces
- Created an isolated `192.168.10.0/24` lab network
- Blocked lab systems from accessing the primary home network
- Preserved Internet connectivity for lab devices
- Tested routing, DNS, ICMP, SSH, and firewall rules
- Documented firewall-rule evidence and troubleshooting

### Wazuh SIEM / XDR

Wazuh now runs as a dedicated VM inside the Proxmox lab and provides centralized monitoring across Windows and Linux endpoints.

Hands-on work includes:

- Wazuh Manager, Indexer, and Dashboard validation
- Windows and Linux agent enrollment
- Windows Security event collection
- Active Directory event monitoring
- Privileged Domain Admins membership monitoring
- File Integrity Monitoring
- Authentication monitoring
- Account-lockout detection
- Security event correlation
- Troubleshooting agent and connectivity issues

### Azure Arc Hybrid Management

Connected Linux infrastructure to Microsoft Azure using Azure Arc.

Work included connected-machine onboarding, agent and service validation, heartbeat verification, hybrid cloud-management experience, and integration with cloud-security monitoring workflows.

### Microsoft Sentinel

Created and worked with a Microsoft Sentinel environment for cloud-based SIEM practice, including security monitoring, log collection, analytics, threat-detection workflows, and cloud security operations.

### Kali & Linux Security

Configured Kali Linux and Ubuntu systems for cybersecurity testing and secure administration, including SSH administration, UFW firewall rules, static IP configuration, remote access, Linux networking, and connectivity troubleshooting.

## Cybersecurity Home Lab

My lab uses a segmented architecture built around pfSense, a TP-Link access point, Proxmox VE, Windows 11, Windows Server 2022, Active Directory Domain Services, DNS, Ubuntu Server, Kali Linux, Wazuh, Microsoft Azure, Azure Arc, Microsoft Sentinel, Splunk, and VMware Fusion.

The lab is designed for hands-on practice with network defense, firewall administration, virtualization, SIEM/XDR, threat detection, Active Directory monitoring, Windows and Linux monitoring, File Integrity Monitoring, SOC-style event investigation, troubleshooting, and cloud-security integration.

## Technologies

**Security & SIEM**  
Wazuh • Microsoft Sentinel • Splunk • CrowdStrike training • Threat Detection • Log Analysis • File Integrity Monitoring

**Networking & Firewalls**  
pfSense • TCP/IP • IPv4 • DNS • DHCP • ICMP • SSH • Routing • Network Segmentation • Firewall Rules

**Systems & Identity**  
Windows 11 • Windows Server 2022 • Active Directory • Privileged Group Monitoring • DNS • Ubuntu Server • Kali Linux

**Cloud**  
Microsoft Azure • Azure Arc • Microsoft Sentinel

**Virtualization**  
Proxmox VE • VMware Fusion • Virtual Machines • Virtual Networking

**Administration**  
PowerShell • Linux CLI • SSH • UFW

## Related Repository

### Cybersecurity Home Lab

I maintain a separate technical repository:

[cybersecurity-home-lab](https://github.com/shivansh2589/cybersecurity-home-lab)

It contains deeper technical documentation for pfSense and the Proxmox cybersecurity lab, including network recovery, Wazuh deployment, Windows Server / Active Directory monitoring, FIM, privileged Domain Admins monitoring, event IDs, troubleshooting steps, and SOC-style investigation notes.

## Current Development

Current priorities include:

- Additional SOC-style investigations
- Custom Wazuh detection rules
- Expanded Linux monitoring
- Additional attack/defense scenarios
- Additional screenshots and evidence
- Continued cloud-security integration

## About Me

**Laxmikant Sharma**  
Cyber & Cloud Security Professional  
Winnipeg, Manitoba, Canada

GitHub: https://github.com/shivansh2589  
LinkedIn: https://www.linkedin.com/in/laxmikant-sharma-cybersecurity

---

This portfolio is maintained as a record of my ongoing hands-on cybersecurity learning, lab development, and professional growth.
