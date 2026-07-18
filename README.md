<div align="center">

[fran.olivares.ai](https://fran.olivares.ai) · [olivares.ai](https://olivares.ai) · [@olivaresai](https://github.com/olivaresai) · [LinkedIn](https://www.linkedin.com/in/francisco-olivares-mart%C3%ADn-165b7b235/)

</div>

---

## Olivares AI

**Ground truth for enterprise AI.** Know what your AI touches, decide what it can do, and prove it.

[![License](https://img.shields.io/badge/license-AGPL--3.0-F08000?style=flat&labelColor=1A1A19)](https://github.com/olivaresai/olivares)
[![Status](https://img.shields.io/badge/status-beta-F08000?style=flat&labelColor=1A1A19)](https://olivares.ai)
[![First release](https://img.shields.io/badge/first_release-v26.7.0-F08000?style=flat&labelColor=1A1A19)](https://olivares.ai)
[![Go](https://img.shields.io/badge/Go-1.26-00ADD8?style=flat&labelColor=1A1A19&logo=go&logoColor=white)](https://go.dev)

Integrate, manage and secure AI in your enterprise — **built around Claude and Claude Code**. Olivares AI gives Claude and the rest of your AI what they need to work in a real organization — context, access to the right resources, managed sessions — and gives you the granular permissions and controls to run all of it across your infrastructure. It complements Claude; it does not compete.

A single self-hosted Go binary with the console embedded — on Linux, Docker, Kubernetes, on-prem or fully air-gapped. Configuration, audit and observation data never leave your perimeter. Read-first and minimal-data by design; honesty is a design axis, not a disclaimer.

| | |
| --- | --- |
| Form | Single static Go binary, console embedded |
| Scope | 29 modules · 157 integrations · 26 compliance framework catalogs |
| Enforcement | 4 deny-closed points: Claude Code hook · inference proxy · MCP gate · A2A gate |
| Agent surfaces | Claude Code · gemini-cli · Cursor · Codex CLI · opencode · goose · cline · OpenHands · OpenClaw · Hermes · Teams |
| Storage | SQLite (single-node, air-gap) or PostgreSQL with row-level security |
| APIs | REST + gRPC · Terraform provider · client SDKs for Go, Java, Python, TypeScript |
| License | AGPL-3.0 open core · Apache-2.0 SDK & connectors · additive commercial enterprise line |

→ [olivares.ai](https://olivares.ai) · [github.com/olivaresai/olivares](https://github.com/olivaresai/olivares)

---

## usulnet

[![License](https://img.shields.io/badge/license-AGPL--3.0-FE9A37?style=flat&labelColor=1A1A19)](https://www.gnu.org/licenses/agpl-3.0.en.html)
[![Release](https://img.shields.io/github/v/release/fran-olivares/usulnet?include_prereleases&style=flat&labelColor=1A1A19&color=FE9A37)](https://github.com/fran-olivares/usulnet/releases)
[![Go](https://img.shields.io/badge/Go-1.25-00ADD8?style=flat&labelColor=1A1A19&logo=go&logoColor=white)](https://go.dev)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat&labelColor=1A1A19&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![NATS JetStream](https://img.shields.io/badge/NATS-2.12_JetStream-27AAE1?style=flat&labelColor=1A1A19&logo=natsdotio&logoColor=white)](https://nats.io)

Self-hosted Docker management platform. Single binary, ~70 MB, no runtime dependencies. A direct alternative to Portainer with wider scope and no SaaS dependency: containers, images, volumes, networks, Compose stacks, Swarm, Trivy CVE scanning, SBOM, RBAC with 46 granular permissions, TOTP 2FA, LDAP/OIDC/OAuth2, encrypted secrets, audit logging, scheduled backups, real-time metrics and alerting, Nginx reverse proxy with Let's Encrypt, and multi-node master/agent over NATS JetStream with mTLS. Server-side rendered with Templ + HTMX + Alpine.js — no SPA, no Node.js at runtime.

**Editions** — Community (AGPL-3.0, free) · Business (€79 / node / year) · Enterprise

→ [usulnet.com](https://usulnet.com) · [github.com/fran-olivares/usulnet](https://github.com/fran-olivares/usulnet)

---

## Alma

[![alma-sdk](https://img.shields.io/npm/v/@olivaresai/alma-sdk?label=alma-sdk&color=FE9A37&labelColor=1A1A19)](https://www.npmjs.com/package/@olivaresai/alma-sdk)
[![alma-mcp](https://img.shields.io/npm/v/@olivaresai/alma-mcp?label=alma-mcp&color=FE9A37&labelColor=1A1A19)](https://www.npmjs.com/package/@olivaresai/alma-mcp)
[![vscode](https://img.shields.io/visual-studio-marketplace/v/olivares.alma-vscode?label=vscode-extension&color=FE9A37&labelColor=1A1A19)](https://marketplace.visualstudio.com/items?itemName=olivares.alma-vscode)

Persistent memory layer for AI — facts, preferences and decisions captured from conversations and made available across every session, tool and platform. REST API, TypeScript SDK, MCP server and VSCode extension, running at the edge on Cloudflare Workers.

→ [alma.olivares.ai](https://alma.olivares.ai)

---

```
languages    Go · TypeScript · SQL · Bash
runtime      single static binaries · Node.js · Cloudflare Workers · Docker
storage      PostgreSQL · SQLite · Redis · KV · R2 · Vectorize
messaging    NATS JetStream · Cloudflare Queues
infra        Arch Linux · Nginx · ~100 self-hosted containers
```
