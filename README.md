# Metasploitable 2 VAPT Report

## Overview
This project contains a comprehensive **Vulnerability Assessment and Penetration Testing (VAPT)** of Metasploitable 2, a deliberately vulnerable Linux distribution designed for security training and assessment.

## Tools Used for Vulnerability Discovery

### 1. **Nmap** (Network Mapper)
- **Purpose**: Network reconnaissance and service discovery
- **What it does**: Scans network ports to identify open services and operating system details
- **Usage in this project**: Identified open ports and running services on Metasploitable 2

### 2. **Nikto** (Web Server Scanner)
- **Purpose**: Web application vulnerability scanning
- **What it does**: Identifies insecure configurations, default credentials, outdated software, and web vulnerabilities
- **Usage in this project**: Scanned web services for known vulnerabilities and misconfigurations
- **Output**: Detailed HTML report (nikto_results.html.htm)

### 3. **Nessus** (Vulnerability Scanner)
- **Purpose**: Comprehensive vulnerability assessment
- **What it does**: Deep scanning for software vulnerabilities, missing patches, configuration issues, and compliance violations
- **Usage in this project**: Conducted detailed vulnerability scanning across all services

### 4. **Metasploit Framework** (Exploitation Platform)
- **Purpose**: Exploitation and verification of identified vulnerabilities
- **What it does**: Tests vulnerabilities by attempting to exploit them, validates findings, and generates payloads
- **Usage in this project**: Verified discovered vulnerabilities and documented exploitability

## Testing Methodology

1. **Reconnaissance** - Network scanning and service enumeration using Nmap
2. **Web Application Assessment** - Vulnerability scanning using Nikto
3. **Comprehensive Vulnerability Scanning** - System-wide assessment using Nessus
4. **Exploitation & Verification** - Testing vulnerabilities using Metasploit Framework
5. **Documentation** - Professional VAPT report generation

## Repository Contents

- **Metasploitable2_VAPT_Report.pdf** - Comprehensive professional VAPT report
- **nikto_results.html.htm** - Nikto web scanner results
- **src/** - Screenshots and evidence from the assessment
- **README.md** - This file

## Key Findings

Refer to **Metasploitable2_VAPT_Report.pdf** for detailed findings including:
- Vulnerability classifications and severity levels
- Detailed exploitation steps
- Risk assessment and impact analysis
- Remediation recommendations

## Prerequisites

To reproduce or conduct similar tests, you'll need:
- Metasploitable 2 VM
- Nmap
- Nikto
- Nessus (licensed or evaluation)
- Metasploit Framework

## Disclaimer

This assessment is conducted on intentionally vulnerable software (Metasploitable 2) for educational and authorized testing purposes only. Unauthorized testing on systems you don't own or have explicit permission to test is illegal.

## References

- [Nmap Documentation](https://nmap.org/book/man.html)
- [Nikto Web Scanner](https://cirt.net/nikto2)
- [Nessus](https://www.tenable.com/products/nessus)
- [Metasploit Framework](https://www.metasploit.com/)