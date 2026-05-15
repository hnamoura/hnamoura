# Hi there, I'm Hamed Namoura 👋

### **Senior AI Systems Architect | Agentic Engineer | Data Scientist | Ph.D. Level (ABD) Researcher**

I specialize in architecting **autonomous AI systems**, **high-frequency trading engines**, and **industrial digital twins**. My background combines Ph.D.-level engineering physics and optimization with modern, scalable software architecture.

> 🔒 **Note on Privacy:** Most of my commercial work and proprietary algorithms are hosted in **private repositories** to protect Intellectual Property. Below is a detailed breakdown of the architectures and systems I have built.

---

## 🏗️ Featured Architectures & Systems

### 🧠 1. Autonomous Agents & RAG Systems
*Production-grade frameworks for autonomous reasoning and tool use.*

| Project | Architecture & Tech Stack |
| :--- | :--- |
| **Demoto Platform (IDP)** | • **Core:** Enterprise Intelligent Document Processing (IDP) with LLM extraction (GPT-4o) and confidence-gated HITL review.<br>• **Orchestration:** **23+ Go microservices** managed via **Temporal** distributed workflows and **Kong API Gateway**.<br>• **Distributed Data:** **PostgreSQL (Citus)** for tenant isolation, **Kafka** event streaming, **ClickHouse** for OLAP billing analytics, and **Qdrant** for hybrid vector search.<br>• **Scale:** Multi-tenant, cloud-native architecture with HMAC-signed webhooks and NATS JetStream notifications. |
| **OmniScale AI (Marketing)** | • **Logic:** **LangGraph** multi-agent orchestrator (Analyst/Strategist/Executor).<br>• **RAG:** **ChromaDB** with semantic filtering for 9+ international markets.<br>• **Stack:** FastAPI, Groq (Llama 3), Pydantic, Docker. |
| **AutoSec (Agentic Framework)** | • **Core:** Autonomous Security Agents using **Model Context Protocol (MCP)**.<br>• **Stack:** Docker, K8s, RAG Pipeline, Observability modules.<br>• **Features:** Self-healing pipelines, autonomous threat detection. |
| **Omni-Lab (R&D Nexus)** | • **Logic:** **LlamaIndex** "Chief Scientist" agent with ReAct (Reason+Act) patterns.<br>• **Data:** **Qdrant** (Vector Search) + **PostgreSQL** (Lab State).<br>• **UI:** React + Tailwind dashboard for real-time agent monitoring. |

### 📈 2. Financial AI & High-Frequency Trading
*Algorithmic trading systems processing real-time market data.*

| Project | Architecture & Tech Stack |
| :--- | :--- |
| **HFT Simulation Engine** | • **Core:** Deterministic, exchange-style simulation written in **Rust**.<br>• **Performance:** Lock-free bounded SPSC queues and fixed-point math for zero-allocation hot paths.<br>• **AI:** Native fixed-point alpha model runtime with offline affine **ONNX-to-native compilation**. |
| **Crypto Signal System** | • **AI:** Real-time ensemble using **LightGBM + XGBoost** with **Optuna** hyperparameter tuning.<br>• **Stack:** **Next.js 15** frontend, **Python 3.12** microservices, **Redis Streams**, and **TimescaleDB**.<br>• **Features:** Dynamic pair subscription with sub-second WebSocket delivery of 30+ quantitative indicators. |
| **Market-Wide "Sniper" Bot** | • **Strategy:** Scans **200+ Futures pairs** for "Whale Reversals" using 11-factor confluence (VPVR, Heatmaps, CVD).<br>• **Ops:** Auto-healing architecture (0-downtime) on Render. |
| **Deep RL Trading Bot** | • **AI:** **PPO (Proximal Policy Optimization)** trained on 1M+ timesteps.<br>• **Stack:** **FastAPI** + **Flutter** dashboard + Binance WebSocket.<br>• **Speed:** <100ms inference latency for real-time signal generation. |
| **Crypto Arbitrage Engine** | • **Data Eng:** **Apache Kafka** (Ingestion) + **Apache Spark** (Stream Processing).<br>• **Orchestration:** **Apache Airflow** DAGs for triangular arbitrage strategies.<br>• **Storage:** **MinIO** S3-compatible Data Lakehouse. |
| **Self-Learning Sentinel** | • **ML:** **River** (Online Machine Learning) for incremental learning (no retraining).<br>• **Features:** Real-time Orderbook analysis, Liquidations, and TPO Profiling. |

### 🏭 3. Industrial Digital Twins & Engineering
*Physics-informed AI for AEC (Architecture, Engineering, Construction).*

| Project | Architecture & Tech Stack |
| :--- | :--- |
| **AEC BIM Neural Twin** | • **Integration:** **Autodesk APS** + **Revit/Navisworks** bi-directional sync.<br>• **IoT:** **Redis Streams** for real-time sensor ingestion.<br>• **AI:** **IsolationForest** for predictive maintenance & anomaly detection. |
| **Neuro-Lattice System** | • **Simulation:** Finite Element Analysis (FEA) with **scikit-fem**.<br>• **AI:** **Graph Neural Networks (GNN)** on PyTorch Geometric for stress prediction.<br>• **Ops:** Full **MLflow** pipeline for experiment tracking. |

### ☁️ 4. Scalable Infrastructure & MLOps
*High-performance backend systems and DevOps implementations.*

| Project | Architecture & Tech Stack |
| :--- | :--- |
| **GigaChat (Enterprise Msg)** | • **Scale:** **ScyllaDB** (Message Store) + **Redis** (Pub/Sub) + **Go (Golang)**.<br>• **Features:** E2E encryption, WebRTC calls, 100k+ concurrent connections. |
| **Kinetic API (MLOps)** | • **Pipeline:** CI/CD for Data (**DVC**), Model (**MLflow**), and Code (GitHub Actions).<br>• **SRE:** Prometheus/Grafana observability, Canary deployments, and Drift Detection. |

### 🛒 5. Enterprise Retail & Desktop Applications
*Commercial-grade, event-driven architectures with embedded analytics.*

| Project | Architecture & Tech Stack |
| :--- | :--- |
| **Smart SupermarketPOS** | • **Core:** **C# / .NET 8.0** + **WPF** (MVVM) Clean Layered Architecture.<br>• **Pattern:** **Event-Driven** (Domain Events, EventJournal) with automated crash recovery.<br>• **AI & Data:** Local **ML.NET** (Forecasting/Anomalies), **SQLite** + EF Core.<br>• **Integration:** ESC/POS Thermal Printer, Barcode Scanner, QuestPDF, EPPlus. |

---

## 🛠 Technical Arsenal

* **Languages:** Rust (High-Performance), Go (Scalability), Python (Expert AI/ML), C# (.NET 8), TypeScript, LaTeX.
* **AI & ML:** LangGraph, LlamaIndex, LightGBM/XGBoost, PyTorch, ML.NET, Optuna, River (Online ML).
* **Front-end:** Next.js 15, React, React Native, Tailwind CSS, Flutter.
* **Data Engineering:** Kafka, Redis Streams, ClickHouse (OLAP), ScyllaDB, PostgreSQL (Citus), Qdrant, ChromaDB, SQLite.
* **DevOps & Infrastructure:** Kubernetes, Docker, GitHub Actions, Prometheus, Grafana, Terraform, Temporal, Kong Gateway.

---

<div align="center">
  <i>"I build systems that think, learn, and scale."</i><br>
  <b>Open for Senior Technical Roles & Consultancy</b>
</div>
