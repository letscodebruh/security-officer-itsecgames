# ITSecGames Security Assessment - AccuKnox Submission

**Candidate:** Damarapati Jashwanth  
**GitHub:** letscodebruh  
**Assessment Target:** itsecgames.com  
**Date:** September 21-22, 2025

## 🎯 Project Overview

This repository contains a comprehensive security assessment of **itsecgames.com** conducted as part of the AccuKnox Security Officer Trainee evaluation process. The assessment demonstrates systematic vulnerability identification, risk analysis, and professional security reporting capabilities.

## 🛡️ About the Security Analyst

**Damarapati Jashwanth** is an entry-level cybersecurity professional with:
- **Education:** B.Tech in Computer Science & Engineering (Cybersecurity specialization) - CGPA 8.31
- **Current Role:** Business Analyst at Akrivia HCM (Security-adjacent requirements, RBAC, authentication workflows)
- **Experience:** SOC-lab exposure, SIEM log analysis, incident response basics, OWASP Top 10 testing
- **Certifications:** CompTIA Security+ (In Progress), NPTEL Cybersecurity, Coursera Cyberattacks
- **Core Skills:** Linux/Windows, Networking, Python/Bash, Nmap, Burp Suite, Wireshark, Nessus

## 🔍 Assessment Methodology

### **Phase 1: Reconnaissance & Information Gathering**
- **Domain Intelligence:** WHOIS lookup, DNS enumeration, IP resolution
- **Technology Fingerprinting:** WhatWeb analysis, HTTP header examination
- **Network Discovery:** Comprehensive port scanning with Nmap

### **Phase 2: Vulnerability Assessment**
- **Web Application Testing:** Nikto vulnerability scanning
- **SSL/TLS Analysis:** Certificate validation, SSL Labs assessment  
- **Directory Enumeration:** Gobuster directory discovery
- **Security Headers Analysis:** Missing protective headers identification

### **Phase 3: Risk Analysis & Reporting**
- **Vulnerability Classification:** CVSS-based severity rating
- **Impact Assessment:** Business risk evaluation
- **Remediation Planning:** Prioritized mitigation strategies
- **Professional Documentation:** Comprehensive security report

## 📊 Key Findings Summary

### **Critical/High Severity Issues**
1. **SSL Certificate Hostname Mismatch** - Browser security warnings, trust failure
2. **Multiple Unnecessary Network Services** - Expanded attack surface (FTP, RTSP, PPTP)
3. **End-of-Life Drupal 7 Platform** - Known vulnerabilities, no security support

### **Medium Severity Issues**
1. **Missing Security Headers** - No HSTS, CSP protection
2. **Exposed Configuration Files** - Installation files accessible
3. **Information Disclosure** - Technology stack revealed in headers

### **Total Findings:** 8 vulnerabilities across High/Medium/Low severity levels

## 📁 Repository Structure

```
├── evidence/                    # Raw scan outputs and logs
│   ├── whois.txt               # Domain registration information
│   ├── nslookup.txt            # DNS resolution results
│   ├── whatweb.txt             # Technology fingerprinting
│   ├── nikto_http.txt          # HTTP vulnerability scan
│   ├── nikto_https.txt         # HTTPS vulnerability scan
│   └── screenshots/            # Visual evidence
├── scans/                      # Detailed scan results
│   ├── nmap_all_ports.txt      # Complete port enumeration
│   ├── nmap_quick.txt          # Fast service detection
│   └── gobuster_results.txt    # Directory enumeration
├── reports/                    # Professional assessments
│   └── ITSecGames_Security_Assessment_Report.pdf
├── tools/                      # Documentation
│   ├── METHODOLOGY.md          # Assessment approach
│   └── TOOLS_USED.md          # Technical toolkit
└── README.md                   # This file
```

## 🛠️ Tools & Technologies Used

**Network Scanning:** Nmap 7.95  
**Web Vulnerability Assessment:** Nikto v2.5.0  
**Technology Fingerprinting:** WhatWeb  
**Directory Enumeration:** Gobuster  
**SSL/TLS Analysis:** SSL Labs, testssl.sh  
**Manual Analysis:** curl, HTTP header examination  

## 🎯 Professional Competencies Demonstrated

### **Technical Skills**
- ✅ Systematic vulnerability assessment methodology
- ✅ Multi-tool security testing approach
- ✅ Network and web application security analysis
- ✅ SSL/TLS configuration assessment
- ✅ Risk-based vulnerability prioritization

### **Documentation & Communication**
- ✅ Professional security report writing
- ✅ Executive summary for management audience
- ✅ Technical details for security teams
- ✅ Clear remediation recommendations
- ✅ Evidence-based findings documentation

### **Industry Standards Alignment**
- ✅ OWASP testing methodology
- ✅ CVSS vulnerability scoring
- ✅ Industry-standard tool utilization
- ✅ Ethical hacking principles
- ✅ Professional security assessment practices

## 🚀 Key Accomplishments

1. **Identified 8 security vulnerabilities** across multiple severity levels
2. **Discovered critical SSL misconfiguration** affecting user trust
3. **Found end-of-life platform** requiring immediate attention
4. **Documented comprehensive remediation strategies** with timelines
5. **Delivered professional-grade security report** suitable for business stakeholders

## 📈 Career Alignment with AccuKnox

This assessment demonstrates readiness for the **Security Officer Trainee** role through:

- **SOC Experience:** Previous SIEM analysis and incident response exposure
- **Business Context:** Current role involving security requirements and RBAC
- **Continuous Learning:** Active CompTIA Security+ certification pursuit
- **Technical Proficiency:** Hands-on experience with industry-standard tools
- **Communication Skills:** Professional documentation and stakeholder management

## 🔗 Assessment Artifacts

- **Complete Security Report:** [ITSecGames_Security_Assessment_Report.pdf](reports/)
- **All Evidence Files:** [evidence/](evidence/) directory
- **Scan Results:** [scans/](scans/) directory
- **Methodology Documentation:** [tools/METHODOLOGY.md](tools/)

## 📞 Contact Information

**Damarapati Jashwanth**  
📧 damarapatijashwanth@gmail.com  
📱 +91 90005 42152  
🔗 [LinkedIn: Jashwanth-damarapati](https://linkedin.com/in/Jashwanth-damarapati)  
⚡ [GitHub: letscodebruh](https://github.com/letscodebruh)

---

*This assessment was conducted in accordance with ethical hacking principles and authorized scope for AccuKnox Security Officer Trainee evaluation purposes.*
