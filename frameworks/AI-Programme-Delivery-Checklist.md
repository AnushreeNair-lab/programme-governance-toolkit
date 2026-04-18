# 🤖 AI Programme Delivery Checklist

> **Programme Governance Toolkit**
> Created by **Anushree Nair** | Programme Manager | [LinkedIn](https://www.linkedin.com/feed/)
> ⚠️ If you use or adapt this checklist, please credit Anushree Nair and reach out on LinkedIn.

---

## 📌 Purpose

This checklist provides governance gates for AI and technology programme delivery. It ensures that at every phase of delivery — from initiation through to live operation — the right checks, approvals, and safeguards are in place.

Use this alongside the **RAID Log** and **Risk Escalation Framework** to manage AI-specific risks consistently across your programme.

---

## 🏗️ Programme Context

| Field | Detail |
|---|---|
| Programme Name | [PROGRAMME NAME] |
| Programme Manager | Anushree Nair |
| AI / Data Lead | [NAME] |
| Version | v1.0 |
| Last Updated | [DATE] |
| Applies To | All AI and data workstreams |

---

## 📖 How to Use This Checklist

- Work through each phase **in sequence** — do not proceed to the next phase until all mandatory items are complete
- Items marked 🔴 **MANDATORY** must be completed and signed off before the phase gate closes
- Items marked 🟡 **RECOMMENDED** are best practice — document why if skipped
- Items marked 🔵 **OPTIONAL** apply depending on programme context
- Record the **Owner** and **Completion Date** for every item
- Raise any incomplete mandatory items as a **HIGH risk** in the RAID Log immediately

---

## Phase Gate Summary

| Phase | Gate Name | Approver |
|---|---|---|
| Phase 1 | Initiation Gate | Programme Sponsor |
| Phase 2 | Design Gate | Programme Director |
| Phase 3 | Build Gate | Programme Manager |
| Phase 4 | Testing Gate | Programme Manager + Legal |
| Phase 5 | Deployment Gate | Programme Sponsor + SteerCo |
| Phase 6 | Live Operations Gate | Programme Manager |

---

## ✅ Phase 1 — Initiation & Discovery

> *Establish the foundations before any AI development begins.*

### 1.1 Business Case & Objectives

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 1.1.1 | AI use case clearly defined with measurable business outcomes | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.1.2 | Business case approved by Programme Sponsor | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.1.3 | Success metrics and KPIs defined and agreed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.1.4 | Alternative non-AI solutions considered and documented | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.1.5 | Expected ROI and benefits quantified | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 1.2 Stakeholder & Team Readiness

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 1.2.1 | Key stakeholders identified and RACI matrix completed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.2.2 | AI / Data Lead appointed with clear accountability | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.2.3 | Programme team skills gap assessed against AI delivery needs | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.2.4 | Training plan in place for skills gaps identified | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.2.5 | Business sponsor actively engaged and committed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.2.6 | End user representatives identified for requirements and UAT | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 1.3 Ethical & Regulatory Assessment

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 1.3.1 | Initial AI ethics assessment completed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.3.2 | Applicable AI regulations identified (EU AI Act, sector-specific) | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.3.3 | Data privacy impact assessment (DPIA) initiated | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.3.4 | Legal and compliance team engaged | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.3.5 | AI risk classification completed (high / limited / minimal risk) | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 1.3.6 | Human oversight requirements defined | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 🔒 Phase 1 Gate — Initiation Sign-Off

| Sign-Off | Name | Date | Signature |
|---|---|---|---|
| Programme Sponsor | | | |
| Programme Manager | Anushree Nair | | |

---

## ✅ Phase 2 — Data & Design

> *Validate data readiness and design the AI solution before building begins.*

### 2.1 Data Readiness

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 2.1.1 | All required data sources identified and documented | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.1.2 | Data quality assessment completed for all source datasets | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.1.3 | Data quality threshold defined and agreed (e.g. min 95% completeness) | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.1.4 | Data lineage documented — source to model input | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.1.5 | Data access permissions and controls confirmed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.1.6 | Data retention and deletion policy confirmed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.1.7 | Training, validation, and test dataset split defined | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.1.8 | Data bias assessment completed — representative datasets confirmed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.1.9 | Synthetic data usage documented if applicable | 🔵 OPTIONAL | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 2.2 Solution Design

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 2.2.1 | AI model type and approach selected and documented | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.2.2 | Model selection rationale documented | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.2.3 | Build vs buy vs partner decision made and approved | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.2.4 | Technical architecture designed and peer reviewed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.2.5 | Infrastructure and compute requirements confirmed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.2.6 | Integration points with existing systems mapped | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.2.7 | Model explainability approach defined | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.2.8 | Fallback and human override process designed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 2.3 Governance & Compliance Design

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 2.3.1 | DPIA completed and approved by Legal | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.3.2 | Model governance framework defined | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.3.3 | Audit trail requirements defined and designed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.3.4 | AI ethics review completed for solution design | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 2.3.5 | Vendor AI governance requirements reviewed if third party | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 🔒 Phase 2 Gate — Design Sign-Off

| Sign-Off | Name | Date | Signature |
|---|---|---|---|
| Programme Director | | | |
| Technical Lead | | | |
| Legal & Compliance | | | |
| Programme Manager | Anushree Nair | | |

---

## ✅ Phase 3 — Build & Development

> *Develop the AI model and supporting infrastructure with quality controls in place.*

### 3.1 Development Standards

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 3.1.1 | Development environment set up and access controls in place | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.1.2 | Code versioning and repository structure established | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.1.3 | Coding standards and peer review process agreed | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.1.4 | Model versioning strategy defined | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.1.5 | Feature engineering documented and reviewed | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 3.2 Model Development

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 3.2.1 | Baseline model trained and performance benchmarked | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.2.2 | Model accuracy meets agreed minimum threshold | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.2.3 | Model bias and fairness evaluation completed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.2.4 | Model explainability outputs reviewed and documented | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.2.5 | Overfitting and underfitting checks completed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.2.6 | Model performance validated on holdout test dataset | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.2.7 | Edge cases and failure modes identified and tested | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.2.8 | Model card or equivalent documentation completed | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 3.3 Infrastructure & Security

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 3.3.1 | Cloud / on-premise infrastructure provisioned and tested | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.3.2 | Security review of AI pipeline completed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.3.3 | Data encryption at rest and in transit confirmed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.3.4 | Access controls and role-based permissions implemented | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 3.3.5 | Monitoring and alerting infrastructure set up | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 🔒 Phase 3 Gate — Build Sign-Off

| Sign-Off | Name | Date | Signature |
|---|---|---|---|
| Technical Lead / Architect | | | |
| AI / Data Lead | | | |
| Programme Manager | Anushree Nair | | |

---

## ✅ Phase 4 — Testing & Validation

> *Rigorously test the AI solution before it touches real users.*

### 4.1 Technical Testing

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 4.1.1 | Unit testing completed with agreed pass rate | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.1.2 | Integration testing completed — all system interfaces verified | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.1.3 | Performance and load testing completed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.1.4 | Security penetration testing completed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.1.5 | Regression testing completed after any fixes | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.1.6 | Disaster recovery and failover tested | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 4.2 AI-Specific Validation

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 4.2.1 | Model performance validated against agreed KPIs | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.2.2 | Bias and fairness re-evaluated on production-representative data | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.2.3 | Model output explainability reviewed by business stakeholders | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.2.4 | Adversarial testing / red team exercise completed | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.2.5 | Human override and fallback process tested end-to-end | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.2.6 | Model drift detection mechanism tested | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 4.3 User Acceptance Testing (UAT)

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 4.3.1 | UAT environment mirrors production environment | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.3.2 | UAT test scripts reviewed and approved by business | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.3.3 | Business users trained ahead of UAT | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.3.4 | UAT completed with agreed pass rate achieved | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.3.5 | All critical UAT defects resolved before go-live | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 4.3.6 | UAT sign-off obtained from business owner | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 🔒 Phase 4 Gate — Testing Sign-Off

| Sign-Off | Name | Date | Signature |
|---|---|---|---|
| Technical Lead | | | |
| Business / Product Owner | | | |
| Legal & Compliance | | | |
| Programme Manager | Anushree Nair | | |

---

## ✅ Phase 5 — Deployment & Go-Live

> *Deploy safely with clear rollback options and stakeholder communication.*

### 5.1 Go-Live Readiness

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 5.1.1 | Go-live readiness assessment completed and approved | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.1.2 | Deployment plan documented and approved | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.1.3 | Rollback plan documented and tested | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.1.4 | Hypercare support plan in place for go-live period | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.1.5 | Go-live communications sent to all stakeholders | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.1.6 | Service desk and support team briefed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.1.7 | All training completed for end users | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 5.2 Compliance & Governance at Go-Live

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 5.2.1 | Final legal and compliance sign-off obtained | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.2.2 | Data governance sign-off confirmed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.2.3 | AI model registry entry created / updated | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.2.4 | Incident response plan for AI failures documented | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 5.2.5 | Post go-live monitoring schedule confirmed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 🔒 Phase 5 Gate — Deployment Sign-Off

| Sign-Off | Name | Date | Signature |
|---|---|---|---|
| Programme Sponsor | | | |
| Steering Committee Chair | | | |
| Technical Lead | | | |
| Legal & Compliance | | | |
| Programme Manager | Anushree Nair | | |

---

## ✅ Phase 6 — Live Operations & Continuous Governance

> *Maintain governance standards after go-live — AI systems need ongoing oversight.*

### 6.1 Model Monitoring

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 6.1.1 | Model performance monitored against KPIs weekly | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.1.2 | Model drift detection active and alerts configured | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.1.3 | Bias and fairness monitoring in place | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.1.4 | Data pipeline health monitored | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.1.5 | Model retraining schedule defined and agreed | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.1.6 | Incident log maintained for all AI-related issues | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 6.2 Ongoing Governance

| # | Item | Priority | Owner | Status | Date |
|---|---|---|---|---|---|
| 6.2.1 | Monthly AI governance review scheduled | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.2.2 | Regulatory changes monitored and assessed | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.2.3 | User feedback mechanism in place and reviewed | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.2.4 | Annual ethics and compliance review scheduled | 🔴 MANDATORY | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.2.5 | Model decommissioning plan documented | 🔵 OPTIONAL | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |
| 6.2.6 | Lessons learned documented and shared | 🟡 RECOMMENDED | [Owner] | [ ] Not Started / [ ] In Progress / [ ] Complete | [DATE] |

### 🔒 Phase 6 Gate — Live Operations Sign-Off

| Sign-Off | Name | Date | Signature |
|---|---|---|---|
| Programme Manager | Anushree Nair | | |
| AI / Data Lead | | | |

---

## 📊 Checklist Completion Tracker

| Phase | Total Items | Mandatory Items | Complete | Incomplete | % Done |
|---|---|---|---|---|---|
| Phase 1 — Initiation | 16 | 12 | [#] | [#] | [%] |
| Phase 2 — Data & Design | 22 | 18 | [#] | [#] | [%] |
| Phase 3 — Build | 18 | 14 | [#] | [#] | [%] |
| Phase 4 — Testing | 17 | 13 | [#] | [#] | [%] |
| Phase 5 — Deployment | 12 | 11 | [#] | [#] | [%] |
| Phase 6 — Live Operations | 12 | 9 | [#] | [#] | [%] |
| **TOTAL** | **97** | **77** | | | |

---

## 📎 Related Artefacts

| Artefact | Location |
|---|---|
| RAID Log | [`/raid/RAID-Log.xlsx`](../raid/RAID-Log.xlsx) |
| Risk Escalation Framework | [`/frameworks/Risk-Escalation-Framework.md`](./Risk-Escalation-Framework.md) |
| Sprint Reporting Dashboard | [`/reporting/Sprint-Reporting-Dashboard.xlsx`](../reporting/Sprint-Reporting-Dashboard.xlsx) |
| Stakeholder RACI Matrix | [`/people/Stakeholder-RACI-Matrix.md`](../people/Stakeholder-RACI-Matrix.md) |

---

*Created by **Anushree Nair** | Programme Manager | [LinkedIn](https://www.linkedin.com/feed/)*
*⚠️ Please credit the author if you use or adapt this checklist.*
