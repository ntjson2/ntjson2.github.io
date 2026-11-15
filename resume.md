# Nathan Johnson
## Principal Forward Deployed Engineer | Applied AI, MCP & Enterprise Data Integration

Missoula, MT | Open to remote and customer-site travel
ntjson@gmail.com | linkedin.com/in/ntjson | github.com/ntjson2 | ntjson2.github.io

## Professional Summary

Principal Software Engineer and former CTO with 20+ years of production experience, focused on Forward Deployed AI Engineering. I embed with domain teams to define schemas and success criteria, then build and ship production LLM pipelines, RAG systems, custom MCP servers, and calibrated ML systems for unstructured data. Experience includes customer discovery, rapid prototyping, evaluation harnesses, guardrails, schema normalization, and multi-tenant AWS/GCP deployments. Open to Principal or Staff Forward Deployed Engineer and Applied AI Architect roles.

## Skills

- AI/ML and Data: Python (scikit-learn, pandas), LLM APIs (OpenAI, Anthropic, OpenRouter), RAG, semantic search, AI agents, prompt engineering, data extraction, schema normalization, model evaluation and calibration (spatial CV, OOD validation).
- Forward Deployed and Delivery: customer discovery, rapid prototyping, solution architecture, production handoff, evaluation harnesses, guardrails, multi-tenant cloud (AWS/GCP), MCP server development.
- Languages and Frontend: TypeScript, JavaScript, Python, Rust, C#, Dart, Solidity, PHP, SQL; React, Next.js, React Native, Flutter, Tailwind CSS, Three.js, Unity (C#/DOTS).
- Backend, Data, and Cloud: Node.js, Express, Django, FastAPI, REST/GraphQL; PostgreSQL, MySQL, MongoDB, DynamoDB, Firestore, Redis; AWS (Lambda, EC2, RDS, S3, API Gateway, ECS), Google Cloud, Firebase, Docker, GitHub Actions, CI/CD.
- Provenance, Protocols, and Quality: append-only provenance, EAS attestation, IPFS, MCP, x402; Jest, Vitest, Playwright, E2E testing, contract auditing, static analysis, security reviews.

## Professional Experience

### Principal Applied AI Engineer (Founder) | Quetzal Collective LLC (AssayChain)
May 2026 - Present | Missoula, MT

- Embedded with critical-minerals domain experts through customer discovery to define extraction schemas and success criteria, then shipped a production LLM pipeline that converts assay reports and drill logs into schema-normalized JSON.
- Built custom Model Context Protocol (MCP) servers and agentic infrastructure so Claude, Cursor, VS Code, and OpenAI Agents SDK clients can securely query, ingest, and process graded data.
- Designed evaluation harnesses with confidence intervals and spatial cross-validation; added guardrails (PII redaction, Grade C manual-review flags, Grade D refunds) and documented where the model does and does not generalize.
- Standardized multi-tenant infrastructure across Node.js, Python, PostgreSQL, AWS, and GCP, with append-only provenance and audit layers plus agent-payable x402 APIs.

### Principal Consulting and Forward Deployed Engineer | Self-employed
Oct 2018 - Present | Missoula, MT

- Led customer discovery and rapid prototyping for ambiguous client problems, delivering working software in short iterations and handing off to client teams.
- Shipped full-stack systems into client AWS/GCP environments using Rust, React/Next.js, Python/Django, Unity (C#/DOTS), Three.js, and LAMP.
- Recent focus: embedded applied-AI deployments, including LLM extraction pipelines, RAG, custom MCP integrations, and evaluation harnesses.

### CTO and Co-founder | Numa Ridge (Lostone)
May 2018 - Oct 2020 | Missoula, MT

- Co-founded and led engineering for Lostone, a real-world multiplayer treasure-hunting game that tied a game economy to public-lands exploration.
- Owned the full stack and multiplayer networking architecture (Unity, Docker, AWS EC2), including secure asset sync, real-time communication, and scalable matchmaking.
- Met hard real-time milestones; the side venture was wound down in 2020.

### Lead Software Developer | Rocky Mountain Rehab
May 2006 - Nov 2018 | Missoula, MT

- Led a statewide case-management platform (Angular, .NET Core, MySQL), aligning stakeholders across disability services, employment counseling, and independent-living programs.
- Mentored an 8-person engineering team and introduced DevOps, automated testing, and CI/CD, increasing delivery velocity by approximately 25%.
- Migrated legacy monoliths to an API-first microservices architecture, directly applicable to integrating modern AI with aging enterprise software.

## Additional Experience

### Lead Blockchain and Cloud Engineer (Contract) | MineralFi
Nov 2023 - Present | Remote

- Designed upgradeable ERC-20 and ERC-1155 contracts (OpenZeppelin) for the MINFI token and built NFT systems for performance-based incentives and stakeholder trusts with milestone-based payouts.
- Built real-time analytics (Next.js, GraphQL, DynamoDB), integrated Uniswap V3 for automated liquidity (approximately 30% capital-efficiency improvement), and established CI/CD with GitHub Actions and Hardhat contract testing.

## Selected Projects

### AssayChain | AI Document Extraction and Grading API (In Production)

- Production extraction and grading pipeline for lab certificates, scanned reports, and drill logs, producing structured JSON against an A-D quality rubric: structural validity, coverage, self-consistency through a second independent extraction pass, and physical-bounds cross-checking. Submitted to NSF SBIR for further development and evaluation.
- Provenance layer using content-addressed storage and an append-only attestation registry, so every extracted value is traceable to its source document.
- Benchmark harness that reports extraction accuracy with confidence intervals, validated on 57 USGS fire-assay samples and a 1937 state-survey fire-assay sheet; Grade D earns an 80% refund and Grade C is flagged for manual review.
- Exposed as a REST and MCP API usable from Claude, Cursor, VS Code, and the OpenAI Agents SDK, and agent-payable via x402 (USDC on Base). Stack: Python, Node.js, React/Next.js, PostgreSQL, AWS, Google Cloud, IPFS, and EAS attestation.

### MineFlowTrack | Multi-tenant Geological Field-Data Platform (In Development)

- Designed a Firestore multi-tenant data model and non-technical field-user workflows, with Google/Apple authentication and an admin review/approval workflow.
- Built an IPFS and EAS attestation export pipeline for verified field-data runs, and modeled a sliding-scale profit-share and x402 revenue system integrated with AssayChain.

### Mineral Prospectivity Model | Honest ML Evaluation

- Trained a multi-label logistic regression model (scikit-learn) to predict metal occurrence from geology, using leave-one-state-out spatial cross-validation to avoid data leakage; calibrated probabilities and validated on a strict out-of-region hold-out.
- Documented where the model does and does not generalize; gold occurrence predicted at F1 0.87 in-region.

## Education

**B.S. Computer Science, Software Engineering** | University of Montana | 2026
Relevant coursework: Advanced Data Structures, Algorithmic Analysis, Machine Learning Systems, Database Architecture.

**A.A. Programming and Application Development** | Missoula College | 2023

## Certifications and Training

- AWS Academy Cloud Foundations | AWS Academy Graduate
- Firebase Web Advanced | Google Developer Training
- Advanced OpenAI API Integration | Professional development
- IPFS and Distributed Systems Architecture | Professional development
