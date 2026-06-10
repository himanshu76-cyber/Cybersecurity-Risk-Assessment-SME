# 🔐 Cybersecurity Risk Assessment Framework for SMEs

![Project](https://img.shields.io/badge/Project-Minor%20Project%20I-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Framework](https://img.shields.io/badge/Framework-NIST%20CSF%20v2.0-orange)
![Year](https://img.shields.io/badge/Year-2025--2026-lightgrey)
![License](https://img.shields.io/badge/License-MIT-green)

> A structured, quantitative **Cybersecurity Risk Assessment Framework** for Small and Medium Enterprises (SMEs) — identifying top threats, scoring risks using **Likelihood × Impact**, and recommending NIST-aligned mitigation strategies.

---

## 👤 Author

| Field | Details |
|-------|---------|
| **Name** | Himanshu Soni |
| **Project** | Minor Project I |
| **Organization** | Naviotech Solution Pvt Ltd |
| **Domain** | Cybersecurity · Risk Management |
| **Year** | 2025–2026 |

---

## 📋 Table of Contents

- "Overview" (#-overview)
- "Objectives" (#-objectives)
- "Critical SME Assets" (#-critical-sme-assets)
- "Top 5 Threats Identified" (#-top-5-threats-identified)
- "Methodology" (#-methodology)
- "Risk Assessment Model" (#-risk-assessment-model)
- "NIST Framework Alignment" (#-nist-framework-alignment)
- "Case Studies" (#-case-studies)
- "Key Findings" (#-key-findings)
- "SME Cybersecurity Best Practices" (#-sme-cybersecurity-best-practices)
- "Repository Structure" (#-repository-structure)
- "References" (#-references)
- "License" (#-license)

---

## 📌 Overview

Small and Medium Enterprises (SMEs) are increasingly targeted by cybercriminals due to limited security budgets and lack of dedicated IT teams. This project develops a **practical, reusable risk assessment framework** that any SME can adopt to:

- Identify and rank cyber threats
- Quantify risk using a scoring model
- Apply targeted mitigation controls
- Align with industry standards (NIST CSF v2.0)

---

## 🎯 Objectives

1. **Identify** the most prevalent cybersecurity risks facing SMEs
2. **Develop** a quantitative Risk Assessment Model (`Risk Score = Likelihood × Impact`)
3. **Propose** cost-effective mitigation strategies aligned with NIST CSF
4. **Validate** the framework through 3 real-world SME case studies

---
## 🖥️ Critical SME Assets

- Employee Accounts
- Customer Data
- Financial Records
- Business Applications
- Email Systems
- Cloud Services
- Network Infrastructure
---
## ⚠️ Top 5 Threats Identified

| # | Threat | Description |
|---|--------|-------------|
| 01 | **Phishing Attacks** | Fake emails/websites used to steal credentials |
| 02 | **Ransomware** | Malware that encrypts files and demands ransom |
| 03 | **Insider Threats** | Employees exposing data intentionally or accidentally |
| 04 | **Weak Passwords** | Poor practices enabling unauthorized access |
| 05 | **Unpatched Software** | Outdated systems with exploitable vulnerabilities |

---
## 🔬 Methodology

1. Identify SME assets and critical business processes.
2. Analyze common cyber threats and vulnerabilities.
3. Assign Likelihood (1–5) and Impact (1–5) values.
4. Calculate Risk Score = Likelihood × Impact.
5. Rank risks by severity.
6. Recommend mitigation controls aligned with NIST CSF.
7. Validate results using SME case studies.
---
## 📊 Risk Assessment Model

### Formula
```
Risk Score = Likelihood (1–5) × Impact (1–5)
```

### Risk Matrix

| Risk / Threat | Likelihood | Impact | Risk Score | Level |
|---------------|-----------|--------|------------|-------|
| Phishing Attacks | 5 | 4 | **20** | 🔴 High |
| Ransomware | 4 | 5 | **20** | 🔴 High |
| Insider Threats | 3 | 5 | **15** | 🟠 High |
| Weak Passwords | 5 | 4 | **20** | 🔴 High |
| Unpatched Software | 4 | 4 | **16** | 🔴 High |

### Risk Level Scale

| Score | Level | Action |
|-------|-------|--------|
| 1 – 5 | 🟢 Low | Monitor |
| 6 – 10 | 🟡 Medium | Plan |
| 11 – 15 | 🟠 High | Respond within 30 days |
| 16 – 25 | 🔴 Critical | Immediate action |

---

## 🛡️ NIST Framework Alignment

| Function | Activities |
|----------|-----------|
| **IDENTIFY** | Asset Management, Risk Assessment, Governance |
| **PROTECT** | Access Control, MFA, Data Security, Training |
| **DETECT** | Continuous Monitoring, Anomaly Detection |
| **RESPOND** | Incident Response Planning, Communications |
| **RECOVER** | Recovery Planning, Backup & Restoration |

---

## 🏢 Case Studies

### 1. 🛒 Retail Store — Phishing Attack
- **Severity:** High
- **Scenario:** Phishing email compromised POS system credentials
- **Controls Applied:** MFA + Employee Security Training
- **Outcome:** Reduced credential theft; staff trained to identify phishing

### 2. 🏥 Healthcare Clinic — Ransomware
- **Severity:** Critical
- **Scenario:** Ransomware encrypted patient records, halting operations
- **Controls Applied:** Automated Backups + Endpoint Security (EDR)
- **Outcome:** Fast recovery with minimal data loss

### 3. 💻 IT Services Firm — Insider Threat
- **Severity:** High
- **Scenario:** Disgruntled employee exfiltrated sensitive client data
- **Controls Applied:** RBAC + Access Audits + Least Privilege Policy
- **Outcome:** Prevented future exposure; breach source identified via audit trail

---

## 🔍 Key Findings

1. SMEs face significant cybersecurity risks due to limited security resources
2. Phishing attacks and ransomware are the most critical external threats
3. Insider threats can cause major data breaches and operational disruptions
4. Weak passwords and unpatched software increase vulnerability significantly
5. Risk assessment helps SMEs prioritize threats based on likelihood and impact
6. Controls like MFA, firewalls, backups, and training effectively reduce cyber risk
---
---
## ✅ SME Cybersecurity Best Practices

- Enable Multi-Factor Authentication (MFA)
- Maintain regular offline backups
- Conduct employee security awareness training
- Apply software patches promptly
- Use endpoint protection solutions
- Implement least-privilege access controls
- Perform periodic risk assessments
---
---
## 📁 Repository Structure

```
Cybersecurity-Risk-Assessment-SME/
├── README.md
├── project_Report.pdf           # Full project report (11 sections)
├── Risk_Matrix.xlsx             # Risk matrix with heat map & mitigation plan
├── Screenshots/
│   ├── Risk_Assessment_Model.png
│   ├── Risk_Matrix.png
│   └── Findings.png
└── References/
    └── References_Bibliography.txt
```

---

## 📚 References

| # | Source |
|---|--------|
| [1] | [NIST Cybersecurity Framework v2.0](https://www.nist.gov/cyberframework) |
| [2] | [ISO/IEC 27001:2022](https://www.iso.org/standard/27001) |
| [3] | [OWASP Top 10](https://owasp.org/www-project-top-ten/) |
| [4] | [FCC Cybersecurity Guide for SMBs](https://www.fcc.gov/cyberplanner) |
| [5] | [Verizon DBIR 2023](https://www.verizon.com/business/resources/reports/dbir/) |
| [6] | [ENISA Threat Landscape for SMEs](https://www.enisa.europa.eu) |

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, adapt, and share with attribution.

---

<p align="center">
  <b>Cybersecurity · Risk Management · 2025–2026</b><br/>
  Made with ❤️ by Himanshu Soni | Naviotech Solution Pvt Ltd
</p>
