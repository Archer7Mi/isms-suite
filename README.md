# ISMS Template Suite — ISO/IEC 27001:2022

## Overview

**What is this?** A complete, production-grade **Information Security Management System (ISMS) template suite** for Stark Industries aligned with **ISO/IEC 27001:2022** and **Kenya Data Protection Act 2019 (KDPA 2019)**.

**The problem it solves:** SMEs and mid-market organisations struggle to build compliant ISMS programmes from scratch — policy writing is time-consuming, risk methodologies aren't standardised, and regulatory mapping is fragmented. This suite provides 10 battle-tested templates covering governance, risk, operations, and audit with all controls pre-mapped.

**Who it's for:** Information Security Officers, Compliance Managers, and internal audit teams in Kenya and East Africa who need to implement or audit a formal ISMS. Also useful for MSSPs (Managed Security Services Providers) onboarding new clients.

**How to use it:** Start with the Information Security Policy (01), inventory your assets (04), assess risks (02), confirm control applicability (03), then operationalise the remaining policies (05–09). Run your first internal audit using the checklist (10).

All 10 documents are built against the **2022 revision** (93 Annex A controls, not the legacy 2013 version), with explicit obligations mapped to **Kenya DPA 2019** throughout.

---

## Repository Structure

```
isms-suite/
├── README.md
├── 01-information-security-policy.docx
├── 02-risk-assessment-methodology.docx
├── 03-statement-of-applicability.xlsx
├── 04-asset-register.xlsx
├── 05-incident-response-plan.docx
├── 06-access-control-policy.docx
├── 07-business-continuity-plan.docx
├── 08-supplier-security-policy.docx
├── 09-security-awareness-training-policy.docx
└── 10-internal-audit-checklist.xlsx
```

---

## Document Index

| # | Document | Format | Annex A Controls | Description |
|---|---|---|---|---|
| 01 | [Information Security Policy](./01-information-security-policy.docx) | DOCX | 5.1, 5.2 | Master ISMS policy; scope, objectives, roles, classification, legal obligations |
| 02 | [Risk Assessment & Treatment Methodology](./02-risk-assessment-methodology.docx) | DOCX | 6.1.2, 6.1.3, 8.2, 8.3 | Asset-based risk assessment; 5×5 matrix; risk appetite; sample risk register |
| 03 | [Statement of Applicability](./03-statement-of-applicability.xlsx) | XLSX | 6.1.3d | All 93 Annex A controls; inclusion/exclusion status; justifications; implementation status |
| 04 | [Asset Register](./04-asset-register.xlsx) | XLSX | 5.9, 5.10 | 25 sample assets across 5 categories; classification colour-coding; dropdown validation |
| 05 | [Incident Response Plan](./05-incident-response-plan.docx) | DOCX | 5.24–5.28 | PICERL framework; P1–P4 severity; KDPA 72-hour breach notification; ODPC template |
| 06 | [Access Control Policy](./06-access-control-policy.docx) | DOCX | 5.15–5.18 | Least privilege; MFA requirements; PAM; NIST SP 800-63B password policy; access reviews |
| 07 | [Business Continuity Plan](./07-business-continuity-plan.docx) | DOCX | 5.29, 5.30, 8.8 | RTO/RPO per system; 3-2-1 backup; alternate processing; crisis comms; test schedule |
| 08 | [Supplier Security Policy](./08-supplier-security-policy.docx) | DOCX | 5.19–5.22 | 3-tier supplier risk classification; onboarding assessment; contractual clauses; monitoring |
| 09 | [Security Awareness Training Policy](./09-security-awareness-training-policy.docx) | DOCX | 6.3, 7.2, 7.3 | Training matrix; phishing simulation; completion tracking; consequence framework |
| 10 | [Internal Audit Checklist](./10-internal-audit-checklist.xlsx) | XLSX | 9.2 | Clauses 4–10 checklist; 50+ audit questions; NC tracker with live COUNTIF summaries |

---

## ISO/IEC 27001:2022 Alignment

### Why 2022 and not 2013?

ISO/IEC 27001 was revised in **October 2022**. Key changes from the 2013 version:

- Annex A reduced from **114 controls to 93 controls**, reorganised into **4 themes** (Organisational, People, Physical, Technological) replacing the previous 14 domains
- **11 new controls** introduced, including: Threat Intelligence (5.7), Information Security for Cloud Services (5.23), ICT Readiness for Business Continuity (5.30), Data Masking (8.11), Data Leakage Prevention (8.12), Web Filtering (8.23), and Secure Coding (8.28)
- Clause structure (4–10) remains the same; organisations certified to 2013 had until **October 2025** to transition

Every document in this suite references the **2022 control numbering and structure**. The Statement of Applicability (Document 03) covers all 93 controls.

### ISMS Clause Coverage

| Clause | Topic | Documents |
|---|---|---|
| 4 | Context of the Organisation | 01, 03 |
| 5 | Leadership | 01 |
| 6 | Planning (Risk Assessment) | 02, 03 |
| 7 | Support (Training, Awareness) | 09 |
| 8 | Operation | 02, 04, 05, 06, 07, 08 |
| 9 | Performance Evaluation (Audit) | 10 |
| 10 | Improvement | 10 |

---

## Kenya Data Protection Act 2019 — Key Obligations Addressed

The KDPA 2019 applies to any person or organisation that collects, processes, or stores personal data in Kenya. This suite addresses the following obligations throughout:

| KDPA Obligation | Section | Document(s) |
|---|---|---|
| Implement appropriate technical and organisational security measures | s.41 | 01, 02, 06 |
| Report personal data breaches to the ODPC within **72 hours** | s.43 | 05 |
| Maintain a register of processing activities | s.19 | 04 |
| Ensure data processor (supplier) agreements are in place | s.37 | 08 |
| Provide staff with data protection awareness | s.41 | 09 |
| Conduct Data Protection Impact Assessments for high-risk processing | s.31 | 02 |

> **Note:** This suite does not replace formal legal advice. Organisations should engage a qualified Data Protection Officer (DPO) and register with the **Office of the Data Protection Commissioner (ODPC)** at [odpc.go.ke](https://www.odpc.go.ke).

---

## How to Use This Suite

### For ISMS Implementation

1. **Start with Document 01** — have senior management review, customise, and sign the Information Security Policy. Replace `[MSSP Client Name]` with your organisation name throughout.
2. **Complete Document 04** (Asset Register) — inventory your actual assets before conducting a risk assessment.
3. **Run Document 02** (Risk Assessment) — identify risks against your real assets; populate the Risk Register.
4. **Use Document 03** (SoA) — review each of the 93 controls; update Included/Excluded status and implementation evidence based on your actual environment.
5. **Operationalise the remaining policies** (05–09) — customise RTOs/RPOs, supplier names, training platforms, and contact details to reflect your organisation.
6. **Use Document 10** (Audit Checklist) to conduct your first internal audit once the ISMS is operational.

### For Audit Purposes

Document 10 maps directly to ISO/IEC 27001:2022 Clauses 4–10 with evidence requirements per question. The NC Tracker sheet auto-counts Major NCs, Minor NCs, and Observations using live formulas.

### Document ID Convention

All documents follow the naming convention: `MS-ISMS-[TYPE]-[NNN]`

| Prefix | Type |
|---|---|
| POL | Policy |
| RISK | Risk Assessment |
| SOA | Statement of Applicability |
| ASSET | Asset Register |
| IRP | Incident Response Plan |
| ACP | Access Control Policy |
| BCP | Business Continuity Plan |
| SUP | Supplier Security Policy |
| TRAIN | Training Policy |
| AUD | Audit Checklist |

---

## About the Author

**Michael Ted**
ISO/IEC 27001:2022 Lead Auditor — Cert ID: `yy8da45yxt` (April 2026)
Security Analyst | Michael's Security — Managed Security Services
GitHub: [@Archer7Mi](https://github.com/Archer7Mi)

This suite was built as a portfolio artifact demonstrating practical ISO 27001:2022 Lead Auditor capability — every document authored from scratch against the standard, not generated from generic templates.

---

## Licence

This repository is licensed under the [MIT License](LICENSE). You are free to use, adapt, and distribute these templates with attribution.

---

*Prepared by Michael's Security • ISO/IEC 27001:2022 • Kenya Data Protection Act 2019*
