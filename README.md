<div align="center">

<a href="https://github.com/michaelbeatman/ARCHON-OS">
  <img src="./archon_header.png" alt="Archon OS — Agentic Operating System" width="1024" />
</a>

# Archon OS — Self-Hosted Multi-Agent Operating System

**Built on [Hermes Agent](https://github.com/NousResearch/hermes-agent) (Nous Research) · MIT Licensed · Local-First & Zero-Egress Ready**

[![Main Repository](https://img.shields.io/badge/GitHub-michaelbeatman%2FARCHON--OS-181717?style=for-the-badge&logo=github)](https://github.com/michaelbeatman/ARCHON-OS)
[![Live Docs](https://img.shields.io/badge/Web-Overview_%26_Docs-3d6b4f?style=for-the-badge)](https://michaelbeatman.github.io/ARCHON-OS/)
[![Release](https://img.shields.io/badge/Release-v0.5.4.2-6366f1?style=for-the-badge)](https://github.com/michaelbeatman/ARCHON-OS/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](https://github.com/michaelbeatman/ARCHON-OS/blob/main/LICENSE)

[**🇬🇧 English README**](https://github.com/michaelbeatman/ARCHON-OS#readme) · [**🇩🇪 Deutsches README**](https://github.com/michaelbeatman/ARCHON-OS/blob/main/README.de.md) · [**📘 Manual (EN PDF, 97 pp.)**](https://github.com/michaelbeatman/ARCHON-OS/blob/main/docs/system/ARCHON_OS_SYSTEM_MANUAL_2026_EN.pdf) · [**📘 Handbuch (DE PDF, 97 S.)**](https://github.com/michaelbeatman/ARCHON-OS/blob/main/docs/system/ARCHON_OS_SYSTEM_HANDBUCH_2026.pdf)

</div>

---

### Main Project: [michaelbeatman/ARCHON-OS](https://github.com/michaelbeatman/ARCHON-OS)

Archon OS extends **Hermes Agent** into a self-hosted multi-agent workspace for founders, teams, and domain specialists:

- **70 Specialist Agent Profiles across 8 Domains** (`agent_profiles.json`) with 3-tier `SOUL.md` prompts (`Compact` / `Pro` / `Full`) to keep context windows lean.
- **AI Boardroom (55 Frameworks):** Multi-perspective debates with isolated specialist drafts, critic cross-examination, and executive synthesis (Pre-Mortem, Six Thinking Hats, OKR, Blue Ocean, M&A Due Diligence).
- **Zero-Egress & OmniRoute Cost Control:** Routes sensitive finance, tax, contract, and CRM tasks strictly to local models (Ollama / LM Studio) inside an `internal: true` Docker network.
- **Tamper-Evident Governance:** SHA-256 hash-chained audit logs, four-eyes Kanban approval gates, EU AI Act classification, and 1-click GoBD procedural documentation export.
- **Local Knowledge & Automation:** Native Obsidian Vault synchronization, local AnythingLLM/Chroma RAG, n8n workflow bridge, Telegram integration, and a built-in MCP Server (`/mcp`).

| Mission Control & Operations | AI Boardroom Debate (55 Frameworks) |
|---|---|
| [![Mission Control](https://raw.githubusercontent.com/michaelbeatman/ARCHON-OS/main/docs/system/screenshots/mission_control.png)](https://github.com/michaelbeatman/ARCHON-OS) | [![AI Boardroom](https://raw.githubusercontent.com/michaelbeatman/ARCHON-OS/main/docs/system/screenshots/demo_4_boardroom.gif)](https://github.com/michaelbeatman/ARCHON-OS) |

### Quick Start

```bash
git clone https://github.com/michaelbeatman/ARCHON-OS.git
cd ARCHON-OS
docker compose up -d
```

Or try the **Zero-Key Read-Only Demo** without API keys:

```bash
ARCHON_DEMO_MODE=true docker compose -f docker-compose.demo.yml up --build -d
# Open http://localhost:8501
```

👉 **[Explore the full repository, documentation, and source code at `michaelbeatman/ARCHON-OS`](https://github.com/michaelbeatman/ARCHON-OS)**
