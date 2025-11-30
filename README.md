# Windows-Event-Log-Analysis-Lab
# 📁 Windows Event Log Analysis SOC Analyst Lab
Using Kali Linux to Attack Windows & Analyzing Logs in Event Viewer

This lab simulates a real SOC investigation using a Windows VM as the victim and a Kali Linux VM as the attacker.
You will perform multiple attacks, trigger Windows event logs, and analyze them like a SOC analyst.

# 🧱 Lab Architecture
Attack Machine: Kali Linux (192.168.56.101)
Target Machine: Windows 10/11 (192.168.56.102)
Network: Host‑Only Adapter


Both VMs are isolated and not connected to the internet.

# 📚 Table of Contents

Prerequisites

Setup

Attack A — Nmap Reconnaissance

Attack B — SMB Brute Force

Attack C — Reverse Shell (PowerShell)

Attack D — MS17-010 EternalBlue Exploit

Attack E — RDP Brute Force

Windows Event Log Analysis

Indicators of Compromise (IOCs)

MITRE ATT&CK Mapping

Report Template

# 🛠 Prerequisites

VirtualBox

Kali Linux ISO

Windows 10/11 ISO

Host‑Only network created in VirtualBox

Windows VM Defender disabled (optional for lab)

PowerShell Script Block Logging enabled (optional but recommended)

# 🔧 Setup
1. Set both VMs to Host‑Only Networking
Settings → Network → Adapter 1 → Host‑Only Adapter

2. Test connection

From Kali:

ping 192.168.56.102

# 🔥 Attack A — Nmap Recon
Command:
nmap -sC -sV -A 192.168.56.102

Windows Events Expected:
Event ID	Description
5156	Filtering Platform allowed connection
5158	Filtering Platform blocked connection
2004	Firewall blocked port scan burst

