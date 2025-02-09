# 🏢 Cybersecurity Lab  
🚀 **A Hands-On Virtual Lab for Cybersecurity Enthusiasts**  

## 📌 Overview  
Welcome to the **Torium Crescent Cybersecurity Lab**, a **virtual enterprise network** designed for learning **network security, system administration, and penetration testing**.  

This project simulates a **corporate environment** for a fictional real estate company, **Torium Crescent**, and covers both **Blue Team (defensive)** and **Red Team (offensive)** cybersecurity practices.  

## 🎯 Objectives  
🔹 **Network Security** – Build and secure a corporate-style network.  
🔹 **System Administration** – Configure Windows Server & Ubuntu Server.  
🔹 **Firewall & Threat Management** – Deploy OPNsense for network protection.  
🔹 **Threat Hunting** – Set up Elasticsearch Security for monitoring & defense.  
🔹 **Penetration Testing** – Simulate attacks to test system vulnerabilities.  

## 🛠️ Technologies & Tools  
| Category                | Tools & Technologies                                      |
|-------------------------|----------------------------------------------------------|
| **Networking & Firewall** | OPNsense, VLANs, Subnetting, pfSense                   |
| **Operating Systems**    | Windows Server 2022, Ubuntu Server 22.04, Kali Linux   |
| **Security Monitoring**  | Elasticsearch, Kibana, Elastic Security, Zeek, Suricata |
| **Active Directory & Management** | Windows Server AD, DNS, File Shares, Group Policy |
| **Penetration Testing**  | Metasploit, Nmap, BloodHound, Mimikatz, Burp Suite     |

---

## 🏗️ Lab Architecture  
### **Network Diagram**  
![Network Diagram](Images/network_diagram.png) *(Coming soon!)*  

The network consists of:  
✅ **Firewall & Edge Security** – OPNsense for traffic control & monitoring.  
✅ **Corporate Infrastructure** – Windows Server for Active Directory, DNS, and File Sharing.  
✅ **Threat Detection & Monitoring** – Elasticsearch for log analysis & attack detection.  
✅ **Pentesting Environment** – Kali Linux to perform Red Team attacks.  

---

## 🚀 Getting Started  
### **Prerequisites**  
- 🖥️ **Virtualization Software**: VMware Workstation / VirtualBox / Proxmox  
- 🏗️ **ISO Images**: Windows Server 2022, Ubuntu Server, Kali Linux  
- 🌐 **Network Configuration**: OPNsense Firewall  

### **Installation Guide**  
📌 Follow the step-by-step setup in the **[Documentation](Documentation/)** folder:  
1️⃣ **[Setting Up Virtual Machines](Documentation/01_Setting_Up_Virtual_Lab.md)**  
2️⃣ **[Configuring OPNsense Firewall](Documentation/03_Setting_Up_OpnSense_Firewall.md)**  
3️⃣ **[Deploying Windows Server & Active Directory](Documentation/04_Configuring_Windows_Server.md)**  
4️⃣ **[Installing Ubuntu Server & Services](Documentation/05_Deploying_Ubuntu_Server.md)**  
5️⃣ **[Threat Hunting with Elasticsearch](Documentation/08_Threat_Hunting_With_Elasticsearch.md)**  
6️⃣ **[Pentesting & Red Teaming](Documentation/10_Pentesting_And_Red_Team_Exercises.md)**  

---

## 🔍 Cybersecurity Learning Paths  
### 🛡️ **Blue Team (Defensive Security)**
✔️ **Network Hardening** – Secure firewall configurations, VLANs, and access control.  
✔️ **Threat Monitoring** – Use **Elastic Security** to analyze logs and detect intrusions.  
✔️ **Active Directory Security** – Implement Group Policies & user permissions.  
✔️ **System Hardening** – Disable unnecessary services & enforce security policies.  

### 🔴 **Red Team (Offensive Security)**  
✔️ **Reconnaissance & Scanning** – Nmap, Wireshark, and OSINT techniques.  
✔️ **Privilege Escalation** – Exploiting misconfigurations in Windows & Linux.  
✔️ **Active Directory Attacks** – Using BloodHound, Mimikatz & Kerberoasting.  
✔️ **Web Exploitation** – Testing web vulnerabilities with Burp Suite.  

---

## 📅 Project Roadmap  
- ✅ **Week 1** – Network & Firewall Setup  
- ✅ **Week 2** – Windows Server & Active Directory  
- ✅ **Week 3** – Threat Detection with Elasticsearch  
- ✅ **Week 4** – Pentesting & Red Teaming  
- 🔜 **Final Phase** – Reporting & Documentation  

---

## 📂 Repository Structure  
