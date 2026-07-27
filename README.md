<h3>Hi, I'm Rehmi! 🤖 <br/>
<a href="https://www.linkedin.com/in/imranrehmi">Data Science Manager - </a>  
<a href="https://www.linkedin.com/in/imranrehmi">AI Solution Lead</a>  
---

# Applied AI, Decision Science & MLOps Portfolio
> **Engineering intelligent systems that transition from research and experimentation to reliable, measurable production outcomes.**

Welcome! This repository serves as the central hub for my work across applied AI research, decision intelligence, computer vision, LLM infrastructure, data-centric engineering, and technical education.

---

## 🧭 Portfolio Navigation
* [🚀 Flagship Applied AI Projects](#-flagship-applied-ai-projects)
* [📚 Technical Tutorials & Engineering Guides](#-technical-tutorials--engineering-guides)
* [🎓 Leadership & Lecture Series](#-leadership--lecture-series)
* [🧩 System Capabilities & Matrix](#-system-capabilities--matrix)

---

## 🚀 Flagship Applied AI Projects

### 🛵 1. Causal Decision Intelligence & Spatial-Temporal Marketplace Simulator
`Python` | `SimPy` | `EconML` | `CausalML` | `OR-Tools` | `GeoPandas` | `PyTorch` | `Streamlit`

A discrete-event simulation and decision-intelligence platform for evaluating operational interventions across two-sided delivery networks. Rather than merely predicting demand, the system estimates heterogeneous treatment effects and optimizes dynamic operational interventions under constraints.

* **Causal Intelligence:** Estimates incremental impacts of rider incentives, shift policies, and dynamic pricing using heterogeneous treatment-effect models.
* **Marketplace Simulation:** Models spatial-temporal rider supply, order demand, service times, and congestion via discrete-event simulation.
* **Decision Optimization:** Applies mixed-integer programming (OR-Tools) to rebalance geographic zones and allocate riders under operational constraints.
* **Network Experimentation:** Evaluates policies while accounting for network interference, spillover effects, and SUTVA violations.
* **Business Outcomes:** Connects operational levers directly to fulfillment rate, rider utilization, delivery time, and contribution margin.

---

### 👁️ 2. Edge-Optimized Industrial Vision System with Neural Attribution & Quantized Inference
`Python` | `PyTorch` | `FastSAM` | `U-Net` | `ONNX Runtime` | `TensorRT` | `OpenCV` | `Grad-CAM` | `Docker`

A production-oriented computer vision architecture for detecting, segmenting, and explaining industrial defects in resource-constrained edge environments.

* **Vision Pipeline:** End-to-end detection and semantic segmentation for surface defects, component damage, and production anomalies.
* **Edge Optimization:** Compiles PyTorch models to ONNX and TensorRT for execution on resource-constrained hardware.
* **Performance Benchmarking:** Real-time execution target (<15 ms latency) across FP32, FP16, and INT8 quantization modes.
* **Explainability & Monitoring:** Integrates Grad-CAM visual attribution overlays alongside tracking for data drift, confidence shift, and latency degradation.
* **Production Packaging:** Containerized microservice in Docker with reproducible preprocessing and prediction interfaces.

---

### 🏛️ 3. Private Multi-Tenant Enterprise LLM Serving & GPU Orchestration Infrastructure
`vLLM` | `Llama` | `Mistral` | `Kubernetes` | `Helm` | `Karpenter` | `Triton` | `Istio` | `WireGuard` | `Prometheus` | `Grafana`

An on-premises and private-cloud orchestration platform for serving open-weight large language models within zero-trust enterprise boundaries.

* **High-Performance Serving:** Leverages vLLM and NVIDIA Triton for continuous batching, KV-cache optimization, and OpenAI-compatible endpoints.
* **GPU Orchestration:** Automated node provisioning, scale-to-zero, and GPU-aware scheduling via Kubernetes and Karpenter.
* **Zero-Trust Security:** Enforces service-mesh routing (Istio), mutual TLS, role-based access control, and isolated namespaces.
* **Production Observability:** Monitors Time-To-First-Token (TTFT), inter-token latency, queue depth, GPU memory utilization, and failure recovery.
* **Cost Engineering:** Tracks real-time cost-per-request and cost-per-token metrics against capacity limits.

---

### 🌐 4. Action-Conditioned Joint-Embedding Predictive Architecture (JEPA) for Visual Planning
`Python` | `PyTorch` | `Vision Transformers` | `Self-Supervised Learning` | `Gymnasium` | `MuJoCo` | `MPC` | `Hydra` | `W&B`

A research implementation of an action-conditioned Joint-Embedding Predictive Architecture (JEPA) for learning visual world dynamics without pixel reconstruction.

* **Latent-Space Prediction:** Predicts trajectory transformations in representation space rather than generating full future frames.
* **Self-Supervised Learning:** Employs energy-based collapse-prevention mechanisms to train encoder and predictor networks.
* **Goal-Conditioned Control:** Integrates Model Predictive Control (MPC) to plan action sequences targeting image-defined goals.
* **Research Rigor:** Evaluates representation collapse, prediction consistency over multi-step rollouts, and action sensitivity.

---

### 🧪 5. Programmatic Weak Supervision, Label Consensus & Parameter-Efficient Model Distillation
`Python` | `Snorkel` | `Hugging Face` | `PyTorch` | `QLoRA` | `PEFT` | `Llama 3` | `MLflow` | `FastAPI`

A data-centric AI pipeline combining weak supervision and parameter-efficient fine-tuning (PEFT) to build quality training sets and low-cost student models.

* **Weak Supervision:** Combines heuristic rules, domain functions, and LLM-generated rationale labels via Snorkel consensus modeling.
* **Student Distillation:** Fine-tunes smaller open-weight models using QLoRA to replicate teacher capabilities at a fraction of the serving cost.
* **Quality & Governance:** Audits dataset lineage, tracks prompt versioning, and filters uncertain/contradictory labels for human review.

---

## 📚 Technical Tutorials & Engineering Guides

First-principles implementations, mathematical derivations, and operational benchmarks for core machine learning paradigms.

| Guide Title | Core Stack | Key Focus & Engineering Concepts |
| :--- | :--- | :--- |
| **Building Transformers from First Principles** | `PyTorch`, `CUDA`, `NumPy` | Multi-head self-attention mechanisms, positional encodings, tensor dimensional tracking, and CUDA memory profiling. |
| **Optimization-Based Meta-Learning (MAML)** | `PyTorch`, `higher` | Task distribution sampling, bi-level gradient optimization, first/second-order updates, and rapid few-shot adaptation. |
| **Explainable AI with SHAP & XGBoost** | `XGBoost`, `SHAP`, `Evidently` | TreeSHAP attribution, global/cohort feature interaction analysis, demographic auditing, and automated governance reports. |
| **Diffusion Models from Scratch (DDPM)** | `PyTorch`, `U-Net`, `CUDA` | Forward/reverse Markov processes, linear/cosine variance schedules, time-conditioned U-Nets, and sampling quality metrics. |
| **Custom Triton Kernels for PyTorch** | `OpenAI Triton`, `CUDA` | GPU memory hierarchy optimization, fused Softmax/LayerNorm, FlashAttention access patterns, and bandwidth profiling. |

---

## 🎓 Leadership & Lecture Series

Practitioner-focused educational programs bridging technical implementation with strategic AI leadership and modern workflows.

### 🧭 Leading AI from Strategy to Scale: Applying PMI-CPMAI
* **Core Themes:** Operational opportunity framing, CPMAI project lifecycles, data readiness assessments, risk mitigation, human oversight, and enterprise value tracking.
* **Target Audience:** AI Leaders, Program Managers, Product Leads, and Transformation Teams.
* **Positioning:** Practical bridge between strategic decision-making, governance, and technical execution.

### 🎨 AI-Native Analytics with Codex: The Science and Art of Data
* **Core Themes:** AI-augmented analytical workflows, pair-programming for exploratory data analysis, automated feature engineering, hallucination management, and code verification.
* **Target Audience:** Data Scientists, Analytics Engineers, Business Intelligence Practitioners, and Technical Directors.
* **Positioning:** Framework for modern data analytics where human judgment directs strategy while AI agents accelerate execution.

---

## 🧩 System Capabilities & Matrix

| Portfolio Capability Area | Primary Implementation / Reference |
| :--- | :--- |
| **Causal Inference & Optimization** | Causal Decision Intelligence & Marketplace Simulator |
| **Computer Vision & Edge AI** | Edge-Optimized Industrial Vision System |
| **LLM Infrastructure & MLOps** | Private Multi-Tenant Enterprise LLM Serving Platform |
| **Applied Research & World Models** | Action-Conditioned JEPA Architecture |
| **Data-Centric AI & Model Distillation** | Programmatic Weak Supervision Pipeline |
| **Deep Learning Fundamentals** | Transformers & Diffusion Guides (First Principles) |
| **Meta-Learning & Optimization** | Optimization-Based Meta-Learning (MAML) |
| **Responsible AI & Governance** | SHAP & XGBoost Explainability Guide |
| **GPU Engineering & Kernel Design** | Custom Triton Kernels Guide |
| **AI Leadership & Analytics Education** | Strategy Lecture Series & AI-Native Analytics |

---

### 📩 Contact & Connect
* **GitHub:** [Your GitHub Handle](#)
* **LinkedIn:** [Your LinkedIn Profile](#)
