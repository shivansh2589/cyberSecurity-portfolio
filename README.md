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
- File Integrity Monitoring
- SOC-style event investigation
- Microsoft Sentinel and Azure Arc experience
- Splunk training and security-monitoring skills
- Linux and Windows administration
- Certifications and technical training
- Resume and professional experience

## Featured Projects

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
- Built a reusable Wazuh view for Windows Server / AD security activity
- Correlated repeated failed logons with an account-lockout event in a SOC-style mini investigation

Verified Windows Security events included:

`4624`, `4625`, `4720`, `4722`, `4724`, `4725`, `4726`, `4728`, `4729`, `4740`, and `4767`.

This project demonstrates practical experience with virtualization, Windows Server, Active Directory, SIEM monitoring, event analysis, FIM, troubleshooting, and basic SOC investigation workflows.

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
- File Integrity Monitoring
- Authentication monitoring
- Account-lockout detection
- Security event correlation
- Troubleshooting agent and connectivity issues

### Azure Arc Hybrid Management

Connected Linux infrastructure to Microsoft Azure using Azure Arc.

Work included:

- Connected-machine onboarding
- Agent and service validation
- Heartbeat verification
- Hybrid cloud-management experience
- Integration with cloud-security monitoring workflows

### Microsoft Sentinel

Created and worked with a Microsoft Sentinel environment for cloud-based SIEM practice.

Areas explored include:

- Security monitoring
- Log collection
- Analytics
- Threat-detection workflows
- Cloud security operations

### Kali & Linux Security

Configured Kali Linux and Ubuntu systems for cybersecurity testing and secure administration.

Work included:

- SSH administration
- UFW firewall rules
- Static IP configuration
- Remote access
- Linux networking
- Connectivity troubleshooting

## Cybersecurity Home Lab

My lab uses a segmented architecture built around:

- pfSense
- TP-Link access point
- Proxmox VE
- Windows 11
- Windows Server 2022
- Active Directory Domain Services
- DNS
- Ubuntu Server
- Kali Linux
- Wazuh
- Microsoft Azure
- Azure Arc
- Microsoft Sentinel
- Splunk
- VMware Fusion

The lab is designed for hands-on practice with:

- Network defense
- Firewall administration
- Virtualization
- SIEM / XDR
- Threat detection
- Active Directory monitoring
- Windows and Linux monitoring
- File Integrity Monitoring
- SOC-style event investigation
- Troubleshooting
- Cloud-security integration

## Technologies

**Security & SIEM**

Wazuh • Microsoft Sentinel • Splunk • CrowdStrike training • Threat Detection • Log Analysis • File Integrity Monitoring

**Networking & Firewalls**

pfSense • TCP/IP • IPv4 • DNS • DHCP • ICMP • SSH • Routing • Network Segmentation • Firewall Rules

**Systems & Identity**

Windows 11 • Windows Server 2022 • Active Directory • DNS • Ubuntu Server • Kali Linux

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

It contains deeper technical documentation for pfSense and the Proxmox cybersecurity lab, including network recovery, Wazuh deployment, Windows Server / Active Directory monitoring, FIM, event IDs, troubleshooting steps, and SOC-style investigation notes.

## Current Development

Current priorities include:

- Privileged Active Directory group monitoring
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
