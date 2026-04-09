# Secure Network Design (Azure Hybrid Architecture)

## Overview
This project presents a secure enterprise network architecture designed to integrate two organizations into a hybrid cloud environment using Microsoft Azure.

The design focuses on segmentation, identity and access management, and layered security controls to protect sensitive data and reduce attack surface.

---

## Key Technologies
- Microsoft Azure (VNet, Firewall, WAF, VPN Gateway)
- Microsoft Entra ID (Azure AD)
- Microsoft Sentinel (SIEM/SOAR)
- Fortinet FortiGate 800D
- Sophos XG Firewall
- Cisco 9300 Switches
- Windows Server 2019 & Ubuntu Linux

---

## Security Focus Areas
- Defense-in-depth architecture
- Zero Trust implementation (MFA, RBAC)
- Network segmentation and firewall enforcement
- Secure remote access (VPN)
- Continuous monitoring and threat detection

---

## Risks Addressed
- Open high-risk ports (21–90, 3389)
- Legacy operating systems (Windows 7)
- Insecure protocols (rlogin, rsh, FTP, VNC)
- Weak authentication controls

---

## Compliance Alignment
- NIST SP 800-53
- PCI DSS
- HIPAA

---

## Documentation
Full architecture and analysis available in the `/docs` folder.

---

## Skills Demonstrated
- Cloud security architecture (Azure)
- Network security design
- Identity and access management
- Risk assessment and remediation
- SIEM integration and monitoring