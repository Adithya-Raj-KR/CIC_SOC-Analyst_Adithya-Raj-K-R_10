# Day 10 Advanced Phishing Analysis (Headers, URLs, Indicators)

## Overview
This project focuses on advanced phishing detection and analysis, including email header inspection, malicious URL identification, and SOC-based investigation techniques used in real-world cybersecurity environments.

---

##  Objectives
- Analyze email headers to detect spoofing
- Identify malicious URLs and phishing patterns
- Understand advanced phishing techniques
- Perform structured phishing investigations
- Apply SOC response strategies

---

## Key Concepts

### 📧 Email Header Analysis
- Detect **From vs Return-Path mismatch** (spoofing)
- Verify **SPF, DKIM, DMARC** authentication
- Trace email origin using **Received fields**

---

###  URL Analysis
- Identify **typosquatting domains**
- Detect use of **IP-based URLs**
- Analyze **shortened links**
- Understand why **HTTPS ≠ safe**

---

### Phishing Indicators
- Credential harvesting pages
- Look-alike domains
- Malicious attachments
- Business Email Compromise (BEC)

---

## Investigation Workflow
1. Analyze email header  
2. Inspect URLs and domains  
3. Check reputation (VirusTotal)  
4. Identify phishing type  
5. Assess impact and response  

---

## SOC Response
- Block malicious domain and sender  
- Remove phishing emails (email purge)  
- Reset compromised accounts  
- Create detection rules using IOCs  

---

##  Example Scenario
- Spoofed email with **SPF/DKIM failure**
- Malicious URL with **typosquatting**
- Result: **Credential harvesting phishing attack (High Severity)**

---

##  Tools & Techniques
- SIEM platforms  
- Email security tools  
- Threat intelligence tools (VirusTotal)  

---

## Key Takeaway
Phishing analysis requires verifying email authenticity, inspecting URLs, and applying structured SOC workflows to detect and respond effectively.
