# Software Engineer — Backend, Cloud & Security Engineering

I build backend and cloud systems, and I'm moving into **security engineering** on the defensive side: detection and response.

Buenos Aires, Argentina · English and Spanish

---

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
