# Hi, I'm Meet Kuber 👋

**Software Developer | AI & Intelligent Automation**

I build full-stack, production-minded AI systems — agentic applications that use tool calling, retrieval, and self-correction, backed by real evaluation harnesses instead of "it seems to work." I care as much about proving a system works as building it in the first place.

📫 meetkuber30@gmail.com · [LinkedIn](#)

---

## 🚀 Featured Projects

### 🤖 ARIA — AI Realtime Intelligence Agent
Full-stack voice AI customer support agent with dual-mode architecture: a request-response pipeline and true real-time speech-to-speech via WebSocket (Gemini Live API, <500ms latency).
- Agentic function-calling loop with tool use (order lookup, refunds, ticketing)
- Automated evaluation harness (25 test cases) integrated into CI/CD
- Production safeguards: per-IP rate limiting, prompt-injection filtering, request tracing
- Deployed on AWS EC2 with Docker

`Python` `FastAPI` `React` `TypeScript` `WebSockets` `Docker` `AWS` `GitHub Actions`

### 📄 DocuMind — RAG Pipeline Over Private Documents
Retrieval-augmented generation system with citation-grounded answers over a document corpus.
- Two-stage retrieval: embedding search + cross-encoder re-ranking
- Evaluated on Recall@k, MRR, and LLM-judged faithfulness — not vibes
- Local embeddings (no API cost), deployed via Docker to AWS

`Python` `FastAPI` `React` `ChromaDB` `sentence-transformers` `Docker` `AWS`

### 🔍 Agentic SQL Search Engine
LLM agent that translates natural language into SQL, executes it against a live database, and self-corrects on execution errors via a retry loop.
- Schema-aware prompting, evaluated on a natural-language test set

`Python` `SQL` `LLM Agents`

### 📈 Hybrid CNN-LSTM Financial Forecasting
Deep learning model combining CNN and LSTM architectures for financial market prediction, with feature engineering and evaluation against baseline models.

`Python` `TensorFlow` `Keras` `Pandas` `NumPy`

---

## 🛠️ Tech Stack

**Languages:** Python · SQL · JavaScript · TypeScript
**AI/ML:** LLMs · Agentic Systems · RAG · Function Calling · Prompt Engineering · Machine Learning · Deep Learning
**Backend:** FastAPI · RESTful APIs · WebSockets
**Frontend:** React · HTML · CSS · Bootstrap 5
**Cloud & DevOps:** AWS (EC2, S3) · Docker · GitHub Actions (CI/CD) · Git
**Databases:** MySQL · SQL Server · SQLite · ChromaDB

---

## 💡 How I Build

Every AI project I ship follows the same discipline: build it, then **measure it** — retrieval accuracy, tool-call correctness, hallucination rate, latency. If I can't put a number on it, I don't consider it done.

---

⭐️ Feel free to explore my repos below, and reach out if you'd like to collaborate!
