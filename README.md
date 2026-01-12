# Qualitative Risk Assessment – Small Real Estate Brokerage Case Study

**Organization:** [Redacted] Real Estate Brokerage
**Location:** Victorville, CA  
**Employees:** 4  
**Assessment Type:** Qualitative Risk Assessment  
**Framework References:** NIST SP 800-30, NIST SP 800-37 (RMF), NIST CSF 2.0  
**Author:** Gregory Sewalt

---

## 1. Purpose & Scope

This risk assessment was conducted to identify, analyze, and prioritize cybersecurity risks impacting a small, independently owned real estate brokerage. The practice relies heavily on digital systems for client records, contracts, financial transactions, and daily operations.

The goal of the assessment was to:
- Identify key information assets and threats
- Evaluate likelihood and impact of cybersecurity risks
- Document existing controls
- Recommend risk treatment strategies appropriate for a small business environment

This assessment focuses on **information systems, people, and processes** directly supporting business operations.

---

## 2. Methodology

The assessment was conducted using a **NIST SP 800-30–aligned qualitative risk methodology**, incorporating:

- Asset identification
- Threat and vulnerability analysis
- Likelihood and impact scoring
- Risk determination
- Risk treatment recommendations

### Risk Scoring Model

| Factor | Scale |
|------|------|
| Likelihood | Low (1), Medium (2), High (3) |
| Impact | Low (1), Medium (2), High (3) |
| Risk Rating | Likelihood × Impact |

| Risk Score | Rating |
|-----------|--------|
| 1–2 | Low |
| 3–4 | Medium |
| 6–9 | High |

---

## 3. Asset Identification

Key assets supporting brokerage operations include:

| Asset | Description |
|-----|-------------|
| Employee Laptops | Used for email, MLS access, contracts |
| Client Data | PII, financial information, transaction records |
| Cloud Email & Storage | Microsoft 365 / Google Workspace |
| NAS / Shared Storage | Local storage for documents and backups |
| Wi-Fi Network | Office network for all devices |
| Third-Party Services | MLS, accounting, e-signature platforms |

---

## 4. Threat Landscape

The following threats were identified as most relevant to the brokerage’s operating environment:

- Phishing and business email compromise (BEC)
- Ransomware
- Credential theft
- Accidental data exposure
- Insider error (non-malicious)
- Loss or theft of endpoint devices
- Third-party service compromise

---

## 5. Risk Register

### High & Medium Risks Identified

| Risk ID | Asset | Threat | Vulnerability | Likelihood | Impact | Risk Rating |
|-------|-------|--------|---------------|------------|--------|------------|
| R-01 | Email System | Phishing / BEC | No MFA on all accounts | High (3) | High (3) | **9 – High** |
| R-02 | Client Data | Data Breach | Shared folders, no access controls | Medium (2) | High (3) | **6 – High** |
| R-03 | Laptops | Ransomware | Inconsistent patching | Medium (2) | High (3) | **6 – High** |
| R-04 | NAS | Data Loss | No verified backups | Medium (2) | Medium (2) | **4 – Medium** |
| R-05 | Wi-Fi Network | Unauthorized Access | Flat network, weak segmentation | Medium (2) | Medium (2) | **4 – Medium** |
| R-06 | Cloud Services | Account Takeover | Weak password practices | Medium (2) | Medium (2) | **4 – Medium** |
| R-07 | Employees | Insider Error | Limited security awareness training | High (3) | Medium (2) | **6 – High** |

---

## 6. Risk Analysis (Selected Examples)

### R-01: Business Email Compromise (BEC)

- **Description:** An attacker could gain access to an employee’s email account and redirect wire transfers or steal sensitive client information.
- **Existing Controls:** Basic spam filtering
- **Impact:** Financial loss, reputational damage, potential legal exposure
- **Risk Level:** High

---

### R-03: Ransomware on Employee Laptops

- **Description:** Malware infection encrypts files and disrupts business operations.
- **Existing Controls:** Antivirus installed on some devices
- **Impact:** Business downtime, potential data loss, ransom demand
- **Risk Level:** High

---

### R-07: Accidental Insider Data Exposure

- **Description:** Employee unintentionally shares or deletes sensitive files.
- **Existing Controls:** Informal verbal guidance
- **Impact:** Client trust loss, compliance concerns
- **Risk Level:** High

---

## 7. Risk Treatment Recommendations

| Risk ID | Recommended Treatment | Risk Strategy |
|-------|----------------------|---------------|
| R-01 | Enforce MFA for all email and cloud accounts | Mitigate |
| R-02 | Implement role-based access controls | Mitigate |
| R-03 | Centralize patching and endpoint protection | Mitigate |
| R-04 | Implement and test backups regularly | Mitigate |
| R-05 | Segment Wi-Fi and secure router configuration | Mitigate |
| R-06 | Enforce password standards and MFA | Mitigate |
| R-07 | Conduct annual security awareness training | Mitigate |

---

## 8. Residual Risk Summary

After recommended controls are implemented:

| Risk Category | Residual Risk |
|--------------|---------------|
| Email & Identity | Low |
| Ransomware | Low–Medium |
| Data Exposure | Low |
| Insider Error | Low |
| Third-Party Risk | Medium (requires ongoing review) |

Residual risk was reviewed with business leadership and accepted as appropriate for the size and operational needs of the organization.

---

## 9. Metrics & Outcomes

| Metric | Before | After (Projected) |
|------|--------|------------------|
| MFA Coverage | 25% | 100% |
| Encrypted Devices | 50% | 100% |
| Staff Security Training | None | Annual |
| Verified Backups | Unverified | Monthly Testing |
| Documented Risks | 0 | 7 |

---

## 10. Conclusion

This risk assessment demonstrates how **formal cybersecurity risk management can be scaled effectively for a small business**. While the brokerage operates with limited resources, targeted controls addressing identity, email security, endpoint protection, and employee awareness significantly reduce overall risk.

By aligning this assessment with NIST guidance, the brokerage gains:
- Clear visibility into cyber risk
- Practical, prioritized remediation steps
- A foundation for ongoing risk management and compliance efforts

This case study reflects a realistic, hands-on approach to cybersecurity risk assessment in a small business environment.

---

**References**
- NIST SP 800-30 – Guide for Conducting Risk Assessments  
- NIST SP 800-37 – Risk Management Framework  
- NIST Cybersecurity Framework (CSF) 2.0
