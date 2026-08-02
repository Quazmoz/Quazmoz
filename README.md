<div align="center">

# Hi, I'm Quinn 👋

### AI and DevOps engineer building local AI infrastructure, agent systems, automation platforms, and focused Android and Wear OS products.

I turn operational friction into software: local inference workstations, governed agent memory, MCP integrations, GitOps platforms, and small products designed around one clear job.

[![Portfolio](https://img.shields.io/badge/Portfolio-profile.quinnfavo.com-00C2FF?style=for-the-badge)](https://profile.quinnfavo.com)
[![Consulting](https://img.shields.io/badge/Consulting-consultant.quinnfavo.com-8B5CF6?style=for-the-badge)](https://consultant.quinnfavo.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Quinn%20Favo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/quinnfavo/)
[![YouTube](https://img.shields.io/badge/YouTube-@QuinnFavo-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@QuinnFavo)

</div>

---

## What I Build

My work sits at the intersection of **AI infrastructure**, **platform automation**, **local-first software**, and **product engineering**.

- **Local AI systems**: OpenAI-compatible inference, OpenVINO GenAI, Intel CPU/GPU/NPU targeting, model lifecycle tooling, diagnostics, packaging, and desktop UX
- **Agent infrastructure**: governed memory, MCP servers, reusable agent defaults, retrieval systems, tool interfaces, and operator control planes
- **DevOps platforms**: Terraform, Ansible, Kubernetes, Flux CD, CI/CD, observability, secret management, and internal automation
- **Android and Wear OS products**: Kotlin, Jetpack Compose, phone-watch protocols, tiles, complications, sensors, haptics, Media3, and Google Play Billing
- **Technical product systems**: release gates, privacy boundaries, app-store readiness, SEO, documentation, support workflows, and product websites

> Build the tool once. Remove the task forever.

---

## Featured Public Source

These repositories best represent my current engineering direction.

| Project | What it is | Stack and focus | Stage |
|---|---|---|---|
| [**InferBridge**](https://github.com/Quazmoz/InferBridge) | Windows-first local AI workstation with an OpenAI-compatible server, browser UI, model operations, vision, embeddings, diagnostics, benchmarking, and Intel device targeting | Python, OpenVINO GenAI, Windows packaging, CPU/GPU/NPU, OpenAI APIs | Active |
| [**MemoryOps**](https://github.com/Quazmoz/memoryops) | Self-hosted memory control plane for AI agents with governed ingestion, lifecycle management, hybrid retrieval, MCP access, and an operator UI | Rust, React, PostgreSQL, Redis, Qdrant, Docker, MCP | Alpha |
| [**AgentDefaults**](https://github.com/Quazmoz/agentdefaults) | Reusable agent profiles, skills, prompts, wrappers, schemas, quick starts, and validation patterns for practical AI workflows | Markdown, Python validation, agent UX, token-efficiency workflows | Active |
| [**GroupMe MCP**](https://github.com/Quazmoz/groupme-mcp) | Go-based MCP server exposing GroupMe groups, messages, direct messages, bots, polls, member operations, and AI-friendly name-based tools | Go, MCP, stdio/HTTP transport, Docker, rate limiting | Active |
| [**K8S Homelab**](https://github.com/Quazmoz/K8SHomelab) | GitOps-managed hybrid Kubernetes platform for local AI, MCP services, automation, observability, and self-hosted tools | Kubernetes, Flux CD, Helm, Kustomize, SOPS, Prometheus, Grafana | Active reference |

### InferBridge

InferBridge turns an Intel Windows PC into a practical local AI workstation without requiring Docker, Electron, or a cloud inference provider.

The codebase includes:

- OpenAI-compatible chat, responses, embeddings, tool-call, structured-output, and vision interfaces
- OpenVINO GenAI execution across CPU, GPU, NPU, AUTO, and advanced device expressions
- Model registration, conversion, loading, cancellation, deletion, benchmarking, and conservative hardware recommendations
- A responsive browser UI with model controls, telemetry, diagnostics, themes, onboarding, and conversation history
- Windows launcher, tray integration, single-instance protection, data-path compatibility, installer and portable packaging, checksums, and signing gates
- Mock-mode contract testing plus explicit separation between simulated validation and real hardware evidence

### MemoryOps

MemoryOps is a control plane for what AI agents remember. It focuses on governed, inspectable, team-oriented memory rather than acting as another vector database wrapper.

Its architecture covers:

- Engineering-event ingestion from systems such as GitHub, Slack, Jira, Linear, and agent observations
- Episodic and semantic memory lifecycles, scoring, decay, promotion, deduplication, pruning, feedback, and auditability
- Hybrid semantic and keyword retrieval with token-aware context packing
- REST and MCP interfaces for coding agents and operational agents
- A self-hosted control UI backed by PostgreSQL, Redis, and Qdrant

### AgentDefaults

AgentDefaults packages reusable behavior instead of repeatedly rebuilding prompts from scratch. It includes canonical agent instructions, thin tool wrappers, composable skills, structured schemas, examples, and validation scripts.

Current workflow areas include:

- Coding, DevOps, research, documentation, SEO, Google Play growth, and Wear OS development
- Claude, Gemini, GitHub Copilot, editor-rule, CLI, and repo-aware agent entrypoints
- Context budgeting, output control, token-efficiency measurement, and benchmark artifacts
- Browser research, authenticated handoff patterns, and MCP-assisted media workflows

---

## Private Product Engineering

The majority of my active Android, Wear OS, automation, and product-stage work is maintained in **private repositories**. The products are described here to show the engineering scope without implying that their source is public.

| Product | Engineering scope | Source |
|---|---|---|
| **SoundLatch** | Android phone, tablet, Android TV, and Google TV audio utility with Media3 playback, compatibility testing, saved profiles, quiet hours, reminders, Room, DataStore, Hilt, and one-time Play Billing | Private |
| **WristCapture** | Paired Android and Wear OS utility that requests Android's native screenshot action from a deliberate watch command while keeping screenshot pixels outside the app | Private |
| **WebHookDeck** | Phone-configured webhook deck for Wear OS with encrypted secrets, HMAC support, safe redirects, redaction, watch sync, tiles, complications, and local-first execution | Private |
| **FlickDeck** | User-armed Wear OS gesture shortcuts for webhooks and Home Assistant with deterministic sensor classification, bounded foreground sessions, confirmations, and cooldowns | Private |
| **FidgetDrop** | Android and Wear OS haptic products with custom gesture mechanics, sensors, stylus support, local records, accessibility semantics, and lifetime Pro unlocks | Private |
| **Consulting and app platform** | React and TypeScript product site with an app catalogue, technical articles, video content, privacy policies, structured SEO, and route-level delivery | Private |

<details>
<summary><strong>Additional private product repositories</strong></summary>

<br>

The broader private portfolio includes projects such as:

- **JetLag** for time-zone, travel-overlap, and weather planning across phone and Wear OS
- **CountCue** and **IntervalTimer** for focused timer and interval workflows
- **MedTick**, **WalkReset**, and related reminder-oriented utilities
- **BaroGuard**, **dbGuard**, **WristLux**, and **WristSense** for sensor-driven watch experiences
- **WristRandom**, **WristConvert**, **SquadTap**, **WristNote**, **WristDash**, **WristRevive**, and **WristPet**
- Private automation, MCP, AI experimentation, dashboards, internal tools, and product websites

These repositories vary from experiments to release candidates and production-stage products. Their inclusion here describes the portfolio, not public source availability.

</details>

### Patterns Repeated Across the Private Codebase

The private portfolio is not a set of disconnected demos. The same production-oriented patterns appear repeatedly:

- Explicit user initiation for sensitive actions, foreground services, sensors, audio, screenshots, and automation triggers
- Versioned phone-watch protocols with deterministic source-of-truth rules, stale-message rejection, and failure-specific states
- Local-first data models with no developer backend where one is not required
- Google Play Billing reconciliation, pending-purchase handling, restore flows, refund or revocation relocking, and clear free-versus-Pro boundaries
- Android Keystore usage, secret redaction, bounded imports, safe network policies, and privacy-focused diagnostics
- Release validation for lint, tests, minified builds, bundles, signing inputs, manifest constraints, API targets, and artifact checks
- Accessibility semantics, large-text resilience, compact round-screen handling, and honest UI status reporting
- Store-ready privacy policies, permissions documentation, Data Safety baselines, reviewer access flows, screenshots, and release checklists

---

## Earlier Public and Reference Work

Not every public repository represents my current flagship direction. Some are predecessors, focused examples, historical projects, sparse starter repositories, or maintained references.

- [**npu-windows**](https://github.com/Quazmoz/npu-windows): earlier Intel NPU local-LLM server and a predecessor to the broader InferBridge architecture
- [**TerraformHomeLab**](https://github.com/Quazmoz/TerraformHomeLab): infrastructure-as-code layer associated with the homelab platform
- [**GroupMeCommunityDocs**](https://github.com/Quazmoz/GroupMeCommunityDocs): GroupMe community documentation and reference material
- [**ai.quinnfavo.com**](https://github.com/Quazmoz/ai.quinnfavo.com): public site repository for AI-focused content and experiments
- [**devops-ai-prompts**](https://github.com/Quazmoz/devops-ai-prompts), [**helpfulscripts**](https://github.com/Quazmoz/helpfulscripts), and [**Public**](https://github.com/Quazmoz/Public): smaller public prompt, script, and example collections
- [**WebsiteDownChecker**](https://github.com/Quazmoz/WebsiteDownChecker), [**groupmebot**](https://github.com/Quazmoz/groupmebot), and [**Counter-Galaxy-Watch-App**](https://github.com/Quazmoz/Counter-Galaxy-Watch-App): earlier focused utilities and application work
- [**Blog**](https://github.com/Quazmoz/Blog), [**ansible**](https://github.com/Quazmoz/ansible), and [**ceph-ansible**](https://github.com/Quazmoz/ceph-ansible): historical, learning, or reference repositories

This separation keeps the public profile honest: active flagship work is promoted first, while older public code remains discoverable without being presented as current product strategy.

---

## Core Stack

| Area | Tools and technologies |
|---|---|
| **AI and agents** | MCP, OpenAI-compatible APIs, OpenVINO GenAI, local LLMs, Open WebUI, agent memory, tool interfaces, prompt and skill systems |
| **Languages** | Python, Rust, Go, TypeScript, Kotlin, PowerShell, Bash |
| **Data and backends** | PostgreSQL, Redis, Qdrant, Room, DataStore, FastAPI-style services, REST APIs, event-driven processing |
| **Infrastructure** | Terraform, Ansible, Kubernetes, Flux CD, Helm, Kustomize, Docker, SOPS, GitHub Actions, Jenkins |
| **Observability** | Prometheus, Grafana, structured logging, health checks, diagnostics, performance telemetry |
| **Android and Wear OS** | Jetpack Compose, Compose for Wear OS, Media3, Hilt, Room, Data Layer, tiles, complications, sensors, haptics, Play Billing |
| **Web** | React, Vite, TypeScript, Express, server-side rendering, Tailwind CSS, structured SEO |
| **Windows delivery** | PyInstaller, Inno Setup, portable packaging, release manifests, checksums, upgrade compatibility, signing gates |

---

## Current Direction

- Making local AI usable on ordinary Intel Windows hardware through **InferBridge**
- Building governed, inspectable context systems for agents through **MemoryOps**
- Turning agent behavior into reusable, testable assets through **AgentDefaults**
- Exposing real systems to agents through **MCP**, typed APIs, and controlled tool surfaces
- Productizing DevOps and automation patterns instead of leaving them as one-off scripts
- Shipping narrow, privacy-conscious Android and Wear OS utilities with disciplined release engineering
- Publishing technical walkthroughs and practical implementation guidance

---

## Elsewhere

- 🌐 Portfolio: [profile.quinnfavo.com](https://profile.quinnfavo.com)
- 🧠 Consulting and apps: [consultant.quinnfavo.com](https://consultant.quinnfavo.com)
- 💼 LinkedIn: [linkedin.com/in/quinnfavo](https://www.linkedin.com/in/quinnfavo/)
- ▶️ YouTube: [youtube.com/@QuinnFavo](https://www.youtube.com/@QuinnFavo)

---

<div align="center">

**Automation over ceremony. Utility over novelty. Systems that compound.**

</div>
