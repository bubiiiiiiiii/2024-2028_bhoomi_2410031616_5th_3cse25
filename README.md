# PashuMitra — E-Governance Digital Service (Virtual Internship Project)

**PashuMitra** ("friend of animals") is a proposed ward-level stray animal grievance and care coordination platform, designed as a digital service for municipal corporations under India's Animal Birth Control (ABC) Rules, 2023. It was developed over a 4-week virtual Junior Web Developer internship, covering the full pre-build lifecycle of a civic-tech e-governance product: requirements planning, UI/UX design, QA strategy, and a pre-launch audit — plus a working front-end prototype built to demonstrate the design in real code.

Rather than a generic "citizen complaint portal," PashuMitra is scoped around the real ABC Rules legal workflow (capture → sterilise → vaccinate → release/shelter), the actual stakeholders involved (citizens, ward officers, AWBI-recognised NGOs, veterinary teams), and the public-health urgency around dog-bite and rabies response — grounded in research on existing initiatives like Panvel's ABC Helpline, MCD's feeding-point registry, and DigiLocker/UMANG's identity patterns.

## In this repository

| File | What it is |
|------|------------|
| [`PashuMitra_Internship_Completion_Report.docx`](PashuMitra_Internship_Completion_Report.pdf) | Full internship report — objectives, week-by-week summary, skills gained, challenges, and conclusion |
| [`PashuMitra_Internship_Summary.pptx`](PashuMitra_Internship_Summary.pdf) | Presentation summarising the project across all four weeks |
| [`index.html`](index.html) | **Working prototype** — a functional citizen portal (report a case, track status, feeder registry, live dashboard). Open it directly in a browser, or view it live via GitHub Pages if enabled |
| [`Completion_Certificate.pdf`](completion_certificate.pdf) | Internship completion certificate |

## Project background

The project was carried out in four phases:

1. **Planning & Requirements Analysis** — stakeholder personas, functional/non-functional requirements, risk analysis
2. **Responsive Web Prototype Design** — site map, high-fidelity mockups across breakpoints, accessibility-first UI
3. **QA & Testing Strategy** — test pyramid, 7 detailed test cases, CI/CD pipeline, risk heatmap
4. **Performance, Accessibility & Security Audit** — Core Web Vitals, WCAG 2.1 AA compliance, OWASP-based findings

Full detail on each phase is documented in the completion report above.

## Tech stack proposed for implementation

- **Frontend:** React Native (mobile) + React.js (web/admin), mobile-first responsive design
- **Backend:** Node.js + Express
- **Database:** PostgreSQL + PostGIS (for ward/geo-fence routing)
- **Testing:** Jest, React Testing Library, Cypress/Playwright, k6, OWASP ZAP, axe-core
- **Hosting:** MeitY GI Cloud ("MeghRaj") empanelled cloud, per standard Indian e-governance deployment norms

## Author

Bhoomi — B.Tech CSE, IILM University, Greater Noida
Virtual Internship — Junior Web Developer
