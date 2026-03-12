# 🛡 Web Application VAPT

## 📌 Project Overview
This repository documents an end-to-end Web Application Vulnerability Assessment and Penetration Testing (VAPT) performed on a deliberately vulnerable application.
The assessment focused on identifying, exploiting, and documenting security weaknesses aligned with OWASP Top 10 standards.

## Target Application:
- [Artist Vulnweb](http://testphp.vulnweb.com/artists.php)

## 🎯 Objectives
- Perform structured web application security testing
- Identify OWASP Top 10 vulnerabilities
- Exploit vulnerabilities in a controlled lab environment
- Assess risk using CVSS scoring
- Provide remediation recommendations

## 🛠 Tools Used

| Tool        | Purpose                              |
|-------------|--------------------------------------|
| Burp Suite  | Web proxy & interception             |
| Nmap        | Port scanning & service enumeration  |
| SQLMap      | Automated SQL Injection testing      |
| Hydra       | Brute force testing                  |
| Nikto       | Web server scanning                  |
| Kali Linux  | Testing environment                  |

## 🔍 Vulnerabilities Identified

1️⃣ SQL Injection (SQLi) =
- Extracted database information using manual and automated techniques
- Identified improper input validation
- Mapped related CVEs and assigned CVSS severity

2️⃣ Cross-Site Scripting (XSS) =
- Demonstrated reflected and stored XSS attacks
- Showed impact on session hijacking and user manipulation

3️⃣ Cross-Site Request Forgery (CSRF) =
- Exploited missing anti-CSRF tokens
- Demonstrated unauthorized state-changing requests

4️⃣ Command Injection =
- Executed system-level commands due to unsanitized input fields

## 📊 Risk Assessment
- Vulnerabilities classified as Low / Medium / High
- CVE references included where applicable
- CVSS scoring applied to determine impact and exploitability
- Business impact analysis documented

## 📄 Reporting Approach
- Each vulnerability report includes:
- Vulnerability Description,
- Proof of Concept (PoC),
- Impact Analysis,
- CVSS Score,
- Remediation Recommendations,
- Screenshots for evidence

## 📁 Repository Structure

```
|--/recon

|--/exploitation

|--/screenshots

|--/reports

|--README.md
```

## 🚀 Key Learning Outcomes
- Practical understanding of OWASP Top 10 vulnerabilities
- Hands-on exploitation techniques
- Risk-based vulnerability classification
- Professional penetration testing report writing
- Exposure to real-world attack simulation methodology

## 👤 Author
Sai Badgujar
Cybersecurity Enthusiast | VAPT Practitioner
Preparing for Certified Ethical Hacker
