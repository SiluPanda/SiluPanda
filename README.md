# Hi, I'm Silu 👋

📍 **Sunnyvale, CA** | 🛠️ **Building AI infrastructure** | 🎓 **IIT Bombay CS** | 💼 **Software Engineer @ LinkedIn**

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP-5A29E4?style=flat-square&logo=data:image/svg+xml;base64,&logoColor=white)
![CLI](https://img.shields.io/badge/-CLI-000000?style=flat-square&logo=gnu-bash&logoColor=white)

> Building the developer tooling layer for AI-native applications — from context graphs and agent orchestration to RAG primitives and prompt engineering.

🔬 **[Meridex Research](https://www.meridexresearch.com/)** (closed source) – The operating system for AI-native investing.
📊 **[MarketOnePager](https://www.marketonepager.com/)** (closed source) – Multi-agent market research platform.

## Featured Projects

- 🧠 **[pith](https://github.com/SiluPanda/pith)** – AI-native task management for humans & agents. MCP-first, CLI-native, self-hosted.
- ⚡ **[weav](https://github.com/SiluPanda/weav)** – In-memory context graph database written in Rust. Sub-10ms retrieval with vector search, temporal modeling, and token budgeting.
- 🤖 **[sweteam](https://github.com/SiluPanda/sweteam)** – Orchestrates your coding agents, so you don't have to.
- 🔁 **[ralph-py](https://github.com/SiluPanda/ralph-py)** – Minimal CLI for orchestrating Ralph loops across coding agents.
- 🕷️ **[agent-crawl](https://github.com/SiluPanda/agent-crawl)** – High performance, lightweight and typesafe web crawler built for LLM agents.

## All Projects

### Agent & Orchestration
- 🧩 **[mcp-tool-router](https://github.com/SiluPanda/mcp-tool-router)** – Aggregates tools from multiple MCP servers into one
- 🧪 **[mcp-server-mock](https://github.com/SiluPanda/mcp-server-mock)** – Programmable mock MCP server for integration testing
- 🔍 **[mcp-schema-lint](https://github.com/SiluPanda/mcp-schema-lint)** – CLI linter for MCP tool/resource schemas
- 🚦 **[mcp-rate-guard](https://github.com/SiluPanda/mcp-rate-guard)** – Protocol-level rate limiter middleware for MCP
- 🏥 **[mcp-healthcheck](https://github.com/SiluPanda/mcp-healthcheck)** – Programmatic health/liveness probe for MCP servers
- ⚙️ **[mcp-config-ts](https://github.com/SiluPanda/mcp-config-ts)** – CLI to discover, add, validate, and sync MCP server configs
- 📋 **[mcp-audit-log](https://github.com/SiluPanda/mcp-audit-log)** – Structured audit logger for MCP tool calls
- 📝 **[agent-scratchpad](https://github.com/SiluPanda/agent-scratchpad)** – Lightweight key-value scratchpad for agent reasoning
- 🔄 **[tool-call-retry](https://github.com/SiluPanda/tool-call-retry)** – AI-specific retry wrapper with circuit breaker for tool calls
- 📐 **[tool-output-guard](https://github.com/SiluPanda/tool-output-guard)** – Runtime validator for tool execution results against schemas
- 💰 **[tool-cost-estimator](https://github.com/SiluPanda/tool-cost-estimator)** – Estimate token cost of tool definitions in the context window
- 📨 **[multimodal-msg](https://github.com/SiluPanda/multimodal-msg)** – Provider-agnostic multimodal message builder

### LLM Infrastructure
- 🔁 **[llm-retry](https://github.com/SiluPanda/llm-retry)** – Smart retry orchestrator for LLM output parsing and validation
- 📼 **[llm-vcr](https://github.com/SiluPanda/llm-vcr)** – Record and replay LLM API calls for deterministic testing
- 🧹 **[llm-sanitize](https://github.com/SiluPanda/llm-sanitize)** – Bidirectional I/O sanitizer middleware for LLMs
- 💾 **[llm-response-cache](https://github.com/SiluPanda/llm-response-cache)** – Prompt-hash-keyed response cache with model-aware invalidation
- 📉 **[llm-regression](https://github.com/SiluPanda/llm-regression)** – Semantic regression testing for prompt versions
- 🧽 **[llm-output-normalizer](https://github.com/SiluPanda/llm-output-normalizer)** – Strip markdown fences and extract clean data from raw LLM output
- ✅ **[llm-eval-lite](https://github.com/SiluPanda/llm-eval-lite)** – One-function LLM evaluation with heuristic and model-graded assertions
- 💲 **[llm-cost-per-test](https://github.com/SiluPanda/llm-cost-per-test)** – Jest/Vitest reporter for per-test-case LLM API costs
- 🔥 **[llm-chain-profiler](https://github.com/SiluPanda/llm-chain-profiler)** – Flame-chart latency profiler for LLM chains
- 🐤 **[llm-canary](https://github.com/SiluPanda/llm-canary)** – Invisible canary tokens for prompt leakage detection
- 📒 **[llm-audit-log](https://github.com/SiluPanda/llm-audit-log)** – Tamper-evident compliance-ready audit logging for LLM I/O
- 🔀 **[llm-dedup](https://github.com/SiluPanda/llm-dedup)** – Coalesce semantically similar in-flight LLM requests
- 🧲 **[llm-semantic-cache](https://github.com/SiluPanda/llm-semantic-cache)** – Self-hosted semantic cache using local embeddings
- 📄 **[llms-txt](https://github.com/SiluPanda/llms-txt)** – Auto-generate and serve llms.txt for AI agent discoverability

### Prompt Engineering
- 🔬 **[prompt-lint](https://github.com/SiluPanda/prompt-lint)** – Static analysis for LLM prompts
- 🔀 **[prompt-diff](https://github.com/SiluPanda/prompt-diff)** – Semantic diff engine for prompts
- 🧹 **[prompt-dedup](https://github.com/SiluPanda/prompt-dedup)** – Detect near-duplicate prompts via content hashing and similarity
- 📈 **[prompt-drift](https://github.com/SiluPanda/prompt-drift)** – Detect silent LLM output changes over time via semantic drift analysis
- 🚩 **[prompt-flags](https://github.com/SiluPanda/prompt-flags)** – AI-native feature flags for prompt variants and model selection
- 🧬 **[prompt-inherit](https://github.com/SiluPanda/prompt-inherit)** – Composable inheritable prompt builder with TypeScript types
- ✂️ **[prompt-optimize](https://github.com/SiluPanda/prompt-optimize)** – Compress prompts to use fewer tokens via deterministic heuristics
- 💵 **[prompt-price](https://github.com/SiluPanda/prompt-price)** – Pre-flight cost estimation for any prompt and model combination
- 📸 **[prompt-snap](https://github.com/SiluPanda/prompt-snap)** – Jest-like snapshot testing for LLM outputs with fuzzy matching
- 🏷️ **[prompt-version](https://github.com/SiluPanda/prompt-version)** – Local-first git-friendly prompt versioning with semver

### RAG & Retrieval
- 🧱 **[chunk-smart](https://github.com/SiluPanda/chunk-smart)** – Structure-aware text chunker for RAG pipelines
- 📐 **[chunk-overlap-optimizer](https://github.com/SiluPanda/chunk-overlap-optimizer)** – Analyze chunk boundaries and recommend optimal overlap size
- 📦 **[context-packer](https://github.com/SiluPanda/context-packer)** – Optimally pack retrieved chunks into an LLM context window
- 💰 **[context-budget](https://github.com/SiluPanda/context-budget)** – Token budget allocator for LLM context windows
- 🪟 **[sliding-context](https://github.com/SiluPanda/sliding-context)** – Provider-agnostic sliding window context manager for LLMs
- 🏗️ **[rag-prompt-builder](https://github.com/SiluPanda/rag-prompt-builder)** – Compose RAG prompts from chunks with automatic metadata injection
- 📎 **[rag-cite](https://github.com/SiluPanda/rag-cite)** – Extract and verify inline citations from LLM responses
- 📊 **[rag-eval-node-ts](https://github.com/SiluPanda/rag-eval-node-ts)** – Lightweight RAG evaluation metrics for CI/CD pipelines
- 🏅 **[rerank-lite](https://github.com/SiluPanda/rerank-lite)** – Lightweight retrieval reranker using cross-encoder scoring
- 🔗 **[fusion-rank](https://github.com/SiluPanda/fusion-rank)** – Reciprocal Rank Fusion for combining multiple retriever results
- 🔢 **[sparse-encode](https://github.com/SiluPanda/sparse-encode)** – Generate BM25 and TF-IDF sparse vectors in JavaScript
- 💎 **[embed-cache](https://github.com/SiluPanda/embed-cache)** – Content-addressable embedding cache with deduplication and TTL
- 🔮 **[embed-cluster](https://github.com/SiluPanda/embed-cluster)** – Cluster embeddings into topics with automatic labeling
- 📉 **[embed-drift](https://github.com/SiluPanda/embed-drift)** – Monitor embedding distribution shifts over time
- 📑 **[docling-node-ts](https://github.com/SiluPanda/docling-node-ts)** – Convert documents to clean RAG-ready markdown in Node.js
- 📊 **[doc-table-extract](https://github.com/SiluPanda/doc-table-extract)** – Extract tables from PDFs and images as structured JSON
- 📋 **[table-chunk](https://github.com/SiluPanda/table-chunk)** – Extract and chunk tables preserving row/column structure

### Data & Knowledge
- 🕸️ **[kg-extract](https://github.com/SiluPanda/kg-extract)** – Extract entity-relationship triples and build knowledge graphs
- 🔗 **[entity-resolve](https://github.com/SiluPanda/entity-resolve)** – Deduplicate and merge entity mentions across documents
- 🧠 **[memory-dedup](https://github.com/SiluPanda/memory-dedup)** – Semantic deduplication of agent memory entries
- 📝 **[md-to-data](https://github.com/SiluPanda/md-to-data)** – Parse LLM markdown responses into typed JSON objects
- 📐 **[schema-from-text](https://github.com/SiluPanda/schema-from-text)** – Generate Zod schemas from natural language descriptions
- 🌉 **[schema-bridge](https://github.com/SiluPanda/schema-bridge)** – Write one Zod schema, get provider-specific structured output configs
- 🏷️ **[label-score](https://github.com/SiluPanda/label-score)** – Inter-annotator agreement metrics in JavaScript
- 🧪 **[synthdata-gen](https://github.com/SiluPanda/synthdata-gen)** – Generate and validate synthetic training data using any LLM
- 👤 **[synth-personas](https://github.com/SiluPanda/synth-personas)** – Generate diverse synthetic user personas for AI testing
- 🎯 **[fewshot-gen](https://github.com/SiluPanda/fewshot-gen)** – Generate diverse few-shot test cases from seed examples
- 📂 **[eval-dataset](https://github.com/SiluPanda/eval-dataset)** – Version-controlled eval dataset manager for LLM testing

### AI Ops & Cost Management
- ⚡ **[ai-circuit-breaker](https://github.com/SiluPanda/ai-circuit-breaker)** – Circuit breaker for AI API spend management
- 💲 **[ai-cost-compare](https://github.com/SiluPanda/ai-cost-compare)** – Compare cost of running prompts across models and providers
- 🏦 **[ai-chargeback](https://github.com/SiluPanda/ai-chargeback)** – Tag and allocate AI API costs by team, project, or feature
- 📈 **[ai-spend-forecast](https://github.com/SiluPanda/ai-spend-forecast)** – Predict future AI API spending from historical usage
- 🔑 **[ai-keyring](https://github.com/SiluPanda/ai-keyring)** – Manage, rotate, and health-check AI API keys across providers
- 🏥 **[ai-provider-healthcheck](https://github.com/SiluPanda/ai-provider-healthcheck)** – Monitor AI provider endpoint latency and availability
- 💰 **[model-price-registry](https://github.com/SiluPanda/model-price-registry)** – Auto-updating registry of LLM pricing across providers

### Safety & Quality
- 🛡️ **[content-policy](https://github.com/SiluPanda/content-policy)** – Declarative business-rule content policy engine for LLMs
- 👻 **[hallucinate-check](https://github.com/SiluPanda/hallucinate-check)** – Heuristic hallucination detection for Node.js
- 🚫 **[jailbreak-heuristic](https://github.com/SiluPanda/jailbreak-heuristic)** – Zero-dependency jailbreak attempt classifier using pattern matching
- 🧪 **[ai-output-assert](https://github.com/SiluPanda/ai-output-assert)** – Rich assertion library for LLM outputs as Jest/Vitest matchers
- 📊 **[output-grade](https://github.com/SiluPanda/output-grade)** – Heuristic LLM output quality scoring without calling another LLM

### Streaming & Real-time
- 🌊 **[stream-tokens](https://github.com/SiluPanda/stream-tokens)** – Aggregate streaming LLM tokens into semantic units
- ✅ **[stream-validate](https://github.com/SiluPanda/stream-validate)** – Progressive Zod validation for streaming LLM responses
- 🎙️ **[voice-turn](https://github.com/SiluPanda/voice-turn)** – Turn-taking manager for voice AI conversations
- 🔊 **[tts-queue](https://github.com/SiluPanda/tts-queue)** – TTS audio streaming manager with sentence-boundary queuing
- 🎵 **[audio-chunker](https://github.com/SiluPanda/audio-chunker)** – Chunk audio streams into transcription-ready segments
- 🎬 **[vidsnap-ai](https://github.com/SiluPanda/vidsnap-ai)** – Smart video frame sampler for vision AI analysis
- 🖼️ **[vision-prep](https://github.com/SiluPanda/vision-prep)** – Resize and optimize images for vision LLM APIs

### Developer Tools
- 🎨 **[ai-terminal-md](https://github.com/SiluPanda/ai-terminal-md)** – Terminal renderer optimized for AI markdown patterns
- ⏳ **[ai-spinner](https://github.com/SiluPanda/ai-spinner)** – AI-aware terminal progress indicators with token and cost display
- 🔀 **[ai-diff](https://github.com/SiluPanda/ai-diff)** – Compare LLM responses across models with semantic diffs
- 📏 **[ai-rules-lint](https://github.com/SiluPanda/ai-rules-lint)** – Linter and validator for AI instruction files
- 📁 **[ai-file-router](https://github.com/SiluPanda/ai-file-router)** – Auto-detect file type and route through optimal parsing pipeline
- 🚀 **[ai-env-init](https://github.com/SiluPanda/ai-env-init)** – Bootstrap all AI config files from a single questionnaire
- 🔐 **[token-fence](https://github.com/SiluPanda/token-fence)** – Token budget enforcement middleware with intelligent truncation
- 🌳 **[convo-tree](https://github.com/SiluPanda/convo-tree)** – Tree-structured conversation state manager for branching chats
- 🗜️ **[convo-compress](https://github.com/SiluPanda/convo-compress)** – Incremental sliding-window chat compressor with rolling summaries
- 🧬 **[codebase-ctx](https://github.com/SiluPanda/codebase-ctx)** – Generate AI-optimized codebase summaries via static analysis
- 📦 **[npm-package-skill](https://github.com/SiluPanda/npm-package-skill)** – Claude Code skill that scaffolds production-grade npm packages

## GitHub Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/SiluPanda)

## What I'm Building

- **AI developer infrastructure** – Modular, composable TypeScript libraries for every layer of the AI application stack
- **Agent orchestration** – Tools to make multi-agent workflows reliable and observable
- **Context engines** – From Rust-powered graph databases to smart chunking and retrieval primitives
- **Side projects** – [Meridex Research](https://www.meridexresearch.com/) and [MarketOnePager](https://www.marketonepager.com/)

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/SiluPanda)
[![LinkedIn](https://img.shields.io/badge/-Silu_Panda-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/silupanda)
[![Website](https://img.shields.io/badge/-silupanda.github.io-FF5722?style=flat-square&logo=google-chrome&logoColor=white)](https://silupanda.github.io/)

---

> Ship fast, ship small, ship often — modular tools that compose into powerful systems.
