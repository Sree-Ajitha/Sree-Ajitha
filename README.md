![Profile Views](https://komarev.com/ghpvc/?username=Sree-Ajitha&label=Profile%20Views&color=0e75b6&style=flat)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sreeaj) [![Email](https://img.shields.io/badge/Email-grey?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hi@sreeajitha.me)  
---
# 👋 Hi, I'm Sree Ajitha  
***🔐 Cybersecurity Professional & Systems Support Analyst | SOC, SIEM & SOAR | 🎯 Active CTF Competitor | 📚 Master's in Cyber Security***

---
> **Note:** This project is currently **In Progress**.  
> New features, updated scripts, and documentation will be added over the coming weeks.
---
> **Goal:** To build a strong portfolio demonstrating **real-world security skills** and readiness for a cybersecurity analyst role.

---

## 🛠 Technical Skills  
- **Cybersecurity**: Suricata, Zeek, Splunk, Wazuh, Nessus, OpenVAS, Scout Suite  
- **Forensics & Threat Hunting**: IOC development, Redline, Wireshark, Tshark  
- **Automation & Cloud**: n8n, Trace Cat, Docker, Nginx, rclone, Linux/Windows admin  
- **Scripting & Dev**: Python, Bash, Batch, HTML  

---

## 🚀 Highlights  
- 🏆 Active in CTFs (NZCSC, Try Hack Me)  
- ✍️ Authored 100+ troubleshooting articles to streamline resolution  
- 📖 Researching Open-Source SOC & Zero Trust Security as part of Master’s study  

---
## 🛠️ Tools & Platforms

| Category          | Tools |
|--------------------|---------------------------------------------|
| **SOC Monitoring** | Splunk, Wireshark, Security Onion, Wazuh   |
| **DFIR**           | Volatility, Autopsy, FTK Imager, Log2Timeline |
| **Offensive Sec**  | Kali Linux, Metasploit, Nmap, Burp Suite    |
| **Cloud Sec**      | GCP, Terraform, IAM, Load Balancing         |
| **Automation**     | Python, Bash, PowerShell, html              |

## 🧪 Home Lab Blueprint – VMware & WSL Cybersecurity Simulation

This lab replicates a **multi-segmented network environment** for **penetration testing, SOC analysis, and DFIR exercises**.  
It combines **on-premises-style VMware VMs** with **cloud-hosted and WSL-based assets**, simulating both enterprise and hybrid infrastructures.

### **Architecture Overview**

| **Platform** | **OS**                       | **Resource Role**                             | **IP Address / CIDR**   |
|--------------|------------------------------|-----------------------------------------------|-------------------------|
| **OCI**      | Ubuntu 24.04.2 (LTS)         | Cloud Server                                  | 122.67.0.0/13           |
| **WSL**      | Kali Linux 2025.1            | Authorised Client                             | 178.18.0.0/18           |
| **VMware**   | Kali Linux 2025.1            | Penetration Tester                            | 178.16.16.92/16         |
| **VMware**   | Ubuntu 24.04.2               | Internal Client                               | 178.16.16.93/16         |
| **VMware**   | Windows 11 24H2              | AD Client                                     | 178.16.16.90/16         |
| **VMware**   | Windows Server 2025 STD      | Active Directory Server (DNS, Apache, IIS)    | 178.16.16.250/16        |
| **VMware**   | Metasploitable 2             | Threat Client                                 | 178.16.16.91/16         |
| **VMware**   | Parrot 6.4 Lorikeet          | Secondary Penetration Tester                  | 178.16.16.33/16         |

---
## 🎓 Certifications  

![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white) ![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)  ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)  ![CS50 Harvard](https://img.shields.io/badge/CS50%20Harvard-A51C30?style=for-the-badge&logo=harvard&logoColor=white)  ![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)  

---
## 🚀 Featured Projects

### [Python Security Tools](https://github.com/Sree-Ajitha/Python-Security-Tools/blob/043d678e509130da729bf498dc15e9dba14093da/README.md)
     
- #### **🔐[Password Strength Analyzer – Version 2.0](https://github.com/Sree-Ajitha/Python-Security-Tools/pull/1#issue-3288836333)**
- #### **🛡 [Log Parser & Suspicious IP Detector – Python Tool](https://github.com/Sree-Ajitha/Python-Security-Tools/blob/1a1380dd739b0cf51c35afcb12ac1275d4d24324/Log%20Parser%20%26%20IP%20Detection%20Tool.md)** 
- #### **🚨[Cross-Platform Brute Force Login Monitor](https://github.com/Sree-Ajitha/Python-Security-Tools/blob/2f5fb28516d1aadbf25fc1fa7bf3f4b4862ee6bf/Brute%20force%20login%20monitoring.md)** 
- #### **🛡 [Ransomware Activity Detection Script](https://github.com/Sree-Ajitha/Python-Security-Tools/blob/fb8d85bf707cc73f10f7bc9b633a59cdb2acc814/Basic%20ransomware%20activity%20detection.md)** 

---

### 🔹 [Threat Hunting Playbooks](https://github.com/Sree-Ajitha/Threat-Hunting-Playbooks/blob/09f575c9f0b83491dd68a7dda90c5cbcb7d509b5/README.md)
#### [⚡Firefox Zero-Day - CVE-2024-9680](https://github.com/Sree-Ajitha/Threat-Hunting-Playbooks/blob/1dbf8c2b346fc9a1ded19bc277bb9e33eb6de441/Firefox%20Zero-Day%20CVE-2024-9680.md)
- **Exploit Type:** Use-After-Free (UAF) → Remote Code Execution  
- **Attack Methods:** Drive-by downloads, watering hole attacks  
- **Mitigation:** Apply patches, enable automatic updates, maintain backups, use endpoint protection
 
---

### 🔹 [DFIR Case Studies](https://github.com/Sree-Ajitha/DFIR-Cases/blob/72d0845dac2c5f7eb229098035d4b51bf51a629f/README.md)
#### [Hybrid Infrastructure Deployment](https://github.com/Sree-Ajitha/DFIR-Cases/blob/3cf5ba11da2afa1ce21f75b00a425a68529d3fb6/Hybrid%20Infrastructure%20Deployment.md)
***Hybrid cloud and on-premises environment for DFIR, SOC monitoring, and penetration testing with automated workflows.***
- **Monitoring & SIEM:** Splunk, Wazuh  
- **Vulnerability & Pen Testing:** Nessus, OpenVAS, Metasploit  
- **Automation & Deployment:** Docker, n8n, Nginx  
- **Network Security:** OpenVPN, OCI VPN, Entra AD RBAC 

---

### 🔹 [Cloud Security Labs (GCP)](https://github.com/Sree-Ajitha/Cloud-Security-Labs/blob/ad44ac96bc023343b80b70a3a889e4d18b3caa23/README.md)
- Earned **Google Cloud Associate Cloud Engineer** certification  
- Deployed **secure, scalable cloud infrastructure**  
- Automated workflows and infrastructure provisioning using **Terraform**  
- Applied **zero-trust principles and cloud security best practices**  
- Practiced hybrid cloud integration, monitoring, and resilience testing

---
### 🔹 [Vulnerability_Scans](https://github.com/Sree-Ajitha/Vulnerability_Scans/blob/409aa9fcf17f323208db8d4ce7334fa50209498c/README.md)
#### [VPN Performance Evaluation](https://github.com/Sree-Ajitha/Vulnerability_Scans/blob/c99012c2bf33f7f44497828b125fb8d97b7c6287/Performance%20evaluation%20of%20VPN%20Protocols.md)

- **IPsec:** Higher throughput at large packet sizes  
- **OpenVPN:** Better performance at small packet sizes  
-  Latency fluctuates depending on network conditions

---

> ⚡ *"Cybersecurity is not just my career path, it’s my mindset. I aim to make the digital world safer—one lab at a time."*

---

> **Note:** This project is currently **In Progress**.  
> New features, updated scripts, and documentation will be added over the coming weeks.  
> Feedback are welcome.
