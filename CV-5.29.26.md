# **Nathan Johnson**

**Software Engineer — Applied AI & Data Systems**
Missoula, MT | [ntjson@gmail.com](mailto:ntjson@gmail.com) | [linkedin.com/in/ntjson](https://www.linkedin.com/in/ntjson/) | [Portfolio Website](https://ntjson2.github.io/resume.html)

### **Professional Summary**

Software engineer with a B.S. in Computer Science – Software Engineering (University of Montana, 2026) and 20+ years of experience shipping production-grade software. I build applied AI and data systems: AI document-extraction pipelines with calibrated quality scoring, multi-tenant field-data platforms, and rigorously-validated machine-learning models. I work as a bridge between technical execution and business goals, and I measure success by operational outcomes rather than technology for its own sake.

### **Core Expertise**

* **Applied AI & Machine Learning:** Document extraction and normalization, quality-graded AI outputs, LLM API integration, RAG systems, MCP integrations, model evaluation and calibration (spatial cross-validation, out-of-domain validation).
* **Full-Stack & Cloud Architecture:** React/Next.js, Node.js/Python, AWS and Google Cloud/Firebase, REST/GraphQL APIs, CI/CD automation.
* **Data Engineering:** Data pipelines, schema design, provenance and audit trails, real-time state, multi-tenant data modeling.
* **Web3 & Provenance (supporting capability):** Solidity, EAS attestation, IPFS, and x402 agent-payable infrastructure — applied where it adds real value.

---

### **Projects & Selected Work**

#### **AssayChain — AI Document Extraction & Grading API** *(In Production)*

* Built an AI pipeline that converts unstructured assay reports (PDF, image, CSV, text) into structured, quality-graded JSON using an A–D rubric (structural validity, coverage, self-consistency via a second extraction pass, physical-bounds cross-check).
* Shipped an honest evaluation layer: 80% refund on Grade D, manual-review flag on Grade C, PII redaction, and ±0.1° coordinate rounding.
* Exposed as a REST + MCP API for Claude, Cursor, VS Code, and the OpenAI Agents SDK; agent-payable via x402 (USDC on Base).

#### **MineFlowTrack — Multi-tenant Geological Field-Data Platform** *(In Development)*

* Designed a Firestore multi-tenant data model with Google/Apple auth and an admin review/approval workflow.
* Built an IPFS + EAS attestation export pipeline for verified field-data runs and a sliding-scale profit-share + x402 revenue model integrated with AssayChain.

#### **Mineral Prospectivity Model — Honest ML Evaluation**

* Multi-label logistic regression (scikit-learn) predicting metal occurrence; leave-one-state-out spatial cross-validation; sigmoid calibration with documented out-of-region limits (gold F1 0.87 in-region).

---

### **Professional Experience**

#### **Lead AI & Software Engineer (Contract)**

**AssayChain** • Jan 2024 – Present | *Remote*

* Built the AI extraction and grading pipeline that structures unstructured assay reports into graded JSON with an A–D quality rubric and self-consistency cross-checks.
* Architected the full-stack platform: React frontend, Node.js backend for USGS data aggregation, Solidity contracts for on-chain verification, and a 14-endpoint API across Google Cloud Functions with multi-tier auth.
* Wired IPFS and EAS attestation so mineral data is immutable and verifiable on-chain; structured mineral-processing data for machine-readable agent/LLM consumption.

#### **Lead Blockchain & Cloud Engineer (Contract)**

**MineralFi** • Jul 2023 – Present | *Remote*

* Designed upgradeable ERC-20 and ERC-1155 contracts (OpenZeppelin) for the MINFI token; built milestone-based NFT incentive systems.
* Engineered a real-time analytics stack (Next.js, GraphQL, DynamoDB); integrated Uniswap V3 (~30% capital-efficiency improvement); established CI/CD with GitHub Actions and Hardhat testing.

#### **Lead Software Engineer**

**Rocky Mountain Rehab** • Jun 2006 – Nov 2018 | *Missoula, MT*

* Led a statewide case-management platform (Angular, .NET Core, MySQL); mentored an 8-person team and introduced DevOps practices, increasing delivery velocity ~25%.
* Migrated legacy monolithic systems to an API-first microservices architecture.

#### **Full-Stack Developer (Contract)**

**Quetzal Collective LLC** • Jan 2020 – Jul 2023 | *Missoula, MT*

* Built and deployed serverless backends across AWS and Firebase; integrated OpenAI models into production applications and added Web3 features to real products.

#### **Game & Systems Developer (Contract)**

**Numa Ridge LLC** • Nov 2018 – Jan 2020 | *Remote*

* Architected a multiplayer backend (Unity, Docker, AWS EC2) with secure asset sync, real-time communication, and scalable matchmaking.

---

### **Skills & Technologies**

* **AI, ML & Data:** Python (scikit-learn, pandas), LLM APIs (OpenAI, Anthropic), AI agents, prompt engineering, RAG, MCP, workflow automation, data extraction, model evaluation & calibration
* **Languages & Frontend:** TypeScript, JavaScript, Python, Solidity, C#, Rust, SQL, Dart | React, Next.js, React Native, Flutter, Tailwind CSS
* **Backend & Databases:** Node.js, Express, Django, FastAPI | PostgreSQL, MySQL, MongoDB, DynamoDB, Firestore, Firebase, Redis
* **Cloud & DevOps:** AWS, GCP, Firebase, Docker, GitHub Actions, CI/CD
* **Web3 & Provenance:** Solidity, ERC-20/721/1155, OpenZeppelin, Hardhat, Foundry, IPFS, EAS attestation, x402

---

### **Education & Certifications**

* **B.S., Computer Science – Software Engineering** – University of Montana (May 2026)
* **A.A., Programming & Application Development** – Missoula College (2023)
* **Certifications:** AWS Academy Cloud Foundations | Google Developer Training: Firebase Web Advanced
