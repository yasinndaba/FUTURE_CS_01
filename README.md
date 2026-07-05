# FUTURE_CS_01 – Cyber Security Internship Tasks

This repository contains cybersecurity tasks completed as part of the Future Interns Cyber Security Internship Program.

The project focuses on practical security analysis, vulnerability assessment, and reporting using real-world tools and methodologies.

---

## 📌 Project Overview

This work demonstrates a structured approach to identifying and documenting common web application security issues using passive assessment techniques.

The goal is to simulate real-world security consulting practices, including risk identification and remediation planning.

---

## 🛠️ Tools Used

- Nmap – Network and service enumeration  
- OWASP ZAP – Passive vulnerability scanning  
- Browser Developer Tools – HTTP header and cookie analysis  
- Canva – Security report design  

---

## 📂 Task 1: Vulnerability Assessment Report

**Target:** demo.testfire.net  
**Type:** Passive Security Assessment  

### Key Findings

- Missing Content Security Policy (CSP)
- Missing HTTP Strict Transport Security (HSTS)
- Missing Clickjacking protection
- Session cookies missing SameSite attribute
- CSRF protection not clearly implemented
- Server version disclosure via HTTP headers
- Missing security hardening headers
- Information disclosure via HTML comments
- Exposed additional HTTP services (attack surface observation)

---

## 📊 Risk Summary

- Medium Risk Findings: 3  
- Low Risk Findings: 3  
- Informational Observations: 2  

---

## 🔐 Key Focus Areas

- Web application security fundamentals  
- HTTP security headers  
- Session security and cookies  
- Attack surface analysis  
- Passive vulnerability assessment techniques  

---

## ⚠️ Disclaimer

All testing was performed in a passive and ethical manner within allowed scope.  
No exploitation or intrusive testing techniques were used.

---

## 🚀 Purpose

This repository is part of my cybersecurity learning journey, focused on building practical SOC Analyst and vulnerability assessment skills.
