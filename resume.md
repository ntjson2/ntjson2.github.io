# Nathan Johnson
## Software Engineer — Applied AI & Data Systems

**Email:** ntjson@gmail.com | **LinkedIn:** linkedin.com/in/ntjson | **Location:** Missoula, MT

---

## Professional Summary

Software engineer with a B.S. in Computer Science – Software Engineering (University of Montana, 2026) and 20+ years shipping production software. I build AI systems that extract, structure, grade, and operationalize real data — AI document-extraction APIs with calibrated quality scoring, multi-tenant field-data platforms, and honestly-evaluated machine-learning models.

Recent work includes **AssayChain** (a production AI extraction and grading API with on-chain provenance) and **MineFlowTrack** (a multi-tenant geological field-data platform, in development). I also design and evaluate my own ML models using spatial cross-validation and probability calibration, and I document exactly where they do and don't generalize.

I'm pragmatic about technology: measurable results over hype, production reliability over trend-chasing. Blockchain, provenance, and agent-payable APIs are tools I apply where they add real value — not the point in itself.

---

## Projects & Selected Work

### AssayChain — AI Document Extraction & Grading API (In Production)
- Built an AI pipeline that turns unstructured assay reports (PDF, image, CSV, text) into structured, quality-graded JSON using an A–D scoring rubric — structural validity, coverage, self-consistency (a second independent extraction pass), and physical-bounds cross-checking.
- Shipped an honest evaluation layer: 80% refund on Grade D and a manual-review flag on Grade C, rather than a black-box output.
- Added PII redaction and ±0.1° coordinate rounding so sensitive data never reaches a response.
- Exposed as a REST + MCP API usable from Claude, Cursor, VS Code, and the OpenAI Agents SDK; agent-payable via x402 (USDC on Base).

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

### Lead AI & Software Engineer (Contract)
**AssayChain** | Jan 2024 – Present | Remote

- Built the AI extraction and grading pipeline that structures unstructured assay reports into graded JSON with an A–D quality rubric and self-consistency cross-checks.
- Architected the full-stack platform: React frontend, Node.js backend for USGS data aggregation, Solidity contracts for on-chain verification, and a 14-endpoint API across Google Cloud Functions with multi-tier auth.
- Wired IPFS and EAS attestation so mineral data is immutable and verifiable on-chain — critical for AI systems that need trustworthy data sources.
- Structured mineral-processing data (gravity separation, ultrasound cavitation, recovery rates) so it's machine-readable for agents and LLMs.

### Lead Blockchain & Cloud Engineer (Contract)
**MineralFi** | Jul 2023 – Present | Remote

- Designed upgradeable ERC-20 and ERC-1155 contracts (OpenZeppelin) for the MINFI token, handling high-volume transactions.
- Built NFT systems for performance-based incentives and stakeholder trusts with milestone-based payouts.
- Engineered a real-time analytics stack (Next.js, GraphQL, DynamoDB) and integrated Uniswap V3 for automated liquidity (~30% capital-efficiency improvement).
- Established CI/CD with GitHub Actions and Hardhat contract testing, substantially reducing production issues.

### Lead Software Engineer
**Rocky Mountain Rehab** | Jun 2006 – Nov 2018 | Missoula, MT

- Led a statewide case-management platform (Angular, .NET Core, MySQL) for disability services, employment counseling, and independent-living coordination.
- Mentored an 8-person engineering team; introduced DevOps practices, automated testing, and CI/CD, increasing delivery velocity ~25%.
- Migrated legacy monolithic systems to a microservices architecture with API-first design, improving resilience and maintainability.

### Full-Stack Developer (Contract)
**Quetzal Collective LLC** | Jan 2020 – Jul 2023 | Missoula, MT

- Built and deployed serverless backends across AWS and Firebase with caching layers for scalable, cost-efficient traffic handling.
- Integrated OpenAI models into production applications and added Web3 features (wallet auth, NFTs on Polygon, marketplace) to real products.

### Game & Systems Developer (Contract)
**Numa Ridge LLC** | Nov 2018 – Jan 2020 | Remote

- Architected a multiplayer backend (Unity, Docker, AWS EC2) with secure asset sync, real-time communication, and scalable matchmaking.

---

## Skills & Technologies

### AI, ML & Data
Python (scikit-learn, pandas), LLM APIs (OpenAI, Anthropic), AI agents, prompt engineering, RAG systems, semantic search, MCP, workflow automation, data extraction & normalization, model evaluation & calibration (spatial CV, OOD validation)

### Languages & Frontend
TypeScript, JavaScript, Python, Solidity, C#, Dart, Rust, PHP, SQL | React, Next.js, React Native, Flutter, Tailwind CSS, Three.js

### Backend & Databases
Node.js, Express, Django, FastAPI, REST/GraphQL APIs | PostgreSQL, MySQL, MongoDB, DynamoDB, Firestore, Firebase, Redis

### Cloud & DevOps
AWS (Lambda, EC2, RDS, S3, DynamoDB, API Gateway), Firebase, Google Cloud, Docker, GitHub Actions, CI/CD

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
