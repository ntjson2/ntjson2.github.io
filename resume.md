# Nathan Johnson
## Principal Forward Deployed Engineer | Applied AI, MCP & Enterprise Data Integration

**Email:** ntjson@gmail.com | **LinkedIn:** linkedin.com/in/ntjson | **Location:** Missoula, MT

---

## Professional Summary

**Principal Software Engineer and former CTO** with 20+ years of production experience, focused on **Forward Deployed AI Engineering**. Works directly with domain teams to define schemas and success criteria, then builds and deploys production LLM pipelines, custom MCP servers, and calibrated ML systems. Experienced in customer discovery, rapid prototyping, evaluation harnesses, guardrails, schema normalization, and multi-tenant cloud (AWS/GCP) deployments.

---

## Projects & Selected Work

### AssayChain — AI Document Extraction & Grading API (In Production)
- Designed and shipped the production extraction and grading pipeline that turns unstructured assay documents (lab certificates, scanned reports, drill logs) into structured JSON with an honest A–D quality rubric — structural validity, coverage, self-consistency (a second independent extraction pass), and physical-bounds cross-checking. I recently submitted this project to NSF SBIR proposal for further development and evaluation.
- Built the provenance layer — content-addressed storage plus an append-only attestation registry — so every extracted value is traceable to the source document it came from.
- Shipped an honest evaluation layer: 80% refund on Grade D and a manual-review flag on Grade C, rather than a black-box output.
- Built the benchmark harness that measures extraction accuracy with a confidence interval; validated on 57 USGS fire-assay samples and a 1937 state-survey fire-assay sheet.
- Connects domain-specific field documents to automated LLM extraction, reducing manual review while keeping confidence scores auditable.
- Added PII redaction and ±0.1° coordinate rounding so sensitive data never reaches a response.
- Exposed as a REST + MCP API usable from Claude, Cursor, VS Code, and the OpenAI Agents SDK; agent-payable via x402 (USDC on Base).
- Stack: Python, Node.js, React/Next.js, PostgreSQL, AWS, Google Cloud, IPFS, EAS attestation.

### MineFlowTrack — Multi-tenant Geological Field-Data Platform (In Development)
- Designed a Firestore multi-tenant data model and non-technical field-user workflows, with Google/Apple auth and an admin review/approval workflow.
- Built an IPFS + EAS attestation export pipeline for verified field-data runs.
- Modeled a sliding-scale profit-share and x402 revenue system integrated with AssayChain.

### Mineral Prospectivity Model — Honest ML Evaluation
- Trained a multi-label logistic regression model (scikit-learn) predicting metal occurrence from geology, using leave-one-state-out spatial cross-validation to avoid data leakage.
- Calibrated probabilities (sigmoid) and validated on a strict out-of-region hold-out; documented where the model does and does not generalize.
- Gold occurrence predicted at F1 0.87 in-region.

---

## Professional Experience

### Principal Applied AI Engineer (Founder) — Quetzal Collective LLC (AssayChain)
**May 2026 – Present | Missoula, MT**

- Partnered directly with critical-minerals domain experts through customer discovery to define extraction schemas, then shipped a production LLM pipeline turning unstructured assay reports and drill logs into schema-normalized JSON.
- Built custom Model Context Protocol (MCP) servers and agentic infrastructure so autonomous AI agents can securely query, ingest, and process graded data.
- Designed evaluation harnesses with confidence intervals and spatial cross-validation; added guardrails (PII redaction, Grade C manual-review flags, Grade D refunds) and documented where the model does and does not generalize.
- Standardized multi-tenant infrastructure across Node.js, Python, PostgreSQL, AWS and GCP, with append-only provenance/audit layers and agent-payable (x402) protocols.

### Lead Blockchain & Cloud Engineer (Contract)
**MineralFi | Nov 2023 – Present | Remote**

- Designed upgradeable ERC-20 and ERC-1155 contracts (OpenZeppelin) for the MINFI token, handling high-volume transactions.
- Built NFT systems for performance-based incentives and stakeholder trusts with milestone-based payouts.
- Engineered a real-time analytics stack (Next.js, GraphQL, DynamoDB) and integrated Uniswap V3 for automated liquidity (~30% capital-efficiency improvement).
- Established CI/CD with GitHub Actions and Hardhat contract testing, substantially reducing production issues.

### Principal Consulting & Forward Deployed Engineer
**Self-employed | Oct 2018 – Present | Missoula, MT**

- Led customer discovery and rapid prototyping for ambiguous client problems, delivering working software in short iterations.
- Shipped full-stack solutions into client cloud environments (AWS/GCP) with production handoff — Rust, React/Next.js, Python/Django, Unity (C#/DOTS), Three.js, and LAMP.
- Recent focus: embedded applied-AI deployments — LLM extraction pipelines, RAG, custom MCP integrations, and evaluation harnesses (see AssayChain above).

### CTO & Co-founder — Numa Ridge (Lostone)
**Numa Ridge | May 2018 – Oct 2020 | Missoula, MT**

- Co-founded and led engineering for Lostone, a real-world, multiplayer treasure-hunting game that tied a game economy to public-lands exploration.
- Owned the full stack and the multiplayer networking architecture (Unity, Docker, AWS EC2) with secure asset sync, real-time communication, and scalable matchmaking.
- Hit several hard real-time milestones. (Side venture pursued while contracting; wound down in 2020.)

### Lead Software Developer
**Rocky Mountain Rehab | May 2006 – Nov 2018 | Missoula, MT**

- Led a statewide case-management platform (Angular, .NET Core, MySQL), aligning non-technical stakeholders across disability services, employment counseling, and independent-living programs.
- Mentored an 8-person engineering team; introduced DevOps, automated testing, and CI/CD, increasing delivery velocity ~25%.
- Migrated legacy monolithic systems to an API-first microservices architecture — directly applicable to integrating modern AI with aging enterprise software.

---

## Skills & Technologies

### AI, ML & Data
Python (scikit-learn, pandas), LLM APIs (OpenAI, Anthropic, OpenRouter), AI agents, prompt engineering, RAG systems, semantic search, MCP, workflow automation, data extraction & normalization, model evaluation & calibration (spatial CV, OOD validation)

### Forward Deployed & Delivery
Customer discovery, rapid prototyping, production handoff, evaluation harnesses & guardrails, schema normalization, multi-tenant cloud (AWS/GCP), MCP server development

### Languages & Frontend
TypeScript, JavaScript, Python, Solidity, C#, Dart, Rust, PHP, SQL | React, Next.js, React Native, Flutter, Tailwind CSS, Three.js, Unity (C#/DOTS)

### Backend & Databases
Node.js, Express, Django, FastAPI, REST/GraphQL APIs | PostgreSQL, MySQL, MongoDB, DynamoDB, Firestore, Firebase, Redis

### Cloud & DevOps
AWS (Lambda, EC2, RDS, S3, DynamoDB, API Gateway, LightSail, ECS), Firebase, Google Cloud, Docker, GitHub Actions, CI/CD, LAMP

### Data Provenance, Auditability & Agent Protocols (MCP / x402)
Append-only provenance, EAS attestation, IPFS content addressing, MCP servers, x402 agent-payable APIs; Solidity / ERC-20/721/1155 where it adds value

### Testing & Quality
Jest, Vitest, Playwright, E2E testing, contract auditing, static analysis, security reviews

---

## Education

**B.S. in Computer Science – Software Engineering**
University of Montana (Graduated 2026) | Missoula, MT

- Core Focus: Advanced Data Structures, Algorithmic Analysis, Machine Learning Systems, Database Architecture.

**A.A., Programming & Application Development**
Missoula College | 2023

---

## Certifications & Professional Training

- AWS Academy Cloud Foundations — AWS Academy Graduate
- Firebase Web Advanced — Google Developer Training
- Advanced OpenAI API Integration — Self-Directed Study
- IPFS & Distributed Systems Architecture — Self-Directed Study

---

*© 2026 Nathan Johnson. All Rights Reserved.*
