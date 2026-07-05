<!-- BANNER — upload as banner.jpg in your repo root -->
<div align="center">
  <img src="./banner.jpg" width="100%" alt="banner"/>
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/kaushal-tiwari-668604363"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:kaushalt102@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://quorvel.tech"><img src="https://img.shields.io/badge/Quorvel-live-00ff88?style=for-the-badge&logo=vercel&logoColor=black" alt="Quorvel"/></a>
</div>

---

## 🧠 About Me

<pre>
🎓  CSE @ ABES Engineering College, Ghaziabad (2023–2027)
⚙️  Backend & distributed-systems engineer — I build the hard parts from scratch
🛡️  Shipped Quorvel: a live, paid reliability layer for AI agents (durable ledger + exactly-once)
🔴  Built a Redis-like distributed cache in Node.js: 53K ops/sec, sub-ms p99 over raw TCP
🌐  Depth in WAL, consistent hashing, pub/sub, idempotency, sagas, durable workflows
🤖  AI-native backends — OpenAI/LangChain, Gemini, embeddings, human-in-the-loop agents
🏆  Oracle OCI 2025 — Certified Generative AI Professional
💡  200+ DSA problems solved · active competitive programmer
📫  kaushalt102@gmail.com
</pre>

---

## 🛠 Languages & Tools

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-EC1C24?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

---

## 🚀 Featured Projects

### 🛡️ Quorvel — Reliability Layer for AI Agents · [Live](https://quorvel.tech) · [App](https://app.quorvel.tech)
> Production SaaS + open TypeScript SDK that makes AI-agent actions **exactly-once, gated, and crash-safe**. Pattern: **record → gate → replay**.

- 📒 **Durable action ledger** — actions are recorded before they run, so retries are safe and crashes replay instead of double-firing
- 🔌 **~3-line integration** with drop-in adapters for **OpenAI, LangChain/LangGraph, MCP, and the Vercel AI SDK**
- ✋ **Human-in-the-loop approval gates** + policies (budgets, rate limits, conditional approval) + **saga auto-rollback**
- ☁️ Multi-tenant hosted Cloud API (Fastify) — Clerk auth, Neon Postgres, Redis/BullMQ, DLQ, circuit breakers, Paddle billing
- ✅ **155/155 Cloud-API tests + 200+ SDK tests green**

### 🔴 Distributed Cache Engine
> Redis-like in-memory distributed cache built from scratch in Node.js — zero external cache dependencies.

- ⚡ **53,000+ ops/sec** · **sub-millisecond p99** over a custom binary TCP protocol
- 🔄 O(1) LRU eviction (4 configurable policies) + partial-read framing
- 💾 **Write-Ahead Log** crash recovery — full state restore in **< 1 second**
- 🌐 Consistent hash ring (150 vnodes) — only **~25% key remap** on node add; heartbeat detection + primary→replica WAL streaming
- 📡 Pub/Sub with glob matching · **206 tests, 0 failures**

### 🟣 Reachly — AI-Native CRM & Agentic Campaign Engine
> Plain-English goal → validated audience → approved, queued send.

- 🧠 Gemini turns a goal into **Zod-validated rule JSON** compiled to **parameterized SQL** (the AI never writes raw SQL)
- 🔁 Idempotent event IDs + **7-state forward-only machine** → exactly-once, ordered updates under retries
- 🚚 BullMQ + Redis dispatch (10 workers, exponential backoff) · deployed as 2 services across Vercel + Render

### 📈 Signalist — Event-Driven Stock Intelligence
> Durable, event-driven backend for automated stock monitoring with AI summaries.

- ⚙️ **~720 durable Inngest executions/day** (alert eval every 2 min) — no separate worker infra
- 🤖 **Gemini** daily summaries + scheduled email digests; Finnhub (~850ms) with ISR caching · **20 req/sec**

---

## 🏆 Achievements

<div align="center">

☁️ **Oracle OCI 2025 — Certified Generative AI Professional**  |  🛡️ **Launched a live, paid AI-agent reliability SaaS (Quorvel)**

🔴 **Hand-built distributed cache benchmarked against Redis**  |  💡 **200+ DSA problems · active competitive programmer**

</div>

---

## 📊 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kaushalv17&theme=react-dark&bg_color=0d1117&hide_border=true&color=00ff88&line=00ff88&point=ffffff&area=true&area_color=00ff88" width="95%" alt="activity graph"/>
</div>

---

<div align="center">
  <img src="./banner.jpg" width="100%" alt="footer"/>
  <br/>
  <i>⚡ "I don't just use abstractions — I build them." ⚡</i>
</div>
