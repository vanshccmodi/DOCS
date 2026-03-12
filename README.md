# ⚙️ MLOps Framework — Documentation & Strategy

> A collection of beautifully designed, self-contained HTML documents covering the full MLOps lifecycle for Machine Learning Systems.  
> No build step, no dependencies — open in any browser and you're done.

---

## 🔗 Live Pages

| Page | URL |
|---|---|
| 📘 Technical Documentation | [mlops_documentation.html](https://vanshccmodi.github.io/DOCS/mlops_documentation.html) |
| 🚰 Pump Optimization Presentation | [pump_optimization.html](https://vanshccmodi.github.io/DOCS/pump_optimization.html) |
| ⚡ Universal MLOps Concept | [mlops_concept.html](https://vanshccmodi.github.io/DOCS/mlops_concept.html) |
| 🔄 Airflow & MLflow Integration Setup | [mlflow_with_airflow.html](https://vanshccmodi.github.io/DOCS/mlflow_with_airflow.html) |
| 📊 Enterprise Sensor ETL Pipeline | [etl_airflow_dag.html](https://vanshccmodi.github.io/DOCS/etl_airflow_dag.html) |

---

## 📄 Pages at a Glance

### 1. `etl_airflow_dag.html` — Enterprise Sensor ETL Pipeline
A **Modern Dark/Glassmorphism**-styled documentation page detailing a production-grade sensor data analytics pipeline.

**Sections covered:**
- 🏗️ **Medallion Architecture**: Bronze (Raw), Silver (Enriched), and Gold (Aggregated) data flow.
- 🧪 **AI Integration**: Anomaly Detection using **Isolation Forest** and Linear Regression trend analysis.
- 📊 **MLflow Observability**: Deep tracking of statistical distributions, lineage, and data health scores.
- 🚨 **Intelligent Alerting**: Success reports via direct SMTP and Failure callbacks.
- 🐋 **Environment Automation**: Docker-compose orchestration and dynamic DB schema management.

**Design system:** Dark Glassmorphism (`#0a0e1a` base, glossy cards, `--accent: #6366f1`) · Inter + JetBrains Mono fonts · Interactive medallion flow diagram · Collapsible implementation steps.

---

### 2. `mlops_documentation.html` — Technical Reference
A **Neumorphism**-styled, scrollable documentation page covering the entire MLOps framework in depth.

**Sections covered:**
- 📐 Framework Overview & Architecture
- 📊 Evaluation Metrics — MAE, RMSE, WAPE, Rolling WAPE, Bias, MASE, MAPE
- 🌿 SHAP-based Explainability
- 🧪 MLflow — Experiment Tracking & Model Registry
- 🌀 Airflow — Pipeline Orchestration & DAG Design
- ️ Model Governance & Rollback Procedures
- 📡 Production Monitoring & Drift Detection

**Design system:** Dark Neumorphism (`#1e2030` base, inset/outset shadows, `--accent: #7c6af7`) · Inter + JetBrains Mono fonts · Active-scroll sidebar nav

---

### 3. `pump_optimization.html` — Strategy Deck
A **Claymorphism**-styled interactive presentation built for stakeholder and mentor walkthroughs, focused on the Smart Pump Monitoring / Ad Sales Forecasting system.

**Sections covered:**
- 🗂️ Dashboard & Tool Selection rationale
- 👤 Role & Responsibility boundaries (MLOps Engineer scope)
- 🏗️ System Architecture overview
- 🌀 Airflow Strategy
- 🧪 MLflow Strategy
- 🐋 Docker Strategy
- 🔁 CI/CD Strategy — GitHub Actions
- 🛡️ Model Governance
- 📡 Monitoring & Alerting
- ↩️ Rollback & Recovery (< 5-minute RTO)

**Design system:** Light Claymorphism (`#e2e8f0` base, puffy card shadows) + full **Dark Mode** toggle · Inter + Fira Code fonts · Mermaid.js diagrams

---

### 4. `mlops_concept.html` — Universal Framework Concept
A **Modern Config-Driven Architecture** documentation page defining a generalized pipeline strategy for any machine learning paradigm.

**Sections covered:**
- ⚙️ Universal Config-Driven Design
- 💾 Data Versioning (DVC) & Feature Store workflows
- ⚖️ Automated Drift Detection & Retraining
- 🧪 MLflow Tracking & Registry
- 🌀 Airflow Orchestration & HITL Gates

**Design system:** Dynamic Dual Theme (Light 🌅 / Dark 🌙 toggle) · Interactive code syntax highlighting · Glossary text tooltips · Inter + JetBrains Mono fonts

---

### 5. `mlflow_with_airflow.html` — Integration Setup Guide
A **Clean Modern**-styled guide documenting the complete setup process required to integrate MLflow with a Dockerized Apache Airflow environment.

**Sections covered:**
- ⚙️ Environment Configuration (`.env`)
- 🐋 Docker Compose Configuration
- 📝 Version Control (`.gitignore`)
- 🚀 How to Run the Stack & Verify

**Design system:** Dynamic Dual Theme (Light 🌅 / Dark 🌙 toggle) · Code syntax highlighting with Copy Buttons · Inter + JetBrains Mono fonts

---

## 🛠️ MLOps Stack

| Tool | Role |
|---|---|
| **Apache Airflow 3.x** | Workflow orchestration — DAG-based scheduling & retries |
| **MLflow** | Experiment tracking, model versioning, promotion gates |
| **PostgreSQL 16** | Core data storage for Bronze/Silver/Gold tiers |
| **Scikit-Learn** | ML-driven Anomaly Detection (Isolation Forest) |
| **Pydantic v2** | Strict data validation & schema governance |
| **Docker / Compose** | Reproducible environments across dev → staging → prod |

---

## 🎨 Design Highlights

| | Technical Reference | Strategy Deck | Universal Concept | Sensor ETL Pipeline |
|---|---|---|---|---|
| **Style** | Neumorphism (Dark) | Claymorphism (Themeable) | Clean Modern (Themeable) | **Glassmorphism (Dark)** |
| **Font** | Inter + JetBrains Mono | Inter + Fira Code | Inter + JetBrains Mono | Inter + JetBrains Mono |
| **Nav** | Fixed sidebar | Sidebar switcher | Scroll-spy | **Fixed sidebar** |
| **Special** | HTML pipeline steps | Mermaid.js flowcharts | Glossary tooltips | **Medallion flow diagram** |
| **Responsive** | ✅ | ✅ | ✅ | ✅ |

---

## 🚀 Run Locally

No build tools needed — just open the files directly:

```bash
# Clone the repo
git clone https://github.com/vanshccmodi/DOCS.git
cd DOCS

# Open in browser (Windows)
start etl_airflow_dag.html
start mlops_documentation.html
start pump_optimization.html
start mlops_concept.html
start mlflow_with_airflow.html

# Open in browser (macOS/Linux)
open etl_airflow_dag.html
open mlops_documentation.html
open pump_optimization.html
open mlops_concept.html
open mlflow_with_airflow.html
```

---

## 📁 Repository Structure

```
DOCS/
├── etl_airflow_dag.html       # Enterprise Sensor ETL Pipeline (Glassmorphism)
├── mlflow_with_airflow.html   # Airflow & MLflow Integration Setup Guide
├── mlops_concept.html         # Universal config-driven architecture doc
├── mlops_documentation.html   # Technical reference (Neumorphism)
├── pump_optimization.html     # Strategy deck (Claymorphism)
└── README.md
```

---

## 👤 Author

**Vansh Modi** · MLOps Engineer  
[GitHub Profile](https://github.com/vanshccmodi)