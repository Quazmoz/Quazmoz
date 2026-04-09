# Hi, I'm Quinn 👋

📍 New York | ☁️ Cloud & DevOps Engineer | 🤖 AI Systems, Automation, and Utility Product Builder

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Wear OS](https://img.shields.io/badge/Wear%20OS-4285F4?style=flat&logo=wearos&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat&logo=windows11&logoColor=white)

**AI Tools I work with daily:**

![Antigravity](https://img.shields.io/badge/Antigravity-000000?style=flat&logo=dependabot&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![Perplexity](https://img.shields.io/badge/Perplexity-20808D?style=flat&logo=perplexity&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)

I build **automation-first systems** across infrastructure, AI workflows, internal tooling, and standalone utility software.

My work keeps coming back to one idea:

> find operational friction, then turn it into software

---

## What I Actually Build

### AI Agent Tooling & MCP Servers
I'm building a multi-language MCP (Model Context Protocol) server ecosystem — Go, Python (FastMCP), and Rust implementations — with OpenAPI specs for each surface. Integrations target real enterprise platforms: **Microsoft 365** (Planner, To Do, Loop), **HPE OneView** for bare-metal infrastructure management, **Tanium** for endpoint security, and **Zerto** for disaster recovery orchestration. The goal is agent-accessible infrastructure, not just chatbots.

### Q-Automation — Script Orchestration Platform
A full production-grade automation platform I built from scratch:
- **React 18 + TypeScript** frontend with Monaco Editor (VS Code's engine) for in-browser script editing
- **Django REST Framework** backend with **Celery + Redis** for async task execution and cron scheduling
- **PostgreSQL** persistence with full audit logging and RBAC
- Enterprise SSO support: SAML 2.0, LDAP/AD, Azure AD OAuth, Okta, Google, GitHub
- Kubernetes-ready with Helm charts and GitHub Actions CI/CD
- Scripts execute in sandboxed subprocesses with configurable timeouts, CPU/memory metrics, and Sentry-integrated error tracking

This is not a toy. It's a platform for teams to manage, schedule, and monitor PowerShell and Python scripts through a hardened web interface.

### PowerShell RMM Pro
A remote monitoring and management tool built across two layers:
- **Go backend** — fast, low-overhead API layer for endpoint communication and telemetry collection
- **Flutter frontend** — cross-platform dashboard for managing endpoints, running scripts, and viewing status

Built because commercial RMM tools are expensive and often overbuilt for the specific operational needs I work against.

### MCP Infrastructure (Go + Python + Rust)
Beyond the server implementations, the `mcp` repo has:
- Pre-commit hooks enforcing code quality across all language targets
- OpenAPI spec library for consistent interface documentation
- Structured contribution patterns for adding new platform integrations

### dbGuard — Android / Wear OS Utility
A Kotlin + Gradle Android project with a Wear OS companion. Focused on a tight, specific UX — the kind of low-friction, haptic-first experience that standalone apps should have but rarely do.

### 🖥️ Homelab
A self-hosted lab running Kubernetes, local LLMs on GPU/NPU hardware, and infrastructure experiments that don't belong in a cloud account. It's where IaC patterns get validated, new tools get stress-tested, and nothing is sacred.
- **K8SHomelab** — live cluster: manifests, operators, Helm deployments, config iteration
- **TerraformHomeLab** — reusable IaC modules for homelab and cloud environments
- **npu-windows** — local AI model experimentation on Windows NPU hardware

---

## Tech I Use Regularly

| Layer | Tools |
|---|---|
| Cloud | Azure, AWS |
| IaC | Terraform, Ansible, Helm |
| Containers | Docker, Kubernetes (AKS) |
| Languages | PowerShell, Python, Go, Rust, TypeScript, Kotlin |
| Backends | Django REST, Go (net/http), FastMCP |
| Frontends | React, Flutter |
| Data | PostgreSQL, Redis, Celery Beat |
| AI/Agents | MCP, FastMCP, local LLMs, n8n, Antigravity, Codex, Claude, Perplexity, Gemini |
| CI/CD | GitHub Actions, Azure DevOps |
| OS | Windows (primary), Linux (servers + containers) |
| Monitoring | Sentry, structured JSON logging, health check endpoints |

---

## What's Private (and Why)

Most of my active work lives in private repos. This includes:
- Internal automation systems and admin tooling
- Dashboard and portal prototypes
- AI workflow experiments and MCP orchestration concepts
- Product-stage wearable app development
- PowerShell-heavy systems administration tooling built for real operational environments

The public repos are a slice. The private side is where the systems actually run.

---

## Patterns I Keep Coming Back To

- **Automation over ceremony** — systems that eliminate work, not just document it
- **Utility over novelty** — tools that solve something real, not demos
- **Productized infrastructure** — if I'm running it manually more than twice, it becomes software
- **Small tools that compound** — narrow utilities that evolve into broader workflows
- **Sandboxed, observable execution** — everything gets logs, metrics, and timeouts

---

## Current Direction

- Agent-orchestrated workflows using MCP as the interface layer
- Expanding enterprise platform coverage in the MCP server ecosystem
- AI for operational leverage: triage, summarization, anomaly flagging in infra pipelines
- Cross-platform utility apps (Wear OS / Android / Flutter) with tight, focused value propositions
- Local-first AI experimentation on GPU and NPU hardware

---

## Elsewhere

- 🌐 [profile.quinnfavo.com](https://profile.quinnfavo.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/quinnfavo/)
- ▶️ [YouTube](https://www.youtube.com/@QuinnFavo)

---

> Build the tool once. Remove the task forever.
