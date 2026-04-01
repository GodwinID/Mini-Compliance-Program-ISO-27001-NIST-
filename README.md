# NovaCloud-AI-Solutions-Information-Security-Compliance-Program
Build a Mini Compliance Program (ISO 27001 / NIST)

> A mini compliance program aligned to **ISO 27001:2022** and **NIST SP 800-53 Rev. 5**, built as a practical GRC lab exercise simulating a real-world compliance officer workflow.

---

## 📋 Overview

This repository contains the foundational compliance documentation for **NovaCloud AI Solutions**, a fictional AI SaaS company. It covers asset inventory, control mapping, maturity assessment, gap analysis, and an executive compliance summary — all production-ready in format and structure.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| [novacloud_compliance.xlsx](https://github.com/user-attachments/files/26252219/novacloud_compliance.xlsx) | Full compliance workbook (3 tabs: Asset Inventory, Control Matrix, Maturity Dashboard) |
| [novacloud_compliance_summary.docx](https://github.com/user-attachments/files/26252247/novacloud_compliance_summary.docx) | 1-page executive summary — scope, objectives, priority gaps, next steps |

---

## 📊 Compliance Workbook — Tab Breakdown

### 1. Asset Inventory
15 IT assets catalogued and classified:
- Servers (AWS EC2, ML cluster, databases)
- Endpoints (developer laptops, admin workstations)
- SaaS tools (GitHub, Slack, Google Workspace, Jira, Datadog)
- Cloud infrastructure (AWS, Tailscale VPN, CI/CD pipelines)

Each asset includes: Owner, CIA Rating (Confidentiality / Integrity / Availability), Classification tier, and Location.

### 2. Control Matrix
20 controls across key security domains, dual-mapped to:
- **ISO 27001:2022 Annex A** control references
- **NIST SP 800-53 Rev. 5** control families

Each control row includes:
- Current implementation status (Implemented / In Progress / Partial / Planned)
- Maturity score (1–5 scale)
- Control owner
- Evidence gaps
- Remediation action with target timeline

### 3. Maturity Dashboard
Live formula-driven summary showing:
- Control counts and percentages by status
- Average maturity score across all controls
- Color-coded maturity legend

---

## 📄 Compliance Summary Document

The Word document covers:
1. **Organization Overview** — company profile and regulatory landscape
2. **ISMS Scope Statement** — what's in and out of scope
3. **Compliance Objectives** — ISO 27001, NIST, SOC 2, GDPR targets and timelines
4. **Control Coverage Snapshot** — high-level status breakdown
5. **Priority Gaps** — CRITICAL and HIGH items requiring immediate action
6. **Recommended Next Steps** — roadmap toward certification readiness

---

## 🎯 Frameworks Covered

| Framework | Purpose |
|-----------|---------|
| ISO/IEC 27001:2022 | ISMS certification target (Annex A controls) |
| NIST SP 800-53 Rev. 5 | Internal control baseline (moderate impact) |
| NIST SP 800-61 Rev. 2 | Incident response alignment |
| SOC 2 (Trust Services Criteria) | Customer assurance target |
| GDPR | EU market readiness |

---

## 📈 Current Maturity Snapshot

| Status | Count | % |
|--------|-------|---|
| ✅ Implemented | 6 | 30% |
| 🔄 In Progress | 2 | 10% |
| ⚠️ Partial | 7 | 35% |
| 🔴 Planned | 5 | 25% |

**Average Maturity Score: ~2.5 / 5**

---

## 🚨 Critical Priority Gaps

| Control | Issue | Due |
|---------|-------|-----|
| CTL-008 | Privileged accounts without MFA | Q1 2025 |
| CTL-014 | No Incident Response Plan documented | Q3 2025 |
| CTL-013 | No vulnerability scanning SLA | Q2 2025 |
| CTL-015 | BCP/DRP not documented or tested | Q3 2025 |

---

## 🗺️ Roadmap

```
Q1 2025  →  Remediate CRITICAL gaps (PAM/MFA, IRP)
Q2 2025  →  Policy approvals, vuln mgmt, security training
Q3 2025  →  BCP/DRP, tabletop exercise, SSDLC rollout
Q4 2025  →  Vendor risk program, GDPR readiness
Q1 2026  →  ISO 27001 Stage 1 readiness assessment
Q3 2026  →  SOC 2 Type II audit
Q4 2026  →  ISO 27001 certification
```

---

## 🧰 How to Use This Project

1. **Download** the [novacloud_compliance.xlsx](https://github.com/user-attachments/files/26258271/novacloud_compliance.xlsx)
workbook and open in Excel or Google Sheets
2. **Update** the Control Matrix as you implement or test controls
3. **Track** maturity scores over time — aim for 4+ across all domains
4. **Use** the summary document as a template for board or customer reporting
5. **Extend** the control list by adding rows aligned to your target framework

---

## 📚 References

- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)
- [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
- [NIST SP 800-61 Rev. 2 — Incident Handling](https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final)
- [CIS Controls v8](https://www.cisecurity.org/controls/v8)
- [MITRE ATT&CK Enterprise](https://attack.mitre.org/)

---

## ⚠️ Disclaimer

This project is a **lab exercise** using a fictional company. It is intended for educational and training purposes. It does not constitute legal or compliance advice. Always consult a qualified GRC professional for real-world implementations.

---

* Built by Godwin Iduye | © 2025*

