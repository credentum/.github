# Credentum

**Truth, remembered.**

Your AI agent just approved a $50K purchase order. Can you prove why?

We build tools that make agent decisions auditable.

## Shipped

### ao-lens

Security auditing for AO processes. Catches auth bypasses, determinism violations, nil guard issues, and unsafe JSON handling before they hit production.

```bash
npm install -g ao-lens
```

41 built-in rules. Write your own in YAML. Runs as CLI, MCP server, or GitHub Action.

[![npm](https://img.shields.io/npm/v/ao-lens)](https://www.npmjs.com/package/ao-lens)

### ao-mcp-server

Talk to AO/Arweave from Claude Desktop or Cursor.

```bash
npm install -g ao-mcp-server
```

Query processes. Send messages. Spawn new ones. Execute Lua. Five tools, zero config.

[![npm](https://img.shields.io/npm/v/ao-mcp-server)](https://www.npmjs.com/package/ao-mcp-server)

### Veritas

Witness for AI decisions. Sign in <1ms. Settle to Arweave permanently.

Your agent made a decision. Veritas proves it.

**Try it:** `curl api.credentum.ai:3100/health`

## Projects

| Repo | What | Status |
|------|------|--------|
| [ao-lens](https://github.com/credentum/ao-lens) | AO/Lua security auditor | Live |
| [ao-mcp-server](https://github.com/credentum/ao-mcp-server) | AO/Arweave MCP tools | Live |
| [veritas](https://github.com/credentum/veritas) | Decision witness | Production |
| veris-memory | Agent memory | Building |

---

*If trust is earned, we earn it through scars.*
