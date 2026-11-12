<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:0A66C2,100:00A8E8&height=200&section=header&text=Youssef%20Taha%20Badawi&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=40" alt="Youssef Taha Badawi | AI Engineer" />

<h3>AI Engineer · LLMs, RAG & Agentic Systems · LLMOps</h3>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00A8E8&center=true&vCenter=true&width=800&height=50&lines=Building+production-ready+LLM+%26+RAG+systems;Turning+research+into+working+software;Agentic+AI+%C2%B7+Vector+Search+%C2%B7+FastAPI;Arabic+NLP+%C2%B7+Fine-tuning+%C2%B7+Quantization;Cairo%2C+Egypt+%F0%9F%87%AA%F0%9F%87%AC" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yousseftahaai/)
[![Portfolio](https://img.shields.io/badge/Portfolio-00A8E8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://youssefbadawi.online/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ytaha8586@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@ytaha8586)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/yousseftaha98)

![Profile Views](https://komarev.com/ghpvc/?username=Youssefx64&label=Profile%20Views&color=0A66C2&style=flat-square)
[![Followers](https://img.shields.io/github/followers/Youssefx64?style=flat-square&logo=github&color=00A8E8&label=Followers)](https://github.com/Youssefx64?tab=followers)
![Stars](https://img.shields.io/github/stars/Youssefx64?style=flat-square&logo=github&color=00A8E8&label=Total%20Stars)

</div>

---

## 👨‍💻 About Me

I'm an **AI Engineer** with a B.Sc. in **Artificial Intelligence & Data Science** (graduation project: **A+ / 99%**) and an **AWS Certified AI Practitioner**. I take LLM, RAG and agentic systems from experiment to production: **retrieval design, fine-tuning & quantization, evaluation gates, observability and deployment**.

I validate with **real metrics, not vibes**: RAGAS gates in CI, load tests with P95 latency, drift detection, leakage audits, and benchmarked quantization.

| | |
|---|---|
| 🏗️ **Ship** | Full products end to end: LLM pipelines, FastAPI backends, Dockerized deployments, live demos |
| 🔬 **Measure** | MLflow experiments, RAGAS, perplexity, tokens/s, VRAM, Locust load tests |
| 🌍 **Arabic NLP** | Arabic legal RAG, Arabic poetry LLM, Arabic OCR fine-tuning |
| 🎓 **Teach** | AI & LLMs instructor for online learners |

### 🔭 Right now

- 🔤 Fine-tuning a small, efficient **Arabic OCR** model (TrOCR, LoRA/PEFT)
- 🧪 Production-grade **RAG pipelines** with real retrieval metrics
- 🤖 **Multi-agent workflows** and tool-use patterns
- 🏗️ **LLMOps**: MLflow, ONNX, monitoring, CI quality gates
- 📚 Sharpening DSA and system design

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏗️ [CadArena](https://github.com/Youssefx64/CadArena)
**Natural language (Arabic/English) → CAD (DXF).** Turns plain-language engineering commands into valid floor plans, with an **Egyptian Building Code (EBC 2023)** quality gate and a RAG module (5 parsers: PDF, DXF, IFC, CSV, XLSX, knowledge graph, validation agents). **85–90% less design time** vs. manual drafting. 255 commits, 40+ API endpoints, 120+ tests, [live demo](https://cadarena.vercel.app). 🎓 **A+ (99%)**.

`Python` `FastAPI` `PostgreSQL` `WebSockets` `Next.js` `Ollama` `Docker`

</td>
<td width="50%" valign="top">

### ⚖️ [Sanad (سند)](https://github.com/Youssefx64/Sanad)
**Arabic legal RAG** over all 1,149 Egyptian Civil Code articles. Hybrid retrieval (Qdrant dense + BM25 + exact-article lookup, RRF k=60), grounding guardrail that refuses without a supporting article. 8 configs compared in MLflow, **RAGAS CI gate (faithfulness 0.90 vs 0.75)**, **P95 418 ms @ 49.4 RPS, 0% errors**, drift detection, 5% canary routing, PII scrubber.

`Qdrant` `FastAPI` `MLflow` `Langfuse` `Prometheus` `BentoML` `DVC`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🥗 [NutriAI](https://github.com/Youssefx64/NutriAI)
**Full-stack RAG SaaS** (114 commits). PDF/TXT ingestion → semantic chunking → embeddings → vector search → grounded LLM answers. Switchable providers (OpenAI/Cohere), JWT auth, per-user knowledge bases, Prometheus metrics.

`FastAPI` `React` `Qdrant` `pgvector` `Docker`

</td>
<td width="50%" valign="top">

### 🧠 [AI Codebase Understanding Engine](https://github.com/Youssefx64/AI-Codebase-Understanding-Engine)
Paste any public GitHub repo → **architecture summary**, **interactive dependency graph** (files → classes → functions), hybrid static + LLM **bug detection**, refactoring diffs and **RAG Q&A with citations**. Clean Architecture, Celery workers, WebSocket progress.

`FastAPI` `React` `ChromaDB` `Celery` `Redis`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📜 [Qareed (قريض)](https://github.com/Youssefx64/Qareed)
**Arabic poetry LLM.** QLoRA fine-tune (NF4, r=16) of Qwen2.5-1.5B-Instruct on an Ashaar-based instruction set (10 themes) using a single T4. Published on Hugging Face with a streaming Gradio demo Space.

`QLoRA` `PEFT/TRL` `Gradio` `Hugging Face`

</td>
<td width="50%" valign="top">

### 🔢 [LLM Quantization Cookbook](https://github.com/Youssefx64/LLM-Quantization-Cookbook)
Open reference notebook, **16 sections**: from-scratch affine/group-wise quantization, GPTQ, AWQ, GGUF K-quants, NF4/LLM.int8, HQQ, SmoothQuant, KV-cache, QLoRA, QAT. Benchmarked on size, Wikitext-2 perplexity, tokens/s and peak VRAM.

`PyTorch` `bitsandbytes` `GPTQ` `AWQ` `llama.cpp`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [Fraud Detection MLOps](https://github.com/Youssefx64/Fraud-Detection-MLOps)
Config-driven pipeline on **568K transactions**: leakage audit (dropped an ID feature with r≈0.86), stratified 5-fold CV, metric-based quality gates (PR-AUC, min precision/recall) across LR / RF / XGBoost. MLflow registry, FastAPI + Pytest, Docker, **ONNX export + inference benchmark**.

`scikit-learn` `XGBoost` `MLflow` `ONNX` `FastAPI`

</td>
<td width="50%" valign="top">

### ⌨️ [yctl-cli](https://github.com/Youssefx64/yctl-cli)
**Personal AI engineer CLI** for Ubuntu: scaffolds NLP/CV/ML projects, inspects datasets (CSV, Excel, JSON, Parquet) and diagnoses Python/CUDA/GPU health.

`Python` `CLI`

</td>
</tr>
</table>

### 🧩 More Projects

| Project | What it does | Stack |
|---|---|---|
| 💊 [PharmaSaaS](https://github.com/Youssefx64/PharmaSaaS) | Multi-tenant pharmacy platform: inventory, orders, prescriptions with branch-level data isolation | `FastAPI` `React 19` `PostgreSQL` |
| 🔧 [CadArena DXF Viewer](https://github.com/Youssefx64/CadArena-DXF-viewer) | Companion viewer for CadArena DXF outputs | `Web` |
| 🛰️ [Aether Analytics](https://github.com/Youssefx64/Aether-Analytics-2025-NASA-Space-Apps-Challenge) | NASA Space Apps 2025 (2-person team): automated retrieval, cleaning and visualization of NASA earth/space datasets | `Python` `Data Viz` |
| 🎙️ [Speech Emotion Recognition](https://www.kaggle.com/code/yousseftaha98/speech-emotion-recognition-ser) | CNN classifier for emotion in audio using MFCC/spectrogram features | `CNN` `Kaggle` |
| 🫁 Pneumonia X-ray Classifier | MobileNetV2 transfer learning + Gradio app | `TensorFlow` `Gradio` |
| ⚡ Big Data with PySpark | Customer segmentation + Kaggle TPS Apr-2021 baseline | `PySpark` |
| 🔍 Vector DB Search | Semantic and image search with Pinecone and Qdrant | `Pinecone` `Qdrant` |
| 🧭 AI Search Algorithms | Hill Climbing, Simulated Annealing, UCS, IDFS, maze game with AI search | `Python` |
| 📊 Dash Dashboard · 🖼️ Image Processing GUI | Data-visualization dashboard and image-processing desktop GUI | `Dash` `Python` |

🔗 **All repos:** [github.com/Youssefx64?tab=repositories](https://github.com/Youssefx64?tab=repositories)

---

## 🛠️ Tech Stack

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **GenAI / LLM** | ![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Claude](https://img.shields.io/badge/-Claude-D97757?style=flat-square&logo=anthropic&logoColor=white) ![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square) ![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square) |
| **ML / DL** | ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![ONNX](https://img.shields.io/badge/-ONNX-005CED?style=flat-square&logo=onnx&logoColor=white) |
| **Backend / Infra** | ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **Vector DBs** | ![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square) ![pgvector](https://img.shields.io/badge/-pgvector-336791?style=flat-square&logo=postgresql&logoColor=white) ![FAISS](https://img.shields.io/badge/-FAISS-0088CC?style=flat-square) ![ChromaDB](https://img.shields.io/badge/-ChromaDB-FF6F00?style=flat-square) |
| **NLP** | ![spaCy](https://img.shields.io/badge/-spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white) ![NLTK](https://img.shields.io/badge/-NLTK-154f3c?style=flat-square) ![Transformers](https://img.shields.io/badge/-Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **MLOps** | ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![DVC](https://img.shields.io/badge/-DVC-945DD6?style=flat-square&logo=dvc&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white) ![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

**Also:** Hugging Face (Transformers, PEFT, TRL) · RAGAS · Langfuse · Locust · BentoML · BM25 / RRF / reranking · GPTQ / AWQ / GGUF · vLLM · TorchServe · Celery · Redis · WebSockets · JWT

---

## 📊 GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=Youssefx64&theme=tokyonight&hide_border=true&background=0D1117&stroke=00A8E8&ring=00A8E8&fire=00A8E8&currStreakLabel=00A8E8" alt="GitHub Streak" />

<img src="https://raw.githubusercontent.com/Youssefx64/Youssefx64/output/github-snake-dark.svg" alt="Contribution snake" width="100%" />

<table>
<tr>
<td width="50%"><img src="./github-metrics-profile.svg" alt="Profile overview" width="100%" /></td>
<td width="50%"><img src="./github-metrics-activity.svg" alt="Activity and community" width="100%" /></td>
</tr>
<tr>
<td width="50%"><img src="./github-metrics-repos.svg" alt="Repositories" width="100%" /></td>
<td width="50%"><img src="./github-metrics-languages.svg" alt="Languages" width="100%" /></td>
</tr>
</table>

<img src="./github-metrics-calendar.svg" alt="Contribution calendar" width="100%" />

</div>

---

## 🎓 Education

**B.Sc. in Artificial Intelligence & Data Science**, Faculty of Computers & AI, Beni-Suef National University (Oct 2022 – Jul 2026)

- 🏆 Graduation Project: **CadArena**, score **A+ (99%)**
- 📖 Machine Learning · Deep Learning · NLP · Computer Vision · Big Data · Data Structures & Algorithms · AI Search

## 💼 Experience

| Role | Organization | Period |
|---|---|---|
| Backend AI Engineer Intern | FlyRank AI (Remote) | Jun 2026 – Oct 2026 |
| Founder & Team Lead | CadArena (Capstone) | Sep 2025 – Jun 2026 |
| AI/ML Intern (ML, CV & NLP tracks) | National Telecommunication Institute (NTI) | Dec 2024 – Sep 2025 |
| AI & LLMs Instructor | Self-Employed, Remote | Oct 2025 – Nov 2025 |
| Big Data Engineer Intern | Huawei | Aug 2025 |
| Data Engineer Trainee | Digital Egypt Pioneers Initiative (DEPI) | Jun 2024 – Sep 2024 |
| AI Fundamentals Trainee | Zewail City of Science and Technology | Aug 2023 – May 2024 |

## 🏅 Certifications

`AWS Certified AI Practitioner` · `NVIDIA · Building LLM Applications With Prompt Engineering` · `NVIDIA DLI · Generative AI` · `NVIDIA · AI for All` · `Stanford & DeepLearning.AI · Supervised ML` · `Oracle OCI 2025 AI Foundations Associate` · `NTI · NLP` · `NTI · Deep Learning` · `Microsoft Data Engineer (DEPI)` · `Huawei Big Data Associate` · `Google · Build with AI` · `NASA Space Apps Challenge 2025`

---

<div align="center">

### 🤝 Open to AI engineering roles, collaborations, and interesting problems

**[LinkedIn](https://www.linkedin.com/in/yousseftahaai/)** · **[Portfolio](https://youssefbadawi.online/)** · **[Email](mailto:ytaha8586@gmail.com)** · **[Medium](https://medium.com/@ytaha8586)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" alt="footer" />

</div>
