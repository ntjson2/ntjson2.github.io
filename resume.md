# Nathan Johnson
## Software Engineer — Applied AI & Data Systems

**Email:** ntjson@gmail.com | **LinkedIn:** linkedin.com/in/ntjson | **Location:** Missoula, MT

---

## Professional Summary

Software engineer with a B.S. in Computer Science – Software Engineering (University of Montana, 2026) and 20+ years shipping production software (2001–present). I build AI systems that extract, structure, grade, and operationalize real data — AI document-extraction APIs with calibrated quality scoring, multi-tenant field-data platforms, and honestly-evaluated machine-learning models.

As founder of **Quetzal Collective LLC**, I build **AssayChain** — a production AI extraction and grading API with an append-only provenance layer — alongside **MineFlowTrack** (a multi-tenant geological field-data platform, in development). I also design and evaluate my own ML models using spatial cross-validation and probability calibration, and I document exactly where they do and don't generalize.

I'm pragmatic about technology: measurable results over hype, production reliability over trend-chasing. Blockchain, provenance, and agent-payable APIs are tools I apply where they add real value — not the point in itself.

---

## Projects & Selected Work

### AssayChain — AI Document Extraction & Grading API (In Production)
- Designed and shipped the production extraction and grading pipeline that turns unstructured assay documents (lab certificates, scanned reports, drill logs) into structured JSON with an honest A–D quality rubric — structural validity, coverage, self-consistency (a second independent extraction pass), and physical-bounds cross-checking.
- Built the provenance layer — content-addressed storage plus an append-only attestation registry — so every extracted value is traceable to the source document it came from.
- Shipped an honest evaluation layer: 80% refund on Grade D and a manual-review flag on Grade C, rather than a black-box output.
- Built the benchmark harness that measures extraction accuracy with a confidence interval; validated on 57 USGS fire-assay samples and a 1937 state-survey fire-assay sheet.
- Added PII redaction and ±0.1° coordinate rounding so sensitive data never reaches a response.
- Exposed as a REST + MCP API usable from Claude, Cursor, VS Code, and the OpenAI Agents SDK; agent-payable via x402 (USDC on Base).
- Stack: Python, Node.js, React/Next.js, PostgreSQL, AWS, Google Cloud, IPFS, EAS attestation.

### MineFlowTrack — Multi-tenant Geological Field-Data Platform (In Development)
- Designed a Firestore multi-tenant data model with Google/Apple auth and an admin review/approval workflow.
- Built an IPFS + EAS attestation export pipeline for verified field-data runs.
- Modeled a sliding-scale profit-share and x402 revenue system integrated with AssayChain.

### Mineral Prospectivity Model — Honest ML Evaluation
- Trained a multi-label logistic regression model (scikit-learn) predicting metal occurrence from geology, using leave-one-state-out spatial cross-validation to avoid data leakage.
- Calibrated probabilities (sigmoid) and validated on a strict out-of-region hold-out; documented where the model does and does not generalize.
- Gold occurrence predicted at F1 0.87 in-region.

---

## Professional Experience

### Founder & Principal Engineer — Quetzal Collective LLC (AssayChain)
**May 2026 – Present | Missoula, MT**

- Designed and shipped the production extraction and grading pipeline that turns unstructured assay documents (lab certificates, scanned reports, drill logs) into structured JSON with an honest A–D quality rubric.
- Built the provenance layer — content-addressed storage plus an append-only attestation registry — so every extracted value is traceable to the source document it came from.
- Shipped a web API and an MCP server so both people and AI agents can call the pipeline.
- Built the benchmark harness that measures extraction accuracy with a confidence interval; validated on 57 USGS fire-assay samples and a 1937 state-survey fire-assay sheet.
- Architected the full-stack platform: React/Next.js frontend, Node.js backend for USGS data aggregation, PostgreSQL, Solidity contracts for on-chain verification, and a 14-endpoint API across Google Cloud Functions with multi-tier auth.
- Wired IPFS and EAS attestation so mineral data is immutable and verifiable on-chain — critical for AI systems that need trustworthy data sources.

### Lead Blockchain & Cloud Engineer (Contract)
**MineralFi | Nov 2023 – Present | Remote**

- Designed upgradeable ERC-20 and ERC-1155 contracts (OpenZeppelin) for the MINFI token, handling high-volume transactions.
- Built NFT systems for performance-based incentives and stakeholder trusts with milestone-based payouts.
- Engineered a real-time analytics stack (Next.js, GraphQL, DynamoDB) and integrated Uniswap V3 for automated liquidity (~30% capital-efficiency improvement).
- Established CI/CD with GitHub Actions and Hardhat contract testing, substantially reducing production issues.

### Independent Full-Stack Software Engineer
**Self-employed | Oct 2018 – Present | Missoula, MT**

- Contract engineering across the stack — Rust, Solidity, React/Next.js, Python/Django, Unity (C#/DOTS), Three.js, LAMP, and AWS (Ubuntu, LightSail, ECS).
- Delivered production web apps, blockchain systems, and real-time interactive systems for clients.
- Recent focus: applied AI and data systems (see AssayChain / Quetzal Collective LLC above).

### CTO & Co-founder — Numa Ridge (Lostone)
**Numa Ridge | May 2018 – Oct 2020 | Missoula, MT**

- Co-founded and led engineering for Lostone, a real-world, multiplayer treasure-hunting game that tied a game economy to public-lands exploration.
- Owned the full stack and the multiplayer networking architecture (Unity, Docker, AWS EC2) with secure asset sync, real-time communication, and scalable matchmaking.
- Hit several hard real-time milestones. (Side venture pursued while contracting; wound down in 2020.)

### Lead Software Developer
**Rocky Mountain Rehab | May 2006 – Nov 2018 | Missoula, MT**

- Led a statewide case-management platform (Angular, .NET Core, MySQL) for disability services, employment counseling, and independent-living coordination.
- Mentored an 8-person engineering team; introduced DevOps practices, automated testing, and CI/CD, increasing delivery velocity ~25%.
- Migrated legacy monolithic systems to a microservices architecture with API-first design, improving resilience and maintainability.

### Software Developer
**USIS | May 2004 – Sep 2005 | Greater Billings Area**

- Full-stack software development delivering enterprise web applications.

### Web Developer
**Versatile Productions Inc | Aug 2001 – Aug 2003 | Carbondale, CO**

- Built client-facing websites and web applications.

---

## Skills & Technologies

### AI, ML & Data
Python (scikit-learn, pandas), LLM APIs (OpenAI, Anthropic), AI agents, prompt engineering, RAG systems, semantic search, MCP, workflow automation, data extraction & normalization, model evaluation & calibration (spatial CV, OOD validation)

### Languages & Frontend
TypeScript, JavaScript, Python, Solidity, C#, Dart, Rust, PHP, SQL | React, Next.js, React Native, Flutter, Tailwind CSS, Three.js, Unity (C#/DOTS)

### Backend & Databases
Node.js, Express, Django, FastAPI, REST/GraphQL APIs | PostgreSQL, MySQL, MongoDB, DynamoDB, Firestore, Firebase, Redis

### Cloud & DevOps
AWS (Lambda, EC2, RDS, S3, DynamoDB, API Gateway, LightSail, ECS), Firebase, Google Cloud, Docker, GitHub Actions, CI/CD, LAMP

### Blockchain & Web3 (supporting capability)
Solidity, Ethereum/Polygon, ERC-20/721/1155, OpenZeppelin, Hardhat, Foundry, Uniswap, IPFS, EAS attestation, x402 protocol

### Testing & Quality
Jest, Vitest, Playwright, E2E testing, contract auditing, static analysis, security reviews

---

## Education

**B.S., Computer Science – Software Engineering**
University of Montana | May 2026

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
