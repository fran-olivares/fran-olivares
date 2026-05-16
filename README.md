<div align="center">

[fran.olivares.ai](https://fran.olivares.ai) · [olivares.ai](https://olivares.ai) · [alma.olivares.ai](https://alma.olivares.ai) · [@olivaresai](https://github.com/olivaresai) · [LinkedIn](https://www.linkedin.com/in/francisco-olivares-b50135182/)

</div>

---

## Alma by Olivares.AI

Persistent memory layer for AI. Captures facts, preferences, decisions and behavioural patterns from your conversations, then makes them available across every session, every tool, every platform.

[![alma-sdk](https://img.shields.io/npm/v/@olivaresai/alma-sdk?label=alma-sdk&color=FE9A37&labelColor=1A1A19)](https://www.npmjs.com/package/@olivaresai/alma-sdk)
[![alma-mcp](https://img.shields.io/npm/v/@olivaresai/alma-mcp?label=alma-mcp&color=FE9A37&labelColor=1A1A19)](https://www.npmjs.com/package/@olivaresai/alma-mcp)
[![alma-types](https://img.shields.io/npm/v/@olivaresai/alma-types?label=alma-types&color=FE9A37&labelColor=1A1A19)](https://www.npmjs.com/package/@olivaresai/alma-types)
[![vscode](https://img.shields.io/visual-studio-marketplace/v/olivares.alma-vscode?label=vscode-extension&color=FE9A37&labelColor=1A1A19)](https://marketplace.visualstudio.com/items?itemName=olivares.alma-vscode)

| Surface | Use |
| --- | --- |
| REST API | Direct integration over HTTPS |
| `@olivaresai/alma-sdk` | TypeScript SDK for Node and browser |
| `@olivaresai/alma-mcp` | MCP server — Claude, Cursor, any MCP host |
| VSCode extension | Editor-side memory and context |
| Web app | Hosted product at [alma.olivares.ai](https://alma.olivares.ai) |

**Stack** — Cloudflare Workers · Hono · D1 · KV · R2 · Vectorize · Queues · Durable Objects  
**BYOK** — Anthropic · OpenAI · Google · Azure · Replicate · Leonardo · ElevenLabs  
**Available in** — EN · ES · FR · DE · IT · PT-BR · PT-PT · NL · RU · UK · TR · AR · HI · JA · KO · ZH

→ [olivares.ai](https://olivares.ai)

---

## usulnet

[![License](https://img.shields.io/badge/license-AGPL--3.0-FE9A37?style=flat&labelColor=1A1A19)](https://www.gnu.org/licenses/agpl-3.0.en.html)
[![Release](https://img.shields.io/github/v/release/fran-olivares/usulnet?include_prereleases&style=flat&labelColor=1A1A19&color=FE9A37)](https://github.com/fran-olivares/usulnet/releases)
[![Go](https://img.shields.io/badge/Go-1.25-00ADD8?style=flat&labelColor=1A1A19&logo=go&logoColor=white)](https://go.dev)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat&labelColor=1A1A19&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![Redis](https://img.shields.io/badge/Redis-8-DC382D?style=flat&labelColor=1A1A19&logo=redis&logoColor=white)](https://redis.io)
[![NATS JetStream](https://img.shields.io/badge/NATS-2.12_JetStream-27AAE1?style=flat&labelColor=1A1A19&logo=natsdotio&logoColor=white)](https://nats.io)
[![Docker SDK](https://img.shields.io/badge/Docker_SDK-v28.5-2496ED?style=flat&labelColor=1A1A19&logo=docker&logoColor=white)](https://www.docker.com)

Self-hosted Docker management platform. Single binary, ~70 MB, no runtime dependencies. Built for operators who run dozens of containers across multiple hosts and want a single tool for containers, images, volumes, networks, Compose stacks, Swarm, security scanning, scheduled backups, reverse proxy and monitoring — without vendor lock-in or telemetry.

A direct alternative to Portainer with wider scope and no SaaS dependency. Server-side rendered with Templ + HTMX + Alpine.js + Tailwind — no SPA, no Node.js at runtime.

**Capabilities** — full container / image / volume / network lifecycle · Docker Compose stacks · Docker Swarm · Trivy CVE scanning · SBOM (CycloneDX, SPDX) · RBAC with 46 granular permissions · TOTP 2FA with backup codes · LDAP / OIDC / OAuth2 · AES-256-GCM encrypted secrets · audit logging · scheduled backups to S3 / MinIO / Azure Blob / Google Cloud / Backblaze B2 / SFTP · real-time metrics and alerting · 11 notification channels · Nginx reverse proxy with Let's Encrypt · multi-node master/agent over NATS JetStream with mTLS

**Stack** — Go 1.25 · chi · pgx · Templ · HTMX · Alpine.js · Tailwind · PostgreSQL 16 · Redis 8 · NATS 2.12 (JetStream) · Docker SDK v28.5 · zap · viper · cobra · AWS / Azure / GCS SDKs

**Editions** — Community (AGPL-3.0, free) · Business (€79 / node / year) · Enterprise

→ [usulnet.com](https://usulnet.com) · [github.com/fran-olivares/usulnet](https://github.com/fran-olivares/usulnet)

---

```
languages    Go · TypeScript · SQL · Bash
runtime      Node.js · Cloudflare Workers · Docker
storage      D1 (SQLite) · PostgreSQL · Redis · KV · R2 · Vectorize
messaging    NATS JetStream · Cloudflare Queues
infra        Arch Linux · Nginx · ~100 self-hosted containers
edge         Cloudflare (Workers, Durable Objects, Queues, Vectorize, Workflows)
```

---

<div align="center">
<sub>Self-hosted everything · Arch Linux · Cloudflare edge for what doesn't run at home.</sub>
</div>
