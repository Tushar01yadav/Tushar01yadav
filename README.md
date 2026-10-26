<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Tushar%20Yadav&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20Production%20LLM%20Systems&descSize=18&descColor=cfd8dc&descAlignY=60" width="100%" alt="Tushar Yadav" />

<p align="center">
  <a href="https://github.com/Tushar01yadav"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=2C5364&center=true&vCenter=true&width=620&lines=Production+RAG+%26+multi-LLM+systems;Reliability+%C2%B7+Observability+%C2%B7+Security;Building+LLM+backends+that+hold+up+under+load" alt="typing" /></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tushar-yadav-ai"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:tusharyadav61900@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Gurugram-India-FF9933?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to-AI%20Engineer%20roles-2ea44f?style=for-the-badge" />
</p>

---

## 👋 About

I build **production LLM systems**: RAG pipelines, multi-LLM routing, and the backend around them.
Currently **AI Associate, Founder's Office @ COG Culture**.

- 🚀 Shipped an internal AI platform used across **4–5+ teams (~25M tokens/month)**
- 🔍 Now going deeper into the systems side: **reliability, observability and security** of LLM backends
- 🎓 B.Tech CS (AI & ML) · Microsoft Azure AI-900 certified

---

## 🧠 How I think about LLM systems

A simplified view of the architecture I work with:

```mermaid
flowchart LR
    C[Client]:::client --> A["API layer<br/>auth + rate limiting"]:::api
    A --> CA[("Cache")]:::data
    A --> R["LLM router<br/>fallback + retries"]:::api
    R --> P1[Provider A]:::llm
    R --> P2[Provider B]:::llm
    A --> Q["Queue<br/>async / long jobs"]:::data
    Q --> W[Workers]:::api
    A -.-> O["Observability<br/>p50/p99, errors, token cost"]:::obs
    R -.-> O
    W -.-> O

    classDef client fill:#E3F2FD,stroke:#1976D2,color:#0D47A1
    classDef api fill:#E8F5E9,stroke:#388E3C,color:#1B5E20
    classDef data fill:#FFF3E0,stroke:#F57C00,color:#E65100
    classDef llm fill:#F3E5F5,stroke:#8E24AA,color:#4A148C
    classDef obs fill:#FFEBEE,stroke:#D32F2F,color:#B71C1C
```

---

## 🔨 Building now

| | Project | Focus |
|---|---|---|
| 🚧 | **LLM Gateway + Observability** | Gateway with live latency dashboard (p50/p99), load tests and security tests. *Repo coming soon.* |
| 📝 | **System Design Notes** | Short decision records on the tradeoffs behind caching, queues, RAG and auth. *Coming soon.* |

---

## 📦 Projects

| Project | What it does |
|---|---|
| 🎯 [**Lead-Generation-Agent-Automation**](https://github.com/Tushar01yadav/Lead-Generation-Agent-Automation) | Pipeline for discovering, enriching and qualifying startup funding data |
| 📄 [**RAG-Based-PDF-Summarizer-QA-Chatbot**](https://github.com/Tushar01yadav/RAG-Based-PDF-Summarizer-QA-Chatbot) | PDF summarization and Q&A using retrieval-augmented generation |

---
## 🛠️ Tech Stack

**Languages & Backend**

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
</p>

**Data & Infra**

<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
</p>

**AI & Automation**

<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" />
</p>
---

## 📫 Let's connect

<p>
  <a href="mailto:tusharyadav61900@gmail.com">tusharyadav61900@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/tushar-yadav-ai">linkedin.com/in/tushar-yadav-ai</a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" width="100%" alt="footer" />
