# PashuMitra — E-Governance Digital Service (Virtual Internship Project)

**PashuMitra** ("friend of animals") is a proposed ward-level stray animal grievance and care coordination platform, designed as a digital service for municipal corporations under India's Animal Birth Control (ABC) Rules, 2023. It was developed over a 4-week virtual Junior Web Developer internship, covering the full pre-build lifecycle of a civic-tech e-governance product: requirements planning, UI/UX design, QA strategy, and a pre-launch audit.

Rather than a generic "citizen complaint portal," PashuMitra is scoped around the real ABC Rules legal workflow (capture → sterilise → vaccinate → release/shelter), the actual stakeholders involved (citizens, ward officers, AWBI-recognised NGOs, veterinary teams), and the public-health urgency around dog-bite and rabies response — grounded in research on existing initiatives like Panvel's ABC Helpline, MCD's feeding-point registry, and DigiLocker/UMANG's identity patterns.

## Weekly deliverables

| Week | Focus | Document | Key artifacts |
|------|-------|----------|----------------|
| 1 | Planning & Requirements Analysis | [`PashuMitra_Week1_Project_Plan.docx`](PashuMitra_Week1_Project_Plan.docx) | `stakeholder_diagram.png`, `flow_diagram.png`, `wireframe_diagram.png` |
| 2 | Responsive Web Prototype Design | [`PashuMitra_Week2_Responsive_Prototype.docx`](PashuMitra_Week2_Responsive_Prototype.docx) | `sitemap_flow.png`, `responsive_homepage.png`, `form_mockup.png`, `grid_system.png` |
| 3 | QA & Testing Strategy | [`PashuMitra_Week3_QA_Testing_Strategy.docx`](PashuMitra_Week3_QA_Testing_Strategy.docx) | `test_pyramid.png`, `cicd_pipeline.png`, `risk_heatmap.png` |
| 4 | Performance, Accessibility & Security Audit | [`PashuMitra_Week4_Audit_Report.docx`](PashuMitra_Week4_Audit_Report.docx) | `web_vitals.png`, `lighthouse_scores.png`, `accessibility_pour.png`, `security_severity.png` |

Each `.docx` file is the full written report for that week (requirements, design rationale, test cases, audit findings). The `.png` files are the diagrams, wireframes, and charts referenced inside each report — included here separately so they're easy to preview directly on GitHub.

## Tech stack proposed for implementation

- **Frontend:** React Native (mobile) + React.js (web/admin), mobile-first responsive design
- **Backend:** Node.js + Express
- **Database:** PostgreSQL + PostGIS (for ward/geo-fence routing)
- **Testing:** Jest, React Testing Library, Cypress/Playwright, k6, OWASP ZAP, axe-core
- **Hosting:** MeitY GI Cloud ("MeghRaj") empanelled cloud, per standard Indian e-governance deployment norms

## Author

Bhoomi — B.Tech CSE, IILM University, Greater Noida
Virtual Internship — Junior Web Developer
