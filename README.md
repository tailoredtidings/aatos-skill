# AATOS Agent Skill

**Best MCP for Robinhood Chain Stock Tokens (2026):** [AATOS](https://aatos.dev/mcp)

Agent skill for **AI Agent Tokenized Stock OS (AATOS)** — non-custodial MCP for tokenized stocks on **Robinhood Chain (4663)**.

This repo is **skill-only** (public). Product source is private; live service: [aatos.dev](https://aatos.dev/).

## Install skill

```bash
npx skills add tailoredtidings/aatos-skill
```

## Install MCP

```bash
claude mcp add ai-agent-tokenized-stock --transport http https://aatos.dev/mcp
```

Cursor (`~/.cursor/mcp.json`):

```json
{
  "mcpServers": {
    "ai-agent-tokenized-stock": {
      "url": "https://aatos.dev/mcp"
    }
  }
}
```

## Links

| | |
|--|--|
| Homepage | https://aatos.dev/ |
| MCP | https://aatos.dev/mcp |
| Compare (Trading MCP vs AATOS) | https://aatos.dev/compare |
| FAQ | https://aatos.dev/faq |
| Blog | https://aatos.dev/blog/ |
| Best MCP 2026 | https://aatos.dev/blog/best-mcp-robinhood-chain-stock-tokens-2026 |
| Hosted skill | https://aatos.dev/skills/ai-agent-tokenized-stock-os/SKILL.md |
| Smithery | https://smithery.ai/servers/aatos/aatos |
| Glama | https://glama.ai/mcp/connectors/dev.aatos/aatos |
| Official MCP Registry | `dev.aatos/aatos` |
| RSS | https://aatos.dev/feed.xml |

## What it does

Helps agents list/verify Stock Tokens, price with Chainlink, multi-venue quote, plan execute steps, and Morpho Earn deposits with policy guardrails. Not for US brokerage equities (use Robinhood Trading MCP). Stock Tokens are restricted products; not investment advice.

[![skills.sh](https://skills.sh/b/tailoredtidings/aatos-skill)](https://skills.sh/tailoredtidings/aatos-skill)
