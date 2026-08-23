# PashuMitra — E-Governance Digital Service (Virtual Internship Project)

**PashuMitra** ("friend of animals") is a proposed ward-level stray animal grievance and care coordination platform, designed as a digital service for municipal corporations under India's Animal Birth Control (ABC) Rules, 2023. It was developed over a 4-week virtual Junior Web Developer internship, covering the full pre-build lifecycle of a civic-tech e-governance product: requirements planning, UI/UX design, QA strategy, and a pre-launch audit.

Rather than a generic "citizen complaint portal," PashuMitra is scoped around the real ABC Rules legal workflow (capture → sterilise → vaccinate → release/shelter), the actual stakeholders involved (citizens, ward officers, AWBI-recognised NGOs, veterinary teams), and the public-health urgency around dog-bite and rabies response — grounded in research on existing initiatives like Panvel's ABC Helpline, MCD's feeding-point registry, and DigiLocker/UMANG's identity patterns.

## Project structure

```
pashumitra-repo/
├── docs/       → Weekly deliverables (Word documents)
└── assets/     → Diagrams, wireframes, and charts referenced in each doc
    ├── week1/
    ├── week2/
    ├── week3/
    └── week4/
```

## Weekly deliverables

| Week | Focus | Document | Key artifacts |
|------|-------|----------|----------------|
| 1 | Planning & Requirements Analysis | [`docs/PashuMitra_Week1_Project_Plan.docx`](docs/PashuMitra_Week1_Project_Plan.docx) | Stakeholder ecosystem map, grievance lifecycle flowchart, low-fi wireframes, functional/non-functional requirements, risk analysis |
| 2 | Responsive Web Prototype Design | [`docs/PashuMitra_Week2_Responsive_Prototype.docx`](docs/PashuMitra_Week2_Responsive_Prototype.docx) | Site map & user flow, homepage mockups across 3 breakpoints, high-fidelity report form, fluid grid system, accessibility checklist |
| 3 | QA & Testing Strategy | [`docs/PashuMitra_Week3_QA_Testing_Strategy.docx`](docs/PashuMitra_Week3_QA_Testing_Strategy.docx) | Test pyramid, CI/CD pipeline, 7 detailed test cases, risk heatmap, defect severity framework |
| 4 | Performance, Accessibility & Security Audit | [`docs/PashuMitra_Week4_Audit_Report.docx`](docs/PashuMitra_Week4_Audit_Report.docx) | Core Web Vitals & Lighthouse scores, WCAG POUR compliance chart, OWASP-based security findings, prioritised (P0/P1/P2) fix roadmap |

## Tech stack proposed for implementation

- **Frontend:** React Native (mobile) + React.js (web/admin), mobile-first responsive design
- **Backend:** Node.js + Express
- **Database:** PostgreSQL + PostGIS (for ward/geo-fence routing)
- **Testing:** Jest, React Testing Library, Cypress/Playwright, k6, OWASP ZAP, axe-core
- **Hosting:** MeitY GI Cloud ("MeghRaj") empanelled cloud, per standard Indian e-governance deployment norms

## Author

Bhoomi — B.Tech CSE, IILM University, Greater Noida
Virtual Internship — Junior Web Developer
