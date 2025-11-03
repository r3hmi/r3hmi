<h1>Hi, I'm Imran Rehmi! 🤖 <br/>
<a href="https://github.com/r3hmi">Data Science Manager</a> • 
<a href="https://www.linkedin.com/in/imranrehmi">AI Solution Arch</a> • 
<a href="https://www.linkedin.com/in/imranrehmi">MLOps/LLMOps</a>  

---
## 🧠 AI Engineering Projects

### 🔹 [Modular RAG: Feedback-Informed Evaluation & Continual Learning](https://github.com/r3hmi/Mod-rag-app)
**Stack:** Python · FastAPI · Streamlit · Hugging Face Transformers · FAISS · Prefect · DVC · MLflow · Evidently AI · Prometheus/Grafana · Guardrails AI
Implements a modular Retrieval-Augmented Generation (RAG) system with continuous feedback loops and retraining. A Prefect-orchestrated pipeline manages embedding refresh, evaluation (nDCG, faithfulness, G-Eval), and prompt AB testing. FastAPI microservices expose retrieval, generation, and feedback APIs with health probes and autoscaling. Evidently AI monitors retrieval precision and hallucination drift, while Guardrails AI enforces safety and PII redaction. All artifacts and datasets are versioned with DVC + MLflow for full reproducibility. CI/CD (GitHub Actions → Helm) performs lint + tests + signed-image deployment. Model and data cards document fairness, bias, and hallucination mitigation policies.


### 🔹 [Deployable Claude Agents: Bedrock AgentCore](https://github.com/r3hmi/claude-bedrock-agentcore)
**Stack:** Amazon Bedrock · Claude · AgentCore SDK · AWS CDK · FastAPI Gateway · Prometheus/Loki/Grafana · IAM Policies · Terraform 

Delivers production-ready Bedrock agents with dynamic tool orchestration and strict governance. Agent scorecards track task success, latency, and cost across prompt versions. IaC (CDK + Terraform) provisions reproducible environments; CI/CD runs static analysis, secret scanning, and signed container pushes. Tool schemas are validated with Pydantic contracts; sandbox proxies log all tool I/O for traceability. Observability includes structured traces (OpenTelemetry), metrics, and alerting pipelines to Slack. Security is enterprise-grade: least-privilege IAM roles, KMS-encrypted logs, VPC-only endpoints, and automated credential rotation. Runbooks define rollback, abuse-handling, and SLA recovery procedures.



### 🔹 [BERT vs. DistilBERT for QA – A/B Testing Performance Evaluation](https://github.com/r3hmi/bert-distilbert-ab-testing)
**Stack:** Python · Hugging Face Transformers · FastAPI · Streamlit · MLflow · DVC · Prefect · Prometheus/Grafana · Locust · Evidently AI

Compares BERT and DistilBERT in a production-style A/B evaluation for question-answering tasks, measuring trade-offs between accuracy, latency, throughput, and cost. Both models are deployed via FastAPI microservices and benchmarked using Locust under concurrent load, with metrics tracked in MLflow and datasets versioned in DVC. A Prefect pipeline automates data preparation, evaluation, and metric logging, while Prometheus/Grafana dashboards visualize latency–accuracy trade-offs and cost per 1 000 queries. Evidently AI monitors performance drift and calibration stability over time, and a Streamlit interface presents real-time A/B results and scenario comparisons for deployment optimization across edge and cloud environments.

---

## 🛠️ MLOps Projects

### 🔹 [Industrial IoT Predictive Maintenance (End-to-End MLOps)](https://github.com/r3hmi/graph-mlops-neo4j-eta)

**Stack:** PySpark · MLflow (Tracking & Registry) · FastAPI · Docker · Kubernetes (Helm) · Prometheus/Grafana · Evidently AI · Neo4j (Lineage) · DVC · Prefect · GitHub Actions

Predicts equipment failures before downtime through a containerised, monitored, and lineage-tracked pipeline. Prefect orchestrates feature extraction (Spark), model retraining, and deployment to K8s via Helm. MLflow handles experiment tracking and model registry with automated version promotion on passing QA tests. FastAPI services expose REST/gRPC inference endpoints with autoscaling and health probes. Evidently AI + Prometheus provide real-time drift, accuracy, and latency dashboards; alerts trigger retraining when thresholds breach. Neo4j lineage graphs record dataset, model, and metric provenance for audit and compliance. Security, SBOM scanning, and signed releases are enforced in CI/CD. Runbooks cover incident response, rollback, and DR (RPO < 15 min).


### 🔹 [RecomPulse: E-Commerce Personalization Engine (End-to-End MLOps)](https://github.com/r3hmi/graph-mlops-neo4j-eta)

**Stack:** Kafka/Kinesis · PySpark · Feature Store (Feast/Redis) · Neo4j · MLflow (Tracking & Registry) · FastAPI · Docker · Kubernetes (Helm) · Prometheus/Grafana · Evidently AI · DVC · Prefect

Streams clicks, carts, and purchases into a lakehouse to train a hybrid recommender (ALS + content + graph features). Orchestrated with Prefect, the system manages nightly retraining, canary rollouts, and lineage updates. A FastAPI microservice serves real-time recommendations through ANN retrieval → model re-rank pipelines with autoscaling. Feast enforces feature contracts and freshness SLAs; Prometheus/Grafana track CTR, conversion, drift, and cohort fairness. CI/CD pipelines handle linting, testing, container signing, and environment promotion. Shadow-mode evaluation compares new models online before rollout. Data and model cards document fairness, privacy, and cold-start policies.


### 🔹 [DelaySense: Responsible AI for Delivery Risk (Explainable Tabular ML)](https://github.com/r3hmi/graph-mlops-neo4j-eta)

**Stack:** XGBoost · Random Forest · SHAP/LIME · Probability Calibration · FastAPI + Streamlit · MLflow (Tracking) · DVC · Evidently AI · Prefect

Predicts shipment delays with explainable, calibrated models and human-in-the-loop oversight. The core model exposes a FastAPI inference API with schema validation and a Streamlit UI for what-if analysis. Prefect orchestrates retraining and calibration checks; Evidently AI monitors feature and calibration drift. Threshold-tuning microservices optimise risk–cost trade-offs per client segment. Model cards and policy documents outline interpretability boundaries, fairness audits, and reviewer override logging. CI/CD ensures reproducibility, test coverage, and signed container deployment to K8s. Documentation includes playbooks for incident handling and ethical escalation.


### 🔹 [Graph‑MLOps on SageMaker: ETA Prediction with Neo4j & LLMs](https://github.com/r3hmi/graph-mlops-neo4j-eta)

**Stack:** AWS SageMaker (Pipelines) · Neo4j · Graph ML · LLM Embeddings · Step Functions · FastAPI · CloudWatch/Grafana · DVC · MLflow Registry · KMS Encryption 

Combines SageMaker Pipelines and Neo4j to forecast last-mile delivery ETAs using graph ML enriched with LLM-derived contextual embeddings. Step Functions orchestrate data ingestion, feature graph refresh, and retraining. Models are versioned in MLflow Registry; deployment to managed SageMaker Endpoints includes canary testing and rollback. CloudWatch + Grafana dashboards monitor segment-level latency, drift, and cost. Security includes VPC-isolated endpoints, encrypted S3/KMS storage, and IAM-scoped roles. Geo-drift detection and fairness metrics (region × time-of-day) ensure reliable performance. Full IaC (Terraform) enables reproducible provisioning, while DR/rollback runbooks achieve 99.9% availability SLAs.

---

## 📊 Analytical Projects

### 🔹 [TSP Optimizer as a Service – Streamlit Dashboard for Dynamic Routing](https://github.com/r3hmi/tsp-optimizer-streamlit)

**Stack:** Python · Metaheuristics · Streamlit · Dynamic Routing  

Solves the Traveling Salesperson Problem using metaheuristic algorithms and delivers real-time routing optimization via an interactive Streamlit dashboard.

---

## 📖 Publications, Frameworks & Educational Content

### 🔹 [The Pragmatic Unicorn (Book)](https://github.com/r3hmi/pragmatic-unicorn-book)
**Format:** Book · Educational   
A practical guide for building production-grade analytics and AI solutions with agility, ethics, and scalability at the core.



## 🤝 Connect with Me

<p align="left">
  <a href="https://www.tiktok.com/@r3hmi" target="_blank">
    <img alt="Imran | TikTok" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/tiktok.svg" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/imranrehmi" target="_blank">
    <img alt="Imran | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
  </a>
</p>

