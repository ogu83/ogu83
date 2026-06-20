# 👋 Hi, I'm Oğuz Koroğlu

🤖 **AI Architect & Voice AI Engineer** | Production AI · Governance · Claude Code · LangGraph · ElevenLabs · Twilio · RAG

20+ years shipping production systems. I build AI that goes to production — with evaluation pipelines, human-in-the-loop oversight, and governance built in from day one. Not demo notebooks. Governed, tested, production-ready systems.

---

## 🎯 What the Market Needs Now

- **AI governance & human oversight** — Every agent I ship has bounded authority, HITL escalation paths, and audit-ready logging. Not a checkbox: built into the architecture from day one. Demonstrated across the Claude Code, n8n, and LangGraph series.
- **Evaluation before deployment** — 1,750+ automated test scenarios validated on a production voice ordering system; pytest coverage across all agentic pipelines; structured output validation with Pydantic. AI that is tested, not trusted blindly.
- **Secure agentic systems** — MCP server development with tool-permission scoping, prompt injection awareness, and production guardrails. See: [Claude Code in Production](https://github.com/ogu83/production-claude-code) series.

---

## 💼 What I Build

- **Voice AI Systems** — Sub-200ms ElevenLabs TTS over bidirectional WebSocket, Twilio Media Streams & ConversationRelay telephony bridges, LangGraph barge-in with Redis checkpointing.
- **Production RAG & Hybrid Search** — BM25+dense hybrid retrieval (Qdrant), RRF fusion, cross-encoder reranking, FastAPI serving. pgvector, Pinecone, ChromaDB.
- **AI Agents & Orchestration** — LangGraph multi-agent pipelines, PydanticAI, multi-model councils (Claude + Gemini + GPT-4o in parallel async), MCP server development.
- **Claude Code & Agentic Dev Workflows** — CLAUDE.md architecture, PostToolUse/PreToolUse/Stop hooks, MCP server development, production guardrails. 4-episode published series.
- **n8n AI Agent Engineering** — Self-hosted n8n agents with persistent Redis memory, RAG pipelines, HITL email gates, Slack bots, multi-agent orchestration. 4-episode published series.
- **LLM Integrations** — Anthropic Claude, OpenAI, NLP-to-SQL (Vanna.ai), structured output pipelines, prompt caching, token optimization.
- **Legacy Modernization** — .NET Framework → .NET 10, Silverlight → OpenSilver/WebAssembly, monolith → FastAPI microservices (Strangler Fig, Circuit Breaker, Saga, Outbox).
- **Backend & Full-Stack** — Python/FastAPI, .NET/C#, Node.js/TypeScript, PostgreSQL, Docker, AWS (ECR, EC2, Cognito, S3).

---

## 📌 Featured Projects

### 🎙️ [voice-agent-architect-lab](https://github.com/ogu83/voice-agent-architect-lab)
Production voice AI series — ElevenLabs bidirectional WebSocket TTS (sub-200ms), Twilio Media Streams vs ConversationRelay telephony bridge (Mu-law/AEC), multi-modal Vision + Voice design, LangGraph Supervisor with Redis barge-in + speculative TTS.
`Python` `FastAPI` `ElevenLabs` `Twilio` `LangGraph` `Redis` `OpenAI Vision`
▶ [Ep1](https://www.youtube.com/watch?v=7pmmLN0pjkE) · [Ep2](https://www.youtube.com/watch?v=NC28T5jRmxo) · [Ep3](https://www.youtube.com/watch?v=ESLrtv-jZ_s) · [Ep4](https://www.youtube.com/watch?v=uinxJe-AaBU)

### 🔍 [qdrant-hybrid-search-lab](https://github.com/ogu83/qdrant-hybrid-search-lab)
Production RAG series — BM25+dense hybrid retrieval, RRF fusion, FastAPI serving layer, cross-encoder reranking. Benchmarks and architectural tradeoffs across all stages.
`Python` `Qdrant` `FastAPI` `BM25` `RRF` `Cross-encoder reranking`
▶ [Ep1](https://www.youtube.com/watch?v=Tl6dfZtXCww) · [Ep2](https://www.youtube.com/watch?v=t0h2-F1AHqA) · [Ep3](https://www.youtube.com/watch?v=agt5ecaj8pg)

### ⚙️ [production-claude-code](https://github.com/ogu83/production-claude-code)
Claude Code in production — CLAUDE.md architecture, PostToolUse/PreToolUse/Stop hooks, MCP server development with FastMCP, context management patterns for long sessions.
`Claude Code` `Python` `MCP` `Bash hooks`
▶ [Ep1](https://www.youtube.com/watch?v=52vtzexSwno) · [Ep4](https://www.youtube.com/watch?v=Nnf-iOXwsxc)

### 🤖 [n8n-ai-agent-lab](https://github.com/ogu83/n8n-ai-agent-lab)
n8n AI Agent Engineering series — self-hosted n8n agents with persistent Redis memory, RAG pipeline with Qdrant, HITL email gate, Slack bot, multi-agent orchestration. Production self-hosting + supervisor patterns.
`n8n` `Python` `Redis` `Qdrant` `Docker`
▶ [Ep1](https://www.youtube.com/watch?v=uSj3hy-wePk) · [Ep2](https://www.youtube.com/watch?v=U92JgQUy2wQ) · [Ep3](https://www.youtube.com/watch?v=_kRnmTJ_xFg) · [Ep4](https://youtu.be/qF9IKi7VvXQ)

### 🤖 [ai-engineering-lab](https://github.com/ogu83/ai-engineering-lab)
AI Engineering for Real Apps series — LangGraph multi-agent report pipeline with structured Pydantic outputs, Anthropic Claude, pytest coverage.
`Python` `LangGraph` `Anthropic Claude` `Pydantic` `pytest`

### 🔄 [monolith-to-fastapi-migration](https://github.com/ogu83/monolith-to-fastapi-migration)
All 7 microservices migration patterns (Strangler Fig, API Gateway, Sidecar, Outbox, Circuit Breaker, Event-Driven decoupling) built with Claude Code agentic workflows.
`Python` `FastAPI` `Kafka` `SQLAlchemy` `Docker` `Claude Code`

### 🏗️ [Northwind.MigrationLab](https://github.com/ogu83/Northwind.MigrationLab)
Practical .NET 10 legacy migration lab — RAG integration, MCP server wiring, clean architecture without pretending the legacy system disappears overnight.
`C#` `.NET 10` `RAG` `MCP`

---

## 🔒 Private / Client Work

- **[ai-decision-room](https://github.com/ogu83/ai-decision-room)** (public — contract closed) — Claude Opus (Chairman) + Gemini Flash (Analyst) + GPT-4o (Risk Officer) running parallel async Python via `asyncio.gather`, synthesized by Claude Sonnet. Vue 3 SPA, Docker + Nginx, deployed to Mac Mini M4 via Tailscale within a 2-week sprint.
- **Media Distribution Platform** (AI Reporting) — NLP-to-SQL with Vanna.ai, ChromaDB RAG chatbot, FastAPI + Anthropic Claude. Taken over mid-development; shipped LLM features in production.
- **Voice Ordering System Architecture Review** (NDA) — FSM+LLM hybrid, LiveKit Agents (Deepgram Nova-3 + GPT-4o-mini + Cartesia Sonic-2), OpenAI Realtime API fallback analysis ($0.82/call vs $0.08/call), 1,750+ tests.

---

## 📊 GitHub at a Glance

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ogu83&show_icons=true&theme=dark)

---

## 🌍 Connect

- 💼 [Upwork](https://www.upwork.com/freelancers/oguzkoroglu)
- 🎥 [YouTube — Beyond The Developer](https://www.youtube.com/@BeyondTheDeveloper)
- 📊 [Kaggle](https://www.kaggle.com/oguzkoroglu/) — 69 notebooks, 6 competitions, bronze medal
- 💬 [HackerRank](https://www.hackerrank.com/oguzkoroglu) · [CodeSignal](https://app.codesignal.com/profile/ogu83)

---

> Building AI that ships to production — governed, evaluated, human-in-the-loop. Voice agents, hybrid search, agentic workflows, MCP servers. Open to senior engineering contracts and AI architecture roles.
