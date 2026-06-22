# 🔐 Internal Network Penetration Test – Metasploitable 2

## 📌 Overview

This repository contains an Internal Network Penetration Test Report performed against the intentionally vulnerable **Metasploitable 2** virtual machine.

The assessment follows a structured penetration testing methodology including reconnaissance, service enumeration, vulnerability analysis, controlled exploitation, post-exploitation validation, and reporting.

The objective of this project was to gain practical experience in identifying and validating common security vulnerabilities in a controlled lab environment while improving documentation and reporting skills.

---

## 🎯 Objectives

- Perform network and service enumeration
- Identify exposed services and outdated software
- Research publicly known vulnerabilities
- Validate vulnerabilities through controlled exploitation
- Assess the impact of successful attacks
- Document findings and provide remediation recommendations

---

## 🛠️ Environment

| Component | Description |
|------------|-----------------------------|
| Attacker Machine | Kali Linux |
| Target Machine | Metasploitable 2 |
| Assessment Type | Internal Black-Box Penetration Test |
| Network | VirtualBox Internal Network |

---

## 🔍 Methodology

```
Reconnaissance
      │
      ▼
Service Enumeration
      │
      ▼
Vulnerability Analysis
      │
      ▼
Controlled Exploitation
      │
      ▼
Post-Exploitation Validation
      │
      ▼
Reporting
```

---

## 🚨 Key Findings

| Finding | Severity |
|-----------------------------------------------|------------|
| vsFTPd 2.3.4 Backdoor RCE (CVE-2011-2523) | Critical |
| WebDAV Arbitrary File Upload & RCE | Critical |
| Samba usermap_script RCE (CVE-2007-2447) | Critical |
| PostgreSQL Weak Authentication & UDF RCE | Critical |
| UnrealIRCd Backdoor RCE (CVE-2010-2075) | Critical |
| Java RMI Remote Code Execution | Critical |
| MySQL Default Authentication | High |
| Telnet Default Credentials | High |
| SMTP User Enumeration | Medium |
| Anonymous FTP & phpinfo() Information Disclosure | Low |

---

## 📄 Report

The complete penetration testing report is available in:

**📄 Metasploitable2_Internal_Pentest_Report.pdf**

The report includes:

- Executive Summary
- Assessment Summary
- Discovery Phase
- Vulnerability Analysis
- Recommendations
- Tools Used

---

## 🧰 Tools Used

- Nmap
- Metasploit Framework
- SearchSploit
- Nikto
- Hydra
- Davtest
- Cadaver
- SMBClient
- MySQL Client
- PostgreSQL Client
- Netcat

---

## 📚 Skills Demonstrated

- Network Enumeration
- Service Fingerprinting
- Vulnerability Research
- Exploit Validation
- Remote Code Execution
- Post-Exploitation Verification
- Technical Documentation
- Penetration Test Reporting

---

## ⚠️ Disclaimer

This project was conducted in a controlled lab environment using the intentionally vulnerable Metasploitable 2 virtual machine for educational purposes only.

The techniques demonstrated should only be used on systems for which explicit authorization has been obtained.

---

## 👤 Author

**Asad Sayyad**

Cybersecurity | Penetration Testing | Application Security
