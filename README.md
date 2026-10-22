# MindfulAI Labs — AI Governance, Risk and Compliance Assessment Portfolio

**Maxine Jones | GRC, IT Risk and Compliance | October 2026**

MindfulAI Labs is a **fictional AI-enabled organization used for a simulated GRC assessment portfolio**. This repository documents a connected set of control assessments, governance registers, and a consolidated findings and remediation process. It demonstrates how an analyst can assess control design and documented operating scenarios, preserve evidence limitations, identify gaps, and communicate risk and corrective-action priorities.

The project is intended for hiring managers and recruiters evaluating skills relevant to **GRC Analyst, IT Risk Analyst, IT Auditor, Compliance Analyst, and Cyber Risk Analyst** roles. It is not a report on an actual organization or an independent assurance engagement.

## Program Scope

| Workstream | Portfolio deliverables |
|---|---|
| Control assessment and documentation | Ten Word artifacts covering data validation, access management, change management, MFA, vulnerability management, privacy, backup and recovery, logging, compliance planning, and third-party risk |
| Risk and control registers | Eleven assets, eleven risks, and eleven controls represented in JSON exports |
| Findings and remediation management | Consolidated Excel tracker with 29 trackable records, 30 remediation actions, and 83 evidence requests |
| Governance and monitoring context | Policy, risk-appetite, and key risk indicator (KRI) JSON exports |

## Repository Structure

```text
MindfulAI-Labs-AI-GRC/
├── README.md
├── 01-Control-Assessments/        10 DOCX artifacts
├── 02-Risk-and-Remediation/       1 XLSX tracker
├── 03-GRC-Registers/             3 JSON exports
└── 04-Governance-and-Metrics/     3 JSON exports
```

## Document Index

### Control Assessments

| ID | Deliverable | Assessment focus |
|---|---|---|
| MAL-CHK-001 | [AI Training Data Validation Checklist](01-Control-Assessments/MAL-CHK-001_AI_Training_Data_Validation_Checklist.docx) | Training-data validation, completeness, and documented review. |
| MAL-ACR-002 | [User Access Review Worksheet](01-Control-Assessments/MAL-ACR-002_User_Access_Review_Worksheet.docx) | Role changes, excess permissions, and deprovisioning exceptions. |
| MAL-CTW-003 | [Change Management Control Test Worksheet](01-Control-Assessments/MAL-CTW-003_Change_Management_Control_Test_Worksheet.docx) | Change documentation, approval checks, and rollback-plan observations. |
| MAL-STD-004 | [Privileged Access and MFA Security Standard](01-Control-Assessments/MAL-STD-004_Privileged_Access_and_MFA_Security_Standard.docx) | Privileged-access governance and authentication requirements. |
| MAL-VMA-005 | [Vulnerability Management Control Assessment](01-Control-Assessments/MAL-VMA-005_Vulnerability_Management_Control_Assessment.docx) | Scan coverage, remediation timeliness, and testing gaps. |
| MAL-PIA-006 | [AI Privacy Impact Assessment](01-Control-Assessments/MAL-PIA-006_AI_Privacy_Impact_Assessment.docx) | Data minimization, privacy safeguards, and retention considerations. |
| MAL-BRT-007 | [Backup and Recovery Test Record](01-Control-Assessments/MAL-BRT-007_Backup_and_Recovery_Test_Record.docx) | Recovery documentation and RTO/RPO recording considerations. |
| MAL-LMA-008 | [Security Logging and Monitoring Control Assessment](01-Control-Assessments/MAL-LMA-008_Security_Logging_and_Monitoring_Control_Assessment.docx) | Log-source coverage and alert-triage practices. |
| MAL-CAP-009 | [Compliance Assessment Plan and Evidence Request](01-Control-Assessments/MAL-CAP-009_Compliance_Assessment_Plan_and_Evidence_Request.docx) | Assessment planning, evidence requests, and open planning questions. |
| MAL-VRA-010 | [Third-Party AI Vendor Risk Assessment](01-Control-Assessments/MAL-VRA-010_Third-Party_AI_Vendor_Risk_Assessment.docx) | Vendor onboarding, risk tiering, and oversight deficiencies. |

### Consolidated Findings and Remediation

**[MAL-FRT-001 — GRC Findings and Remediation Tracker](02-Risk-and-Remediation/MAL-FRT-001_GRC_Findings_and_Remediation_Tracker.xlsx)**

The workbook connects observations and documented deficiencies to their originating assessment artifacts. Its eight worksheets provide a dashboard, findings log, remediation actions, evidence requests, source reconciliation, identifier crosswalk, and data dictionary, along with a project disclosure.

| Tracker measure | Documented total |
|---|---:|
| Confirmed findings within simulated scenarios | 12 |
| Observations | 13 |
| Planning gaps | 4 |
| Total trackable records | 29 |
| Remediation action records | 30 |
| Evidence requirements | 83 |
| Independently validated closures | 0 |

Evidence requests are **not automatically treated as deficiencies**. Reported remediation within a simulated scenario is distinguished from independently verified closure.

### Source Registers and Governance Exports

| Source | Purpose |
|---|---|
| [MindfulAI_Labs_Assets.json](03-GRC-Registers/MindfulAI_Labs_Assets.json) | Asset inventory and business context |
| [MindfulAI_Labs_Risks.json](03-GRC-Registers/MindfulAI_Labs_Risks.json) | Risk register and scoring inputs |
| [MindfulAI_Labs_Controls.json](03-GRC-Registers/MindfulAI_Labs_Controls.json) | Control inventory and effectiveness context |
| [MindfulAI_Labs_Policies.json](04-Governance-and-Metrics/MindfulAI_Labs_Policies.json) | Policy governance records |
| [MindfulAI_Labs_Risk_Appetite_Statements.json](04-Governance-and-Metrics/MindfulAI_Labs_Risk_Appetite_Statements.json) | Risk appetite context |
| [MindfulAI_Labs_KRIs.json](04-Governance-and-Metrics/MindfulAI_Labs_KRIs.json) | Key risk indicator definitions and monitoring context |

## Frameworks and Standards Referenced

| Framework or standard | Application in this portfolio |
|---|---|
| ISO/IEC 27001 | Control references for data governance, recovery, compliance, and review processes |
| NIST Cybersecurity Framework | Access management, vulnerability monitoring, and risk-oriented control context |
| SOC 2 Trust Services Criteria | Change management and third-party risk assessment references |
| CIS Controls v8 | Privileged access and security logging practices |
| GDPR principles | Privacy impact assessment and data minimization considerations |

Framework references guide the simulated assessment documentation. They **do not imply certification, regulatory compliance, or an external audit opinion**.

## Skills Demonstrated

**Risk and governance:** Maintaining risk, asset, control, policy, and KRI registers; identifying missing coverage; and documenting governance considerations.

**Control assurance:** Structuring assessment procedures, recording observations, preserving original control ratings, and distinguishing control effectiveness from evidence availability.

**Issue management:** Tracking findings, accountable owners, source IDs, remediation actions, target dates, evidence requirements, and closure criteria.

**Audit-ready reporting:** Source traceability, documented assumptions and limitations, consistent classifications, and a consolidated management dashboard.

**Professional judgment:** Avoiding unsupported residual-risk calculations, invented approvals, fabricated evidence, and premature remediation closure.

## Program Status and Next Steps

| Component | Status |
|---|---|
| Ten control and governance assessment artifacts | Included |
| Six JSON register and governance exports | Included |
| MAL-FRT-001 findings and remediation workbook | Included |
| Independent peer-review assessment for Control 11 | Planned; not included |
| Integrated AI risk assessment report | Planned; not included |
| Multi-framework control mapping matrix | Planned; not included |
| Executive GRC assessment report | Planned; not included |

## Simulation and Evidence Disclosure

All organizations, scenarios, assessment results, observations, and remediation statuses in this repository are **simulated educational portfolio materials**. They do not document access to live production systems, actual client data, independently obtained audit evidence, or completed external assurance procedures. Where evidence was requested but not supplied, that limitation is retained rather than treated as proof of a control failure.

## Platform Credit and Attribution

**GRC Practice Lab was created by John Bommeraveni Joseph.**

- [GRC Practice Lab](https://johnbjoseph-cybersec.github.io/grc-lab.html)
- [Creator's GitHub profile](https://github.com/Johnbjoseph-cybersec)

The GRC Practice Lab is a third-party educational platform used as part of this portfolio exercise. **I did not develop, own, or create the lab platform.** Credit for its software, interface, and learning environment belongs to its creator. The assessment write-ups, register-based analysis, and assembled MindfulAI Labs portfolio presented here are my practice deliverables. This repository is not affiliated with or endorsed by the platform creator.

## About the Author

**Maxine Jones** holds an M.S. in Business Cybersecurity Management from West Virginia University and a B.S. in Computer Science from Chicago State University, and has earned CompTIA Security+. Her work includes risk assessment, compliance documentation, cybersecurity analysis, audit-oriented reporting, and cross-functional project coordination.

- **GitHub:** https://github.com/Mkjones10
- **LinkedIn:** https://www.linkedin.com/in/maxinekjones/
- **Portfolio website:** https://maxine-jones-portfolio.netlify.app/

**Last updated:** October 2026
