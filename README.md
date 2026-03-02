# ⚙️ MLOps Framework — Documentation & Strategy

> A pair of beautifully designed, self-contained HTML documents covering the full MLOps lifecycle for an **Ad Sales Forecasting / Smart Pump Monitoring** system.  
> No build step, no dependencies — open in any browser and you're done.

---

## 🔗 Live Pages

| Page | URL |
|---|---|
| 📘 Technical Documentation | [mlops_documentation.html](https://vanshccmodi.github.io/DOCS/mlops_documentation.html) |
| 🎯 Strategy Presentation | [mlops_presentation.html](https://vanshccmodi.github.io/DOCS/mlops_presentation.html) |

---

## 📄 Pages at a Glance

### 1. `mlops_documentation.html` — Technical Reference
A **Neumorphism**-styled, scrollable documentation page covering the entire MLOps framework in depth.

**Sections covered:**
- 📐 Framework Overview & Architecture
- 📊 Evaluation Metrics — MAPE, WAPE, RMSE
- 🌿 SHAP-based Explainability
- 🧪 MLflow — Experiment Tracking & Model Registry
- 🌀 Airflow — Pipeline Orchestration & DAG Design
- 🐋 Docker — Containerisation Strategy
- 🔁 CI/CD — GitHub Actions Pipelines
- 🛡️ Model Governance & Rollback Procedures
- 📡 Production Monitoring & Drift Detection

**Design system:** Dark Neumorphism (`#1e2030` base, inset/outset shadows, `--accent: #7c6af7`) · Inter + JetBrains Mono fonts · Active-scroll sidebar nav

---

### 2. `mlops_presentation.html` — Strategy Deck
A **Claymorphism**-styled interactive presentation built for stakeholder and mentor walkthroughs.

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

## 🛠️ MLOps Stack

| Tool | Role |
|---|---|
| **Apache Airflow** | Workflow orchestration — DAG-based scheduling & retries |
| **MLflow** | Experiment tracking, model versioning, promotion gates |
| **Docker / Compose** | Reproducible environments across dev → staging → prod |
| **GitHub Actions** | CI/CD — automated testing before every deployment |

---

## 🎨 Design Highlights

| | Documentation | Presentation |
|---|---|---|
| **Style** | Neumorphism (Dark) | Claymorphism (Light + Dark toggle) |
| **Font** | Inter + JetBrains Mono | Inter + Fira Code |
| **Navigation** | Fixed sidebar with scroll-spy | Sidebar with section switching |
| **Diagrams** | ASCII / HTML pipeline steps | Mermaid.js flowcharts |
| **Responsive** | ✅ | ✅ |

---

## 🚀 Run Locally

No build tools needed — just open the files directly:

```bash
# Clone the repo
git clone https://github.com/vanshccmodi/DOCS.git
cd DOCS

# Open in browser (Windows)
start mlops_documentation.html
start mlops_presentation.html

# Open in browser (macOS/Linux)
open mlops_documentation.html
open mlops_presentation.html
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
├── mlops_documentation.html   # Technical reference (Neumorphism)
├── mlops_presentation.html    # Strategy deck (Claymorphism + dark mode)
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