# 👋 Hi, I’m Brice Nelson

## 💼 Applied Machine Learning & Backend Engineer | Systems-Focused Problem Solver

🧠 *Licensed Civil Engineer building applied ML and backend systems for infrastructure.*
I specialize in turning messy real-world data into **reliable systems** and **defensible decisions**—from infrastructure analytics to risk modeling.

I build **ML as production software**, not isolated notebooks. ☕

---

## 🚀 Focus Areas

* 🧠 **Applied Machine Learning** – Risk modeling, time series analysis, forecasting, and real-world evaluation under uncertainty  
* ⚙️ **Backend & Systems Engineering** – API-first architectures, authentication, and production-ready services  
* 🧱 **Data Engineering** – ETL pipelines, schema design, and reproducible workflows  
* 🏗️ **Infrastructure Analytics** – Asset risk modeling, cost intelligence, and decision-support systems  

---

## 🧰 Core Tech Stack

| Category                 | Tools                                                                   |
| ------------------------ |-------------------------------------------------------------------------|
| **Languages**            | Python, SQL                                                             |
| **Backend Frameworks**   | FastAPI, Flask, SQLAlchemy                                              |
| **Data & ML**            | Pandas, NumPy, Scikit-Learn                                             |
| **Databases**            | PostgreSQL, MySQL, SQLite, DuckDB                                       |
| **Infra & DevOps**       | AWS (in progress), Docker (in progress), GitHub Actions, Heroku, Vercel |
| **Workflow & Packaging** | Git, Conda, uv                                                          |
| **Docs & Analysis**      | JupyterLab, Quarto, PyCharm, DataSpell, VSCode                          |

---

## 🧩 Featured Projects

### 🛠️ Toronto Pipeline Failure Prediction — Applied ML & Infrastructure Risk System

[https://github.com/Brice-Machine-Learning/Toronto-Pipeline-Failure-Predict](https://github.com/Brice-Machine-Learning/Toronto-Pipeline-Failure-Predict)

A real-world **applied machine learning project** focused on predicting **water main failure risk** using public infrastructure, environmental, and asset data from the City of Toronto. The project is intentionally designed as the foundation for a **deployable, decision-support system**, not a standalone model.

This work prioritizes **data realism**, **engineering constraints**, and **defensible modeling decisions**, reflecting the realities faced by municipal utilities where data is incomplete, heterogeneous, and operationally constrained.

**Status:** 🟢 Active development
**Core Stack:** Python, Pandas, Scikit-Learn, Geo-enabled datasets, Quarto

_**Applied ML Focus**

* Asset-level feature engineering (installation year, material, diameter, environmental exposure)
* Spatial and temporal aggregation of infrastructure and failure data
* Failure labeling under incomplete and inconsistent municipal records
* Model evaluation aligned with risk prioritization, not academic metrics
* Explicit handling of uncertainty and data limitations

_**Systems & Backend Direction (In Progress / Planned)**

* Backend service to operationalize risk scoring and model inference
* Secure authentication and role-based access for internal and stakeholder users
* API endpoints for asset-level risk queries and scenario analysis
* Dashboard integration for infrastructure risk visualization (Power BI or equivalent BI tooling)
* Deployment-focused design emphasizing reproducibility, auditability, and model versioning

_**Engineering Philosophy**

* ML treated as a system component, not a notebook artifact
* Clear separation between data processing, modeling logic, and serving layers
* Design decisions driven by how results will be consumed by engineers, planners, and decision-makers

**Goal:** Deliver an applied ML–driven infrastructure risk system that bridges modeling, backend services, and operational dashboards—demonstrating end-to-end thinking from raw municipal data to deployable decision support.

---

### 🏗️ Cost Query Pro — Infrastructure Cost Intelligence & Analytics Platform

[https://github.com/Brice-Engineering-Projects/Cost-Query-Pro](https://github.com/Brice-Engineering-Projects/Cost-Query-Pro)

A **FastAPI-powered backend platform** for querying, aggregating, and analyzing civil bid-item pricing across large datasets, with a clear roadmap toward **applied machine learning–driven cost analytics**. Built for engineers, analysts, and decision-makers who need structured, defensible insights from infrastructure cost data.

**Status:** ⚙️ MVP development Phase
**Core Stack:** FastAPI, PostgreSQL, SQLAlchemy, JWT Authentication, AWS RDS

_**Current Capabilities (Backend-First)**

* Hierarchical domain models (Projects → Items → Costs)
* High-performance REST APIs for cost queries and filtering
* Secure authentication and role-aware data access
* Schema design optimized for analytical workloads

_**Applied ML Roadmap**

* Cost trend modeling and normalization across projects and regions
* Anomaly detection for outlier bid items and pricing inconsistencies
* Feature engineering on historical bid data (time, location, scope)
* Predictive cost ranges to support early-stage planning

_**Engineering Focus**

* Clean service boundaries and API design
* Data integrity and query performance at scale
* ML-ready data pipelines built on a stable backend foundation

**Goal:** Deliver a production-ready backend system that evolves into an applied ML–enabled cost analytics platform for infrastructure decision support.

---

### 🧠 MinutesIQ — Intelligent Document Processing & Infrastructure Signal Extraction Platform  

[https://github.com/Brice-Engineering-Projects/Minutes-IQ](https://github.com/Brice-Engineering-Projects/Minutes-IQ)

A **backend-driven intelligence platform** that ingests public meeting records and extracts structured insights using configurable keyword pipelines and automated document processing. Designed to surface **early infrastructure signals** from unstructured data, enabling proactive decision-making for engineers, analysts, and planners.

**Status:** ⚙️ Completed MVP with ongoing enhancements  
**Core Stack:** FastAPI, Turso (libSQL), HTMX, Jinja2, Background Tasks, JWT Authentication  

---

_**Current Capabilities (Backend-First)**

* End-to-end document ingestion and processing pipeline (PDF/HTML → structured outputs)  
* Configurable keyword intelligence system with client-specific filtering  
* Selective PDF page extraction with keyword-level highlighting, enabling rapid validation of extracted signals within original source context  
* Background job orchestration with progress tracking and state management  
* Secure authentication with role-based access and session handling  
* Exportable outputs (CSV) for downstream analysis  

---

_**Applied Intelligence Roadmap**  

* Named entity recognition (projects, locations, funding references)  
* Context-aware classification of infrastructure initiatives  
* Trend detection across meeting records and time-series signals  
* Integration with external data sources for enriched analysis  
* Transition from keyword-based filtering to ML-driven signal extraction  

---

_**Engineering Focus**  

* Scalable background processing and job orchestration  
* Clean service-layer architecture and modular pipeline design  
* Efficient storage and retrieval of semi-structured document data  
* Secure, production-oriented backend with real-world user workflows  

---

**Goal:** Build a production-grade intelligence platform that transforms unstructured public records into actionable infrastructure insights, bridging document processing with applied ML and backend systems.

---

### ⚙️ Lift Station Predictive Maintenance — Applied ML for Infrastructure Reliability  

[https://github.com/Brice-Machine-Learning/lift-station-predictive-maintenance
](https://github.com/Brice-Machine-Learning/lift-station-predictive-maintenance)  

An **applied machine learning platform** for predictive maintenance of wastewater lift stations, leveraging SCADA data, pump performance metrics, and system behavior to identify early indicators of failure. Designed to help utilities transition from reactive maintenance to **data-driven, risk-based asset management**.

**Status:** 🧪 Design Phase (Architecture & Data Strategy Defined)    
**Core Stack:** Python, pandas, scikit-learn, FastAPI (planned), PostgreSQL (planned), Time-Series Processing, ML Pipelines  

---

_**Current State**_

* System architecture and ML pipeline design defined  
* Data strategy outlined for SCADA and operational signals  
* Repository scaffolded with CI/CD, typing, and development standards  
* Implementation of data ingestion and modeling pipelines planned next  

---

_**Planned Capabilities (ML-First System)**

* SCADA data ingestion and preprocessing pipelines for time-series operational data  
* Pump runtime analysis and degradation pattern tracking  
* Wet-well level modeling and anomaly detection  
* Failure pattern identification using historical operational signals  
* ML-based risk scoring for proactive maintenance prioritization  
* Dashboard-ready outputs for operational decision support  

---

_**Applied ML Focus**  

* Time-series feature engineering (lags, rolling stats, usage patterns)  
* Supervised learning for failure prediction and risk classification  
* Anomaly detection for early warning signals  
* Model evaluation under real-world class imbalance (rare failure events)  
* Integration of domain-specific features (pump cycles, inflow variability, system load)  

---

_**Engineering Focus**  

* End-to-end ML pipeline design (ingestion → feature engineering → modeling → outputs)  
* Reproducible experimentation and model versioning  
* CI/CD with testing, linting, typing, and security checks  
* ML-ready backend architecture for future API integration  
* Strong documentation and modular project structure for scalability  

---

**Goal:** Build a production-ready predictive maintenance system that enables utilities to anticipate lift station failures, reduce downtime, and optimize maintenance strategies using applied ML and robust backend engineering.

---

## 🧠 Research & Applied Exploration

Smaller, focused projects exploring modeling techniques, data workflows, and system design patterns.

---

**Default Detect — Credit Risk Modeling & Explainability**  
Applied ML project exploring credit risk prediction with SHAP-based interpretability and API deployment concepts.

**NASA SpaceApps — Climate Data Modeling**  
Exploratory project applying data analysis and modeling techniques to real-world environmental datasets.

**Pencils & Python — Mathematical Foundations in Code**  
Translating mathematical concepts into structured, production-style Python implementations.

---

## 🧭 GitHub Ecosystem

| Organization                        | Focus                                              | Link                                                                                           |
|-------------------------------------|----------------------------------------------------|------------------------------------------------------------------------------------------------|
| **Brice Machine Learning Projects** | Applied ML, risk modeling, predictive analytics    | [https://github.com/Brice-Machine-Learning](https://github.com/Brice-Machine-Learning)         |
| **Brice Backend Projects**          | Backend services, APIs, authentication, ML systems | [https://github.com/Brice-Backend-Projects](https://github.com/Brice-Backend-Projects)         |
| **Brice Engineering Projects**      | Infrastructure analytics, cost intelligence        | [https://github.com/Brice-Engineering-Projects](https://github.com/Brice-Engineering-Projects) |

---

## 🎯 Career Focus

Focused on applying software engineering, data analysis, and applied machine learning techniques to support infrastructure, risk analysis, and decision-support workflows, with emphasis on:

* Production ML and model deployment
* Data-intensive backend systems
* Risk, infrastructure, and decision-support analytics
* Treating ML as a first-class software concern

---

## 🎨 Fun & Creative Projects

Because engineering isn’t just about APIs and abstractions — sometimes it’s about curiosity, physics, and asking better questions.

### 🌌 The Fermi Paradox Simulation — Where Python Meets the Cosmos

[https://github.com/Brice-Physics-Projects/Fermi-Paradox](https://github.com/Brice-Physics-Projects/Fermi-Paradox)

A probabilistic exploration of the Fermi Paradox using simulation-driven modeling inspired by the Drake Equation.

* Probabilistic universe modeling
* Parameterized assumptions and sensitivity analysis
* A blend of physics intuition and clean Python design

---

### ✨ MadLibs Magic — Next.js, Edge Databases & Premium UX

[https://github.com/bnelsonemail/MadLibs-Next](https://github.com/bnelsonemail/MadLibs-Next)

A playful but surprisingly robust Mad Libs generator built with modern web tooling and backend-first design thinking.

* Dynamic routing and story builder logic
* Turso (edge SQLite) for analytics and polling
* Premium upgrade paths and future AI-enhanced features

Sometimes the best way to test architectural ideas is to ship something fun 😄

---

### 🧠 Fun Fact

I’ve designed **water systems beneath streets** and **risk models beneath spreadsheets**.
Both rely on flow, pressure, and well-defined boundary conditions.

---

## 🤝 Let’s Connect

📬 [brice@devbybrice.com](mailto:brice@devbybrice.com)  |  🌐 [https://www.devbybrice.com](https://www.devbybrice.com)  |  🔗 [LinkedIn](https://www.linkedin.com/in/brice-a-nelson-p-e-mba-36b28b15/)  

![Profile Views](https://komarev.com/ghpvc/?username=bnelsonemail)

---

*Thank you for visiting my GitHub! I’m passionate about building systems where machine learning meets real-world impact. Feel free to explore my projects and reach out if you’d like to collaborate or connect!*
