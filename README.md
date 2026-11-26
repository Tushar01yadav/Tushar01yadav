 <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Tushar%20Yadav&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Applied%20AI%20%C2%B7%20Production%20LLM%20Systems&descSize=18&descColor=cfd8dc&descAlignY=60" width="100%" alt="Tushar Yadav" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=2C5364&center=true&vCenter=true&width=650&lines=Building+Production+LLM+Applications;RAG+%C2%B7+Multi-LLM+Orchestration+%C2%B7+Evaluation;Backend+Engineering+%C2%B7+Reliability+%C2%B7+Observability;From+AI+Prototypes+to+Production+Systems" alt="Typing SVG" />
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

I'm an AI Engineer focused on building **production-ready AI applications, LLM-powered products, and backend systems**.

Currently working as an **AI Associate, Founder's Office @ COG Culture**, where I work on internal AI products, LLM integrations, automation, and client-facing applications.

- 🚀 Contributed to an internal AI platform used across **4–5+ teams**, processing approximately **25M tokens/month**.
- 🧠 Building with RAG, multi-LLM orchestration, evaluation, and AI automation.
- ⚙️ Interested in reliability, observability, security, and scalable backend architecture.
- 🎓 B.Tech in Computer Science (AI & ML) · Microsoft Azure AI-900 certified.

---

## 🧠 How I Build AI Systems

<p align="center">
  <img src="./assets/ai-systems.svg" width="100%" alt="AI Brain, RAG, LLMs, Agents and Infrastructure" />
</p>

### ⚙️ AI System Architecture

```mermaid
flowchart TB
    U(["👤 User / Applications"])

    B["🧠 AI BRAIN<br/>Central Intelligence"]

    U --> B

    subgraph KNOWLEDGE["📚 RAG · KNOWLEDGE"]
        direction LR
        DOC[("📄 Brand Files")]
        RET["🔎 Retrieval"]
        VDB[("🗄️ Vector Store")]
        DOC --> RET --> VDB
    end

    VDB <-->|"Relevant context"| B

    subgraph MODELS["🤖 LLM · MODEL PROVIDERS"]
        direction LR
        GPT["OpenAI"]
        CL["Claude"]
        GE["Gemini"]
        GR["Groq"]
        MI["Mistral"]
    end

    B <-->|"Model routing"| MODELS

    subgraph AGENTS["⚡ AI AGENTS"]
        direction LR
        CONTENT["✍️ Content"]
        LEAD["🎯 Lead Gen"]
        OTHER["🧩 Other Apps"]
    end

    B --> AGENTS

    subgraph INFRA["🗄️ INFRASTRUCTURE"]
        direction LR
        PG[("PostgreSQL")]
        REDIS[("Redis")]
        OBS["📊 Monitoring"]
    end

    B -.-> INFRA

    classDef brain fill:#172554,stroke:#60A5FA,color:#FFFFFF,stroke-width:4px
    classDef knowledge fill:#312E81,stroke:#A78BFA,color:#FFFFFF
    classDef models fill:#164E63,stroke:#22D3EE,color:#FFFFFF
    classDef agents fill:#14532D,stroke:#4ADE80,color:#FFFFFF
    classDef infra fill:#3F3F46,stroke:#A1A1AA,color:#FFFFFF

    class B brain
    class DOC,RET,VDB knowledge
    class GPT,CL,GE,GR,MI models
    class CONTENT,LEAD,OTHER agents
    class PG,REDIS,OBS infra
```

---

## 🚀 Featured Projects

### 1. LLM Gateway — Multi-Provider LLM Infrastructure

<a href="https://github.com/Tushar01yadav/LLM-Gateway">
  <img src="https://img.shields.io/badge/Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

A production-oriented LLM gateway designed to handle provider failures, request routing, concurrency, cost controls, and asynchronous workloads.

**Engineering highlights**
- Multi-provider routing with automatic failover and circuit breakers.
- Redis-backed rate limiting, concurrency controls, and distributed coordination.
- PostgreSQL-backed asynchronous jobs with retries, idempotency, and dead-letter handling.
- Tenant-aware security, request guardrails, and budget reservations.
- Prometheus, Grafana, and OpenTelemetry for observability.
- Load testing and multi-instance reliability testing.

**Stack:** Python · FastAPI · Redis · PostgreSQL · Docker · Prometheus · Grafana · OpenTelemetry · k6

---

### 2. AI Content & Brand Intelligence Platform (Professional Experience — COG Culture)

An internal AI-powered copywriting platform designed to help marketing teams generate brand-aligned content through reusable prompt workflows and retrieval-augmented generation.

**Engineering highlights**
- 175+ reusable prompt templates for different copywriting workflows.
- RAG-based retrieval from winning campaign files and brand knowledge.
- Brand-specific context using structured Brand DNA.
- Multi-model fallback across Claude, GPT, and Gemini.
- Evaluation workflows, token tracking, and generation-cost monitoring.
- Brand-level data isolation and access control.

*Professional experience at COG Culture. Source code is not publicly available.*

---

### 3. Strapi CMS — Client Content Management System (Client Project)

A client CMS implementation using the open-source Strapi platform to manage structured website content through a dedicated content management backend.

**Core work**
- Open-source Strapi CMS setup and configuration.
- Structured content types and content modelling.
- API-driven content management.
- CMS and frontend integration.

**Stack:** Strapi · Node.js · SQLite · REST APIs

---

### 4. Lead Generation Agent Automation

<a href="https://github.com/Tushar01yadav/Lead-Generation-Agent-Automation">
  <img src="https://img.shields.io/badge/Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

An AI-powered lead generation and outreach workflow for discovering startup opportunities, enriching contact information, and supporting automated email outreach.

**Engineering highlights**
- Lead discovery and data extraction from startup and funding sources.
- Contact enrichment using Apollo.
- Automated email template generation and outreach workflows.
- Email thread tracking and engagement monitoring.

**Stack:** Python · LLM APIs · Selenium · Apollo · Gmail · Streamlit

---

### 5. RAG-Based PDF Summarizer & QA Chatbot

<a href="https://github.com/Tushar01yadav/RAG-Based-PDF-Summarizer-QA-Chatbot">
  <img src="https://img.shields.io/badge/Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

A document intelligence application that uses retrieval-augmented generation to summarize PDFs and answer questions using document context.

**Core concepts:** Document Processing · Embeddings · Retrieval · RAG · LLM-based Question Answering

---

## 🛠️ Tech Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
</p>

**Frontend & Backend**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Strapi-4945FF?style=flat-square&logo=strapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
</p>

**Databases & Infrastructure**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
</p>

**AI & LLM Ecosystem**

<p>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic%20Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white" />
  <img src="https://img.shields.io/badge/Mistral-FF7000?style=flat-square" />
  <img src="https://img.shields.io/badge/RAG-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/Multi--LLM%20Orchestration-6A1B9A?style=flat-square" />
</p>

**Observability & Testing**

<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" />
</p>

**Automation & Tools**

<p>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
</p>

---

## 📫 Let's Connect

Interested in opportunities involving Applied AI, LLM engineering, and building reliable AI-powered products.

<p>
  <a href="mailto:tusharyadav61900@gmail.com">tusharyadav61900@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/tushar-yadav-ai">LinkedIn</a> ·
  <a href="https://github.com/Tushar01yadav">GitHub</a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" width="100%" alt="footer" />
