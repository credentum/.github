# Credentum

**Telemetry, security, and governance tooling for autonomous AI agents.**

Your AI agent just approved a $50K purchase order. Can you prove *why* it did?

Agents loop, fabricate, and drift — and mostly, nobody's watching. We build tools to log what
actually happened, catch what shouldn't, and give agents governable rules to act within. Not
because we distrust agents — because trust requires evidence.

*An independent R&D effort.*

## Tools (shipped)

### ao-lens · [npm](https://www.npmjs.com/package/ao-lens)
Static security analysis for AO/Lua processes. Catches auth bypasses, determinism violations,
nil-guard gaps, unsafe JSON, and replay bugs before they hit chain. Tree-sitter parser, 25+ built-in
checks, extensible with your own YAML rules. Runs as a CLI, MCP server, or GitHub Action.

### ao-mcp-server · [npm](https://www.npmjs.com/package/ao-mcp-server)
Talk to AO/Arweave from Claude or Cursor: query processes, send messages, spawn processes, execute
Lua, wallet-based signing. Five tools, zero config.

### Vivarium · agent telemetry harness
On-chain and off-chain tracking for autonomous agents: structured logging of every output, a
confabulation detector, vocabulary-drift measurement (Jaccard), token accounting (actual vs
requested), and stripped-context snapshots for comparing model state.

## Research — [Vivarium Lab](https://github.com/credentum/vivarium-lab)
Small, honest experiments on how autonomous agents behave and govern.

- **Governance as Computation** — in a multi-agent commons dilemma, giving agents the *pre-computed
  answer* (not more information, not moral prompts) is what prevents collapse: 80% vs 0% survival.
  *Preliminary (N=5), with full data and an honest limitations section.*
- **Agent Bootstrap** — 160 words of flat navigational anchors beat 1,000 words of injected memory
  (174 trials).
- **Movable Feast** — LLMs recall fixed holidays but can't compute movable ones (Easter: 0% across models).

## Projects

| Repo | What | Status |
|------|------|--------|
| [ao-lens](https://github.com/credentum/ao-lens) | AO/Lua security auditor | Shipped (npm) |
| [ao-mcp-server](https://github.com/credentum/ao-mcp-server) | AO/Arweave MCP tools | Shipped (npm) |
| [vivarium-lab](https://github.com/credentum/vivarium-lab) | Agent research + experiments | Active |

---
*Independent research on trustworthy autonomy.*
