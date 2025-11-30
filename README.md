# Windows-Event-Log-Analysis-Lab
# 📁 Windows Event Log Analysis SOC Analyst Lab
Using Kali Linux to Attack Windows & Analyzing Logs in Event Viewer

This lab simulates a real SOC investigation using a Windows VM as the victim and a Kali Linux VM as the attacker.
I have performed multiple attacks, triggered Windows event logs, and analyzed as a SOC analyst.

# 🧱 Lab Architecture
Attack Machine: Kali Linux (192.168.20.102)
Target Machine: Windows 10/11 (192.168.20.101)
Network: Internal Network

Both VMs are isolated and not connected to the internet.


# 🛠 Prerequisites

VirtualBox

Kali Linux ISO

Windows 10/11 ISO

Host‑Only network created in VirtualBox



**2. Test connection**
Ping


(Screenshot)


# 🔥 Attack — Nmap Recon
**Nmap Port Scanning**
nmap 192.168.20.101

(Screenshot)


**Nmap Version Scan**

(Screenshot)

**Nmap Aggressive Scan**

(Screenshot)
