<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:1a1f35,70:0d2137,100:0a3d5c&height=200&section=header&text=Gaurav%20Bomra&fontSize=80&fontColor=58a6ff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20%7C%20RAG%2C%20LLM%20Agents%2C%20Python%20Backend&descAlignY=58&descSize=20&descColor=8b949e)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&multiline=false&width=800&lines=Building+AI+systems+that+hold+up+in+production;RAG+%7C+LLM+Apps+%7C+AI+Agents+%7C+Python+Backend;Open+to+remote+AI+Engineer+roles)](https://github.com/GauravFrr)

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=GauravFrr&color=58a6ff&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/GauravFrr)
[![GitHub followers](https://img.shields.io/github/followers/GauravFrr?style=for-the-badge&color=58a6ff&labelColor=0d1117&label=FOLLOWERS)](https://github.com/GauravFrr)
[![Open to Work](https://img.shields.io/badge/%F0%9F%9F%A2%20OPEN%20TO%20WORK-AI%20Engineer%20Roles-2ea44f?style=for-the-badge)](https://linkedin.com/in/gauravstack)

</div>

---

<div align="center">

```python
class Gaurav:
    name        = "Gaurav Bomra"
    location    = "Bhiwani, Haryana, India 🇮🇳"
    role        = ["AI Engineer", "RAG & LLM Systems", "Python Backend"]
    education   = "BCA @ S.L.N. Hindu College — started Aug 2026"
    core_stack  = ["Python", "FastAPI", "LangGraph", "PostgreSQL/pgvector", "Docker"]
    currently   = ["MemoryOS 🧠", "JobPilot 🎯"]
    experience  = "3+ years building AI systems (client work + own products)"
    open_to     = "Full-time AI Engineer / Backend — Remote"
    linkedin    = "linkedin.com/in/gauravstack"
    email       = "gauravdevxd@gmail.com"
```

</div>

---

## ⚡ What I Build

<table>
<tr>
<td width="50%">

**🤖 AI & LLM Systems**
- RAG pipelines: hybrid retrieval (BM25 + dense + RRF) with cross-encoder reranking and eval harnesses
- Multi-agent systems with LangGraph: supervisor orchestration, persistent memory, human-in-the-loop approvals
- LLM API integrations (Claude, Gemini, OpenAI, Groq, Ollama)
- Vector search with pgvector / ChromaDB

</td>
<td width="50%">

**🔧 Backend & Infrastructure**
- FastAPI + PostgreSQL + Redis backends, Dockerized
- LLM gateways: rate limiting, budget caps, circuit-breaker failover
- Observability: OpenTelemetry tracing, Prometheus + Grafana
- Telegram bots and workflow automation

</td>
</tr>
</table>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="33%" align="center" valign="top">

### 📊 [Retryv](https://github.com/GauravFrr/Retryv)
**Production RAG Pipeline**

Hybrid retrieval (BM25 + dense + RRF) with cross-encoder reranking over the FastAPI docs. Recall went from 23% to 84% on a 52-query eval set. [Read the case study](https://github.com/GauravFrr/Retryv/blob/main/case_study.md).

`FastAPI` `Gemini` `ChromaDB`
`BM25` `Cross-Encoder`

</td>
<td width="33%" align="center" valign="top">

### 🤖 [Agent Orchestration](https://github.com/GauravFrr/agent-orchestration)
**Multi-Agent System**

LangGraph supervisor delegates to specialist agents, keeps memory across sessions, and pauses for human approval on sensitive actions. Traced with OpenTelemetry, replayable from checkpoints.

`LangGraph` `FastAPI` `Redis`
`PostgreSQL` `OpenTelemetry`

</td>
<td width="33%" align="center" valign="top">

### 🚦 [LLM Gateway](https://github.com/GauravFrr/LLM-Gateway)
**Provider Failover & Rate Limiting**

One API in front of Gemini, Claude, Groq and Ollama. Redis-backed rate limits and budget caps, circuit breakers with automatic fallback. ~1.4ms median overhead.

`FastAPI` `Redis` `Prometheus`
`Grafana`

</td>
</tr>
<tr>
<td width="33%" align="center" valign="top">

### 🔍 [RankFuse](https://github.com/GauravFrr/RankFuse)
**Hybrid RAG Retrieval Library**

Open-source `pip install rankfuse`. Dense + BM25 fusion with cross-encoder and LLM-judge reranking. Config-driven, bring your own keys.

`Python` `ChromaDB` `BM25`
`PyPI`

</td>
<td width="33%" align="center" valign="top">

### 🧠 [MemoryOS](https://github.com/GauravFrr/MemoryOs)
**Universal AI Memory Layer**

Chrome extension captures ChatGPT, Claude and Gemini conversations, extracts structured memories, and injects context into new sessions.

`Next.js` `NestJS` `pgvector`
`Redis` `BullMQ`

</td>
<td width="33%" align="center" valign="top">

### 🎯 [JobPilot](https://github.com/GauravFrr/JobPilot)
**Job-Application Automation**

Discovers roles, tailors resumes with LLM matching, and applies through a Telegram bot. Every submission needs a human tap, nothing auto-submits.

`FastAPI` `Next.js` `pgvector`
`Telegram Bot`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**🧠 AI & LLM**

![LangChain](https://img.shields.io/badge/LangChain-0d1117?style=for-the-badge&logo=chainlink&logoColor=375BD2)
![LangGraph](https://img.shields.io/badge/LangGraph-0d1117?style=for-the-badge&logo=chainlink&logoColor=58a6ff)
![Anthropic](https://img.shields.io/badge/Anthropic-0d1117?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-0d1117?style=for-the-badge&logo=google&logoColor=4285F4)
![OpenAI](https://img.shields.io/badge/OpenAI-0d1117?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-0d1117?style=for-the-badge&logo=llvm&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0d1117?style=for-the-badge&logo=databricks&logoColor=FF6B35)
![HuggingFace](https://img.shields.io/badge/HuggingFace-0d1117?style=for-the-badge&logo=huggingface&logoColor=FFD21E)

**💻 Languages**

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Bash](https://img.shields.io/badge/Bash-0d1117?style=for-the-badge&logo=gnubash&logoColor=4EAA25)

**⚙️ Backend & Database**

![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=009688)
![NestJS](https://img.shields.io/badge/NestJS-0d1117?style=for-the-badge&logo=nestjs&logoColor=E0234E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=4169E1)
![Redis](https://img.shields.io/badge/Redis-0d1117?style=for-the-badge&logo=redis&logoColor=DC382D)
![Celery](https://img.shields.io/badge/Celery-0d1117?style=for-the-badge&logo=celery&logoColor=37814A)
![Supabase](https://img.shields.io/badge/Supabase-0d1117?style=for-the-badge&logo=supabase&logoColor=3ECF8E)

**🎨 Frontend**

![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind-0d1117?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8)

**🚀 DevOps & Observability**

![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=2496ED)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=FCC624)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1117?style=for-the-badge&logo=githubactions&logoColor=2088FF)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-0d1117?style=for-the-badge&logo=opentelemetry&logoColor=F5A800)
![Prometheus](https://img.shields.io/badge/Prometheus-0d1117?style=for-the-badge&logo=prometheus&logoColor=E6522C)
![Grafana](https://img.shields.io/badge/Grafana-0d1117?style=for-the-badge&logo=grafana&logoColor=F46800)

</div>

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GauravFrr&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=6" height="165"/>

[![GitHub Streak](https://streak-stats.demolab.com?user=GauravFrr&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=1f2937&ring=58a6ff&fire=FF6B35&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff)](https://github.com/GauravFrr)

</div>

---

## 📫 Let's Connect

<div align="center">

[![Email](https://img.shields.io/badge/Gmail-gauravdevxd@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gauravdevxd@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gauravstack-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gauravstack)
[![Portfolio](https://img.shields.io/badge/Portfolio-gauravxd.dev-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://gauravxd.dev)

</div>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:0a3d5c,40:0d2137,70:1a1f35,100:0d1117&height=120&section=footer)
