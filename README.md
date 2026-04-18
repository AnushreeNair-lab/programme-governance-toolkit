# 📋 Programme Governance Toolkit

> A collection of reusable templates, frameworks, and artefacts for Programme Managers running hybrid delivery across AI and technology programmes.

---

## 🎯 Purpose

This toolkit provides ready-to-use governance artefacts designed for **medium-sized programmes** (3–5 teams, 10–50 people) running in a **hybrid Agile/Waterfall** environment. Whether you're managing an AI transformation, a technology platform programme, or a business change initiative, these templates give you a consistent, professional foundation from day one.

Each artefact is production-ready — simply clone the repo, adapt to your programme context, and go.

---

## 📁 Repository Structure

```
programme-governance-toolkit/
│
├── README.md                          ← You are here
│
├── raid/
│   └── RAID-Log.xlsx                  ← Risks, Assumptions, Issues, Dependencies tracker
│
├── reporting/
│   └── Sprint-Reporting-Dashboard.xlsx ← Sprint metrics and programme status dashboard
│
├── frameworks/
│   ├── Risk-Escalation-Framework.md   ← Risk tiers, escalation paths, decision matrix
│   └── AI-Programme-Delivery-Checklist.md ← AI-specific governance gates by delivery phase
│
├── people/
│   └── Stakeholder-RACI-Matrix.md     ← RACI template with roles and guidance
│
└── docs/
    └── how-to-use.md                  ← Detailed usage guide for each artefact
```

---

## 🗂️ Artefacts at a Glance

| Artefact | Format | Purpose | When to Use |
|----------|--------|---------|-------------|
| [RAID Log](./raid/RAID-Log.xlsx) | Excel | Track Risks, Assumptions, Issues, Dependencies | From programme initiation onwards |
| [Sprint Reporting Dashboard](./reporting/Sprint-Reporting-Dashboard.xlsx) | Excel | Sprint velocity, RAG status, burndown summary | Every sprint / reporting cycle |
| [Risk Escalation Framework](./frameworks/Risk-Escalation-Framework.md) | Markdown | Define escalation tiers and decision paths | Programme setup and risk reviews |
| [AI Programme Delivery Checklist](./frameworks/AI-Programme-Delivery-Checklist.md) | Markdown | AI-specific governance gates across delivery phases | AI / ML programme delivery |
| [Stakeholder RACI Matrix](./people/Stakeholder-RACI-Matrix.md) | Markdown | Map roles, responsibilities, accountability | Kick-off and team changes |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/programme-governance-toolkit.git
cd programme-governance-toolkit
```

### 2. Adapt to Your Programme

Each artefact includes placeholder fields marked with `[BRACKETS]` — replace these with your programme-specific details:

- `[PROGRAMME NAME]` — Your programme name
- `[DATE]` — Relevant dates
- `[OWNER]` — Named individual or role
- `[TEAM]` — Your team or workstream name

### 3. Choose Your Starting Point

| If you're... | Start with... |
|---|---|
| Just kicking off a new programme | RACI Matrix → RAID Log → Risk Escalation Framework |
| Mid-programme needing better governance | RAID Log → Sprint Reporting Dashboard |
| Running an AI or data programme | AI Delivery Checklist → RAID Log |
| Preparing for a governance review | Risk Escalation Framework → Sprint Reporting Dashboard |

---

## 📐 Design Principles

These templates are built around four core principles:

1. **Hybrid-ready** — Frameworks work whether your teams are running Scrum sprints, Kanban flows, or waterfall stages. No methodology lock-in.

2. **Scalable** — Designed for medium programmes (10–50 people) but can scale down for smaller workstreams or up for larger portfolios.

3. **Opinionated but flexible** — Sensible defaults are provided so you can get started immediately, but every field and category can be adapted.

4. **Documentation-first** — All frameworks are written in Markdown for full version control, pull request reviews, and GitHub rendering out of the box.

---

## 🤝 Contributing

Contributions, improvements, and issue reports are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-improvement`
3. Commit your changes: `git commit -m 'Add: improvement description'`
4. Push and open a Pull Request

Please keep templates generic enough to be reusable across programmes — avoid embedding organisation-specific content.

---

## 📄 Licence

This toolkit is released under the [MIT Licence](./LICENCE.md). You are free to use, adapt, and distribute these artefacts in your own programmes — commercial or otherwise.

---

## 👤 Author

Built and maintained by a Programme Manager with experience across AI, technology, and business transformation programmes.

---

*Last updated: 2025 | Contributions welcome*
