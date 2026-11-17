# Software Engineer — Backend, Cloud & Security Engineering

I build backend and cloud systems, and I'm moving into **security engineering** on the defensive side: detection and response.

Buenos Aires, Argentina · English and Spanish

---

### Security research

- **[CVE-2026-104850](https://github.com/modelcontextprotocol/typescript-sdk/security/advisories/GHSA-6qxp-vccf-f47h)** (High, CVSS 7.5) — credited reporter. I independently reported a flaw in the OAuth client of the official Model Context Protocol TypeScript SDK: it could send stored credentials to an authorization server chosen by a malicious MCP server. Fixed in `@modelcontextprotocol/sdk` 1.31.0 and `@modelcontextprotocol/client` 2.2.0.

### Now

- **Hack The Box Academy** — Junior Cybersecurity Associate (CJCA) path, in progress. Done so far: Linux Fundamentals, Bash Scripting, Network Foundations, Introduction to Networking, Web Requests, Introduction to Web Applications, Windows Fundamentals.
- **Next** — the SOC Analyst path (CDSA): SIEM, log analysis and incident handling.
- **Degree in Cybersecurity** (Licenciatura) at Universidad de Palermo, in progress.

### Background

- **AI Engineer, Slice** (2025–2026) — LLM integrations in production services.
- **Backend & Cloud Developer, DAMM Capital** (2024) — FastAPI services on AWS Lambda, PostgreSQL on RDS, Docker images on ECR, scoped IAM permissions between services, Terraform.
- **Freelance developer** (2022–2025).

### Projects

Tools I built for running AI systems in production. None of them is a security tool. They share the habits I want to bring to detection work: instrument everything, alert when behaviour changes, and explain the failure.

- **[pipeline-observatory](https://github.com/OriginalKazdov/pipeline-observatory)** — Observability SDK for LLM applications. It patches the OpenAI and Anthropic clients and records latency, cost and quality for every call, with drift alerts based on an exponential moving average.
- **[adaptergate](https://github.com/OriginalKazdov/adaptergate)** — CI gate for fine-tuned model adapters. It compares a candidate against the current baseline on held-out data, blocks the release when quality drops, and reports which group of queries regressed.
- **[agent-framework](https://github.com/OriginalKazdov/agent-framework)** — Framework for AI agents where every step (reasoning, tool call, result) is traced and stored in SQLite, with a UI to inspect a run afterwards.
- **[adaptive-rag](https://github.com/OriginalKazdov/adaptive-rag)** — Retrieval system that classifies each query and picks a search strategy for it, including refusing to answer when it has no grounds to.

### Stack

![Python](https://img.shields.io/badge/Python-306998?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Claude API](https://img.shields.io/badge/Claude_API-191919?style=for-the-badge&logo=anthropic&logoColor=white)

- **Languages:** Python, Bash, SQL
- **Backend:** FastAPI, Pydantic, PostgreSQL, SQLite
- **Cloud:** AWS (Lambda, RDS, S3, ECR, IAM), Terraform, Docker
- **AI:** Claude and OpenAI APIs, retrieval (RAG), evaluation
- **Learning:** Linux and Windows administration, networking, web fundamentals

### Contact

Open to security engineering, cloud security and backend or infrastructure roles, remote.

- LinkedIn: [linkedin.com/in/juancruzdovzak](https://www.linkedin.com/in/juancruzdovzak)
- Telegram: [t.me/kazdoveth](https://t.me/kazdoveth)
- X: [@kazdovETH](https://x.com/kazdovETH)
