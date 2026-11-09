### Hi, I'm Tristan 👋

4th-year computer science engineering student at **INSA Lyon**. I build AI agents and the production systems around them: retrieval, evaluation, MCP servers, and the infrastructure that keeps them running.

**Looking for a 4-month AI engineering internship (Forward Deployed / Applied AI / Agentic systems) from May 10, 2027 — Paris, Lyon or anywhere in the EU.**

---

#### What I did last summer — AI & Systems Software Engineer intern @ Mindlapse (cyber-GRC SaaS)

- **149 pull requests merged to production in 9 weeks** (Python, TypeScript).
- Built **agentic microservices with LangGraph on FastAPI**, with strict Pydantic contracts and tests that mock only I/O boundaries.
- Designed, deployed and operated an **MCP server** that gives coding agents a knowledge graph of the codebase, from proof of concept to on-call (alerting, two incidents handled).
- Built an **LLM evaluation harness** (LLM-as-judge, versioned scorecards) to decide which model and refresh cadence to use, and caught a confound in my own benchmark before anyone acted on it.
- Argued for and shipped a **retrieval design** (Postgres full-text search + reranker + LLM-emitted confidence) instead of an embedding store.

*The code is private; happy to walk through the design in an interview.*

---

#### What I'm building now

| Project | What it shows | Status |
|---|---|---|
| **Second Brain, AI-native** | Agents (LangGraph), hybrid retrieval (BM25 + pgvector + RRF), voice capture, MCP server, evals in CI, observability | 🚧 building |
| **Chess coach that doesn't hallucinate** | Fine-tuning (LoRA, DPO), verifiable evals with python-chess + Stockfish, vLLM serving | 🗓️ next |
| **Music transformer from scratch** | Attention, RoPE and KV cache written by hand in PyTorch, trained on MIDI | 🗓️ planned |

Already here: [`chess-coach`](https://github.com/tristanhp/chess-coach) (local MCP server that coaches from chess.com games with Stockfish) · [`cockpit`](https://github.com/tristanhp/cockpit) (local-first life dashboard syncing Notion, Linear and Google Calendar — Next.js, SQLite, Drizzle)

---

#### Stack

**AI** — LangGraph · MCP · RAG / hybrid retrieval · LLM evals · Claude, Mistral and local models (Ollama)  
**Backend** — Python · FastAPI · Pydantic · PostgreSQL · pytest  
**Frontend** — TypeScript · React / Next.js · tRPC · Vitest · Playwright  
**Infra** — Docker · Linux · Caddy · CI/CD (GitHub Actions, SonarQube)

---

📫 [LinkedIn](https://www.linkedin.com/in/tristan-hausermann-pernet) · tristan.hausermann@gmail.com
