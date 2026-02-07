# Windows-Event-Log-Analysis-Lab
# 📁 Windows Event Log Analysis SOC Analyst Lab
Using Kali Linux to Attack Windows & Analyzing Logs in Event Viewer

This lab simulates a real SOC investigation using a Windows VM as the victim and a Kali Linux VM as the attacker.
I have performed multiple attacks, triggered Windows event logs, and analyzed as a SOC analyst.

# 🧱 Lab Architecture
Attack Machine: Kali Linux (192.168.1.101)
Target Machine: Windows 10/11 (192.168.1.100)
Network: Internal Network

Both VMs are isolated and connected to the internet through pFSense Router/Firewall.


# 🛠 Prerequisites

VirtualBox

Kali Linux ISO

Windows 10/11 ISO

pfSense ISO

Internal network created in VirtualBox



**2. Test connection**
Ping

<img src="https://imgur.com/a/jlQNbB9.png" height="80%" width="80%" alt="ping"/>

# 🔥 Attack — Nmap Recon
**Nmap Port Scanning**
nmap -F 192.168.20.101 
To fast scan the most common ports to see any active ports.

[https://imgur.com/a/jlQNbB9]


**Nmap Version Scan**

(Screenshot)

**Nmap Aggressive Scan**

(Screenshot)
