# Hey, I'm Nehil 👋

### Applied AI · Backend engineering · Building the whole thing

I like projects that start with “wouldn't it be cool if…” and eventually require a retry policy.

I build AI applications, backend systems, and the interfaces that make them useful. The interesting part, for me, is what happens after the first successful demo: messy inputs, slow models, failing integrations, and actual users.

[Portfolio](https://nehil.vercel.app) · [LinkedIn](https://www.linkedin.com/in/nehil-chandrakar-272410259/) · [X](https://x.com/Chandrakar43234)

---

## 🛠️ The work that shaped me

### Alcovia — owning a product beyond the happy path

As the sole engineer at Alcovia, I designed and shipped across **3 React Native apps, 2 Next.js web apps, a WebSocket service, and a PostgreSQL-backed backend**.

A few parts I'm particularly proud of:

- **Keeping systems in sync:** built a ClickUp outbox pipeline with advisory locking, exponential-backoff retries, dead-letter handling, and reconciliation.
- **Getting AI out of the waiting room:** moved long-running Gemini extraction for session notes and study plans into asynchronous jobs with polling.
- **Following the awkward bugs:** fixed an iOS-only authentication refresh storm and a scheduled job exhausting the database connection pool.
- **Owning the full journey:** data modelling, APIs, mobile and web interfaces, deployment, and production debugging.

That experience gave me a lasting interest in a deceptively simple question:

**What happens when this doesn't work?**

## 🧪 Things you can explore

### 🧠 [ZenFit — AI Fitness & Nutrition Coach](https://github.com/NEhIL06/zenfit)

Personalized workout and nutrition plans, with a conversational AI trainer underneath.

The interesting engineering lives behind the chat:

- **LangGraph Self-RAG:** query routing, context prefetching, ChromaDB retrieval, batched document grading, and Cohere reranking.
- **Evidence handling:** web-search fallback when retrieval is insufficient, followed by a response faithfulness check.
- **Backend foundations:** JWT authentication, MongoDB persistence, Redis caching, and provider fallback paths.
- **Delivery:** Docker Compose with Next.js, ChromaDB, and Nginx; automated tests and deployment through GitHub Actions.

A project about fitness that became an exploration of AI reliability.

`TypeScript` `Next.js` `LangGraph` `ChromaDB` `MongoDB` `Redis` `Docker`

### 🔎 [RAG-Powered Talent Search](https://github.com/NEhIL06/RAG_talent_search)

A resume–job matching system built around a question: **how do you know your retrieval is actually useful?**

- Combined **semantic retrieval with Elasticsearch BM25** rather than relying on a single search method.
- Added weighted score fusion and optional CrossEncoder reranking.
- Built an evaluation harness using **Recall@K, Precision@K, and MRR**.
- Exposed ingestion and query APIs through FastAPI, with Docker Compose for the service and data stores.

Because “the results look pretty good” is where evaluation should begin.

`Python` `FastAPI` `Elasticsearch` `ChromaDB` `CrossEncoder` `Docker`

### 🌐 [Virtual Office — A Backend You Can Walk Around In](https://github.com/NEhIL06/metaverse_2d)

A 2D workspace where people can move around, see who's nearby, chat, and start proximity-based calls.

- WebSockets for live presence, movement, chat, and call signalling.
- Peer-to-peer WebRTC for proximity-based calls.
- Separate REST API and realtime services, with PostgreSQL and Prisma for persistent data.
- A TypeScript monorepo with automated builds, tests, and deployment workflows.

The fun part: turning connections and events into somewhere people can hang out.

`TypeScript` `Node.js` `WebSockets` `WebRTC` `PostgreSQL` `Prisma`

<details>
<summary><strong>More experiments from the workbench ↗</strong></summary>

- **[The Journal](https://github.com/NEhIL06/The_Journal)** — a Spring Boot journaling application with authentication, Redis caching, Kafka event handling, and API documentation.
- **[EcoSAP](https://github.com/NEhIL06/Ecosap)** — tree-crown segmentation using YOLOv8 and FastAPI, connected to an eco-credit application.
- **[KeyBankPro](https://github.com/NEhIL06/keybackpro)** — an API-key vault exploring encryption, authentication, and API security.
- **[AI Food Assistant](https://github.com/NEhIL06/RAG-Engine-for-food-recommendation)** — multilingual food recommendations using Python, CrewAI, and retrieval.

</details>

## ⚙️ Tools I reach for

**Languages:** Python, TypeScript / JavaScript, Java  
**AI:** LangGraph, LangChain, CrewAI, embeddings, RAG, reranking, retrieval evaluation  
**Backend:** FastAPI, Node.js, Express, Spring Boot, REST APIs, WebSockets  
**Data:** PostgreSQL, MongoDB, Redis, Elasticsearch, ChromaDB  
**Product & delivery:** React, Next.js, React Native, Docker, GitHub Actions

## 📡 Currently curious about

- Making AI agents easier to evaluate, debug, and trust.
- Go, gRPC, and the mechanics of distributed systems.
- Security for AI-powered applications.
- How much complexity a system actually needs—and how much I accidentally gave it.

## Beyond the repositories

🎓 **B.E. CSE (AI/ML), Siddaganga Institute of Technology · Class of 2026**

🏆 **2nd — Mercuria India Hackathon** · **3rd — Emerging Tech Hackathon**  
Also a finalist at HackCult, The Better Hack, and DishNetworks.

Away from code, I like sci-fi and mythology. Sometimes those interests collide, and a thought about AI turns into a very ambitious movie plot.

---

**Building something useful? Have a strange bug or an interesting idea? [Let's talk.](https://www.linkedin.com/in/nehil-chandrakar-272410259/)**
