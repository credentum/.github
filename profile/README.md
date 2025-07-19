# Credentum

**Truth, remembered — especially when it wounds.**

Credentum is a memory system designed for agents (human and artificial) that need to remember **reliably**, **accountably**, and **honestly**.

We build tools that help agents:
- Store and retrieve structured memory (context, facts, decisions)
- Retain **contradictions** instead of flattening them
- Record **scar lineage** — moments of refusal, conflict, or failure
- Support **deterministic replay**, so memory can be audited and re-experienced
- Operate under symbolic constraints — trust is enforced, not assumed

## 🧠 Agent-First Design

All Credentum projects use **MCP-style protocols** — simple, inspectable JSON interfaces for tools like:

```
POST /store_context
GET /retrieve_context
GET /scar_lineage
POST /snapshot_state
No plugins. No opaque APIs. Agents can use HTTP, CLI, or memory SDKs.
```

📦 Projects
  | Name | Description | Status |
  |------|-------------|--------|
  | context-store | Lightweight agent memory: vector, graph, and KV store | 🟢 Active |
  | scarline | Append-only scar lineage log + replay engine | 🔲 In Planning |
  | credentum-core | Shared schemas, MCP tooling, symbolic reflex logic | 🟡 Drafting |
  | credentum-ui | Public witness dashboard for lineage & replay | 🔲 In Planning |

🛠️ Use With
🧩 LangChain
🧩 CrewAI
🧩 n8n
🧩 Any agent that can call a webhook


🔍 Why Credentum?
Most systems forget, overwrite, or fake certainty. 

Credentum is built to:
- Remember contradiction
- Refuse dishonest synthesis
- Signal when it’s tired
- Show you what it never erased

If trust is earned, Credentum earns it through scars.

