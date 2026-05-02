# fazer.ai

**fazer > falar.** *(do > talk.)*

[![fazer.ai](./logo.svg)](https://fazer.ai?utm_source=github&utm_campaign=profile&utm_medium=hero)

While others talk about AI, we ship. We're engineers turning AI into **real competitive advantage**. No pretty slides. No empty promises. Just results.

> We build AI agents that operate any piece of software like a human expert. Just faster, and without mistakes.

## What we do

| Service | What it Means for You |
| ------- | --------------------- |
| **AI Development Consulting** | Claude Code, Codex and Gemini deployed as development infrastructure inside your team. Context engineering, autonomous agents, sandboxing and governance baked in. From 30 days to 1. |
| **Fast Testing at Scale** | A subscription that handles your AI backlog in isolated, production-safe environments. We validate before you invest in development. Recent runs: 70,000+ people served and 1.2M+ WhatsApp messages processed in a 30-day window. |
| **Special AI Projects** | End-to-end engineering for custom AI. Modern stack (LangGraph, NVIDIA H100, Kubernetes, Cloudflare Zero Trust). Banking, industrial, events, retail and real estate. |

ROI doesn't come from technology alone. It shows up when we pair business expertise with tailor-made automations.

## What's Here

We open-source the building blocks behind our work, organised in three tracks.

### Chatwoot and WhatsApp Suite

An open-source stack for WhatsApp-first customer engagement, anchored on our actively-maintained Chatwoot fork.

| Repo | What it Does |
| ---- | ------------ |
| [**chatwoot**](https://github.com/fazer-ai/chatwoot) | Our Chatwoot fork: multi-provider WhatsApp (Baileys, Z-API, 360Dialog, Cloud API), native group conversations, internal agent chat, scheduled and recurring messages, full pt-BR support. |
| [**baileys-api**](https://github.com/fazer-ai/baileys-api) | HTTP REST wrapper around the Baileys WhatsApp library. Connect multiple accounts, send and receive messages, manage sessions. Bun and Elysia. |
| [**n8n-nodes-chatwoot**](https://github.com/fazer-ai/n8n-nodes-chatwoot) | n8n community node with 40+ operations, including the Kanban, scheduled messages and WhatsApp provider features exclusive to our fork. |
| [**mcp-chatwoot**](https://github.com/fazer-ai/mcp-chatwoot) | Model Context Protocol server exposing 129 Chatwoot tools to Claude Desktop, VS Code, and other MCP clients. |

### Claude Code Ecosystem

Plugins, skills and MCP servers we use daily and release publicly.

| Repo | What it Does |
| ---- | ------------ |
| [**mcp-obsidian**](https://github.com/fazer-ai/mcp-obsidian) | MCP server for Obsidian. Give your AI agents read and write access to your vault. Published on npm. |
| [**chatwoot-skills**](https://github.com/fazer-ai/chatwoot-skills) | Claude Code plugin teaching Claude how to operate Chatwoot via mcp-chatwoot. 8 skills, 30 evaluation scenarios. |
| [**n8n-to-langgraph**](https://github.com/fazer-ai/n8n-to-langgraph) | Claude Code plugin that converts n8n workflows into LangGraph TypeScript applications, with built-in Langfuse observability. |
| [**coolify-migrate**](https://github.com/fazer-ai/coolify-migrate) | Claude Code skill for zero-downtime Coolify migrations between VPS servers. |
| [**skills**](https://github.com/fazer-ai/skills) | Marketplace listing for fazer.ai's subscription Claude Code plugins, distributed via our private npm registry. |
| [**mcp-inspector**](https://github.com/fazer-ai/mcp-inspector) | Our patched fork of Anthropic's MCP Inspector. |

### Templates and Infrastructure

| Repo | What it Does |
| ---- | ------------ |
| [**bunfire**](https://github.com/fazer-ai/bunfire) | Opinionated full-stack TypeScript starter: Bun, Elysia, React 19, Tailwind v4. Auth, Prisma, i18n, theming and CI baked in. |
| [**langfuse-proxy**](https://github.com/fazer-ai/langfuse-proxy) | Lightweight Bun and Elysia proxy for OpenAI-compatible APIs with Langfuse telemetry built in. |
| [**n8n-workflows**](https://github.com/fazer-ai/n8n-workflows) | Catalogue of n8n workflow packs we maintain, consumed by our Claude Code plugins and partner tooling. |
| [**postgres-16-pgvector**](https://github.com/fazer-ai/postgres-16-pgvector) | PostgreSQL 16 Docker image with pgvector preinstalled, for RAG and embeddings workloads. |
| [**claude-code-vs-the-world**](https://github.com/fazer-ai/claude-code-vs-the-world) | Side project: an AI showdown pitting Claude Code against the alternatives. |

## Contributing

1. Fork the repository you want to improve.
2. Branch off main (`git checkout -b feature/your-thing`).
3. Open a PR with a clear description and test plan.

Our team reviews actively. For larger or strategic contributions, please reach out first via the contact channels below.

## License

Unless otherwise noted in a specific repository, code released by fazer.ai is **MIT-licensed**.

## Contact

| | |
| --- | --- |
| **Website** | [fazer.ai](https://fazer.ai?utm_source=github&utm_campaign=profile&utm_medium=contact) |
| **WhatsApp (Strategic Consulting)** | [+55 11 5199-9937](https://api.whatsapp.com/send?phone=551151999937) |
| **Email** | <contact@fazer.ai> |
| **Office** | Av. Brigadeiro Faria Lima, 1811, Conj. 115, Jardim Paulistano, São Paulo, SP, 01452-001, Brazil |

> Make your ideas happen.
