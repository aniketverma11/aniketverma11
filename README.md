<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=280&section=header&text=Aniket%20Verma&fontSize=72&fontAlignY=40&desc=Senior%20GenAI%20%26%20ML%20Infrastructure%20Engineer&descSize=20&descAlignY=62&animation=fadeIn&fontColor=ffffff" width="100%"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=620&lines=Building+production+LLM+infrastructure+on+H100+%2F+A100+GPUs;vLLM+%7C+LangGraph+%7C+CrewAI+%7C+Agentic+Systems;Fine-tuning+%26+deploying+open-source+LLMs+at+scale;FastAPI+%7C+Django+%7C+Airflow+%7C+Microservices;3%2B+years+in+AI%2FML+%C2%B7+Backend+%C2%B7+Cloud+Systems)](https://git.io/typing-svg)

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-181717?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:aniketverma1103@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-181717?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/aniketverma11)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aniketverma11)
[![Twitter](https://img.shields.io/badge/Twitter-181717?style=for-the-badge&logo=twitter&logoColor=1DA1F2)](https://twitter.com/aniket_verma11)

</div>

---

<img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aniketverma11&layout=compact&hide_border=true&theme=github_dark&title_color=58A6FF&text_color=8b949e&bg_color=0d1117" width="38%"/>

### About

I build production AI infrastructure — fine-tuning LLMs, deploying them on GPU clusters, and wiring agentic systems end-to-end.

I run the **Orinn AI platform** on GCP H100 / A100 hardware, built from scratch — custom fine-tuned models, vLLM inference, FastAPI + Nginx serving layer, and a full agentic stack.

- 3+ years across AI/ML infra, backend engineering, and cloud
- Delivered 4+ SaaS products and 10+ corporate solutions
- Open to high-impact engineering roles

<br clear="right"/>

---

## Experience

| | Role | Company | Period |
|---|---|---|---|
| | Senior Software Engineer | Coforge | Sep 2024 – Present |
| | Full Stack Python Developer | Benthon Labs | Oct 2023 – Jul 2024 |
| | Software Developer Engineer | CreateBytes | Jul 2022 – Sep 2023 |
| | Blockchain Developer | Rapid Innovation | Nov 2021 – Jul 2022 |

<details>
<summary>&nbsp;<b>View details →</b></summary>

<br/>

**Senior Software Engineer — Coforge** `Sep 2024 – Present`
Building backend systems for insurance and mortgage platforms using Django and ReactJS. Developed AI-powered workflow automation features and SDLC tooling with FastAPI and Jinja2.

**Full Stack Python Developer — Benthon Labs** `Oct 2023 – Jul 2024`
Led CRM system development (Node.js, Express, MongoDB, AWS EC2). Designed a microservices architecture that improved API response times and system reliability.

**Software Developer Engineer — CreateBytes** `Jul 2022 – Sep 2023`
Built ML/AI SaaS products on AWS. Delivered YugYog — video analytics platform with **30% faster** data processing via a custom ML pipeline.

**Blockchain Developer — Rapid Innovation** `Nov 2021 – Jul 2022`
Built production DApps and smart contracts in Solidity. Automated testing suite (Chai, Hardhat) with Python orchestration.

</details>

---

## Orinn AI Platform &nbsp;·&nbsp; [orinn.in](https://orinn.in)

> *Private LLM inference cloud — designed, built, and operated independently.*

<div align="center">

| | |
|:---:|---|
| **Models** | Orinn-1.6 (Qwen3.5-based fine-tune) &nbsp;·&nbsp; Orinn-1.7 (Flash Linear Attention) |
| **Inference** | vLLM on GCP H100 `gpu-1xh100` + 2×A100 cluster |
| **Serving** | FastAPI user-facing layer &nbsp;·&nbsp; Nginx load balancer across GPU nodes |
| **Agentic** | LangGraph &nbsp;·&nbsp; LangChain &nbsp;·&nbsp; CrewAI &nbsp;·&nbsp; Copilot Studio |
| **Storage** | AWS S3 model sync &nbsp;·&nbsp; Multimodal API (PDF / Image) |

</div>

<details>
<summary>&nbsp;<b>Engineering highlights →</b></summary>

<br/>

- Recovered a stopped GCP H100 VM by booting from its detached disk on a fresh instance — zero data loss, static IP migrated
- Diagnosed Orinn-1.7 throughput bottleneck: tensor format mismatch → fixed with `VLLM_USE_V1=1`
- Patched `default_loader.py` to skip `visual.*` weight validation on text-only VL-named model weights
- Nginx upstream routing distributing inference traffic across both GPU machines with FastAPI as the API layer

</details>

---

## Projects

<div align="center">

| Project | Description | Stack |
|---|---|---|
| **[LabOps](https://labops.in)** | Lab Management System — cut AWS costs **50%** | Django · PostgreSQL · AWS |
| **Baimanus.in** | News platform for Maharashtra's tribal communities | Django · CloudFront · S3 |
| **YugYog** | Video analytics SaaS · 30% faster data processing | Django · AWS · ML Pipelines |
| **LegalExpert API** | Legal document export service | FastAPI · Nginx · Gunicorn |

</div>

---

## Skills

<div align="center">

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0d1117?style=flat-square&logo=tensorflow&logoColor=FF6F00)
![HuggingFace](https://img.shields.io/badge/HuggingFace-0d1117?style=flat-square&logo=huggingface&logoColor=FFD21E)
![LangChain](https://img.shields.io/badge/LangChain-0d1117?style=flat-square&logo=chainlink&logoColor=58A6FF)
![vLLM](https://img.shields.io/badge/vLLM-0d1117?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![NumPy](https://img.shields.io/badge/NumPy-0d1117?style=flat-square&logo=numpy&logoColor=4DABCF)
![Pandas](https://img.shields.io/badge/Pandas-0d1117?style=flat-square&logo=pandas&logoColor=130654)

**Backend & APIs**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![Django](https://img.shields.io/badge/Django-0d1117?style=flat-square&logo=django&logoColor=092E20)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=009688)
![Celery](https://img.shields.io/badge/Celery-0d1117?style=flat-square&logo=celery&logoColor=37814A)
![Airflow](https://img.shields.io/badge/Airflow-0d1117?style=flat-square&logo=apacheairflow&logoColor=017CEE)
![GraphQL](https://img.shields.io/badge/GraphQL-0d1117?style=flat-square&logo=graphql&logoColor=E10098)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=339933)

**Cloud & DevOps**

![GCP](https://img.shields.io/badge/GCP-0d1117?style=flat-square&logo=googlecloud&logoColor=4285F4)
![AWS](https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Azure](https://img.shields.io/badge/Azure-0d1117?style=flat-square&logo=microsoftazure&logoColor=0078D4)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0d1117?style=flat-square&logo=kubernetes&logoColor=326CE5)
![Nginx](https://img.shields.io/badge/Nginx-0d1117?style=flat-square&logo=nginx&logoColor=009639)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=FCC624)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![MongoDB](https://img.shields.io/badge/MongoDB-0d1117?style=flat-square&logo=mongodb&logoColor=47A248)
![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=4479A1)
![Redis](https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=DC382D)

**Blockchain**

![Solidity](https://img.shields.io/badge/Solidity-0d1117?style=flat-square&logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-0d1117?style=flat-square&logo=ethereum&logoColor=white)
![Web3.js](https://img.shields.io/badge/Web3.js-0d1117?style=flat-square&logo=web3dotjs&logoColor=F16822)

</div>

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=aniketverma11&show_icons=true&hide_border=true&hide_rank=true&theme=github_dark&title_color=58A6FF&text_color=8b949e&icon_color=58A6FF&bg_color=0d1117&include_all_commits=true" height="155"/>
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=aniketverma11&hide_border=true&background=0d1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=8b949e&dates=555555&stroke=21262d" height="155"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=aniketverma11&bg_color=0d1117&color=58A6FF&line=58A6FF&point=ffffff&area=true&area_color=58A6FF&hide_border=true" width="95%"/>

</div>

---

<div align="center">

**B.Tech, Computer Science & Engineering &nbsp;·&nbsp; AKTU &nbsp;·&nbsp; 2022 &nbsp;·&nbsp; 7.23 CGPA**

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=aniketverma11&style=flat-square&color=58A6FF&label=Profile+Views)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=120&section=footer&animation=fadeIn" width="100%"/>
