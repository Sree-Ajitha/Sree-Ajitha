# 👋 Hi, I'm Sree Ajitha  
**Aspiring Cybersecurity Analyst | SOC & Threat Hunting | Building Secure Digital Frontiers**

![Profile Views](https://komarev.com/ghpvc/?username=Sree-Ajitha&label=Profile%20Views&color=0e75b6&style=flat)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/sreeaj)  
[![Email](https://img.shields.io/badge/Email-sree%40hotmail.co.nz-red?style=flat&logo=gmail)](mailto:hi@sreeajitha.me)  
> **Note:** This project is currently **In Progress**.  
> New features, updated scripts, and documentation will be added over the coming weeks.
---

## 🛡️ About Me

Cybersecurity enthusiast pursuing a **Master’s in IT (Cybersecurity)** with hands-on expertise in:
- **SOC Analysis, Threat Hunting, Digital Forensics, Cloud Security, Python Scripting**
- Experience in **CTF challenges, malware analysis, ethical hacking, and SIEM monitoring**
- Certified **Junior Security Analyst (SBT)**, **Google Associate Cloud Engineer**, **Microsoft AZ-900, AI-900, SC-900**

> **Goal:** To build a strong portfolio demonstrating **real-world security skills** and readiness for a cybersecurity analyst role.

---

## 🚀 Featured Projects

### 🔹 [Threat Hunting Playbooks](https://github.com/YOUR_GITHUB_USERNAME/Threat-Hunting)
Queries and detection techniques for suspicious activities using Splunk and Wireshark.  
- MITRE ATT&CK-based detection rules  
- PCAP analysis labs using Wireshark  
 
---

### 🔹 [DFIR Case Studies](https://github.com/YOUR_GITHUB_USERNAME/DFIR-Cases)
Digital forensic investigations:
- Evidence acquisition, timeline analysis, and incident reports  
- Open-source forensic tools (Volatility, Autopsy)  
- Sample simulated attack reports

---

### 🔹 [Python Security Scripts](https://github.com/Sree-Ajitha/Python-Security-Tools/blob/043d678e509130da729bf498dc15e9dba14093da/README.md)
Automation scripts for:
- #### **🔐[Password Strength Analyzer – Version 2.0](https://github.com/Sree-Ajitha/Python-Security-Tools/pull/1#issue-3288836333)**
- #### **🛡 [Log Parser & Suspicious IP Detector – Python Tool](https://github.com/Sree-Ajitha/Python-Security-Tools/blob/1a1380dd739b0cf51c35afcb12ac1275d4d24324/Log%20Parser%20%26%20IP%20Detection%20Tool.md)** 
- #### **🚨[Cross-Platform Brute Force Login Monitor](https://github.com/Sree-Ajitha/Python-Security-Tools/blob/2f5fb28516d1aadbf25fc1fa7bf3f4b4862ee6bf/Brute%20force%20login%20monitoring.md)** 
- #### **🛡 [Ransomware Activity Detection Script](https://github.com/Sree-Ajitha/Python-Security-Tools/blob/fb8d85bf707cc73f10f7bc9b633a59cdb2acc814/Basic%20ransomware%20activity%20detection.md)** 

---

### 🔹 [Cloud Security Labs (GCP)](https://github.com/YOUR_GITHUB_USERNAME/Cloud-Security-Labs)
Projects showcasing:
- IAM access configuration, monitoring, and logging  
- Secure network architecture setup on GCP  
- Terraform-based provisioning

---

## ✍ Cybersecurity Blog

I share **short articles** about my cybersecurity journey, research, and hands-on labs:
- [How I Detected a Simulated Ransomware Attack Using SIEM](https://YOUR_GITHUB_PAGES_URL/article1)
- [Forensic Investigation of a Phishing Attack – A Step-by-Step Analysis](https://YOUR_GITHUB_PAGES_URL/article2)
- [Zero Trust in Practice – My Oracle Cloud Ubuntu Setup](https://YOUR_GITHUB_PAGES_URL/article3)

📌 **New post on [GitHub Pages Blog](https://YOUR_GITHUB_PAGES_URL) and [LinkedIn](https://www.linkedin.com/in/sreeaj).

---

## 🛠️ Tools & Platforms

| Category          | Tools |
|--------------------|---------------------------------------------|
| **SOC Monitoring** | Splunk, Wireshark, Security Onion, Nagios   |
| **DFIR**           | Volatility, Autopsy, FTK Imager, Log2Timeline |
| **Offensive Sec**  | Kali Linux, Metasploit, Nmap, Burp Suite    |
| **Cloud Sec**      | GCP, Terraform, IAM, Load Balancing         |
| **Automation**     | Python, Bash, PowerShell                    |

## 🧪 Home Lab Blueprint – VMware & WSL Cybersecurity Simulation

This lab replicates a **multi-segmented network environment** for **penetration testing, SOC analysis, and DFIR exercises**.  
It combines **on-premises-style VMware VMs** with **cloud-hosted and WSL-based assets**, simulating both enterprise and hybrid infrastructures.

### **Architecture Overview**

| **Platform** | **OS**                       | **Resource Role**                             | **IP Address / CIDR**   |
|--------------|------------------------------|-----------------------------------------------|-------------------------|
| **OCI**      | Ubuntu 24.04.2 (LTS)         | Cloud Server                                  | 152.67.0.0/13           |
| **WSL**      | Kali Linux 2025.1            | Authorised Client                             | 172.18.0.0/18           |
| **VMware**   | Kali Linux 2025.1            | Penetration Tester                            | 172.16.16.92/16         |
| **VMware**   | Ubuntu 24.04.2               | Internal Client                               | 172.16.16.93/16         |
| **VMware**   | Windows 11 24H2              | AD Client                                     | 172.16.16.90/16         |
| **VMware**   | Windows Server 2025 STD      | Active Directory Server (DNS, Apache, IIS)    | 172.16.16.250/16        |
| **VMware**   | Metasploitable 2             | Threat Client                                 | 172.16.16.91/16         |
| **VMware**   | Parrot 6.4 Lorikeet          | Secondary Penetration Tester                  | 172.16.16.33/16         |

---

### **Key Lab Features**
- **Hybrid Environment:** Mix of cloud-hosted, Linux WSL, and on-prem VMware instances.  
- **Red & Blue Team Exercises:**  
  - *Red Team:* Kali Linux & Parrot OS for offensive security and exploitation.  
  - *Blue Team:* Windows Server + AD for SOC monitoring, DFIR, and incident response.  
- **Target Systems:** Vulnerable hosts (Metasploitable 2) for controlled exploit testing.  
- **Simulated Enterprise Services:** DNS, Apache, IIS, and AD authentication.

---

### **Use Cases**
- Penetration testing & exploit validation  
- Active Directory attack simulations (Kerberoasting, Pass-the-Hash, GPO abuse)  
- Threat detection and SIEM rule testing (Splunk, Elastic, Security Onion)  
- DFIR workflows – log correlation, evidence acquisition, and incident reporting  
- Cloud-edge integration testing with **OCI Ubuntu node**

---

### **Planned Attack Simulations**
- **Brute Force Attacks** – Hydra, Medusa against AD & SSH  
- **Lateral Movement** – SMB relay, WMI exec, RDP hijacking  
- **Privilege Escalation** – Unquoted service paths, UAC bypass  
- **Web Exploitation** – SQL injection, XSS on vulnerable apps  
- **Ransomware Containment Drills** – Simulated encryption & rollback

> ⚡ **Note:** This lab environment is isolated and air-gapped to ensure safe testing of malicious scenarios without impacting production systems.

---

> ⚡ *"Cybersecurity is not just my career path, it’s my mindset. I aim to make the digital world safer—one lab at a time."*

---

> **Note:** This project is currently **In Progress**.  
> New features, updated scripts, and documentation will be added over the coming weeks.  
> Feedback are welcome.
