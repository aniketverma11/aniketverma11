<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Aniket%20Verma&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Senior%20GenAI%20%26%20ML%20Infrastructure%20Engineer&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=3000&pause=1000&color=7C83FD&center=true&vCenter=true&width=600&lines=Building+production+AI+infrastructure+at+scale;vLLM+%7C+LangGraph+%7C+CrewAI+%7C+Agentic+Systems;Fine-tuning+%26+deploying+LLMs+on+A100+%2F+H100+GPUs;Backend+Architect+%7C+Cloud+%26+MLOps+Practitioner)](https://git.io/typing-svg)

</div>

---

<div align="center">

[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aniketverma1103@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aniketverma11)
[![GitHub](https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aniketverma11)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/aniket_verma11)
[![Location](https://img.shields.io/badge/📍_Noida,_India-333333?style=for-the-badge)](https://maps.google.com/?q=Noida,India)

</div>

<br/>

## `$ whoami`

```python
class AniketVerma:
    role        = "Senior GenAI & ML Infrastructure Engineer"
    location    = "Noida, Uttar Pradesh, India"
    experience  = "3+ years in production AI, backend, and cloud systems"

    current_work = [
        "Building AI infrastructure @ Charter Communications (BGP/Network monitoring, Airflow pipelines)",
        "Deploying & fine-tuning LLMs on H100/A100 GPU clusters via vLLM (Orinn platform)",
        "Architecting agentic systems with LangGraph, CrewAI, LangChain",
        "FastAPI microservices + Nginx load balancing for inference at scale",
    ]

    expertise = {
        "AI/ML":     ["vLLM", "LangGraph", "LangChain", "CrewAI", "PyTorch", "TensorFlow", "RAG"],
        "Backend":   ["Python", "Django", "FastAPI", "Celery", "Airflow", "GraphQL"],
        "Cloud":     ["GCP (A100/H100 VMs)", "AWS (EC2, S3, Lambda, SageMaker)", "Azure"],
        "DevOps":    ["Docker", "Kubernetes", "Nginx", "CI/CD", "Linux"],
        "Databases": ["PostgreSQL", "MongoDB", "MySQL", "Redis"],
        "Other":     ["Blockchain", "Solidity", "Web3", "MERN"],
    }

    quote = "Build systems that outlast the hype."
```

---

## 🏢 Professional Experience

<table>
<tr>
<td width="50%">

### 🔷 Charter Communications
**Senior Software Engineer — NetOps**
`Sep 2024 – Present`

- Network monitoring & BGP infrastructure using Python Airflow pipelines
- Onboarded to ARIN WHOIS scraper codebase; extending network telemetry features
- Refactored `juniper_inventory_report` DAG: extracted standalone `GraphQLClient` package with lazy auth + retry logic
- Migrated project to `pyproject.toml`; eliminated Vault dependency by leveraging Airflow-native secrets

</td>
<td width="50%">

### 🔶 Coforge
**Senior Software Engineer**
`Sep 2024 – Present`

- Architecting insurance, reinsurance & mortgage solutions (Django, ReactJS)
- Driving AI-powered mobile features and workflow automation
- Built SDLC tooling with FastAPI + Jinja2 templating layer

</td>
</tr>
<tr>
<td width="50%">

### 🟣 Benthon Labs
**Full Stack Python Developer**
`Oct 2023 – Jul 2024`

- Led development of CRM system (Node.js, Express, MongoDB, AWS EC2)
- Designed microservices architecture; improved API response times and customer satisfaction scores

</td>
<td width="50%">

### 🟢 CreateBytes
**Software Developer Engineer — Python/Django**
`Jul 2022 – Sep 2023`

- Built scalable ML/AI SaaS products on AWS
- Delivered **YugYog** — video analytics platform with 30% faster data processing
- Built custom CRM + ML microservices pipelines

</td>
</tr>
<tr>
<td colspan="2">

### 🔴 Rapid Innovation
**Blockchain Developer**
`Nov 2021 – Jul 2022`

- Built DApps & smart contracts (Solidity, Hardhat, Chai, Python automation)
- Automated end-to-end blockchain testing workflows; delivered Web3 integrations for production clients

</td>
</tr>
</table>

---

## 🤖 AI Infrastructure — Orinn Platform

> *Building and operating a private AI inference cloud from the ground up.*

<div align="center">

| Component | Details |
|-----------|---------|
| **Models** | Orinn-1.6 (Qwen3.5-based fine-tune), Orinn-1.7 (Flash Linear Attention architecture) |
| **Inference Engine** | vLLM on GCP H100 (`gpu-1xh100`) + 2×A100 cluster |
| **Load Balancer** | Nginx upstream routing across GPU nodes |
| **API Layer** | FastAPI microservices — text, multimodal (PDF/image) |
| **Storage** | AWS S3 (`final-model-orinn-30b`) for model weights sync |
| **Agentic Stack** | LangGraph · LangChain · CrewAI · Microsoft Copilot Studio |

</div>

**Notable engineering challenges solved:**
- 🔧 GCP H100 VM recovery: booted from detached disk on a new instance, migrated static IP with zero data loss
- ⚡ Diagnosed & fixed Orinn-1.7 slow throughput — traced to tensor format mismatch; resolved with `VLLM_USE_V1=1`
- 🛠️ Surgical patch to `default_loader.py` to skip `visual.*` weight validation on text-only VL-named model weights
- 🏗️ Built Nginx load balancer distributing vLLM inference traffic across both GPU machines

---

## 🌟 Featured Projects

<table>
<tr>
<td align="center" width="33%">

### 🧠 Orinn AI Platform
`orinn.in` · `labops.in`

Private LLM inference cloud — custom fine-tuned models deployed on H100/A100 clusters via vLLM, served through FastAPI + Nginx

**Stack:** vLLM · FastAPI · GCP · Nginx · PyTorch

</td>
<td align="center" width="33%">

### 🗂️ LabOps
`labops.in (2024)`

Lab Management System that cut AWS infrastructure costs by **50%** through optimized Django + PostgreSQL backend architecture

**Stack:** Django · PostgreSQL · AWS · Docker

</td>
<td align="center" width="33%">

### 📰 Baimanus.in
`2024`

News platform serving Maharashtra's tribal communities — built with Django, AWS CDN & CloudFront for fast, reliable content delivery

**Stack:** Django · AWS CloudFront · CDN · S3

</td>
</tr>
<tr>
<td align="center" width="33%">

### 📊 YugYog
`CreateBytes (2022–23)`

Video analytics platform — achieved **30% faster** data processing with custom ML pipeline on AWS. High user satisfaction scores post-launch.

**Stack:** Django · AWS · ML Pipelines · PostgreSQL

</td>
<td align="center" width="33%">

### ⚖️ LegalExpert API
`api-legalexpert.api.tamko.com`

Legal document export service — FastAPI + Nginx on Ubuntu, multi-environment worker tuning, cron-based zip cleanup

**Stack:** FastAPI · Nginx · Ubuntu · Celery

</td>
<td align="center" width="33%">

### 🔗 Web3 DApps
`Rapid Innovation (2021–22)`

Multiple production DApps & smart contracts — automated testing suite (Chai, Hardhat), Solidity + Python orchestration

**Stack:** Solidity · Hardhat · Python · Ethereum

</td>
</tr>
</table>

---

## 🛠️ Tech Arsenal

<div align="center">

### Core Languages & Runtimes
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

### AI / ML Infrastructure
![vLLM](https://img.shields.io/badge/vLLM-FF6B6B?style=flat-square&logo=pytorch&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=flat-square&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

### Backend & APIs
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

### Cloud & DevOps
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</div>

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aniketverma11&show_icons=true&theme=transparent&hide_border=true&title_color=7C83FD&icon_color=7C83FD&text_color=cdd6f4&bg_color=00000000" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aniketverma11&layout=compact&theme=transparent&hide_border=true&title_color=7C83FD&text_color=cdd6f4&bg_color=00000000" height="160"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aniketverma11&theme=transparent&hide_border=true&stroke=7C83FD&ring=7C83FD&fire=FF6B6B&currStreakLabel=cdd6f4&sideLabels=cdd6f4&dates=666" width="49%"/>
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=aniketverma11&theme=onestar&no-frame=true&no-bg=true&margin-w=6&column=7" width="100%"/>
</div>

---

## 🎓 Education & Certifications

<table>
<tr>
<td width="50%">

**🎓 B.Tech — Computer Science & Engineering**
Dr. A.P.J. Abdul Kalam Technical University · 2022
CGPA: 7.23

</td>
<td width="50%">

**📜 Certifications**
- Python & Django Framework — Udemy
- Python OS Scripting — Coursera
- SQL (Advanced) — HackerRank
- Problem Solving — HackerRank
- AWS Containerized Applications

</td>
</tr>
</table>

---

<div align="center">

### 💬 Philosophy

*"Infrastructure is the product. Build it like it will run for ten years."*

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=aniketverma11&color=7C83FD&style=flat-square&label=Profile+Views)](https://github.com/aniketverma11)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
