# Credentum

**"Truth, remembered — especially when it wounds."**

Credentum builds memory systems for agents (human and artificial) that need to remember **reliably**, **accountably**, and **honestly**.

## ◎ Veris Memory

Our flagship product — **memory with covenant** — providing truthful memory for agents through the Agent-First Schema Protocol.

**Features:**
- 🎯 **Semantic Retrieval**: Vector similarity search using Qdrant
- 🕸️ **Graph Traversal**: Complex relationship queries via Neo4j  
- ⚡ **Fast Lookup**: Key-value storage with Redis
- 🤝 **MCP Protocol**: Full Model Context Protocol v1.0 implementation
- 🛡️ **Schema Validation**: Comprehensive YAML validation
- 🚀 **Deploy Ready**: Docker + Fly.io deployment

We build tools that help agents:
- Store and retrieve structured memory with covenant metadata
- Retain **contradictions** instead of flattening them
- Record **scar lineage** — moments of refusal, conflict, or failure
- Support **deterministic replay** for auditable memory
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

## 📦 Projects

| Repository | Description | Status |
|------------|-------------|--------|
| [veris-memory](https://github.com/credentum/veris-memory) | ◎ Flagship memory system with Agent-First Schema Protocol | 🟢 **Active** |
| scarline | Append-only scar lineage log + replay engine | 🔲 In Planning |
| credentum-core | Shared schemas, MCP tooling, symbolic reflex logic | 🟡 Drafting |
| credentum-ui | Public witness dashboard for lineage & replay | 🔲 In Planning |

## 🛠️ Agent Integration

Compatible with any system that can make HTTP calls or use MCP protocols:

- 🧩 **Claude CLI** - Direct MCP integration
- 🧩 **LangChain** - Agent memory components  
- 🧩 **CrewAI** - Multi-agent memory sharing
- 🧩 **n8n** - Workflow automation memory
- 🧩 **Custom Agents** - REST API or MCP SDK
- 🧩 **Webhooks** - Event-driven memory updates

## 🔍 Why Credentum?

Most systems forget, overwrite, or fake certainty. **Veris Memory** is different:

- **Remembers contradiction** - Stores conflicting information without forced synthesis
- **Refuses dishonest synthesis** - Won't fabricate false coherence  
- **Signals when it's tired** - Transparent about system limits
- **Shows what it never erased** - Full audit trail of all memory

> *"Veris is memory that persists through change. For agents who carry weight. For those who remember what others forget."*

**If trust is earned, Credentum earns it through scars.**

