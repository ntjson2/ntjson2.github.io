# **Nathan Johnson**

**Principal Software Engineer | Applied AI & Data Systems Architect**
Missoula, MT | [ntjson@gmail.com](mailto:ntjson@gmail.com) | [linkedin.com/in/ntjson](https://www.linkedin.com/in/ntjson/) | [Portfolio Website](https://ntjson2.github.io/resume.html)

### **Professional Summary**

Pragmatic, systems-focused engineer combining 20+ years of production full-stack experience with a rigorous, modern B.S. in Computer Science. Specializing in applied AI infrastructure, secure data extraction pipelines, and agentic orchestration via Model Context Protocol (MCP). Proven track record of managing engineering teams, migrating legacy architectures to resilient cloud microservices, and deploying honestly-evaluated machine learning models. Focused on delivering high-reliability, schema-validated AI deployments that drive measurable operational efficiency.

### **Core Expertise**

* **Applied AI & Machine Learning:** Document extraction and normalization, quality-graded AI outputs, LLM API integration, RAG systems, MCP integrations, model evaluation and calibration (spatial cross-validation, out-of-domain validation).
* **Full-Stack & Cloud Architecture:** React/Next.js, Node.js/Python, AWS and Google Cloud/Firebase, REST/GraphQL APIs, CI/CD automation.
* **Data Engineering:** Data pipelines, schema design, provenance and audit trails, real-time state, multi-tenant data modeling.
* **Web3 & Provenance (supporting capability):** Solidity, EAS attestation, IPFS, and x402 agent-payable infrastructure — applied where it adds real value.

---

### **Projects & Selected Work**

#### **AssayChain — AI Document Extraction & Grading API** *(In Production)*

* Built an AI pipeline that converts unstructured assay documents (lab certificates, scanned reports, drill logs) into structured JSON with an honest A–D rubric (structural validity, coverage, self-consistency via a second extraction pass, physical-bounds cross-check).
* Built the provenance layer — content-addressed storage plus an append-only attestation registry — so every extracted value is traceable to its source document.
* Built a benchmark harness that measures extraction accuracy with a confidence interval; validated on 57 USGS fire-assay samples and a 1937 state-survey fire-assay sheet.
* Shipped an honest evaluation layer: 80% refund on Grade D, manual-review flag on Grade C, PII redaction, and ±0.1° coordinate rounding.
* Exposed as a REST + MCP API for Claude, Cursor, VS Code, and the OpenAI Agents SDK; agent-payable via x402 (USDC on Base).
* Stack: Python, Node.js, React/Next.js, PostgreSQL, AWS, Google Cloud, IPFS, EAS attestation.

#### **MineFlowTrack — Multi-tenant Geological Field-Data Platform** *(In Development)*

* Designed a Firestore multi-tenant data model with Google/Apple auth and an admin review/approval workflow.
* Built an IPFS + EAS attestation export pipeline for verified field-data runs and a sliding-scale profit-share + x402 revenue model integrated with AssayChain.

#### **Mineral Prospectivity Model — Honest ML Evaluation**

* Multi-label logistic regression (scikit-learn) predicting metal occurrence; leave-one-state-out spatial cross-validation; sigmoid calibration with documented out-of-region limits (gold F1 0.87 in-region).

---

### **Professional Experience**

#### **Founder & Principal Engineer — Quetzal Collective LLC (AssayChain)**

**May 2026 – Present | *Missoula, MT***

* Architected and deployed AssayChain, a production-grade applied AI document-parsing pipeline transforming unstructured critical-mineral reports into schema-validated JSON.
* Integrated Model Context Protocol (MCP) and agentic infrastructure to allow autonomous AI agents to securely query, ingest, and process graded data.
* Built a custom machine-learning evaluation framework utilizing spatial cross-validation to isolate, benchmark, and document model generalization limits.
* Standardized infrastructure across Node.js, Python, PostgreSQL, and AWS, implementing append-only data provenance layers and agent-payable (x402) protocols.

#### **Lead Blockchain & Cloud Engineer (Contract)**

**MineralFi** • Nov 2023 – Present | *Remote*

* Designed upgradeable ERC-20 and ERC-1155 contracts (OpenZeppelin) for the MINFI token; built milestone-based NFT incentive systems.
* Engineered a real-time analytics stack (Next.js, GraphQL, DynamoDB); integrated Uniswap V3 (~30% capital-efficiency improvement); established CI/CD with GitHub Actions and Hardhat testing.

#### **Independent Full-Stack Software Engineer**

**Self-employed** • Oct 2018 – Present | *Missoula, MT*

* Contract engineering across the stack — Rust, Solidity, React/Next.js, Python/Django, Unity (C#/DOTS), Three.js, LAMP, and AWS (Ubuntu, LightSail, ECS).
* Delivered production web apps, blockchain systems, and real-time interactive systems for clients; recent focus on applied AI and data systems (see AssayChain above).

#### **CTO & Co-founder — Numa Ridge (Lostone)**

**Numa Ridge** • May 2018 – Oct 2020 | *Missoula, MT*

* Co-founded and led engineering for Lostone, a real-world, multiplayer treasure-hunting game tying a game economy to public-lands exploration.
* Owned the full stack and multiplayer networking architecture (Unity, Docker, AWS EC2) with secure asset sync, real-time communication, and scalable matchmaking.

#### **Lead Software Developer**

**Rocky Mountain Rehab** • May 2006 – Nov 2018 | *Missoula, MT*

* Led a statewide case-management platform (Angular, .NET Core, MySQL); mentored an 8-person team and introduced DevOps practices, increasing delivery velocity ~25%.
* Migrated legacy monolithic systems to an API-first microservices architecture.

#### **Software Developer**

**USIS** • May 2004 – Sep 2005 | *Greater Billings Area*

* Full-stack software development delivering enterprise web applications.

#### **Web Developer**

**Versatile Productions Inc** • Aug 2001 – Aug 2003 | *Carbondale, CO*

* Built client-facing websites and web applications.

---

### **Skills & Technologies**

* **AI, ML & Data:** Python (scikit-learn, pandas), LLM APIs (OpenAI, Anthropic), AI agents, prompt engineering, RAG, MCP, workflow automation, data extraction, model evaluation & calibration
* **Languages & Frontend:** TypeScript, JavaScript, Python, Solidity, C#, Rust, SQL, Dart | React, Next.js, React Native, Flutter, Tailwind CSS
* **Backend & Databases:** Node.js, Express, Django, FastAPI | PostgreSQL, MySQL, MongoDB, DynamoDB, Firestore, Firebase, Redis
* **Cloud & DevOps:** AWS, GCP, Firebase, Docker, GitHub Actions, CI/CD
* **Web3 & Provenance:** Solidity, ERC-20/721/1155, OpenZeppelin, Hardhat, Foundry, IPFS, EAS attestation, x402

---

### **Education & Certifications**

* **B.S. in Computer Science – Software Engineering** – University of Montana (Graduated 2026) | Missoula, MT — Core Focus: Advanced Data Structures, Algorithmic Analysis, Machine Learning Systems, Database Architecture.
* **A.A., Programming & Application Development** – Missoula College (2023)
* **Certifications:** AWS Academy Cloud Foundations | Google Developer Training: Firebase Web Advanced
