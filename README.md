# Smart Parking System — BA Portfolio

> A professional Business Analysis portfolio project demonstrating end-to-end BA practice: requirements engineering, process modelling, systems design, and a working Python prototype.

---

## Project Overview

Urban parking management is a significant operational and economic challenge for municipalities and private operators. This project delivers a complete BA engagement for a **Smart Parking System** — a technology-enabled solution that replaces manual parking operations with real-time space tracking, automated entry/exit, and data-driven reporting.

This is a solo professional rebuild of a group academic project, restructured as a real-world consulting deliverable.

**Industry:** Smart Cities / Urban Mobility  
**Engagement type:** Greenfield system implementation  
**Methodology:** Agile (with BPMN process modelling and UML use case modelling)

---

## Business Problem

Manual parking operations across urban areas suffer from:

- No real-time visibility into space availability
- High labour costs for manual ticketing and enforcement
- Revenue leakage through unpaid parking and human error
- Poor user experience driving traffic congestion as drivers circle for spaces
- No data for capacity planning or demand forecasting

**Estimated impact:** A 500-space urban car park loses an average of 18–22% potential revenue annually due to these inefficiencies.

---

## Solution Scope

The Smart Parking System addresses these problems through:

1. Real-time space availability tracking via sensor integration
2. Automated vehicle entry and exit with barrier control
3. Digital payment processing (cash, card, mobile)
4. Management dashboard with occupancy and revenue reporting
5. Driver-facing availability display (signage and mobile)

---

## Repository Structure

```
smart-parking-system-ba/
│
├── README.md                          ← This file
│
├── docs/
│   ├── phase-01-business-context/
│   │   ├── business-context.docx      ← Problem statement, objectives, scope
│   │   └── stakeholder-register.docx  ← All stakeholders with analysis
│   │
│   ├── phase-02-requirements/
│   │   ├── requirements-document.docx
│   │   └── user-stories.docx
│   │
│   ├── phase-03-process-models/
│   │   ├── as-is-process.png
│   │   ├── to-be-process.png
│   │   └── gap-analysis.docx
│   │
│   ├── phase-04-use-cases/
│   │   ├── use-case-diagram.png
│   │   └── use-case-descriptions.docx
│   │
│   ├── phase-05-data-design/
│   │   ├── erd-diagram.png
│   │   └── data-dictionary.docx
│   │
│   ├── phase-06-prototype/
│   │   └── (see /prototype folder)
│   │
│   ├── phase-07-testing/
│   │   ├── test-cases.docx
│   │   └── traceability-matrix.xlsx
│   │
│   └── phase-08-presentation/
│       └── executive-summary.pdf
│
├── prototype/
│   ├── main.py                        ← Entry point
│   ├── database.py                    ← SQLite setup and queries
│   ├── parking.py                     ← Core business logic
│   ├── reports.py                     ← Reporting module
│   ├── parking.db                     ← Auto-generated SQLite database
│   └── requirements.txt
│
└── diagrams/
    └── (source files for all diagrams)
```

---

## Project Phases

| Phase | Deliverable | Status |
|-------|-------------|--------|
| 01 — Business Context | Problem statement, stakeholder register | ✅ Complete |
| 02 — Requirements | User stories, MoSCoW prioritisation | ✅ Complete |
| 03 — Process Models | AS-IS & TO-BE BPMN diagrams | ✅ Planned |
| 04 — Use Cases | Use case diagram & descriptions | 🔲 Planned |
| 05 — Data Design | ERD & data dictionary | 🔲 Planned |
| 06 — Prototype | Python CLI application | 🔲 Planned |
| 07 — Testing | Test cases & RTM | 🔲 Planned |
| 08 — Presentation | Executive summary | 🔲 Planned |

---

## Key Skills Demonstrated

- Business requirements elicitation and documentation
- MoSCoW prioritisation and stakeholder management
- BPMN process modelling (AS-IS and TO-BE)
- UML use case modelling
- Entity-Relationship data modelling
- Agile user story writing with acceptance criteria
- Requirements traceability
- Python prototype development (SQLite, CLI)

---

## About This Project

**Author:** urya Umashankar  
**Background:** Bachelors of Information Systems  
**Contact:** umashankarsurya1@gmail.com

> This project was independently developed as a professional portfolio piece. It is based on a real-world problem domain explored during academic study, rebuilt from scratch as a solo consulting-grade deliverable.
