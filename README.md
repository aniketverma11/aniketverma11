<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,2,5,30&height=3&section=header" width="100%"/>

<br/>

```
 ______  __   __  __   __  ___   _  _______  _______
|      ||  |_|  ||  | |  ||   | | ||       ||       |
|  _    ||       ||  |_|  ||   |_| ||    ___||_     _|
| | |   ||       ||       ||      _||   |___   |   |
| |_|   ||       ||_     _||     |_ |    ___|  |   |
|       || ||_|| |  |   |  |    _  ||   |___   |   |
|______| |_|   |_|  |___|  |___| |_||_______|  |___|
```

### Aniket Verma
**Senior GenAI · ML Infrastructure · Backend Systems**

[![Mail](https://img.shields.io/badge/-aniketverma1103@gmail.com-black?style=flat&logo=gmail&logoColor=white)](mailto:aniketverma1103@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-aniketverma11-black?style=flat&logo=linkedin)](https://www.linkedin.com/in/aniketverma11)
[![GitHub](https://img.shields.io/badge/-aniketverma11-black?style=flat&logo=github)](https://github.com/aniketverma11)
[![Twitter](https://img.shields.io/badge/-aniket__verma11-black?style=flat&logo=twitter)](https://twitter.com/aniket_verma11)

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,2,5,30&height=3&section=header" width="100%"/>

</div>

<br/>

> I build production AI infrastructure — fine-tuning LLMs, deploying them on GPU clusters, and wiring agentic systems end-to-end. I run the **Orinn** AI platform on GCP H100/A100 hardware, built from scratch. 3+ years across AI/ML infrastructure, backend engineering, and cloud systems.

<br/>

---

## Experience

<table>
<tr>
<td valign="top" width="50%">

**Senior Software Engineer**
Coforge &nbsp;·&nbsp; `Sep 2024 – Present`

Building backend systems for insurance and mortgage platforms using Django and ReactJS. Developed AI-powered workflow automation and SDLC tooling with FastAPI and Jinja2.

</td>
<td valign="top" width="50%">

**Full Stack Python Developer**
Benthon Labs &nbsp;·&nbsp; `Oct 2023 – Jul 2024`

Led CRM system development (Node.js, Express, MongoDB, AWS EC2). Designed microservices architecture; improved API response times and overall system reliability.

</td>
</tr>
<tr>
<td valign="top" width="50%">

**Software Developer Engineer**
CreateBytes &nbsp;·&nbsp; `Jul 2022 – Sep 2023`

Built ML/AI SaaS products on AWS. Delivered YugYog — a video analytics platform with **30% faster** data processing via a custom ML pipeline.

</td>
<td valign="top" width="50%">

**Blockchain Developer**
Rapid Innovation &nbsp;·&nbsp; `Nov 2021 – Jul 2022`

Developed production DApps and smart contracts in Solidity. Built an automated testing suite with Chai and Hardhat; Python-based blockchain orchestration.

</td>
</tr>
</table>

---

## Orinn AI Platform &nbsp;·&nbsp; [orinn.in](https://orinn.in)

> *End-to-end private LLM inference cloud — built and operated independently.*

<table>
<tr>
<td width="30%" align="center"><b>Models</b></td>
<td>Orinn-1.6 (Qwen3.5-based fine-tune) &nbsp;·&nbsp; Orinn-1.7 (Flash Linear Attention architecture)</td>
</tr>
<tr>
<td align="center"><b>Inference</b></td>
<td>vLLM on GCP H100 <code>gpu-1xh100</code> + 2×A100 cluster</td>
</tr>
<tr>
<td align="center"><b>Serving</b></td>
<td>FastAPI user-facing layer &nbsp;·&nbsp; Nginx upstream load balancer across GPU nodes</td>
</tr>
<tr>
<td align="center"><b>Agentic Stack</b></td>
<td>LangGraph &nbsp;·&nbsp; LangChain &nbsp;·&nbsp; CrewAI &nbsp;·&nbsp; Microsoft Copilot Studio</td>
</tr>
<tr>
<td align="center"><b>Storage</b></td>
<td>AWS S3 for model weight sync &nbsp;·&nbsp; Multi-modal API (PDF / Image)</td>
</tr>
</table>

**Engineering highlights:**
- Recovered a stopped GCP H100 VM by booting from its detached disk on a new instance — zero data loss, static IP migrated
- Diagnosed Orinn-1.7 throughput bottleneck: tensor format mismatch → resolved with `VLLM_USE_V1=1`
- Patched `default_loader.py` to skip `visual.*` weight validation on text-only VL-named model weights

---

## Projects

**LabOps &nbsp;·&nbsp; [labops.in](https://labops.in)**
Lab Management System. Cut AWS costs by **50%** through Django + PostgreSQL backend architecture optimization.

**Baimanus.in**
News platform for Maharashtra's tribal communities. Django backend, AWS CloudFront and S3 for fast content delivery.

**YugYog**
Video analytics SaaS — 30% faster data processing, custom ML pipeline, high post-launch satisfaction scores.

**LegalExpert API**
Legal document export service — FastAPI + Nginx, multi-environment Gunicorn tuning, cron-based artifact cleanup.

---

## Skills

<div align="center">

![Python](https://img.shields.io/badge/Python-000?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-000?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-000?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-000?style=flat-square&logo=celery&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-000?style=flat-square&logo=apacheairflow&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-000?style=flat-square&logo=graphql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-000?style=flat-square&logo=nodedotjs&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-000?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-000?style=flat-square&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000?style=flat-square&logo=chainlink&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-000?style=flat-square&logo=huggingface&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-000?style=flat-square&logo=pytorch&logoColor=white)

![GCP](https://img.shields.io/badge/GCP-000?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-000?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-000?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-000?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-000?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-000?style=flat-square&logo=linux&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-000?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-000?style=flat-square&logo=redis&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-000?style=flat-square&logo=solidity&logoColor=white)

</div>

---

## Education

**B.Tech — Computer Science & Engineering** &nbsp;·&nbsp; AKTU &nbsp;·&nbsp; 2022 &nbsp;·&nbsp; 7.23 CGPA

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=aniketverma11&show_icons=true&hide_border=true&hide_rank=true&theme=dark&title_color=ffffff&text_color=aaaaaa&icon_color=ffffff&bg_color=0d1117&include_all_commits=true" height="150"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aniketverma11&layout=compact&hide_border=true&theme=dark&title_color=ffffff&text_color=aaaaaa&bg_color=0d1117" height="150"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=aniketverma11&hide_border=true&theme=dark&background=0d1117&ring=ffffff&fire=ffffff&currStreakLabel=ffffff&sideLabels=aaaaaa&dates=555555&stroke=333333" width="60%"/>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,2,5,30&height=3&section=footer" width="100%"/>

</div>
