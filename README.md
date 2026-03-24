# ⚙️ MLOps Framework — Documentation & Strategy

> A collection of beautifully designed, self-contained HTML documents covering the full MLOps lifecycle for Machine Learning Systems.  
> No build step, no dependencies — open in any browser and you're done.

---

## 🔗 Live Pages

| Page | URL |
|---|---|
| 📘 Technical Documentation | [mlops_documentation.html](https://vanshccmodi.github.io/DOCS/mlops_documentation.html) |
| 🚀 Real-Life MLOps Pipeline | [op_final.html](https://vanshccmodi.github.io/DOCS/op_final.html) |
| 🚰 Pump Optimization Presentation | [pump_optimization.html](https://vanshccmodi.github.io/DOCS/pump_optimization.html) |
| 📊 ETL Pipeline for Sensor Data Processing | [etl_airflow_dag.html](https://vanshccmodi.github.io/DOCS/etl_airflow_dag.html) |
| ⚡ Universal MLOps Concept | [mlops_concept.html](https://vanshccmodi.github.io/DOCS/mlops_concept.html) |
| 🚀 Omni ML Pro Pipeline v2 | [omni_ml_pipeline.html](https://vanshccmodi.github.io/DOCS/omni_ml_pipeline.html) |
| 🕉️ Ramayana RAG: Story-Aware Archive | [RamayanaOg.html](https://vanshccmodi.github.io/DOCS/RamayanaOg.html) |
| 🔄 Airflow & MLflow Integration Setup | [mlflow_with_airflow.html](https://vanshccmodi.github.io/DOCS/mlflow_with_airflow.html) |

---

## 📄 Pages at a Glance

### 1. `op_final.html` — Real-Life MLOps Pipeline Documentation
A **Premium Architecture**-driven documentation detailing a production-grade Industrial IoT ML system.

**Sections covered:**
- 🏗️ **System Architecture**: Vertical mermaid-flow of the full IoT data lifecycle.
- 📁 **File Map**: Connectivity between DAGs, tasks, plugins, and APIs.
- ⚙️ **Environment Setup**: Docker, .env, and Airflow configuration guides.
- 🧪 **Task-by-Task**: Deep dive into KS-Drift testing, MLflow registry, and S3 deployment.
- 📡 **API services**: Mock IoT sensor stream and FastAPI model serving.
- 🛡️ **Resilience**: Retry logic, cleanup strategies, and failure callbacks.

**Design system:** Modern Dual Theme (Light/Dark toggle) · Mermaid.js v10 Vertical Flow · Code Copy Buttons · Inter + JetBrains Mono fonts · Scroll Progress Tracking.

---

### 2. `etl_airflow_dag.html` — ETL Pipeline for Sensor Data Processing
A **Premium Glassmorphism**-styled documentation detailng a production-grade sensor data ETL pipeline using Airflow, PostgreSQL, and MLflow.

**Sections covered:**
- 🏗️ **Orchestration Flow**: Sequential pipeline execution from schema setup to notification.
- 🔄 **Append Strategy**: Implementation of incremental loading to build rich time-series history.
- 📝 **Atomic Traceability**: Inclusion of `run_date` and `batch_id` for expert-level data lineage.
- 🧪 **AI Guards**: Anomaly Detection using **Isolation Forest** and Linear Regression trend analysis.
- 📊 **MLflow Integration**: Tracking statistical distributions, dataset snapshots, and artifacts.

**Design system:** Dark Glassmorphism (`#0a0e1a` base, radial glow effects, `--accent: #6366f1`) · Inter font · Mermaid.js architecture visualization.

---

### 3. `mlops_documentation.html` — Technical Reference
A **Neumorphism**-styled, scrollable documentation page covering the entire MLOps framework in depth.

**Sections covered:**
- 📐 Framework Overview & Architecture
- 📊 Evaluation Metrics — MAE, RMSE, WAPE, Bias, MASE, MAPE
- 🌿 SHAP-based Explainability
- 🧪 MLflow — Experiment Tracking & Model Registry
- 🌀 Airflow — Pipeline Orchestration & DAG Design
- 📡 Production Monitoring & Drift Detection

**Design system:** Dark Neumorphism (`#1e2030` base, inset/outset shadows) · Inter + JetBrains Mono fonts · Active-scroll sidebar nav.

---

### 4. `RamayanaOg.html` — Ramayana RAG Knowledge Archive
A **Neumorphic-Glassmorphism (v3)**-styled portal detailing a high-fidelity spiritual RAG system.

**Sections covered:**
- 🕉️ **Project Genesis**: Valmiki Ramayana to queryable deep-reasoning archive.
- 🧩 **Story-Aware Strategy**: Narrative chunking (202 events) chronologically respected.
- ⚙️ **Technical Stack**: LanceDB, BGE-M3, FlashRank, and Groq/SambaNova failover.
- 🧪 **RAG Monitoring**: Automated safety gates for Faithfulness and Relevance.

**Design system:** Dark Neumorphic-Glassmorphism (`#0a0e1a` base) · Mermaid.js Graph RAG viz · Interactive Story Timeline.

---

### 5. `pump_optimization.html` — Strategy Deck
A **Claymorphism**-styled interactive presentation focused on the Smart Pump Monitoring / Ad Sales Forecasting system.

**Sections covered:**
- 🏗️ Architecture, Airflow, MLflow, and Docker strategies.
- 🔁 CI/CD Strategy via GitHub Actions.
- 🛡️ Model Governance & Rollback Procedures.
- 📡 Monitoring & Alerting systems.

---

### 6. `mlops_concept.html` — Universal Framework Concept
A **Modern Config-Driven Architecture** documentation page defining a generalized pipeline strategy.

**Sections covered:**
- ⚙️ Universal Config-Driven Design
- 💾 Data Versioning (DVC) & Feature Store workflows
- ⚖️ Automated Drift Detection & Retraining

---

### 7. `omni_ml_pipeline.html` — Omni ML Pro Pipeline v2
A **Production-grade MLOps Pipeline** documentation detailing a complete ML lifecycle orchestrating multiple AWS services natively on Airflow 3.x.

**Sections covered:**
- 🏗️ **Orchestration**: End-to-end task automation with Airflow.
- 📦 **Training**: Local Scikit-learn vs Cloud AWS SageMaker Training.
- 📊 **Model Tracking**: Deep integration with MLflow logging.
- 🤖 **AI Analysis**: Utilizing Amazon Bedrock (Nova Lite) for automated report summaries.

---

## 🛠️ MLOps Stack

| Tool | Role |
|---|---|
| **Apache Airflow 3.x** | Workflow orchestration — DAG-based scheduling & retries |
| **MLflow** | Experiment tracking, model versioning, promotion gates |
| **PostgreSQL 16** | Core data storage for Bronze/Silver/Gold tiers |
| **AWS S3** | Production model artifacts & CHAMPION model hosting |
| **FastAPI** | High-performance model serving & sensor simulation |
| **Docker / Compose** | Reproducible environments across dev → staging → prod |

---

## 🎨 Design Highlights

| | Technical Docs | Real-Life Pipeline | Universal Concept | **Sensor ETL** |
|---|---|---|---|---|
| **Style** | Neumorphism | **Modern UI** | Clean Modern | **Glass v2** |
| **Theme** | Dark Only | **Dual (L/D)** | Dual (L/D) | Dark Only |
| **Nav** | Sidebar | **Fixed Sidebar** | Scroll-spy | Fixed sidebar |
| **Diagram** | Static | **Mermaid TD** | Mermaid LR | Mermaid v2 |

---

## 🚀 Run Locally

No build tools needed — just open the files directly:

```bash
# Clone the repo
git clone https://github.com/vanshccmodi/DOCS.git
cd DOCS

# Open in browser (Example)
start op_final.html
start mlops_documentation.html
start pump_optimization.html
start omni_ml_pipeline.html
```

---

## 📁 Repository Structure

```
DOCS/
├── op_final.html            # Real-Life Industrial MLOps Pipeline Documentation
├── etl_airflow_dag.html     # ETL Pipeline for Sensor Data Processing
├── mlflow_with_airflow.html # Airflow & MLflow Integration Setup Guide
├── mlops_concept.html       # Universal config-driven architecture doc
├── omni_ml_pipeline.html    # Omni ML Pro Pipeline v2 MLOps Architecture
├── RamayanaOg.html         # Ramayana RAG Story-Aware Knowledge Archive
├── mlops_documentation.html # Technical reference (Neumorphism)
├── pump_optimization.html   # Strategy deck (Claymorphism)
└── README.md
```

---

## 👤 Author

**Vansh Modi** · MLOps Engineer  
[GitHub Profile](https://github.com/vanshccmodi)