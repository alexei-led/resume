# Alexei Ledenev

## **AI Engineering & Cloud Platform Leader**

📧 [alexei.led@gmail.com](mailto:alexei.led@gmail.com) | 📱 [+972-52-5697080](tel:+972525697080) | 📍 Israel

🧑🏻‍💻 [LinkedIn](https://www.linkedin.com/in/alexeiledenev/) | 🛠️ [GitHub](https://github.com/alexei-led) | 📝 [Medium](https://medium.com/@alexeiled)

---

### **Summary**

Engineering leader with 20+ years building and shipping platform software, now focused on **agentic AI systems and developer-facing AI products**. Hands-on author of Telegram tmux bridge to AI coding agents (ccgram - 160 stars) and two production MCP servers (k8s-mcp-server, aws-mcp-server — ~400 GitHub stars combined), a multi-agent cloud-ops platform, and several LLM-driven workflows running across AWS, GCP, and Azure. Track record of growing high-performing distributed engineering teams, architecting and delivering enterprise-grade SaaS, and translating fast-moving AI research into shippable platform capabilities. Open-source maintainer (Pumba — 3K+ stars), conference speaker, and active contributor to the agentic-tooling ecosystem.

---

### **What I Build in the Agentic Space**

- **Reflex** (DoiT, internal — strategic initiative) — Currently leading this project in the autonomous agentic-AI domain for cloud operations. Architecting an enterprise-grade multi-agent system with safety guardrails, controlled execution under human approval, and proactive collaboration across cloud platforms. _Implementation details proprietary._
- **[k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server)** (Python, **208★**) — Model Context Protocol server giving Claude secure, sandboxed access to `kubectl`, `helm`, `istioctl`, and `argocd` inside a hardened container. Used by developers running AI-driven Kubernetes operations.
- **[aws-mcp-server](https://github.com/alexei-led/aws-mcp-server)** (Python, **182★**) — MCP server exposing the entire AWS CLI (200+ services) to Claude, Cursor, and other MCP clients. Containerized, IAM-scoped, streamable-HTTP transport, proper MCP error semantics. Published to PyPI and GHCR.
- **[ccgram](https://github.com/alexei-led/ccgram)** (Python, **102★**) — Control plane bridging Telegram to tmux-based AI coding agents (Claude Code, Codex CLI, Gemini CLI). Lets users monitor and steer running agent sessions remotely.
- **[cc-thingz](https://github.com/alexei-led/cc-thingz)** — Plugin suite for Claude Code, Codex, Pi and Gemini (30 skills, 3 sub-agents, 10 hooks), cross-compliation to multiple targets.
- **InvoiceHarbor** — Production LLM workflow (LangChain + OpenAI + LangSmith) extracting structured data from AWS billing PDFs at scale.

---

### **Professional Experience**

#### **Principal Software Engineer — DoiT International** | April 2025 – Present

- Leading **Reflex**, a strategic initiative in the autonomous agentic-AI domain — architecting an enterprise-grade multi-agent system for cloud operations with safety guardrails and human-in-the-loop execution.
- Architecting the migration of the **DCI (DoiT Cloud Intelligence) platform** from GCP to AWS/EKS — a multi-tenant SaaS used by enterprise FinOps customers.
- Leading the **BigQuery → ClickHouse** research and redesign for the analytics pipeline; building the Go sync service running across a 6-shard × 2-replica cluster.
- Driving BigQuery cost and performance optimization across the platform leading to saving above 100K yearly.

#### **Staff Cloud Architect — DoiT International** | September 2019 – April 2025

- Built and led a distributed team of senior Forward Deployed Engineers working with customers across multiple clouds: AWS, GCP, and Azure and multiple domains: AI/ML, containers, analytics, inrastructure, automation.
- Owned architecture reviews, technical strategy, and best-practice governance across the team.
- Designed and shipped internal AI products integrated into the DoiT Cloud Intelligence platform:
  - **Zenrouter** — AI-driven ticket routing system that improved assignment accuracy and response quality.
  - **AI invoice-processing workflow** for AWS invoices (LLM + OCR pipeline) that materially reduced manual finance work.
- Drove adoption of cloud-native and FinOps patterns across customer engagements; delivered certified AWS and GCP training.
- Spoke at industry conferences and meetups on cloud architecture, DevOps, and (more recently) agentic AI.

#### **Solutions Architect — Amazon Web Services** | July 2018 – September 2019

- Trusted technical advisor to enterprise customers; designed Well-Architected solutions across security, cost, performance, reliability, and operations.
- Member of the **Containers Technical Field Community**, specializing in Kubernetes and container platforms.
- Ran technical workshops, immersion days, and reference-architecture authoring; contributed customer feedback into the AWS roadmap.

#### **Chief of Research — Codefresh** | March 2017 – July 2018

- Led R&D on Kubernetes, Docker, and CI/CD; helped shape a SaaS microservices platform that became a core product offering.
- Maintained open-source projects and grew the Containers 101 TLV meetup community.

#### **Chief Software Architect — Hewlett-Packard Enterprise (ADM Business Unit)** | 2013 – March 2017

- Principal architect for the Application Delivery Management business unit; led and mentored a team of product architects across multiple enterprise products.
- Led an innovation team researching emerging tech and driving next-generation product direction.
- **Awarded 9 patents** in test automation, including the patented "Mirror Testing" concept and AI-driven Visual Object Recognition for UI automation — early production application of ML to developer tools.
- Drove the migration of legacy enterprise products to SaaS, opening a new revenue stream for the business unit.
- Led architectural due diligence for acquisitions and the org-wide transition from Waterfall to Agile (~30% reduction in time-to-market).

#### **Earlier Roles** | Software Engineer → Team Lead → R&D Manager → Architect | 1997 - 2013

- Hewlett-Packard, Mercury Interactive, Mer Technologies, Myriad Interactive. Consistent progression while remaining hands-on and shipping software.

---

### **Open Source**

- **[Pumba](https://github.com/alexei-led/pumba)** (Go, **3,017★**) — Flagship project. Chaos engineering for Docker containers — network emulation, fault injection, stress testing. Widely adopted in the container community for production resilience testing. Supports multiple container technologies: Docker, Podman, Containerd.
- **[KubeIP](https://github.com/doitintl/kubeip)** (Go, **447★**) — Kubernetes controller assigning static public IPs to nodes on GKE / EKS.
- **[Secrets-Init](https://github.com/doitintl/secrets-init)** (Go, **172★**) — Minimalistic init system for containers with native AWS / GCP secret-manager integration; a small but core piece of secure container runtime.

---

### **Skills**

- **AI / Agentic:** LLM application architecture, Model Context Protocol (MCP), multi-agent systems (AutoGen, OpenClaw), LangChain, evaluation and safety guardrails for AI products, prompt and instruction design at scale
- **Languages:** Go, Python, TypeScript, others
- **Cloud / Platform:** AWS, GCP, Azure, Kubernetes (EKS/GKE), Docker, Cloud Run, BigQuery, ClickHouse
- **Software Architecture:** Microservices, distributed systems, SaaS, event-driven, modular architecture (Balanced Coupling)
- **DevOps / DevSecOps:** GitHub Actions, Terraform, CI/CD pipeline design, secure execution of agent-driven changes (scoped credentials, human-in-the-loop approvals)
- **Leadership:** Building and mentoring distributed engineering teams, architecture governance, stakeholder and customer management, hiring, technical strategy

---

### **Education**

- **M.Sc. in Computer Science** — Tel Aviv University, 2006–2007
- **B.Sc. in Computer Science & Statistics** — Tel Aviv University, 1992–1996

### **Certifications**

- Google Cloud Professional Cloud Architect · Google Cloud Authorized Trainer
- AWS Solutions Architect – Professional · AWS Authorized Instructor
- Certified Kubernetes Administrator (CKA)

### **Patents**

- 9 granted patents in test automation, UI testing, protocol handling, and AI-driven automation (HP / Mercury Interactive).
