# ISO/IEC 27001 ISMS Portfolio — Audit-Grade
### CloudRise Analytics SaaS Scenario

![ISO 27001](https://img.shields.io/badge/ISO%2FIEC-27001%3A2022-blue?style=flat-square&logo=shield&logoColor=white)
![NIST CSF](https://img.shields.io/badge/NIST-CSF%202.0-darkgreen?style=flat-square)
![SOC 2](https://img.shields.io/badge/SOC%202-Type%20II%20Mapped-orange?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

**Author:** Raya Rohith Yadav
**Discipline:** Cyber Security | GRC | Security Assurance | Internal Audit
**Portfolio Type:** ISO/IEC 27001:2022 ISMS documentation and internal audit execution

---

## Overview

This repository is an audit-grade ISO/IEC 27001:2022 ISMS portfolio built around a realistic fictional SaaS company, CloudRise Analytics, a cloud-based financial data platform handling sensitive customer data across multiple jurisdictions.

The portfolio is structured as a real assurance engagement, not a checklist exercise. Every control decision traces back to a risk, every implemented control maps to verifiable evidence, and every audit finding has a documented corrective action and closure proof.

**Full traceability chain:**

```
Risk Register → Statement of Applicability → Control Implementation
→ Evidence (EV-001..EV-015) → Internal Audit → Findings → CAPA → Follow-up Verification
```

---

## Repository Structure

```
ISO27001-ISMS-GRC-Portfolio/
│
├── 01_ISMS_Core/          Core ISMS documentation: scope, policy, risk method,
│                          objectives, access review, IR plan, supplier assessments
│
├── 02_Registers/          Risk register, Statement of Applicability (SoA),
│                          vulnerability log, supplier register, document register
│
├── 03_Audit_Pack/         Audit program, plan, checklist, evidence log,
│                          findings report, CAPA tracker, follow-up verification
│
├── 04_Evidence/           Screenshots and artefacts (EV-001 to EV-015)
│                          mapped to every implemented control
│
├── RECRUITER-ONE-PAGER.md Fast summary: what was built and what it proves
├── CASE-STUDY.md          End-to-end walkthrough: audit → findings → CAPA → closure
├── PORTFOLIO-MAP.md       ISO 27001 clauses mapped to exact artefacts and evidence
├── NIST-CSF-MAP.md        Cross-mapping to NIST Cybersecurity Framework 2.0
├── SOC2-MAP.md            Cross-mapping to SOC 2 Trust Service Criteria
└── healthcheck.py         Python script: validates artefact completeness
```

---

## Start Here: 10-Minute Reviewer Path

If you are a hiring manager or auditor, open these in order:

| Step | File | Purpose |
|---|---|---|
| 1 | `RECRUITER-ONE-PAGER.md` | Fast summary of what was built and what it proves |
| 2 | `CASE-STUDY.md` | Baseline audit, findings, CAPA, follow-up verification |
| 3 | `PORTFOLIO-MAP.md` | ISO clauses mapped to exact artefacts and evidence |
| 4 | `04_Evidence/EV-INDEX_Evidence_Index_v0.1_2026-02-07.csv` | Master evidence list (EV-001 to EV-015) |
| 5 | `03_Audit_Pack/AUD-005_Audit_Report_Findings_v0.1_2026-02-07.md` | Audit report and findings |
| 6 | `03_Audit_Pack/AUD-008_Followup_Audit_Report_v0.1_2026-02-07.md` | Follow-up verification and closure proof |
| 7 | `02_Registers/ISMS-005_SoA_v0.1_2026-02-07.csv` | Statement of Applicability: controls mapped to evidence |

---

## What This Portfolio Demonstrates

**ISO 27001 ISMS Implementation**
Scope definition, ISMS policy, risk assessment methodology, security objectives and metrics, documented information control procedure.

**Risk-Based Control Selection**
Risk register with asset identification, threat and vulnerability analysis, likelihood and impact scoring, risk treatment decisions, and SoA justification for each Annex A control.

**Internal Audit Execution**
Full audit programme and plan, clause-by-clause checklist, evidence log, findings report with nonconformity classification, and a follow-up audit confirming closure.

**Corrective Action Lifecycle**
CAPA procedure, tracker with root cause analysis, closure evidence, and independent verification. Every finding has a documented resolution.

**Operational Readiness Documentation**
Incident response plan and tabletop exercise record, backup and restore test record, supplier assessment (including GitHub as a critical supplier), vulnerability management procedure and log, access review, and security awareness training record.

**Evidence Discipline**
Every implemented control maps to a numbered evidence item (EV-001 to EV-015). No control is claimed without a corresponding artefact.

**Framework Cross-Mapping**
Controls are mapped to NIST CSF 2.0 functions and SOC 2 Trust Service Criteria, demonstrating transferability across compliance frameworks.

---

## Scenario: CloudRise Analytics

CloudRise Analytics is a fictional UK-based SaaS company providing cloud-hosted financial data analytics to enterprise customers. The ISMS scope covers the production environment, customer data processing pipeline, and supporting infrastructure. The scenario was chosen to reflect a realistic high-stakes environment where data protection, access control, and audit readiness are business-critical requirements.

---

## Tech Stack and Standards

| Category | Detail |
|---|---|
| Primary Standard | ISO/IEC 27001:2022 |
| Implementation Guidance | ISO/IEC 27002:2022 |
| Risk Methodology | ISO/IEC 27005, qualitative likelihood/impact matrix |
| Cross-Mappings | NIST CSF 2.0, SOC 2 Type II |
| Scripting | Python 3 (healthcheck.py: artefact validation) |
| Documentation Format | Markdown, CSV, XLSX |
| Version Control | Git, GitHub |

---

## Author

**Raya Rohith Yadav**
MSc Cyber Security, University of Edinburgh (2023-2025)
BEng Electronics and Communication Engineering, Anna University (2019-2023)

[LinkedIn](https://www.linkedin.com/in/raya-rohith-yadav-b71206204/) | [GitHub](https://github.com/RayaRohith)

---

*This is a simulation portfolio built for professional development and demonstration purposes. CloudRise Analytics is a fictional organisation. No real customer data or production systems are involved.*
