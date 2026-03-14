<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=260&section=header&text=Aniket%20Verma&fontSize=68&fontColor=ffffff&fontAlignY=42&desc=Senior%20GenAI%20%26%20ML%20Infrastructure%20Engineer&descColor=a78bfa&descSize=19&descAlignY=62&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=14&duration=2600&pause=800&color=A78BFA&center=true&vCenter=true&width=640&lines=Building+LLM+inference+infra+on+H100+%2F+A100+GPUs;vLLM+%E2%80%A2+LangGraph+%E2%80%A2+CrewAI+%E2%80%A2+Agentic+Systems;Fine-tuning+%26+deploying+open-source+LLMs+at+scale;FastAPI+%E2%80%A2+Django+%E2%80%A2+Airflow+%E2%80%A2+Microservices;3%2B+yrs+in+AI%2FML+Infra+%E2%80%A2+Backend+%E2%80%A2+Cloud)](https://git.io/typing-svg)

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-181717?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:aniketverma1103@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-181717?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/aniketverma11)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aniketverma11)
[![Twitter](https://img.shields.io/badge/Twitter-181717?style=for-the-badge&logo=twitter&logoColor=1DA1F2)](https://twitter.com/aniket_verma11)
[![Portfolio](https://img.shields.io/badge/Orinn.in-181717?style=for-the-badge&logo=vercel&logoColor=a78bfa)](https://orinn.in)

<br/><br/>

</div>

---

<img align="right" width="42%" src="https://github-readme-stats.vercel.app/api?username=aniketverma11&show_icons=true&hide_border=true&hide_rank=true&theme=midnight-purple&title_color=a78bfa&text_color=8b949e&icon_color=a78bfa&bg_color=0d1117&include_all_commits=true&count_private=true"/>

**I build production AI infrastructure** — fine-tuning LLMs, deploying them on GPU clusters, and wiring agentic systems that run in the real world.

I run the **[Orinn AI Platform](https://orinn.in)** on GCP H100 / A100 hardware, built end-to-end from scratch — custom fine-tuned models, vLLM inference engine, FastAPI + Nginx serving layer, and a full LangGraph/CrewAI agentic stack.

**At a glance:**
- 3+ years in AI/ML infra, backend engineering & cloud systems
- Delivered 4+ SaaS products & 10+ corporate solutions
- Hands-on with GPU infrastructure, model fine-tuning & deployment
- Built on AWS, GCP & Azure across production workloads

<br clear="right"/>

---

## 💼 Experience

<table width="100%">
<tr>
<td width="50%" valign="top">

**Senior Software Engineer**
`Coforge` &nbsp;·&nbsp; Sep 2024 – Present

Building backend systems for insurance and mortgage platforms (Django, ReactJS). Developed AI-powered workflow automation and SDLC tooling with FastAPI + Jinja2.

</td>
<td width="50%" valign="top">

**Full Stack Python Developer**
`Benthon Labs` &nbsp;·&nbsp; Oct 2023 – Jul 2024

Led CRM system (Node.js, Express, MongoDB, AWS EC2). Designed microservices architecture; improved API response times and system reliability significantly.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Software Developer Engineer**
`CreateBytes` &nbsp;·&nbsp; Jul 2022 – Sep 2023

Built ML/AI SaaS products on AWS. Delivered **YugYog** — video analytics platform with **30% faster** data processing via custom ML pipeline.

</td>
<td width="50%" valign="top">

**Blockchain Developer**
`Rapid Innovation` &nbsp;·&nbsp; Nov 2021 – Jul 2022

Production DApps + smart contracts in Solidity. Automated testing suite (Chai, Hardhat) with Python orchestration scripts.

</td>
</tr>
</table>

---

## 🤖 Orinn AI Platform

<div align="center">
<img src="https://img.shields.io/badge/Status-Live-a78bfa?style=flat-square&logo=circle&logoColor=a78bfa"/>
&nbsp;
<img src="https://img.shields.io/badge/Hardware-H100%20%2F%20A100-181717?style=flat-square&logo=nvidia&logoColor=76B900"/>
&nbsp;
<img src="https://img.shields.io/badge/Engine-vLLM-181717?style=flat-square&logo=pytorch&logoColor=EE4C2C"/>
&nbsp;
<img src="https://img.shields.io/badge/Serving-FastAPI%20%2B%20Nginx-181717?style=flat-square&logo=fastapi&logoColor=009688"/>
</div>

<br/>

<table width="100%">
<tr><td width="22%" align="center"><b>Models</b></td><td>Orinn-1.6 (Qwen3.5-based fine-tune) &nbsp;·&nbsp; Orinn-1.7 (Flash Linear Attention architecture)</td></tr>
<tr><td align="center"><b>Inference</b></td><td>vLLM on GCP H100 <code>gpu-1xh100</code> + 2×A100 cluster with Nginx load balancing</td></tr>
<tr><td align="center"><b>API Layer</b></td><td>FastAPI microservices &nbsp;·&nbsp; Multimodal endpoints (text, PDF, image)</td></tr>
<tr><td align="center"><b>Agentic Stack</b></td><td>LangGraph &nbsp;·&nbsp; LangChain &nbsp;·&nbsp; CrewAI &nbsp;·&nbsp; Microsoft Copilot Studio</td></tr>
<tr><td align="center"><b>Storage</b></td><td>AWS S3 for model weight sync &nbsp;·&nbsp; GCP persistent disks for active inference</td></tr>
</table>

<details>
<summary><b>&nbsp;Engineering deep-dives</b></summary>
<br/>

- **VM Recovery** — Recovered a stopped GCP H100 instance by booting from its detached disk on a fresh VM; migrated static IP with zero data loss
- **Throughput Fix** — Diagnosed Orinn-1.7 bottleneck to a tensor format mismatch; resolved cleanly with `VLLM_USE_V1=1`
- **Weight Loader Patch** — Surgically patched `default_loader.py` to skip `visual.*` weight validation on text-only VL-named model weights (Orinn-1.6)
- **Load Balancing** — Built Nginx upstream config distributing inference traffic across both GPU nodes behind a single FastAPI gateway

</details>

---

## 🗂 Projects

<div align="center">

| Project | What it does | Stack | Impact |
|---|---|---|---|
| **[LabOps](https://labops.in)** | Lab Management System | Django · PostgreSQL · AWS | 50% AWS cost reduction |
| **[Baimanus.in](https://baimanus.in)** | News platform for tribal communities in Maharashtra | Django · CloudFront · S3 | Production CDN delivery |
| **YugYog** | Video analytics SaaS | Django · AWS · ML Pipelines | 30% faster processing |
| **LegalExpert API** | Legal document export service | FastAPI · Nginx · Gunicorn | Multi-env production deploy |

</div>

---

## 🛠 Tech Stack

<div align="center">

**AI / ML & LLM Infrastructure**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow&theme=dark"/>
&nbsp;
[![vLLM](https://img.shields.io/badge/vLLM-181717?style=flat-square&logo=pytorch&logoColor=EE4C2C)](https://github.com/vllm-project/vllm)
[![LangChain](https://img.shields.io/badge/LangChain-181717?style=flat-square&logo=chainlink&logoColor=a78bfa)](https://langchain.com)
[![LangGraph](https://img.shields.io/badge/LangGraph-181717?style=flat-square&logo=chainlink&logoColor=a78bfa)](https://langchain.com)
[![CrewAI](https://img.shields.io/badge/CrewAI-181717?style=flat-square&logo=openai&logoColor=white)](https://crewai.com)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-181717?style=flat-square&logo=huggingface&logoColor=FFD21E)](https://huggingface.co)

<br/><br/>

**Backend & APIs**

<img src="https://skillicons.dev/icons?i=python,django,fastapi,nodejs,graphql&theme=dark"/>
&nbsp;
[![Celery](https://img.shields.io/badge/Celery-181717?style=flat-square&logo=celery&logoColor=37814A)](https://docs.celeryq.dev)
[![Airflow](https://img.shields.io/badge/Airflow-181717?style=flat-square&logo=apacheairflow&logoColor=017CEE)](https://airflow.apache.org)

<br/><br/>

**Cloud & DevOps**

<img src="https://skillicons.dev/icons?i=gcp,aws,azure,docker,kubernetes,nginx,linux,git&theme=dark"/>

<br/><br/>

**Databases**

<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis&theme=dark"/>

<br/><br/>

**Blockchain**

<img src="https://skillicons.dev/icons?i=solidity&theme=dark"/>
&nbsp;
[![Hardhat](https://img.shields.io/badge/Hardhat-181717?style=flat-square&logo=ethereum&logoColor=F0D060)](https://hardhat.org)
[![Web3.js](https://img.shields.io/badge/Web3.js-181717?style=flat-square&logo=web3dotjs&logoColor=F16822)](https://web3js.org)

</div>

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=aniketverma11&hide_border=true&background=0d1117&ring=a78bfa&fire=a78bfa&currStreakLabel=a78bfa&sideLabels=8b949e&dates=555555&stroke=21262d&currStreakNum=ffffff&sideNums=ffffff" width="55%"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aniketverma11&layout=compact&hide_border=true&theme=midnight-purple&title_color=a78bfa&text_color=8b949e&bg_color=0d1117" width="38%"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=aniketverma11&bg_color=0d1117&color=a78bfa&line=a78bfa&point=ffffff&area=true&area_color=302b63&hide_border=true" width="95%"/>

</div>

---

<div align="center">

**B.Tech — Computer Science & Engineering &nbsp;·&nbsp; AKTU &nbsp;·&nbsp; 2022 &nbsp;·&nbsp; 7.23 CGPA**

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=aniketverma11&style=flat-square&color=a78bfa&label=Profile+Views)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=130&section=footer&animation=fadeIn" width="100%"/>

</div>
