# Selected engineering case studies

[Back to profile](README.md) · [Portfolio](https://mateusbonette.com.br) · [LinkedIn](https://www.linkedin.com/in/mateus-bonette/)

This page explains my professional work at a system-design and product-impact level. Client and commercial repositories are private. Figures below come from my professional experience and have not been independently audited as part of this README.

## 1. Junta Já Brasil — production AI for personal finance

**Role:** Co-founder · Software & AI Engineer (2026–present)

**Problem.** Financial administration involves repetitive entry, inconsistent statement formats, and a high cost of reviewing errors.

**My work.** I co-designed and implemented the product end-to-end: frontend, backend, databases, infrastructure, integrations and AI-assisted workflows.

- Created an OCR + Gemini/Vertex AI extraction pipeline for invoices and bank statements, with structured JSON, normalization, classification, deduplication and validation before persistence.
- Added deterministic financial rules and human-in-the-loop review for ambiguous outputs.
- Developed a WhatsApp AI assistant that uses tool calling and application APIs to retrieve actual account information rather than inventing balances.
- Built MCP integrations for Google Cloud and Cloudflare, as well as observability for token consumption, latency, costs, failures and model fallback.
- Worked with Python, FastAPI, SQLAlchemy, PostgreSQL, React, TypeScript, Docker, Cloud Run, Cloud SQL, GitHub Actions and CI/CD.

**Reported impact:** more than 100 users; over 1,000 processed invoices/statements; extraction and categorization accuracy above 90%. These are application-level claims from the supplied professional history, not a published benchmark.

**Engineering considerations:** privacy, validation, costs, idempotent persistence, human review, operational reliability and API-grounded responses.

## 2. Moontech — mobility data and reporting platform

**Role:** Full Stack Developer focused on Applied AI (2024–2026)

**Problem.** An urban-mobility organization depended on spreadsheets and manually prepared recurring reports.

**My work.** Led the platform's development for about a year, replacing manual spreadsheets with integrated data dashboards. Connected Python and Streamlit reporting to Node.js/Express APIs and PostgreSQL, and added a RAG assistant for organizing and querying business data.

**Reported impact:** generation of reports dropped from roughly 3–4 hours to about 1 minute; 20+ people used the platform.

**Engineering considerations:** data consistency, usability for non-technical employees, reproducibility and operational integration.

## 3. Moontech — industrial quality control and auditability

**Problem.** Quality records and batch traceability depended on manual processes.

**My work.** Implemented a responsive system using React, Node.js, Express and PostgreSQL, capturing evidence, nonconformities and batch traceability. Added a natural-language assistant combining RAG, tool calling, guardrails and parameterized SQL queries for auditable data retrieval.

**Reported impact:** used by 10 employees; the system was approved in an ISO 9001 audit.

**Engineering considerations:** traceability, explainability, structured access to verified data and process compliance.

## 4. byron.solutions — client-facing web applications

**Role:** Full Stack Developer (2020–2021)

Worked with the UNIFEI junior enterprise on websites, e-commerce, mobile applications and REST APIs for real clients.

- Created an online store with Mercado Pago for a business that previously sold through WhatsApp.
- Delivered a real-estate website with search optimization and responsive user journeys.
- Implemented React/TypeScript interfaces, Node.js APIs and Flutter mobile features.
- Participated in client discovery, scope definition, design, delivery and team planning.

These experiences informed my approach to turning business requirements into maintainable engineering solutions.

## Public work you can inspect

| Repository | Engineering emphasis |
|---|---|
| [FamilyMoney](https://github.com/mateus-bonette00/family-money) | Full-stack architecture, financial data, security and integrations |
| [OpenClaw Agents](https://github.com/mateus-bonette00/config-open-claw) | AI agents, messaging automation and operational workflows |
| [AI Control Center](https://github.com/mateus-bonette00/centro-controle-ias) | Local observability, scanning and backend/frontend boundaries |
| [FBA Automation](https://github.com/mateus-bonette00/fba-automation) | Practical automation, browser interaction and APIs |
| [CoinSight](https://github.com/mateus-bonette00/coinsight_tcc) | Applied ML, feature engineering and temporal evaluation |

**Contact:** [Portfolio](https://mateusbonette.com.br) · [LinkedIn](https://www.linkedin.com/in/mateus-bonette/) · [Email](mailto:mateus.bonette00@gmail.com)
