# 🔐 Botium Toys — Internal Security Audit

> ⚠️ **This is a fictional audit.** Botium Toys is a fictitious company created for the [Google Cybersecurity Certificate](https://grow.google/certificates/cybersecurity/) program. All data, findings, and recommendations in this project are simulated for educational purposes only.

---

## 📋 Project Overview

This project is a simulated internal security audit conducted as part of the Google Cybersecurity Certificate coursework. The goal was to assess the security posture of a fictional toy company — Botium Toys — by reviewing its existing controls and evaluating compliance with key industry frameworks.

---

## 🎯 Scope & Goals

- Assess current controls in place at Botium Toys
- Identify gaps in security practices
- Evaluate compliance with PCI DSS, GDPR, and SOC standards
- Provide recommendations to improve the company's security posture

---

## 🔎 Key Findings

### Controls Assessment

| Control | In Place? |
|---|---|
| Firewall | ✅ Yes |
| Antivirus software | ✅ Yes |
| Locks / CCTV / Fire detection | ✅ Yes |
| Least Privilege | ❌ No |
| Separation of Duties | ❌ No |
| Encryption | ❌ No |
| Intrusion Detection System (IDS) | ❌ No |
| Disaster Recovery Plans | ❌ No |
| Backups | ❌ No |
| Password Management System | ❌ No |

### Compliance Evaluation

| Framework | Compliant? |
|---|---|
| PCI DSS | ⚠️ Partial |
| GDPR | ✅ Mostly compliant |
| SOC type 1 & 2 | ❌ Not compliant |

---

## 🛡️ Recommendations

**1. Access Controls (Critical)**
Implement Least Privilege and Separation of Duties. Currently, all employees have access to sensitive customer data including credit card information and PII/SPII.

**2. Encryption (Critical)**
Credit card data is stored and transmitted without encryption, placing the company in direct violation of PCI DSS requirements.

**3. Business Continuity**
Establish a Disaster Recovery Plan (DRP) and implement regular backups with offsite storage to protect against ransomware, hardware failure, or physical disasters.

**4. Intrusion Detection**
Deploy an IDS to monitor network activity and detect threats in real time.

**5. Password Management**
Update the password policy to meet modern complexity standards and deploy a centralized password management system.

---

## 📁 Files

| File | Description |
|---|---|
| `Controls_and_compliance_checklist.pdf` | Completed audit checklist with controls and compliance assessment |

---

## 🎓 Context

This project was completed as part of the **Google Cybersecurity Certificate** — Course 2: *Play It Safe: Manage Security Risks*.

The scenario, company, and all associated data are entirely fictional and were provided by Google for educational purposes.

---

## 👤 Author

Made by [your name] · [LinkedIn profile] · [year]
