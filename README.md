<h1 align="center">Hi, I'm Sreehari 👋</h1>
<h3 align="center">Backend &nbsp;·&nbsp; Distributed Systems &nbsp;·&nbsp; Cloud &nbsp;·&nbsp; AI Infrastructure</h3>

<p align="center">
Most of what you'll find here started with a question that didn't have a satisfying answer.
<br/>
The projects grew from there.
</p>

<p align="center">
  <a href="mailto:rsreehari.rsh@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 🚀 Featured Work

###  [CORE — Distributed Code Review Platform](https://github.com/rshsreehari/coderev-platform)
An event-driven code review system deployed end to end on AWS. SHA-256 content hashing feeds a Redis cache layer, an **SQS-backed worker pool** processes analysis jobs asynchronously, and a **dead-letter queue with retry handling** recovers failures. Workers scale independently of the API.
> **Result:** sub-2s responses on cache hits (60–70% hit rate), decoupled and horizontally scalable.
> `Node.js` · `PostgreSQL (RDS)` · `Redis` · `AWS SQS / EC2` · `Docker`

###  [SpecPilot — AI-Powered API Documentation Evaluation Platform](https://github.com/rshsreehari/specpilot)
Point it at **any OpenAPI 3.x spec** — URL or file — and it answers questions about that API, then **mechanically** checks every citation against the spec's own machine-readable definition. No LLM ever grades another LLM. Custom **BM25 + Reciprocal Rank Fusion** retrieval with per-provider indexing, an **MCP-compatible tool-calling agent**, and a mechanical evaluation harness that turns hallucination into a number instead of an impression.
> **Result:** parameter hallucination cut from **33% → 12%** (agent vs. single-pass), measured across **446 endpoints** and an **80-question** evaluation suite spanning Stripe, GitHub, and OpenAI.
> `Python` · `FastAPI` · `PostgreSQL + pgvector` · `MCP` · `RAG` · `React` · `Docker`

###  [Assistive Communication System (RAG)](https://github.com/rshsreehari/llmaacworking)
A full-stack assistive-communication app. Two **fine-tuned FLAN-T5** models sit behind a **FAISS-backed RAG pipeline**, served through a Flask API with a React frontend.
> **Result:** improved METEOR 2× and ROUGE-L 2.3× over a zero-shot baseline.
> `Python` · `Flask` · `FAISS` · `FLAN-T5` · `React`

---

## 🔨 Currently Building

###  AssetLoop — Event-Driven Personal Obligations Platform *(in progress)*
Turns receipts, bills, and subscription notices into structured obligations through an **idempotent extraction pipeline** with a **transactional outbox**, DLQ recovery, and scheduled reconciliation. Polyglot by design: a Python/FastAPI core with a **Java/Spring Boot ledger service**, a **Kafka** event backbone, a cited-source RAG assistant, and an **MCP access layer** that inherits the backend's auth and RBAC.
> `Python (FastAPI)` · `Java (Spring Boot)` · `PostgreSQL + pgvector` · `Redis` · `Kafka` · `AWS` · `Terraform` · `OpenTelemetry`

---

## 🛠️ Tech Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>
</p>

**Backend**
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Microservices-FF6C37?style=flat-square&logo=apachekafka&logoColor=white"/>
</p>

**Data & Messaging**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS_SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white"/>
</p>

**Cloud & DevOps**
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
</p>

**Security & Design**
<p>
  <img src="https://img.shields.io/badge/OAuth2-EB5424?style=flat-square&logo=auth0&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/RBAC-2C3E50?style=flat-square&logo=keycdn&logoColor=white"/>
  <img src="https://img.shields.io/badge/System_Design-2C3E50?style=flat-square&logo=blueprint&logoColor=white"/>
</p>

**AI / LLM**
<p>
  <img src="https://img.shields.io/badge/RAG_Pipelines-4B32C3?style=flat-square&logo=chainlink&logoColor=white"/>
  <img src="https://img.shields.io/badge/Agentic_AI-6E56CF?style=flat-square&logo=probot&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/LLM_Evaluation-10A37F?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white"/>
  <img src="https://img.shields.io/badge/FLAN--T5_Fine--Tuning-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
</p>

---

## 📊 Activity

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=rshsreehari&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rshsreehari&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rshsreehari&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <i>Commits, PRs, issues, and contributions above are pulled live from GitHub, including private repos.</i>
</p>
