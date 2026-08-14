# Hi, I'm Dennis 👋

Applied AI engineer based in Berlin, with 10+ years shipping production ML and LLM systems. I build agentic AI that runs in production, with paying customers.

## 🛠️ What I'm building

**Caselink**, an AI-native visa & immigration platform for universities and HR teams, with paying customers and recurring revenue. I'm the sole engineer behind:

- **A multi-agent layer on Python + LangGraph:** tool-using agents (onboarding, document feedback, case auditing, engagement detection) with human-in-the-loop review on every client-facing output
- **A portal-automation agent** that fills the German consular visa portal from case data, mapped through a versioned, embassy-scoped field catalog and executed inside the consultant's browser
- **An AI document pipeline:** automatic classification of uploaded documents (Claude, native PDF), structured field extraction, and validation findings that feed the feedback agents
- **Automated credential recognition:** reverse-engineered Anabin's undocumented API (the German credential-recognition registry) and mirrored ~75k records into a searchable database, with custom weighted matching and incremental sync exploiting timestamps encoded in the API's MongoDB ObjectIDs, plus weekly full re-syncs
- **An eval harness** with deterministic checks and an advisory LLM-as-judge, plus a data flywheel that turns curated production corrections (rejected drafts, dismissed recommendations, consultant edits) into regression tests
- **RAG** with dual embeddings (Voyage + OpenAI) and Voyage re-ranking for retrieval precision
- **A polyglot architecture:** a TypeScript/Next.js app and a dedicated Python agents service communicating over event-scoped internal APIs; agent tool calls derive their authorization from the triggering event, defusing prompt injection through tool arguments
- **Production integrations & runtime:** DocuSeal (digital signing), Gmail via Google Workspace domain-wide delegation, FastAPI on Fly.io, Postgres with multi-tenant row-level security, LangSmith tracing

▶️ **See it in action:** [youtu.be/Y5f-EgsljwU](https://youtu.be/Y5f-EgsljwU)

## ⚙️ How I work

`LangGraph` · `FastAPI` · `Anthropic Claude` · `OpenAI` · `RAG` · `evals` · `HITL orchestration` · `Python` · `TypeScript / Next.js` · `Postgres / Supabase` · `Vercel` · `Fly.io`

Built AI-native with coding agents: Claude Code + MCP servers, with a repo-level agent-instruction harness governing code generation.

## 📌 Before Caselink

A decade across data science and product, including an in-house ML bidder at GetYourGuide, where I defined the inputs and optimisation logic, that outperformed Google's native bidder for ~12 months, and ML + optimisation pricing work at Zalando that contributed to a 3% company-wide margin lift.

## 📈 About the green squares

Most of my work lives in private repositories (Caselink), so the contribution graph below is the public shadow of it. Ask me about the architecture.

### 📫 Reach me

[LinkedIn](https://linkedin.com/in/dennis-maass-7327465) · dennis.maass@gmail.com
