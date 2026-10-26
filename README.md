# 👋 Hi, I'm Himanshu Meena

## Team Lead – AI Engineering | Agentic AI, Multi-Agent Systems & Production LLM Platforms

I build production-grade agentic AI platforms, multi-agent systems, and enterprise LLM applications.

Currently I'm **Team Lead – AI Engineering** at **Pansophic Technologies** — I joined as an AI Engineer in Oct 2024 and moved into the lead role in Jan 2026. I lead a team of 10 AI engineers and architect systems that reason, call tools, keep long-term memory, retrieve over enterprise knowledge, and run real work end to end with humans in the loop.

The part I care about is less the model and more the orchestration, latency and reliability around it — getting an agent to call the right tool, remember the right thing, and fail safely.

---

## 🧪 Open Source

### 🛡️ [llm-resilience](https://github.com/HimanshuMeena2416/llm-resilience)

Reliability primitives for LLM API calls — retry with jittered backoff, circuit breaking, API-key rotation with per-key cooldown, bounded concurrency, and cross-provider fallback. Async, provider-agnostic, zero runtime dependencies.

A production LLM call fails in five distinct ways, and each one wants a different response; most retry helpers collapse them into a single policy. Time is injected through a `Clock` protocol, so the full test suite advances a manual clock by hand and runs in under half a second — no sleeps, no flakes.

`Python` · `asyncio` · `circuit breaker` · `key rotation` · `provider fallback`

### 🤖 [career-agent](https://github.com/HimanshuMeena2416/career-agent)

Reference implementation of a Google ADK multi-agent career assistant: 6 MCP tool servers, versioned LLM skill modules that each pair a prompt and an output schema with a deterministic offline fallback, and human-in-the-loop gates enforced in code rather than in prompts.

The whole pipeline runs end to end with no API keys and no network, so the architecture is inspectable without credentials. The repo implements the AI layer of a 23-page product specification.

`Google ADK` · `Gemini` · `MCP` · `FastAPI` · `PostgreSQL + pgvector`

---

## 🏗️ Production Work

*The platforms below are proprietary. Architecture and design details available on request.*

**Allyra GenAgent / Agent Builder** — multi-tenant, no-code platform for building and deploying enterprise AI agents: multi-layer RAG (Vertex AI Search, Qdrant, FAISS), persistent session memory, intelligent tool routing, and autonomous multi-agent collaboration over A2A Protocol and MCP.

**MailDesk & ComAssist** — enterprise AI email platforms for Gmail and Outlook with 85+ function-calling tools, OAuth 2.0 and Microsoft Graph integration, real-time mailbox synchronization, RAG grounding, confidence-based routing and AI guardrails.

**Multi-Agent Recruitment Platform** — hiring automation across 6+ microservices: JD generation, CV parsing, semantic CV–JD matching, AI screening, evidence-backed evaluation scorecards, and interview scheduling.

**Real-Time AI Interview Platform** — low-latency multimodal interviewing on GPT Realtime: bidirectional audio streaming, VAD/barge-in, live transcription, and AI-avatar video.

**Enterprise Document Intelligence** — layout-aware extraction, OCR and semantic retrieval across 15+ document formats with sub-second lookup.

---

## 🛠 Stack

**Agentic AI & LLM** Google ADK · Multi-Agent Systems · A2A Protocol · MCP · LiteLLM · LangGraph · Function & Tool Calling · Prompt Engineering · Enterprise RAG · Semantic Search · Human-in-the-Loop Workflows · AI Guardrails

**Models** OpenAI GPT · GPT Realtime API · Google Gemini · Anthropic Claude · xAI Grok

**Backend** Python · Golang · FastAPI · AsyncIO · Pydantic · SQLAlchemy · REST APIs · WebSockets · HTTPX

**Data & Infrastructure** PostgreSQL · MongoDB · Redis · Qdrant · FAISS · ChromaDB · NebulaGraph · Docker · Vertex AI · GCP · AWS S3

---

## 🌱 Currently Exploring

Agent evaluation frameworks · reliable and observable AI systems · AI safety and guardrails · enterprise agent architectures · long-term agent memory · autonomous multi-agent collaboration

---

## 📫 Connect

- 💼 LinkedIn: https://www.linkedin.com/in/himanshu-meena-63476a1a5/
- 📧 Email: himanshumeena2416@gmail.com
