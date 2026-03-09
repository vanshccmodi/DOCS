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

---

## 📄 Pages at a Glance

### 1. `mlops_documentation.html` — Technical Reference
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

### 2. `pump_optimization.html` — Strategy Deck
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
- 📋 Ownership Matrix

**Design system:** Light Claymorphism (`#e2e8f0` base, puffy card shadows) + full **Dark Mode** toggle · Inter + Fira Code fonts · Mermaid.js diagrams

---

### 3. `mlops_concept.html` — Universal Framework Concept
A **Modern Config-Driven Architecture** documentation page defining a generalized pipeline strategy for any machine learning paradigm.

**Sections covered:**
- ⚙️ Universal Config-Driven Design
- 💾 Data Versioning (DVC) & Feature Store workflows
- ⚖️ Automated Drift Detection & Retraining
- 🌿 Model Explainability (SHAP)
- 🧪 MLflow Tracking & Registry
- 🌀 Airflow Orchestration & HITL Gates

**Design system:** Dynamic Dual Theme (Light 🌅 / Dark 🌙 toggle) · Interactive code syntax highlighting · Glossary text tooltips · Inter + JetBrains Mono fonts

---

## 🛠️ MLOps Stack

| Tool | Role |
|---|---|
| **Apache Airflow** | Workflow orchestration — DAG-based scheduling & retries |
| **MLflow** | Experiment tracking, model versioning, promotion gates |
| **Docker / Compose** | Reproducible environments across dev → staging → prod |
| **GitHub Actions** | CI/CD — automated testing before every deployment |

---

## 🎨 Design Highlights

| | Documentation | Pump Optimization | Universal Concept |
|---|---|---|---|
| **Style** | Neumorphism (Dark) | Claymorphism (Light + Dark toggle) | Clean Modern (Light + Dark toggle) |
| **Font** | Inter + JetBrains Mono | Inter + Fira Code | Inter + JetBrains Mono |
| **Navigation** | Fixed sidebar with scroll-spy | Sidebar with section switching | Fixed sidebar with scroll-spy |
| **Special** | HTML pipeline steps + tables | Mermaid.js flowcharts | Code syntax highlighting + Glossary tooltips |
| **Responsive** | ✅ | ✅ | ✅ |

---

## 🚀 Run Locally

No build tools needed — just open the files directly:

```bash
# Clone the repo
git clone https://github.com/vanshccmodi/DOCS.git
cd DOCS

# Open in browser (Windows)
start mlops_documentation.html
start pump_optimization.html
start mlops_concept.html

# Open in browser (macOS/Linux)
open mlops_documentation.html
open pump_optimization.html
open mlops_concept.html
```

Or serve with any static file server:

```bash
npx serve .
# → http://localhost:3000
```

---

## 📁 Repository Structure

```
DOCS/
├── mlops_concept.html         # Universal config-driven architecture doc
├── mlops_documentation.html   # Technical reference (Neumorphism)
├── pump_optimization.html     # Strategy deck (Claymorphism + dark mode)
└── README.md
```

---

## 📌 Key Decisions

- **No DVC** — MLflow handles data + model versioning at this scale.
- **No Kubeflow** — Docker Compose is sufficient; Kubernetes is overkill here.
- **No cloud MLaaS** — On-premises Linux server; self-hosted MLflow.
- **No Weights & Biases** — Covered fully by self-hosted MLflow.

---

## 👤 Author

**Vansh Modi** · MLOps Engineer  
[GitHub Profile](https://github.com/vanshccmodi)