 <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Tushar%20Yadav&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Applied%20AI%20%C2%B7%20Production%20LLM%20Systems&descSize=18&descColor=cfd8dc&descAlignY=60" width="100%" alt="Tushar Yadav" />

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=2C5364&center=true&vCenter=true&width=650&lines=Building+Production+LLM+Applications;RAG+%C2%B7+Multi-LLM+Orchestration+%C2%B7+Evaluation;Reliability+%C2%B7+Observability+%C2%B7+Security;From+AI+Prototypes+to+Production+Systems" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tushar-yadav-ai">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:tusharyadav61900@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Gurugram-India-FF9933?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to-AI%20Engineer%20Roles-2ea44f?style=for-the-badge" />
</p>

---

## 👋 About Me

I'm an AI Engineer focused on building **production-ready AI applications and LLM-powered backend systems**.

Currently working as an **AI Associate, Founder's Office @ COG Culture**, where I work on internal AI products, LLM integrations, and automation systems.

- 🚀 Contributed to an internal AI platform used across **4–5+ teams**, processing approximately **25M tokens/month**.
- 🧠 Building systems around RAG, multi-LLM orchestration, evaluation, and AI automation.
- ⚙️ Interested in the engineering challenges behind production AI: reliability, observability, security, and scalability.
- 🎓 B.Tech in Computer Science (AI & ML) · Microsoft Azure AI-900 certified.

---

## 🚀 Featured Projects

### 1. LLM Gateway — Multi-Provider LLM Infrastructure

<a href="https://github.com/Tushar01yadav/LLM-Gateway">
  <img src="https://img.shields.io/badge/Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

A production-oriented LLM gateway built to handle provider failures, request routing, concurrency, cost controls, and asynchronous workloads.

**Engineering highlights:**
- Multi-provider routing with automatic failover and circuit breakers.
- Redis-backed rate limiting, concurrency controls, and distributed coordination.
- PostgreSQL-backed asynchronous jobs with retries, idempotency, and dead-letter handling.
- Tenant-aware security, request guardrails, and budget reservations.
- Prometheus, Grafana, and OpenTelemetry for observability.
- Load testing and multi-instance reliability testing.

**Stack:** Python · FastAPI · Redis · PostgreSQL · Docker · Prometheus · Grafana · OpenTelemetry · k6

---

### 2. CopyAgent — Production AI Copywriting Platform

**Professional project · COG Culture**

An internal AI copywriting platform designed to help non-expert copywriters generate brand-aligned marketing content using reusable prompt workflows and retrieval-augmented generation.

**Engineering highlights:**
- 175+ reusable prompt templates for different copywriting workflows.
- RAG-based retrieval from winning campaign and brand knowledge files.
- Brand-specific context and structured Brand DNA.
- Multi-model fallback across Claude, GPT, and Gemini.
- Evaluation workflows, token tracking, and generation-cost monitoring.

*Internal project — source code is not publicly available.*

---

### 3. Lead Generation Agent Automation

<a href="https://github.com/Tushar01yadav/Lead-Generation-Agent-Automation">
  <img src="https://img.shields.io/badge/Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

An AI-powered lead generation and outreach workflow that discovers startup and funding-related opportunities, enriches lead information, and supports automated email outreach.

**Engineering highlights:**
- Lead discovery and data extraction from startup and funding sources.
- Contact enrichment using Apollo.
- Automated email template generation and outreach workflows.
- Email thread tracking and engagement monitoring.

**Stack:** Python · LLM APIs · Selenium · Apollo · Gmail · Streamlit

---

### 4. RAG-Based PDF Summarizer & QA Chatbot

<a href="https://github.com/Tushar01yadav/RAG-Based-PDF-Summarizer-QA-Chatbot">
  <img src="https://img.shields.io/badge/Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

A document intelligence application that uses retrieval-augmented generation to summarize PDFs and answer questions using document context.

**Core concepts:** Document processing · Retrieval · Embeddings · RAG · LLM-based question answering

---

## 🧠 System Design

I enjoy understanding the engineering decisions behind reliable AI systems.

A simplified view of the architecture patterns I work with:

```mermaid
flowchart LR
    C[Client] --> A[API Layer]
    A --> AUTH[Authentication & Rate Limits]
    AUTH --> R[LLM Router]
    R --> P1[Provider A]
    R --> P2[Provider B]
    A --> Q[Async Job Queue]
    Q --> W[Workers]
    A --> CACHE[(Redis Cache)]
    A --> DB[(PostgreSQL)]
    R --> O[Observability]
    W --> O
    A --> O
```

Areas I explore:
- LLM routing, retries, and failure handling
- RAG architecture and retrieval evaluation
- Distributed systems and asynchronous processing
- API security, rate limiting, and tenant isolation
- Latency, token usage, and cost optimization

---

## 🛠️ Tech Stack

**Languages & Backend**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
</p>

**Databases & Infrastructure**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Gunicorn-499848?style=flat-square&logo=gunicorn&logoColor=white" />
</p>

**AI & LLM Engineering**

<p>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/Multi--LLM%20Orchestration-6A1B9A?style=flat-square" />
</p>

**Observability & Testing**

<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
</p>

**Additional Tools**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" />
</p>

---

## 📫 Let's Connect

I'm interested in opportunities involving Applied AI, LLM engineering, and building reliable AI-powered products.

<p>
  <a href="mailto:tusharyadav61900@gmail.com">tusharyadav61900@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/tushar-yadav-ai">LinkedIn</a> ·
  <a href="https://github.com/Tushar01yadav">GitHub</a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" width="100%" alt="footer" />
