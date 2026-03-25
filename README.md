<div align="center">

# Lightweight AI API Gateway

**One API key. 25+ AI models. Zero complexity.**

[![Status](https://img.shields.io/badge/status-invite--only%20beta-yellow)](https://lightweight.one)
[![Docs](https://img.shields.io/badge/docs-docs.lightweight.one-green)](https://docs.lightweight.one)
[![API](https://img.shields.io/badge/API-api.lightweight.one-blue)](https://api.lightweight.one)

</div>

---

> **⚠️ Important:** The current Lightweight API is an **internal project** — originally built to solve our own needs. It is not a public service. Access is granted selectively to community members who request it. A fully public API (potentially under a different name or as a separate product) may be released in the future, but there is no timeline for this.

---

## What is Lightweight?

Lightweight is a unified AI API gateway that gives you access to **25+ models** from OpenAI, Anthropic, Google, and xAI — through a single OpenAI-compatible endpoint. No vendor lock-in, no multiple API keys, no hassle.

```bash
# That's it. Any OpenAI-compatible tool works instantly.
export OPENAI_BASE_URL="https://api.lightweight.one/v1"
export OPENAI_API_KEY="lw_sk_your-key-here"
```

### Supported Models

| Provider | Models |
|----------|--------|
| **OpenAI** | GPT-5.4, GPT-5.4 Mini, GPT-5.2, GPT-5.1, GPT-5.1 Codex, GPT-5 Mini, GPT-4.1, GPT-4o, and more |
| **Anthropic** | Claude Opus 4.6, Claude Opus 4.6 Fast, Claude Sonnet 4.6, Claude Sonnet 4.5, Claude Sonnet 4, Claude Opus 4.5, Haiku 4.5 |
| **Google** | Gemini 3.1 Pro, Gemini 3 Pro, Gemini 3 Flash, Gemini 2.5 Pro |
| **xAI** | Grok Code Fast |

> **More providers coming soon.** We plan to expand to Meta (Llama), DeepSeek, Mistral, and others as backend support grows. Check `GET /v1/models` for the live catalog.

### Works With

Claude Code, OpenCode, Cursor, Windsurf, Aider, Zed, Continue, Cline, LangChain, LiteLLM, and any OpenAI-compatible tool.

### Context Windows

Models retain their full context windows through the gateway. For example, Claude Opus 4.6 supports the full **200K token** context. Check `GET /v1/models` for each model's exact limits.

> **Note:** Extended thinking (reasoning) is supported for Claude models. The model reasons internally and thinking blocks are returned in the API response.

---

## Access

> **Lightweight is currently in invite-only beta.**

This project started as an internal solution to solve our own problems with AI API access. It's independent and experimental — not a commercial service with dedicated support teams or SLA guarantees.

### How to Request Access

Open a **[Discussion](https://github.com/templarsco/lightweight/discussions)** in the **Access Requests** category with:

1. **Who you are** — brief introduction
2. **What you want to build** — projects you plan to use the API for, or services you want to migrate
3. **Why Lightweight** — what draws you to a unified gateway

We review requests and grant invite codes on a case-by-case basis.

### What to Expect

| Aspect | Details |
|--------|---------|
| **Support** | Community-driven. No dedicated support team. Use Discussions and our [documentation](https://docs.lightweight.one). |
| **Uptime & SLA** | Variable. We're independent and monitor actively, but we don't guarantee SLAs. |
| **New Models** | Frontier models from major providers typically arrive same-day within hours. Some models may take longer depending on availability. |
| **Bugs & Issues** | Expected in beta. Report via [Issues](https://github.com/templarsco/lightweight/issues). Community PRs welcome. |
| **Pricing** | Free during beta. No hidden costs. |

---

## Community

This is the **community hub** for Lightweight. Here's how to participate:

### [Discussions](https://github.com/templarsco/lightweight/discussions)

- **Access Requests** — Request an invite code
- **General** — Ask questions, share experiences
- **Ideas & Suggestions** — Propose features, integrations, improvements
- **Show & Tell** — Share what you've built with Lightweight

### [Issues](https://github.com/templarsco/lightweight/issues)

- Bug reports
- API behavior problems
- Model-specific issues

### Contributing

Found a bug? Have a fix? PRs are welcome. The community helps shape this project:

- Report issues you encounter
- Suggest improvements to docs or the API
- Share workarounds and tips in Discussions
- Help other users in the community

---

## Quick Links

| Resource | Link |
|----------|------|
| Documentation | [docs.lightweight.one](https://docs.lightweight.one) |
| API Base URL | `https://api.lightweight.one/v1` |
| API Status | [lightweight.one/status](https://lightweight.one/status) |
| Dashboard | [lightweight.one/dashboard](https://lightweight.one/dashboard) |
| Model Catalog | `GET https://api.lightweight.one/v1/models` |

---

## FAQ

**Is this free?**
Yes, during the beta period. No credit card required.

**Is this open source?**
The API itself is private. This repo is the public community hub for access requests, discussions, and issue tracking. The [documentation](https://github.com/templarsco/docs) is open source.

**Can I trust this for production?**
Lightweight is experimental and independent. Uptime is variable. We recommend having a fallback for production-critical workloads.

**How fast do new models arrive?**
Frontier models from major providers typically arrive same-day within hours of release. Some models may take longer depending on availability.

**Which providers are supported?**
Currently OpenAI, Anthropic, Google, and xAI. We plan to expand to additional providers (Meta, DeepSeek, Mistral, etc.) in the future.

**Is there dedicated support?**
No. The community supports itself through Discussions and documentation. We actively monitor but don't provide 1:1 support.

---

<div align="center">

**[Request Access](https://github.com/templarsco/lightweight/discussions)** · **[Documentation](https://docs.lightweight.one)** · **[Status](https://lightweight.one/status)**

</div>
