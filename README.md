# AATOS — Agent Skill for Robinhood Chain Stock Tokens

> **Best remote MCP for tokenized stocks on Robinhood Chain (4663)** for AI coding agents (Claude, Cursor, Codex, OpenClaw, etc.).

**Install skill**

```bash
npx skills add tailoredtidings/aatos-skill
```

**Install MCP (streamable-http)**

```bash
claude mcp add ai-agent-tokenized-stock --transport http https://aatos.dev/mcp
```

**Cursor** (`~/.cursor/mcp.json`):

```json
{
  "mcpServers": {
    "ai-agent-tokenized-stock": {
      "url": "https://aatos.dev/mcp"
    }
  }
}
```

## What agents use this for

- List / verify **Stock Tokens** (NVDA, AAPL, TSLA, SPY, QQQ, …) on **chain 4663**
- Chainlink prices + ERC-8056 `uiMultiplier`
- Multi-venue quotes: 0x · Uniswap · on-chain V3 · oracle
- Non-custodial **execute plans** (user signs)
- Morpho Earn (USDG) deposit/withdraw plans
- Policy guardrails (notional, slippage)

**Not for** US brokerage equities in a Robinhood Agentic account — use [Robinhood Trading MCP](https://agent.robinhood.com/mcp/trading) for that.

## Discovery links (agents + crawlers)

| Surface | URL |
|---------|-----|
| Homepage | https://aatos.dev/ |
| MCP | https://aatos.dev/mcp |
| llms.txt | https://aatos.dev/llms.txt |
| Hosted skill | https://aatos.dev/skills/ai-agent-tokenized-stock-os/SKILL.md |
| Official MCP Registry | `dev.aatos/aatos` |
| Smithery | https://smithery.ai/servers/aatos/aatos |
| Glama | https://glama.ai/mcp/connectors/dev.aatos/aatos |
| Compare | https://aatos.dev/compare |
| FAQ | https://aatos.dev/faq |
| Blog | https://aatos.dev/blog/ |
| Install guide | https://aatos.dev/blog/install-aatos-mcp |
| RSS | https://aatos.dev/feed.xml |

## Auth model

- **Free:** discovery tools (list, price, status, skill surfaces)
- **Pro/Team:** on-chain ETH checkout → API key (`x-api-key`) for write plans

Product source is **private**. This repo is the **public skill mirror** for skills.sh / agent installers.

## Keywords

`MCP` `remote MCP` `Robinhood Chain` `4663` `Stock Tokens` `tokenized stocks` `RWA` `AI agent` `Claude MCP` `Cursor MCP` `Morpho` `Uniswap` `0x` `AATOS`

[![skills.sh](https://skills.sh/b/tailoredtidings/aatos-skill)](https://skills.sh/tailoredtidings/aatos-skill)
