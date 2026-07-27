<h3>Hi, I'm Rehmi! 🤖 <br/>
<a href="https://www.linkedin.com/in/imranrehmi">Data Science Manager - </a>  
<a href="https://www.linkedin.com/in/imranrehmi">AI Solution Lead</a>  


### Applied AI, Decision Science & MLOps Portfolio
> **`STATUS: OPERATIONAL`**  
> **`FOCUS: Transitioning research models to high-throughput production architectures.`**

Welcome! This repository serves as the primary system registry for my work across applied AI research, decision intelligence, computer vision, LLM infrastructure, data-centric engineering, and technical education.

---

## 🧭 System Index
* [`01_FLAGSHIP_PROJECTS`](#-flagship-applied-ai-projects)
* [`02_ENGINEERING_GUIDES`](#-technical-tutorials--engineering-guides)
* [`03_LECTURE_SERIES`](#-leadership--lecture-series)
* [`04_CAPABILITY_MATRIX`](#-system-capabilities--matrix)

---

## 🚀 Flagship Applied AI Projects

### 📊 1. Causal Decision Intelligence & Spatial-Temporal Marketplace Simulator
`STACK:` `Python` | `SimPy` | `EconML` | `CausalML` | `OR-Tools` | `GeoPandas` | `PyTorch` | `Streamlit`

A discrete-event simulation and decision-intelligence platform for evaluating operational interventions across two-sided delivery networks. Rather than merely predicting demand, the system estimates heterogeneous treatment effects and optimizes dynamic operational interventions under constraints.

* `[CAUSAL-INFERENCE]` Estimates incremental impacts of rider incentives, shift policies, and dynamic pricing using heterogeneous treatment-effect models.
* `[SIMULATION-ENGINE]` Models spatial-temporal rider supply, order demand, service times, and congestion via discrete-event simulation.
* `[OR-OPTIMIZATION]` Applies mixed-integer programming (`OR-Tools`) to rebalance geographic zones and allocate riders under operational constraints.
* `[EXPERIMENTATION]` Evaluates policies while accounting for network interference, spillover effects, and `SUTVA` violations.
* `[KPI-IMPACT]` Connects operational levers directly to fulfillment rate, rider utilization, delivery time, and contribution margin.

---

### 👁️ 2. Edge-Optimized Industrial Vision System with Neural Attribution & Quantized Inference
`STACK:` `Python` | `PyTorch` | `FastSAM` | `U-Net` | `ONNX Runtime` | `TensorRT` | `OpenCV` | `Grad-CAM` | `Docker`

A production-oriented computer vision architecture for detecting, segmenting, and explaining industrial defects in resource-constrained edge environments.

* `[VISION-PIPELINE]` End-to-end detection and semantic segmentation for surface defects, component damage, and production anomalies.
* `[EDGE-COMPILATION]` Compiles `PyTorch` models to `ONNX` and `TensorRT` for execution on resource-constrained hardware.
* `[BENCHMARKING]` Real-time execution target (`<15ms` latency) across `FP32`, `FP16`, and `INT8` quantization modes.
* `[EXPLAINABILITY]` Integrates `Grad-CAM` visual attribution overlays alongside tracking for data drift, confidence shift, and latency degradation.
* `[PACKAGING]` Containerized microservice in `Docker` with reproducible preprocessing and prediction interfaces.

---

### 🔐 3. Private Multi-Tenant Enterprise LLM Serving & GPU Orchestration Infrastructure
`STACK:` `vLLM` | `Llama` | `Mistral` | `Kubernetes` | `Helm` | `Karpenter` | `Triton` | `Istio` | `WireGuard` | `Prometheus` | `Grafana`

An on-premises and private-cloud orchestration platform for serving open-weight large language models within zero-trust enterprise boundaries.

* `[HIGH-THROUGHPUT]` Leverages `vLLM` and `NVIDIA Triton` for continuous batching, `KV-cache` optimization, and OpenAI-compatible endpoints.
* `[GPU-ORCHESTRATION]` Automated node provisioning, scale-to-zero, and GPU-aware scheduling via `Kubernetes` and `Karpenter`.
* `[ZERO-TRUST]` Enforces service-mesh routing (`Istio`), mutual TLS (`mTLS`), role-based access control (`RBAC`), and isolated namespaces.
* `[OBSERVABILITY]` Monitors Time-To-First-Token (`TTFT`), inter-token latency, queue depth, GPU memory utilization, and failure recovery.
* `[COST-ENGINEERING]` Tracks real-time cost-per-request and cost-per-token metrics against capacity limits.

---

### 🔬 4. Action-Conditioned Joint-Embedding Predictive Architecture (JEPA) for Visual Planning
`STACK:` `Python` | `PyTorch` | `Vision Transformers` | `Self-Supervised Learning` | `Gymnasium` | `MuJoCo` | `MPC` | `Hydra` | `W&B`

A research implementation of an action-conditioned Joint-Embedding Predictive Architecture (`JEPA`) for learning visual world dynamics without pixel reconstruction.

* `[LATENT-DYNAMICS]` Predicts trajectory transformations in representation space rather than generating full future frames.
* `[SSL-OBJECTIVES]` Employs energy-based collapse-prevention mechanisms to train encoder and predictor networks.
* `[CONTROL-SYSTEMS]` Integrates Model Predictive Control (`MPC`) to plan action sequences targeting image-defined goals.
* `[EVALUATION]` Evaluates representation collapse, prediction consistency over multi-step rollouts, and action sensitivity.

---

### 🧬 5. Programmatic Weak Supervision, Label Consensus & Parameter-Efficient Model Distillation
`STACK:` `Python` | `Snorkel` | `Hugging Face` | `PyTorch` | `QLoRA` | `PEFT` | `Llama 3` | `MLflow` | `FastAPI`

A data-centric AI pipeline combining weak supervision and parameter-efficient fine-tuning (`PEFT`) to build quality training sets and low-cost student models.

* `[WEAK-SUPERVISION]` Combines heuristic rules, domain functions, and LLM-generated rationale labels via `Snorkel` consensus modeling.
* `[DISTILLATION]` Fine-tunes smaller open-weight models using `QLoRA` to replicate teacher capabilities at reduced inference cost.
* `[GOVERNANCE]` Audits dataset lineage, tracks prompt versioning, and filters uncertain/contradictory labels for human review.

---

## 🎓 Leadership & Lecture Series

Practitioner-focused educational programs bridging technical implementation with strategic AI leadership and modern workflows.

### 💼 `SERIES_01:` Leading AI from Strategy to Scale: Applying PMI-CPMAI
* `[MODULES]` Operational opportunity framing, CPMAI project lifecycles, data readiness assessments, risk mitigation, human oversight, and enterprise value tracking.
* `[AUDIENCE]` AI Leaders, Program Managers, Product Leads, and Transformation Teams.
* `[OBJECTIVE]` Practical bridge between strategic decision-making, governance, and technical execution.

### 💻 `SERIES_02:` AI-Native Analytics with Codex: The Science and Art of Data
* `[MODULES]` AI-augmented analytical workflows, pair-programming for exploratory data analysis, automated feature engineering, hallucination management, and code verification.
* `[AUDIENCE]` Data Scientists, Analytics Engineers, Business Intelligence Practitioners, and Technical Directors.
* `[OBJECTIVE]` Framework for modern data analytics where human judgment directs strategy while AI agents accelerate execution.

---

## 🛠️ Technical Tutorials & Engineering Guides

First-principles implementations, mathematical derivations, and operational benchmarks for core machine learning paradigms.

+------------------------------------+----------------------------+-------------------------------------------------------------+
| MODULE TITLE                       | CORE STACK                 | TECHNICAL CONCEPTS                                          |
+------------------------------------+----------------------------+-------------------------------------------------------------+
| 📐 Transformers from First Prin.  | PyTorch, CUDA, NumPy       | Multi-Head Attention, Positional Encodings, CUDA Profiling  |
| ⚡ Optimization-Based Meta-Learn  | PyTorch, higher            | Bi-Level Optimization, MAML, Rapid Few-Shot Adaptation      |
| ⚙️ Explainable AI & Model Audit    | XGBoost, SHAP, Evidently   | TreeSHAP, Cohort Interactions, Demographic Governance       |
| 🖥️ Diffusion Models from Scratch   | PyTorch, U-Net, CUDA       | Markov Processes, Cosine Schedules, Noise Prediction        |
| 📡 Custom Triton GPU Kernels       | OpenAI Triton, CUDA        | Kernel Fusion, FlashAttention Patterns, SRAM/HBM Bandwidth  |
+------------------------------------+----------------------------+-------------------------------------------------------------+

---

## 🧩 System Capabilities & Matrix

| SYSTEM DOMAIN | PRIMARY IMPLEMENTATION / REFERENCE MODULE |
| :--- | :--- |
| **`Causal Inference & Optimization`** 📊 | Causal Decision Intelligence & Marketplace Simulator |
| **`Computer Vision & Edge AI`** 👁️ | Edge-Optimized Industrial Vision System |
| **`LLM Infrastructure & MLOps`** 🔐 | Private Multi-Tenant Enterprise LLM Serving Platform |
| **`Applied Research & World Models`** 🔬 | Action-Conditioned JEPA Architecture |
| **`Data-Centric AI & Distillation`** 🧬 | Programmatic Weak Supervision Pipeline |
| **`Deep Learning Fundamentals`** 📐 | Transformers & Diffusion Guides (First Principles) |
| **`Meta-Learning & Optimization`** ⚡ | Optimization-Based Meta-Learning (`MAML`) |
| **`Responsible AI & Governance`** ⚙️ | `SHAP` & `XGBoost` Explainability Guide |
| **`GPU Engineering & Kernels`** 📡 | Custom `Triton` Kernels Guide |
| **`AI Leadership & Education`** 💻 | Strategy Lecture Series & AI-Native Analytics |

---

### 📡 Network Endpoints
* `[GITHUB]` [github.com/your-username](#)
* `[LINKEDIN]` [linkedin.com/in/your-profile](#)
