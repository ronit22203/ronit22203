# Ronit Saxena
### AI/ML Engineer | Production ML Systems | Healthcare + Regulated Data

<div align="center">

[![Remote, India](https://img.shields.io/badge/-Remote%2C%20India-0066FF?style=for-the-badge)](https://maps.google.com/?q=Remote)
[![IIIT-B PGDip](https://img.shields.io/badge/IIIT--B-Deep%20Learning-8A2BE2?style=for-the-badge)](https://www.iiitb.ac.in/)
[![Azure DP-100](https://img.shields.io/badge/Azure-Data%20Scientist-0078D4?style=for-the-badge&logo=microsoftazure)](https://learn.microsoft.com/en-us/certifications/azure-data-scientist/)

</div>

## Core Principle

**Production first ML systems** engineered for real world constraints.

### Shipped
- Complete prediction pipelines end to end (healthcare no show, delay, cost forecasting)
- Hybrid Graph Vector RAG (Neo4j + Qdrant) with automated PII/PHI redaction
- Deterministic vision intelligence (image/video reasoning without LLMs)
- Config-driven clinical AI platform (LangGraph + Temporal, zero-code agent definition)

### Current
Independent ML/GenAI Engineer (Contract) | Ex: **pragyaa.ai** (10+ healthcare deployments, 3,000+ daily appointments)

## About me

> Production code, research, and client work:

<div align="center">

[![Website](https://img.shields.io/badge/Website-ronitsaxena.in-181717?style=for-the-badge&logo=internet-explorer)](https://www.ronitsaxena.in)

</div>

## Performance

| Achievement | Metric |
|:---|---:|
| **Hybrid RAG** | 85% recall@5, 74.9% NDCG@5 |
| **Prediction Engine** | 100% show accuracy 500 real world records, 73% delay recall, ±12.6 min error |
| **Portfolio** | 97 Lighthouse, 95 PageSpeed |
| **Privacy** | 100% automated PII/PHI detection |
| **Image Awareness** | 100% Determinism, Modular Stages, ImageRecord, Pre Language Model Intelligence |

## Featured Work

### Clinical Agents — Config-Driven Clinical Research AI
**Repo:** [clinical-agents](https://github.com/ronit22203/clinical-agents)

Production platform for clinical research AI where agent behavior, tool selection, model parameters, and workflow routing are defined entirely in YAML — no source code changes required. Runs on two runtimes from one config: LangGraph ReAct (low latency) and Temporal Workflows (durable, auditable, human-in-the-loop).

**Engineering highlights:**
- YAML-first design: swap models, tools, prompts without touching Python
- Dual runtime (LangGraph ReAct + Temporal.io) from identical config files
- Parallel tool execution across PubMed, openFDA, ClinicalTrials.gov, and internal GraphRAG
- Human-in-the-loop approval gate before LLM synthesis (Temporal signal)
- Full audit trail per execution (latency, tokens, tools called, git commit)

**Status:** Fully containerized, regulated-environment ready.

---

### Privacy-First Medical Ingestion Pipeline
**Design Doc:** [ronitsaxena.in](https://www.ronitsaxena.in/media/statics/ingestion_layer_casestudy.pdf)

HIPAA compliant knowledge base: **Neo4j** clinical graphs + **Qdrant** semantic search. Transforms unstructured medical PDFs into production intelligence while maintaining data sovereignty.

**Engineering highlights:**
- Vision-aware extraction (Surya OCR for complex layouts)
- Automated privacy layer (PII/PHI redaction)
- Optimized chunking (512 token budget)
- Dual storage (semantic + relationship reasoning)

**Status:** Fully containerized, regulated-environment ready.

## Tech Stack

| Category | Tools |
|:---|---|
| **ML/AI** | Python, PyTorch, Transformers, XGBoost, HuggingFace |
| **MLOps** | Docker, Azure ML, MLflow, FastAPI, GitHub Actions |
| **Data** | Pandas, NumPy, SQL, Neo4j, Qdrant |
| **Infrastructure** | Linux, REST APIs, Azure, AWS, GCP |
| **Compliance** | Microsoft Presidio, audit logging |

## Featured Projects

| Project | Tech | Highlight |
|:---|---|---|
| [clinical-agents](https://github.com/ronit22203/clinical-agents) | LangGraph, Temporal, Ollama | Config-driven clinical research AI, dual runtime, HITL |
| [PredictML-Production](https://github.com/ronit22203/PredictML-Production) | XGBoost, SHAP, FastAPI | Two-stage hospital no-show/delay prediction |
| [Medical-RAG-Ingestion](https://github.com/ronit22203/Medical-RAG-Ingestion) | Neo4j, Qdrant, Presidio | Hybrid Graph-Vector RAG with PII redaction |
| [Image-Reasoning-Pipeline](https://github.com/ronit22203/Image-Reasoning-Pipeline) | CLIP, Policy Engine | Deterministic pre-LLM vision intelligence |

## Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/ronitsaxena.in-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://ronitsaxena.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ronitsaxena)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ronit22203)

</div>

---

<div align="center">

**Building production systems for healthcare at scale**

</div>
