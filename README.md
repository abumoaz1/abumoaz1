# Abu Moaz

AI Engineer focused on production RAG systems, multi-agent orchestration, and scalable FastAPI services.

[Website](https://abumoaz.me) | [LinkedIn](https://linkedin.com/in/abu-moaz) | [GitHub](https://github.com/abumoaz1) | [Email](mailto:moazkhan7496@gmail.com)

## Professional Summary

AI Engineer with hands-on experience building production-ready LLM pipelines, multi-agent orchestration systems, and semantic vector search integrations. My work includes zero-downtime search migrations for 26M+ records, RAG-powered ticketing assistants with pgvector and AWS Bedrock, and AI security tooling for code analysis and remediation. Open source contributor to AgentWire.

## Technical Skills

- **Languages:** Python, JavaScript, Java
- **Frameworks:** FastAPI, Flask, LangChain, LlamaIndex, React.js, Next.js
- **AI & LLM:** RAG Pipelines, Multi-Agent Systems, Prompt Engineering, AWS Bedrock, Ollama, OpenAI API, pgvector, FAISS
- **Evaluation & Observability:** RAGAS, DeepEval, Langfuse, Pydantic v2
- **Databases & Search:** PostgreSQL, Elasticsearch, Redis, ChromaDB
- **Infrastructure:** Docker, AWS (EC2, S3, IAM), GitHub Actions, CI/CD, Linux

## Experience

### Blackcoffer Pvt Ltd
**Software Engineer, AI & Backend** | June 2025 – Feb 2026 | Noida, UP

- Developed scalable FastAPI backend services handling 1.2M+ daily requests, reducing average response times by 35%.
- Led zero-downtime migration of search infrastructure (26M+ records) from Elasticsearch 5.6 to 9.2 with backward-compatible APIs.
- Built a role-based AI ticketing assistant using pgvector RAG pipelines, achieving 92%+ retrieval accuracy.
- Integrated AWS Bedrock LLMs via Boto3 to orchestrate cloud-native AI inference pipelines on provisioned AWS infrastructure (EC2, S3, IAM).

### Frazor Enterprises Solutions
**Associate Software Engineer (Internship)** | Feb 2025 – May 2025 | Gurgaon, Haryana

- Developed asynchronous FastAPI inference endpoints for generative AI models, reducing payload processing time by 45%.
- Optimized LLM data ingestion pipelines using custom semantic chunking, reducing token costs by 30% while decreasing hallucination rates.

## Projects

### Validgen – AI Code Security Scanner
`FastAPI · Docker · AST Analysis` | [validgen.com](https://validgen.com)

- Built and deployed an AI code security scanner using 150+ custom detection rules (regex + AST analysis) to catch vulnerabilities in AI-generated code, acquiring active users and processing 50+ repository scans in month one.
- Architected a sandboxed Docker-in-Docker scanning environment with a zero-code-retention policy for user privacy.

### SEO-Agentica – Multi-Agent Local SEO Auditor
`FastAPI · Ollama · React · SSE` | [GitHub](https://github.com/abumoaz1)

- Architected an async multi-agent orchestration engine running fully local LLMs (gemma3:1b, phi4-mini), built without LangChain or CrewAI.
- Engineered real-time event-streaming (FastAPI SSE) to push agent execution steps to the UI, improving perceived latency by 70%+ over polling.

### Validex – API Contract Validator
`FastAPI · pgvector · Redis · Docker` | [GitHub](https://github.com/abumoaz1/validex)

- Built an automated testing platform using pgvector RAG to ingest OpenAPI specs and generate test scripts, reducing manual QA test creation time by 60%.
- Architected a sandboxed Docker environment with a Redis async task queue, scaling to 50+ concurrent container tests.

## Open Source Contributions

### [AgentWire](https://github.com/dotdevdotdev/agentwire-dev) – Agentic AI Orchestration Framework
3 merged PRs

- **PR #524:** Fixed a critical multi-session reliability bug where worktree worker done-reports dead-lettered silently against a busy orchestrator. Passed 2 rounds of blocking review. +193 / −3 lines across 5 files.
- **PR #501:** Improved onboarding DX and CLI docs; shipped in v1.45.0 as the first-ever outside contributor.

## Education

### Aligarh Muslim University
**Master of Computer Applications** | CGPA: 8.5/10 | June 2025 | Aligarh, UP

## Current Focus

- Production-grade RAG and retrieval systems
- FastAPI backend architecture and performance
- Multi-agent orchestration and local LLM deployment
- AI security tooling and automated remediation
