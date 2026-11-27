# Arta AI Lab

**Multi-Agent Systems & Intelligent Automation** — an ArtaBlockchain Team project.

Arta AI Lab develops multi-agent AI systems: coordinated teams of specialized
AI agents designed to plan, research, analyze, create and communicate under human supervision.

Our server-deployed system — **Arta AI Team** — runs as a set of containerized services.
At the last infrastructure inspection (November 2026) the deployment comprised
**15 running Docker containers**, including nine agent services and the supporting
infrastructure (orchestration, gateway, data stores). Container availability is verified;
agent-level functionality is under evaluation.

This repository documents the architecture, intended agent roles and research direction.
It contains no source code, no server configuration and no internal operational data.

---

## Agent Team

Nine specialized agent services with intended roles:

| Agent | Intended specialization |
|---|---|
| **Director** | Coordinating the team, setting priorities and managing execution flow |
| **Strategist** | Long-term planning, scenario analysis, strategic options |
| **Analytics** | Data analysis, metrics, quantitative assessment |
| **Research** | Information gathering, investigation, source evaluation |
| **Learning** | Training programs, knowledge building, skill development |
| **Critic** | Quality review, argument evaluation, risk and gap detection |
| **Content** | Content production and editorial work |
| **Community** | Community operations and engagement |
| **Outreach** | External communications and partnership development |

The table describes designed roles. Verified runtime behavior of each agent is being
evaluated and is not claimed here.

See [AGENTS.md](./AGENTS.md) for the full role descriptions.

## Infrastructure

Containerized deployment (Docker), with orchestration, gateway and persistence layers:

- Business Orchestrator — workflow orchestration
- Manager — operational coordination
- Gateway — unified entry point for agent communication
- X Executor — task execution service
- PostgreSQL 16 — persistent storage
- Redis 7.4 — caching and message brokering

See [ARCHITECTURE.md](./ARCHITECTURE.md) for the architecture overview and diagrams.

## Research & Applications

- **[Arta Business Lab](docs/business-lab.md)** — a multi-agent business laboratory:
  role-based AI training, knowledge base, agent memory, business research, experiments,
  metrics and project management. Applied directions include real estate, business
  analytics and workflow automation.
- **[Diamond AI](docs/diamond-ai.md)** — a research effort in structured training and
  assessment of AI agents (academy-style curriculum, exams, datasets, evaluation).

## Status

- Arta AI Team: infrastructure operational — 15 containers observed in running state at the
  November 2026 inspection; agent-level functionality is under evaluation.
- Arta Business Lab: internal research and development; public materials describe structure,
  not data.
- Diamond AI: research and development in progress; no training results are claimed at
  this stage.

## Roadmap

See [ROADMAP.md](./ROADMAP.md).

## Security

See [SECURITY.md](./SECURITY.md). Server internals (addresses, credentials, internal
instructions) are intentionally not part of this repository.

## Links

- Website: https://artablockchain.in
- Email: support@artablockchain.in
- Telegram: https://t.me/ArtaBlockchain20
- GitHub profile: https://github.com/artablok

---

*Arta AI Lab is an engineering initiative of ArtaBlockchain Team. All systems operate under
human supervision. No autonomous claims are made beyond verified, documented state.*
