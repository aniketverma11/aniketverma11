<div align="center">

# Aniket Verma

**Senior GenAI & ML Infrastructure Engineer**

[aniketverma1103@gmail.com](mailto:aniketverma1103@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/aniketverma11) &nbsp;·&nbsp; [GitHub](https://github.com/aniketverma11) &nbsp;·&nbsp; [Twitter](https://twitter.com/aniket_verma11) &nbsp;·&nbsp; Noida, India

</div>

---

I build and operate production AI infrastructure — from fine-tuning LLMs to deploying them on GPU clusters and wiring up agentic systems that run in production. Currently working at **Charter Communications** on network monitoring pipelines, and independently running the **Orinn** AI platform on GCP H100/A100 hardware.

---

## Experience

**Senior Software Engineer &mdash; Charter Communications** &nbsp;&nbsp;`Sep 2024 – Present`

Working on the NetOps team — Python-based Airflow pipelines for BGP/network monitoring and ARIN WHOIS data ingestion. Refactored the `juniper_inventory_report` project: extracted a standalone `GraphQLClient` package with lazy auth and retry logic, rewrote report and mailer modules using stdlib only, removed Vault dependency in favor of Airflow-native secrets, and migrated to `pyproject.toml`.

**Senior Software Engineer &mdash; Coforge** &nbsp;&nbsp;`Sep 2024 – Present`

Building backend systems for insurance and mortgage platforms using Django and ReactJS. Developed AI-powered workflow automation features and SDLC tooling with FastAPI and Jinja2.

**Full Stack Python Developer &mdash; Benthon Labs** &nbsp;&nbsp;`Oct 2023 – Jul 2024`

Led development of a CRM system (Node.js, Express, MongoDB, AWS EC2). Designed a microservices architecture that improved API response times and system reliability.

**Software Developer Engineer &mdash; CreateBytes** &nbsp;&nbsp;`Jul 2022 – Sep 2023`

Built ML/AI SaaS products on AWS. Delivered YugYog — a video analytics platform with 30% faster data processing via a custom ML pipeline on AWS.

**Blockchain Developer &mdash; Rapid Innovation** &nbsp;&nbsp;`Nov 2021 – Jul 2022`

Developed production DApps and smart contracts in Solidity. Built an automated testing suite using Chai and Hardhat with Python orchestration.

---

## Projects

**Orinn AI Platform** &nbsp;&nbsp;[orinn.in](https://orinn.in)

Private LLM inference cloud. Fine-tuned and deployed Orinn-1.6 (Qwen3.5-based) and Orinn-1.7 (Flash Linear Attention architecture) on GCP H100 and 2×A100 clusters via vLLM. FastAPI serves as the user-facing layer; Nginx distributes traffic across GPU nodes. Model weights synced to AWS S3. Agentic layer built on LangGraph, LangChain, and CrewAI.

Key engineering: recovered a stopped GCP H100 VM by booting from its detached disk on a fresh instance with zero data loss; diagnosed and fixed Orinn-1.7 throughput bottleneck (tensor format mismatch → `VLLM_USE_V1=1`); patched `default_loader.py` to skip visual weight validation on text-only VL-named model weights.

**LabOps** &nbsp;&nbsp;[labops.in](https://labops.in)

Lab Management System. Reduced AWS infrastructure costs by 50% through backend architecture optimization — Django, PostgreSQL, and targeted query tuning.

**Baimanus.in**

News platform for Maharashtra's tribal communities. Django backend, AWS CloudFront and S3 for fast, reliable content delivery.

**LegalExpert API**

Legal document export service — FastAPI + Nginx on Ubuntu, multi-environment Gunicorn worker tuning, cron-based cleanup of export artifacts.

---

## Skills

| | |
|---|---|
| **AI / ML** | vLLM, PyTorch, TensorFlow, LangGraph, LangChain, CrewAI, HuggingFace, RAG pipelines |
| **Backend** | Python, Django, FastAPI, Celery, Apache Airflow, GraphQL, Node.js |
| **Cloud** | GCP (A100/H100 VMs), AWS (EC2, S3, Lambda, SageMaker, CloudWatch, ECS), Azure |
| **DevOps** | Docker, Kubernetes, Nginx, Linux, CI/CD |
| **Databases** | PostgreSQL, MongoDB, MySQL, Redis |
| **Blockchain** | Solidity, Hardhat, Web3.js, Ethereum, DeFi |

---

## Education

B.Tech, Computer Science & Engineering &nbsp;·&nbsp; Dr. A.P.J. Abdul Kalam Technical University &nbsp;·&nbsp; 2022 &nbsp;·&nbsp; 7.23 CGPA

---

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=aniketverma11&show_icons=true&hide_border=true&theme=default&title_color=24292f&text_color=57606a&icon_color=0969da&bg_color=ffffff&hide_rank=false)](https://github.com/aniketverma11)&nbsp;[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=aniketverma11&layout=compact&hide_border=true&theme=default&title_color=24292f&text_color=57606a&bg_color=ffffff)](https://github.com/aniketverma11)

</div>
