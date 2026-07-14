### Hi, I'm Maxim Kholodulin

**AI Engineer — LLM Applications & Agents** ·
[LinkedIn](https://www.linkedin.com/in/maxim-kholodulin) · maxkholodulin@gmail.com

I build complete, production-ready LLM systems — from backend agents to streaming user interfaces.

#### 🎙 Featured Project: [VoiceOps — Realtime Voice Sales Agent with RAG](https://github.com/Kholodulin/voice-AI-assistant)

A production-shaped realtime voice agent that qualifies inbound leads on live calls, answers knowledge-base questions, books demos via Cal.com, and pushes leads to HubSpot. Includes a recorded demo call and a full evaluation suite.

**Key Features:**

- **Orchestration** — LangGraph state machine with LLM-routed transitions and structured output for robust conversation handling
- **RAG Pipeline** — Hybrid retrieval (dense + BM25 with Reciprocal Rank Fusion), cross-encoder reranking, citations, and confidence-based fallback to human
- **Voice Experience** — Streaming STT/TTS with barge-in and cached filler audio to minimize perceived latency *(LiveKit · Deepgram · ElevenLabs)*
- **Guardrails** — Input filtering (jailbreak, off-topic, PII) and output hallucination checks
- **Quality Assurance** — Scenario-based evals in CI covering task completion, hallucination rate, RAGAS faithfulness, and p95 latency; regressions are blocked automatically
- **Observability** — Structured logging, tracing, and per-call cost tracking *(LangSmith · OpenTelemetry · Prometheus/Grafana)*

---

#### Professional Background

Two years of production frontend development, including:
- Developed parts of the frontend architecture for a highly configurable low-code platform that enables building complex business applications through configuration. Worked on a comprehensive UI-kit, advanced theming system, dynamic entity tables with computed columns, and adaptive charting components (line, bar, pie) using React and MobX.
- Designed and implemented the core frontend for a realtime courier dispatch dashboard: couriers and deliveries rendered as draggable cards across status columns with live updates, ensuring all logistics operators see the same synchronized board.
- Built an event-driven Redux state layer with status-mapping state machines that relocate entities on incoming events and apply concurrent filters, eliminating stale data and duplicated cards across multiple operators.
- Owned the architecture and implementation of an in-product email client, including folder operations, attachments, pagination, and real-time store consistency.

**Core Stack:**  
Python · FastAPI · LangGraph · LangChain · Qdrant · RAGAS · Docker · TypeScript · React · Redux · MobX · Next.js · Nx

---

*Open to new opportunities in LLM engineering, real-time AI systems, and complex frontend architecture*
