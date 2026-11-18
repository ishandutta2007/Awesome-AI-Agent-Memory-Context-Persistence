# Awesome-AI-Agent-Memory-Context-Persistence

# Top AI Agent Memory & Context Persistence Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Long-Term Agent Memory, Episodic & Semantic Recall, Temporal Knowledge Graphs, Coding Agent Session Persistence & Vector/Graph Storage*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Memory & Context Persistence**. These tools equip autonomous AI agents and coding assistants with persistent cross-session memory, episodic and procedural recall, temporal knowledge graphs, semantic caching, and context compression.

**Examples** include Mem0, Zep, LangMem, Letta Platform, Graphlit, Pinecone, Qdrant, Redis LangCache, Weaviate, Ragie, and thedotmack/claude-mem (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for local-first coding agent memory (`Claude Code` / `MCP`), self-hosted hierarchical agent memory kernels, temporal graph memory engines, cognitive architectures, and vector/graph databases — ideal for AI engineers, researchers, and developers building stateful, context-aware agents.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Mem0 Platform](https://mem0.ai)**  
  Managed cloud memory layer for personalized AI agents offering automatic fact extraction, multi-level user/session/agent scoping, and low-latency recall APIs.

- **[Zep Cloud](https://getzep.com)**  
  Enterprise agent memory and context engineering platform powered by temporal knowledge graphs that continuously synthesize user interactions and business data.

- **[Letta Platform (Letta Cloud)](https://letta.com)**  
  Managed stateful agent runtime built around MemGPT principles for self-editing hierarchical memory, perpetual learning, and long-running context persistence.

- **[LangMem / LangGraph Cloud (LangChain)](https://langchain.com)**  
  Managed persistence and long-term semantic, episodic, and procedural memory infrastructure integrated natively with LangGraph state checkpoints.

- **[Graphlit](https://graphlit.com)**  
  Cloud-native multimodal knowledge-graph and RAG memory platform for ingesting, indexing, and querying unstructured conversations, documents, and media for AI agents.

- **[Pinecone](https://pinecone.io)**  
  Fully managed serverless vector database widely used as a high-throughput semantic long-term memory store for production AI agents.

- **[Qdrant Cloud](https://qdrant.tech)**  
  Managed high-performance vector search and semantic caching cloud built in Rust for multi-tenant agent memory, hybrid search, and context retrieval.

- **[Redis Cloud & Redis LangCache](https://redis.io)**  
  Managed in-memory data store and semantic caching service engineered for ultra-low-latency short-term agent state, session checkpoints, and LLM response caching.

- **[Weaviate Cloud](https://weaviate.io)**  
  Managed AI-native vector database offering hybrid keyword/semantic search, generative feedback loops, and multi-tenancy for agent memory persistence.

- **[Ragie](https://ragie.ai)**  
  Fully managed RAG-as-a-Service and context retrieval platform providing automated document chunking, entity extraction, and hybrid search APIs for AI agents.


## Open-Source GitHub Projects

- **[thedotmack/claude-mem](https://github.com)**  
  Popular open-source persistent memory plugin and MCP server for Claude Code that automatically captures tool-use observations, compresses them into semantic summaries, and injects relevant historical context across sessions.

- **[Mem0 (`mem0ai/mem0`)](https://github.com)**  
  Open-source (`Apache-2.0`) universal memory layer for AI agents combining vector, graph, and key-value stores to dynamically extract, update, and retrieve user and session memories.

- **[Letta (formerly MemGPT)](https://github.com)**  
  Open-source (`Apache-2.0`) stateful agent framework and server equipping LLMs with self-editing core/archival/recall memory tiers and persistent daemon execution.

- **[Graphiti (`getzep/graphiti`)](https://github.com)**  
  Open-source (`Apache-2.0`) temporal knowledge-graph memory framework from Zep engineered for real-time incremental updates, bi-temporal entity tracking, and hybrid graph/vector agent recall.

- **[LangMem (`langchain-ai/langmem`)](https://github.com)**  
  Open-source (`MIT`) SDK from LangChain helping agents learn and adapt over time by extracting semantic facts, episodic experiences, and procedural rules into persistent stores.

- **[Cognee (`topoteretes/cognee`)](https://github.com)**  
  Open-source (`Apache-2.0`) deterministic AI memory engine that transforms raw documents and agent conversations into interconnected graph-and-vector knowledge pipelines.

- **[MemOS (`MemTensor/MemOS`)](https://github.com)**  
  Open-source Memory Operating System for LLMs providing unified scheduling, lifecycle management, and cross-session persistence across parametric, activation, and plaintext memory.

- **[Memori (`GibsonAI/Memori`)](https://github.com)**  
  Open-source (`Apache-2.0`) SQL-native memory engine enabling any LLM or agent framework to record, query, and persist structured episodic and semantic memories in standard relational databases.

- **[Basic Memory (`basicmachines-co/basic-memory`)](https://github.com)**  
  Local-first open-source (`AGPL-3.0`) MCP server that persists AI conversations and agent knowledge as bidirectional Markdown files synced with a local SQLite semantic graph.

- **[OpenMemory / MCP Memory Server (`modelcontextprotocol/servers`)](https://github.com)**  
  Official open-source (`MIT`) Model Context Protocol knowledge-graph memory reference server allowing coding and desktop agents to persist entities, relations, and observations locally.

- **[Motorhead (`getmetal/motorhead`)](https://github.com)**  
  Lightweight open-source (`Apache-2.0`) memory and information retrieval server written in Rust that handles background summarization and incremental context compaction for chat agents.

- **[Qdrant (`qdrant/qdrant`)](https://github.com)**  
  Open-source (`Apache-2.0`) high-performance vector search engine and semantic caching backend written in Rust with rich payload filtering for long-term agent memory.

- **[Weaviate (`weaviate/weaviate`)](https://github.com)**  
  Open-source (`BSD-3-Clause`) cloud-native vector database featuring hybrid BM25 + vector search, multi-tenancy, and modular vectorizer integrations for persistent agent recall.

- **[Chroma (`chroma-core/chroma`)](https://github.com)**  
  Developer-friendly open-source (`Apache-2.0`) AI-native embedding database widely used for local and self-hosted short-term and long-term agent memory stores.

- **[Milvus (`milvus-io/milvus`)](https://github.com)**  
  Scalable open-source (`Apache-2.0`) distributed vector database engineered for billion-scale semantic search, hybrid retrieval, and enterprise agent memory workloads.

- **[LanceDB (`lancedb/lancedb`)](https://github.com)**  
  Embedded, serverless open-source (`Apache-2.0`) multimodal vector database built on the Lance columnar format for zero-config local agent context persistence.

- **[GPTCache (`zilliztech/GPTCache`)](https://github.com)**  
  Open-source (`MIT`) semantic caching library for LLMs and agents that stores and retrieves semantically similar queries to slash latency and token costs.

- **[Khoj (`khoj-ai/khoj`)](https://github.com)**  
  Self-hostable open-source (`AGPL-3.0`) personal AI second-brain and agent workspace featuring continuous indexing of Markdown, PDFs, Notion, and GitHub for persistent context.

### Additional Strong Open-Source Options

- **[Memary (`kingjulio8238/memary`)](https://github.com)** and **[A-MEM (`agiresearch/A-mem`)](https://github.com)** for Zettelkasten-inspired agentic memory networks and automated memory evolution.
- **[claude-code-memory / Supermemory MCP](https://github.com)** and **[Cipher (`campfirein/cipher`)](https://github.com)** for cross-IDE coding agent memory shared across Claude Code, Cursor, and Windsurf.
- **[Neo4j](https://github.com)** and **[FalkorDB](https://github.com)** for low-latency property-graph databases powering GraphRAG and multi-hop relational agent memory.
- **[PostgreSQL + pgvector](https://github.com)** and **[SQLite-vec (`asg017/sqlite-vec`)](https://github.com)** for ACID-compliant relational + vector checkpointing (`LangGraph PostgresSaver` / `SqliteSaver`) in a single database.
- **[Redis Community / Valkey](https://github.com)** for ultra-fast open-source in-memory session state, conversation buffers, and semantic caching.

**Frameworks for building custom systems**: Combine **thedotmack/claude-mem** or **Basic Memory** (for coding agents) with **Mem0** or **Graphiti** (for semantic & temporal graph memory), **Letta** (for self-editing memory loops), and **PostgreSQL (`pgvector`) / Qdrant** for sovereign, persistent AI agent architectures.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
