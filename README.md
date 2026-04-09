# Secure Network Design – Azure Hybrid Architecture

## 📌 Overview
This project presents a secure enterprise network design integrating on-premise infrastructure with Microsoft Azure cloud services. The architecture focuses on security, scalability, and compliance using a Zero Trust and Defense-in-Depth approach.

The solution supports a merger scenario between two organizations with legacy vulnerabilities, ensuring secure connectivity, identity management, and monitoring.

---

## 🎯 Objectives
- Design a secure hybrid cloud architecture
- Mitigate legacy vulnerabilities and insecure protocols
- Implement centralized identity and access management
- Ensure secure remote access across environments
- Align with industry frameworks (NIST, PCI DSS, HIPAA)

---

## 🏗️ Architecture Components

### ☁️ Cloud (Microsoft Azure)
- Azure Virtual Network (VNet) with segmented subnets
- Azure Firewall + Web Application Firewall (WAF)
- Azure VPN Gateway (site-to-site connectivity)
- Microsoft Entra ID (Azure AD) for identity + MFA
- Azure Key Vault for secrets management
- Microsoft Sentinel (SIEM/SOAR) for monitoring

### 🖥️ On-Prem Infrastructure
- Fortinet FortiGate 800D (Company A firewall)
- Sophos XG Firewall (Company B)
- Cisco 9300 Switches (upgrade from 3750X)
- Windows Server 2019 & Ubuntu Linux systems
- Hyper-V virtualization hosting enterprise workloads

### 🌐 Network & Systems
- Site-to-site VPN between on-prem and Azure
- Segmented network zones (production, admin, public)
- Secure web architecture:
  - NGINX reverse proxy
  - Apache Tomcat (application server)
  - PostgreSQL / MariaDB databases
- Elasticsearch cluster for logging and analytics

---

## 🔐 Security Design

### Zero Trust Principles
- Identity-based access control (RBAC)
- Multi-factor authentication (MFA)
- Continuous verification of users and devices

### Defense in Depth
- Network segmentation
- Firewalls and WAF protection
- Endpoint security controls
- Encryption (data in transit + at rest)

---

## ⚠️ Key Risks Identified
- Open high-risk ports (21–90, 3389)
- Legacy protocols (rlogin, rsh, FTP, VNC)
- Weak authentication policies
- End-of-life systems (Windows 7, XP, Cisco 3750X)

---

## 🛠️ Remediation Strategy
- Enforce MFA and strong password policies
- Replace legacy hardware and operating systems
- Disable insecure protocols and services
- Implement centralized logging with SIEM (Microsoft Sentinel)
- Apply network segmentation and firewall rules

---

## 📊 Compliance Alignment
- NIST SP 800-53
- PCI DSS (cardholder data protection)
- HIPAA (data privacy and security)

---

## 📁 Project Files
- `secure_network_design.pdf` – Full architecture and implementation plan

---

## 🚀 Key Takeaways
This project demonstrates:
- Enterprise network architecture design
- Risk-based security decision-making
- Cloud and on-prem integration
- Real-world application of Zero Trust and security frameworks

---

## 🔗 Author
Akio Simmonds  
Senior Analyst | Safety Management Systems (SMS) | Cybersecurity & GRC  
[LinkedIn](https://linkedin.com/in/akio-simmonds-693844203)
