<div align="center">

# Hi, I'm Quinn 👋

**AI Engineer · Automation Engineer · Product Builder**

I build **local AI infrastructure**, **agent systems**, **developer tooling**, **automation platforms**, and **production Android & Wear OS software**.

[**Portfolio**](https://profile.quinnfavo.com) · [**Consulting**](https://consultant.quinnfavo.com) · [**LinkedIn**](https://www.linkedin.com/in/quinnfavo/) · [**YouTube**](https://www.youtube.com/@QuinnFavo)

</div>

---

## Featured Engineering

### 🧠 [InferBridge](https://github.com/Quazmoz/InferBridge)

**Local AI workstation for Intel hardware.**

InferBridge turns Intel Windows PCs into practical local AI workstations with an OpenAI-compatible server, browser UI, model lifecycle tooling, diagnostics, benchmarking, and CPU/GPU/NPU targeting through OpenVINO GenAI.

**Engineering focus:** OpenVINO GenAI · OpenAI-compatible APIs · Windows packaging · local inference · hardware diagnostics · model lifecycle · reliability

[Repository](https://github.com/Quazmoz/InferBridge) · [Video walkthrough](https://youtu.be/rya6rJhkQrw) · [Releases](https://github.com/Quazmoz/InferBridge/releases)

### 🧠 [MemoryOps](https://github.com/Quazmoz/memoryops)

**Self-hosted memory control plane for AI agents.**

MemoryOps ingests engineering activity and turns it into governed, inspectable memory that agents can retrieve through API, MCP, and a control UI. It focuses on memory lifecycle, hybrid retrieval, context packing, auditability, and operator control rather than acting as another vector-database wrapper.

**Engineering focus:** Rust · React · PostgreSQL · Redis · Qdrant · Docker · MCP · retrieval systems

[Repository](https://github.com/Quazmoz/memoryops)

### 🤖 [AgentDefaults](https://github.com/Quazmoz/agentdefaults)

**Reusable, production-minded infrastructure for AI-assisted engineering.**

AgentDefaults packages canonical agents, composable skills, prompts, schemas, bounded execution loops, validation, and thin wrappers for multiple AI tools. It also includes practical automation workflows for areas such as Google Play, RevenueCat, and AdMob.

**Engineering focus:** agent architecture · MCP · governance · validation · reusable workflows · token efficiency · mobile release automation

[Repository](https://github.com/Quazmoz/agentdefaults) · [Human index](https://github.com/Quazmoz/agentdefaults/blob/main/INDEX.md)

---

## What I Build

| Area | Focus |
|---|---|
| **AI Infrastructure** | Local inference, model serving, OpenAI-compatible APIs, OpenVINO, RAG, CPU/GPU/NPU workloads |
| **Agent Systems** | MCP, memory, tool orchestration, retrieval, governance, reusable agent behavior, operator control planes |
| **Platform Engineering** | Terraform, Ansible, Kubernetes, GitOps, CI/CD, observability, secrets, internal automation |
| **Developer Tooling** | Secure local tools, CLIs, workflow automation, packaging, diagnostics, release engineering |
| **Product Engineering** | Android, Wear OS, Kotlin, Compose, phone-watch protocols, billing, production release workflows |

> **Build the tool once. Remove the task forever.**

---

## Currently Building

- **[InferBridge](https://github.com/Quazmoz/InferBridge)** — making local AI more usable on ordinary Intel Windows hardware, with stronger lifecycle, diagnostics, packaging, and hardware evidence.
- **[CLIHarbor](https://github.com/Quazmoz/CLIHarbor)** — a local browser interface for command-line tools with a secure allowlisted execution boundary and declarative pack model.
- **[AgentDefaults](https://github.com/Quazmoz/agentdefaults)** — reusable agent infrastructure, bounded implementation/review loops, validation, and cross-tool workflows.
- **Private product work** — Android, Wear OS, automation, and 3D/mobile product experiments that move from focused ideas into production-grade releases.

---

## 📱 I Ship Products Too

Beyond infrastructure and AI engineering, I design, build, release, and operate Android and Wear OS products on Google Play.

That work exercises a different but complementary part of the engineering stack: product UX, Kotlin and Compose, sensors and haptics, phone-watch protocols, billing, release automation, Play policy, privacy boundaries, accessibility, and production support.

### Selected product work

- **WristCapture** — paired Android/Wear OS screenshot utility built around deliberate user initiation and native platform behavior.
- **WebHookDeck** — phone-configured webhook deck for Wear OS with encrypted secrets, HMAC support, redaction, watch sync, tiles, and complications.
- **JetLag** — phone and Wear OS travel utility for time-zone planning, overlap windows, and weather-aware travel context.

<div align="center">

[![Google Play](https://img.shields.io/badge/Google_Play-Explore_My_Apps-34A853?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/dev?id=8067447984067693441)

</div>

<details>
<summary><strong>Production patterns across the private mobile portfolio</strong></summary>

<br>

- Explicit user initiation for sensitive actions, foreground services, sensors, audio, screenshots, and automation triggers
- Versioned phone-watch protocols with deterministic source-of-truth rules, stale-message rejection, and failure-specific states
- Local-first data models with no developer backend where one is not required
- Google Play Billing reconciliation, pending-purchase handling, restore flows, refund or revocation relocking, and clear free-versus-Pro boundaries
- Android Keystore usage, secret redaction, bounded imports, safe network policies, and privacy-focused diagnostics
- Release validation for lint, tests, minified builds, bundles, signing inputs, manifest constraints, API targets, and artifact checks
- Accessibility semantics, large-text resilience, compact round-screen handling, and honest UI status reporting
- Store-ready privacy policies, permissions documentation, Data Safety baselines, reviewer access flows, screenshots, and release checklists

</details>

---

## Core Stack

| Area | Tools and technologies |
|---|---|
| **AI and agents** | MCP, OpenAI-compatible APIs, OpenVINO GenAI, local LLMs, Open WebUI, agent memory, retrieval, prompt and skill systems |
| **Languages** | Python, Rust, Go, TypeScript, Kotlin, PowerShell, Bash |
| **Data and backends** | PostgreSQL, Redis, Qdrant, Room, DataStore, REST APIs, event-driven processing |
| **Infrastructure** | Terraform, Ansible, Kubernetes, Flux CD, Helm, Kustomize, Docker, SOPS, GitHub Actions, Jenkins |
| **Observability** | Prometheus, Grafana, structured logging, health checks, diagnostics, performance telemetry |
| **Android and Wear OS** | Jetpack Compose, Compose for Wear OS, Media3, Hilt, Room, Data Layer, tiles, complications, sensors, haptics, Play Billing |
| **Web** | React, Vite, TypeScript, Express, Tailwind CSS, structured SEO |
| **Windows delivery** | Go, PyInstaller, Inno Setup, embedded web UIs, portable packaging, checksums, upgrade compatibility, signing gates |

---

## More Public Work

<details>
<summary><strong>Public repositories and reference projects</strong></summary>

<br>

- [**K8S Homelab**](https://github.com/Quazmoz/K8SHomelab) — GitOps-managed hybrid Kubernetes platform for local AI, MCP services, automation, observability, and self-hosted tools
- [**GroupMe MCP**](https://github.com/Quazmoz/groupme-mcp) — Go-based MCP server exposing GroupMe workflows through AI-friendly tools
- [**npu-windows**](https://github.com/Quazmoz/npu-windows) — earlier Intel NPU local-LLM server and predecessor to the broader InferBridge architecture
- [**TerraformHomeLab**](https://github.com/Quazmoz/TerraformHomeLab) — infrastructure-as-code layer associated with the homelab platform
- [**GroupMeCommunityDocs**](https://github.com/Quazmoz/GroupMeCommunityDocs) — GroupMe community documentation and reference material
- [**ai.quinnfavo.com**](https://github.com/Quazmoz/ai.quinnfavo.com) — public site repository for AI-focused content and experiments
- [**devops-ai-prompts**](https://github.com/Quazmoz/devops-ai-prompts), [**helpfulscripts**](https://github.com/Quazmoz/helpfulscripts), and [**Public**](https://github.com/Quazmoz/Public) — smaller prompt, script, and example collections

</details>

---

## Technical Content

I publish practical walkthroughs around **local AI**, **automation**, **developer tooling**, **agent systems**, and **shipping software**.

[**Watch on YouTube →**](https://www.youtube.com/@QuinnFavo)

---

## Work With Me

I work on **AI infrastructure**, **automation engineering**, **developer platforms**, **agent systems**, and **local/private AI deployments**.

[**View consulting work →**](https://consultant.quinnfavo.com)

