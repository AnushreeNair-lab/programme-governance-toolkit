# 🔺 Risk Escalation Framework

> **Programme Governance Toolkit**
> Created by **Anushree Nair** | Programme Manager | [LinkedIn](https://www.linkedin.com/feed/)
> ⚠️ If you use or adapt this framework, please credit Anushree Nair and reach out on LinkedIn.

---

## 📌 Purpose

This framework defines how risks are identified, scored, escalated, and resolved across the programme. It ensures that the right people are making decisions at the right level — and that nothing critical falls through the gaps.

Use this alongside the **RAID Log** to manage risks consistently across all workstreams.

---

## 🏗️ Programme Context

| Field | Detail |
|---|---|
| Programme Name | [PROGRAMME NAME] |
| Programme Manager | Anushree Nair |
| Version | v1.0 |
| Last Updated | [DATE] |
| Applies To | All workstreams and delivery teams |

---

## 1️⃣ Risk Scoring Matrix

Every risk is scored by multiplying **Likelihood** and **Impact** on a 1–5 scale.

> **Risk Score = Likelihood (1–5) × Impact (1–5)**

### Likelihood Scale

| Score | Level | Description |
|---|---|---|
| 1 | Rare | Very unlikely to occur — less than 10% probability |
| 2 | Unlikely | Could occur but not expected — 10–30% probability |
| 3 | Possible | Might occur under some circumstances — 30–50% probability |
| 4 | Likely | Will probably occur — 50–75% probability |
| 5 | Almost Certain | Expected to occur — greater than 75% probability |

### Impact Scale

| Score | Level | Description |
|---|---|---|
| 1 | Negligible | Minimal effect — no impact on programme timeline or budget |
| 2 | Minor | Small disruption — manageable within team without escalation |
| 3 | Moderate | Noticeable impact — may affect sprint goals or milestone dates |
| 4 | Major | Significant impact — delivery timeline, budget or quality at risk |
| 5 | Severe | Critical impact — programme objective or business case at risk |

### Risk Score → Rating Mapping

| Risk Score | Risk Rating | RAG Status | Action Required |
|---|---|---|---|
| 20 – 25 | 🔴 CRITICAL | RED | Immediate escalation to Programme Director / Sponsor |
| 12 – 19 | 🟠 HIGH | RED / AMBER | Escalate to Programme Manager — action plan within 48 hours |
| 6 – 11 | 🟡 MEDIUM | AMBER | Managed by Workstream Lead — reviewed weekly |
| 1 – 5 | 🟢 LOW | GREEN | Monitored by team — reviewed fortnightly |

---

## 2️⃣ Escalation Tiers

### Tier 1 — Team Level (LOW & MEDIUM risks)

**Who owns it:** Delivery Lead / Scrum Master
**Who is informed:** Programme Manager

| Risk Rating | Response Time | Actions |
|---|---|---|
| LOW | Fortnightly review | Log in RAID, assign owner, monitor |
| MEDIUM | Weekly review | Log in RAID, define mitigation, update at sprint review |

**Escalate to Tier 2 if:**
- A MEDIUM risk score increases to HIGH
- Mitigation actions are not effective after two review cycles
- The risk affects more than one workstream

---

### Tier 2 — Programme Level (HIGH risks)

**Who owns it:** Programme Manager (Anushree Nair)
**Who is informed:** Programme Director, relevant Workstream Leads

| Risk Rating | Response Time | Actions |
|---|---|---|
| HIGH | Within 48 hours of identification | Formal mitigation plan, owner assigned, tracked in RAID |

**Actions at this tier:**
- Risk formally documented in RAID Log with full details
- Mitigation plan drafted and approved within 48 hours
- Risk reviewed at every Programme Governance meeting
- Impact on programme plan assessed and communicated
- Contingency options identified

**Escalate to Tier 3 if:**
- A HIGH risk score increases to CRITICAL
- Mitigation requires budget or resource decisions beyond PM authority
- Risk has cross-programme or organisational impact

---

### Tier 3 — Steering Committee Level (CRITICAL risks)

**Who owns it:** Programme Sponsor / Steering Committee
**Who is informed:** All key stakeholders

| Risk Rating | Response Time | Actions |
|---|---|---|
| CRITICAL | Immediate — same day | Emergency escalation, SteerCo notified, contingency activated |

**Actions at this tier:**
- Programme Manager raises formal escalation note (see template below)
- SteerCo convened within 24–48 hours (emergency session if needed)
- Contingency plan activated or programme pause considered
- Decision and actions minuted and communicated to all stakeholders
- Risk owner at Sponsor / Director level

---

## 3️⃣ Escalation Decision Tree

```
Risk Identified
      │
      ▼
Score the Risk (Likelihood × Impact)
      │
      ├── Score 1–5  (LOW)    ──► Tier 1: Team manages | Fortnightly review
      │
      ├── Score 6–11 (MEDIUM) ──► Tier 1: Team manages | Weekly review
      │                              │
      │                              └── Not resolved after 2 cycles?
      │                                        │
      │                                        ▼
      ├── Score 12–19 (HIGH)  ──► Tier 2: Programme Manager | 48hr action plan
      │                              │
      │                              └── Mitigation insufficient or score rises?
      │                                        │
      │                                        ▼
      └── Score 20–25 (CRITICAL) ──► Tier 3: SteerCo | Immediate escalation
```

---

## 4️⃣ Risk Categories

Use these standard categories when logging risks in the RAID Log:

| Category | Examples |
|---|---|
| **Strategic** | Changing business priorities, programme objectives misaligned |
| **Technical** | Architecture failure, integration issues, technical debt |
| **Resource** | Key person dependency, skills gap, team capacity |
| **Vendor / External** | Third-party delays, SLA breaches, supplier failure |
| **Compliance** | Regulatory change, data privacy, legal risk |
| **Financial** | Budget overrun, funding withdrawal, cost escalation |
| **Operational** | Process failure, BAU impact, change fatigue |
| **AI-Specific** | Model bias, data quality, AI regulation, ethical risk |

---

## 5️⃣ Escalation Note Template

Use this template when escalating a HIGH or CRITICAL risk to the Programme Director or SteerCo.

---

**RISK ESCALATION NOTE**

| Field | Detail |
|---|---|
| Risk ID | [e.g. R-004] |
| Date of Escalation | [DATE] |
| Escalated By | Anushree Nair |
| Escalated To | [Name / Committee] |
| Risk Title | [Short description] |
| Risk Description | [Full description of the risk] |
| Current Score | Likelihood [X] × Impact [X] = Score [XX] |
| Risk Rating | [CRITICAL / HIGH] |
| RAG Status | [RED / AMBER] |
| Impact on Programme | [What happens if this risk materialises?] |
| Mitigation Attempted | [What has already been done?] |
| Decision Required | [What do you need from the escalation recipient?] |
| Options Available | Option 1: [description] / Option 2: [description] |
| Recommended Action | [Your recommendation] |
| Target Decision Date | [DATE] |

---

## 6️⃣ Risk Governance Rhythm

| Cadence | Activity | Owner | Forum |
|---|---|---|---|
| Daily | New risks logged in RAID as identified | All team members | — |
| Weekly | MEDIUM and HIGH risks reviewed and updated | Programme Manager | Programme team call |
| Fortnightly | LOW risks reviewed, RAID log maintained | Workstream Leads | Delivery sync |
| Monthly | Full RAID review — status, scoring, closures | Programme Manager | Programme Governance meeting |
| Ad hoc | CRITICAL risk escalation | Programme Manager | Emergency SteerCo |

---

## 7️⃣ Risk Closure Criteria

A risk can be closed in the RAID Log when **all** of the following are true:

- ✅ The risk event can no longer occur (window has passed)
- ✅ Mitigation actions have been fully implemented and verified
- ✅ The risk owner has formally confirmed closure
- ✅ The Programme Manager has reviewed and approved closure
- ✅ Any residual risk has been logged as a new, separate entry

---

## 📎 Related Artefacts

| Artefact | Location |
|---|---|
| RAID Log | [`/raid/RAID-Log.xlsx`](../raid/RAID-Log.xlsx) |
| Sprint Reporting Dashboard | [`/reporting/Sprint-Reporting-Dashboard.xlsx`](../reporting/Sprint-Reporting-Dashboard.xlsx) |
| AI Programme Delivery Checklist | [`/frameworks/AI-Programme-Delivery-Checklist.md`](./AI-Programme-Delivery-Checklist.md) |
| Stakeholder RACI Matrix | [`/people/Stakeholder-RACI-Matrix.md`](../people/Stakeholder-RACI-Matrix.md) |

---

*Created by **Anushree Nair** | Programme Manager | [LinkedIn](https://www.linkedin.com/feed/)*
*⚠️ Please credit the author if you use or adapt this framework.*
