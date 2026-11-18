<div align="center">

# Hi, I'm Bruno Santomé 👋

### Software engineer building ML and AI systems

I build applied ML that ships, from production backends to on-device deep learning. 
Currently completing an MSc in Artificial Intelligence in London, with a particular interest in edge AI and model compression.

📍 London, UK &nbsp;•&nbsp; 🎯 Open to **ML/AI Engineer**, **Forward-Deployed Engineer** & **Backend + ML** roles

<a href="https://www.linkedin.com/in/bruno-santome-antolin-es/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:b.santomeantolin@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/BrunoSantome"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

</div>

---

## 🚀 About me

Software engineer with **3 years of industry experience** building and deploying production systems, now focused on **applied ML and deep learning**, with a specialism in **Edge AI** — pushing models onto devices to cut cloud dependency.

- 🔬 Most recently at **UBICUA**, where I deployed an **offline multilingual NLP model on in-vehicle hardware** and solely owned the backend platforms and production infrastructure of a **€1M government-funded** vehicle-identity project.
- 🛩️ Previously at **ALTEN**, developing, verifying and validating **safety-critical software** for an **Airbus tactical UAS** ground control station.
- 🎓 Completing an **MSc in Artificial Intelligence** (on track for Distinction), with a thesis on **continual learning for on-device NLU**.
- 🌊 Most of my research projects lean toward ML for real-world / environmental problems — marine-debris detection, ocean-plastic cleanup, edge NLU.

---

## 🛠️ Tech Stack

**Languages**

!Python (→ img.shields.io)
!Java (→ img.shields.io)
!JavaScript (→ img.shields.io)
!SQL (→ img.shields.io)
!C++ (→ img.shields.io)

**ML / Deep Learning**

!PyTorch (→ img.shields.io)
!Hugging Face (→ img.shields.io)
!scikit-learn (→ img.shields.io)
!TensorFlow (→ img.shields.io)
!OpenCV (→ img.shields.io)

*Focus areas: knowledge distillation · quantisation · on-device / edge deployment · offline speech (Vosk) · *

**MLOps & Tooling**

!MLflow (→ img.shields.io)
!Weights & Biases (→ img.shields.io)
!DVC (→ img.shields.io)
!Docker (→ img.shields.io)

**Backend & Infrastructure**

!PostgreSQL (→ img.shields.io)
!MongoDB (→ img.shields.io)
!Quarkus (→ img.shields.io)
!Keycloak (→ img.shields.io)
!MQTT (→ img.shields.io)
!Linux (→ img.shields.io)
!FastAPI (→ img.shields.io)

---

## 📌 Featured Projects

### 🛰️ ViT-UNet for Marine-Debris Semantic Segmentation (→ github.com)
Hybrid ViT-UNet for detecting marine plastic on Sentinel-2 satellite imagery. Adapted an ImageNet ViT-B/16 encoder from 3 RGB to **11 spectral bands** via weight surgery and positional-embedding interpolation — **beating the published MARIDA baselines** (Random Forest & U-Net) on mean IoU (0.73 vs 0.69 and 0.57).
PyTorch · timm · Weights & Biases

### 🛡️ [Safe Agent Payments](https://github.com/BrunoSantome/safe-agent-payments)
An LLM agent that turns natural-language requests into structured payments, with a **deterministic policy engine** deciding whether each one is approved, **held for human review**, or denied. The model never approves a payment or reports on one; denials feed back into the conversation so the agent can revise. Found and fixed a live failure where **an LLM outage led to the wrong payee being paid**. Covered by **178 tests**.
Python · Gemini · Pydantic · pytest

### 🧠 Knowledge Distillation from Multilingual Transformers (→ github.com)
Distilled an XLM-RoBERTa-Large teacher into a **22M-parameter MiniLM-L6 student** on the MASSIVE dataset (EN/ES, 60 intents), lifting macro-F1 from 0.80 → 0.82 and **surpassing the larger DistilmBERT on English** despite the student having no multilingual pre-training — surfacing a teacher–student compatibility insight.
PyTorch · Hugging Face Transformers · Weights & Biases

### 🌊 Deep RL for Ocean-Plastic Interception (→ github.com)
Custom **stochastic grid environment** (646k states, battery constraint) with Q-learning, Double + Dueling DQN and PPO implemented and compared from scratch. Dueling Double DQN reached **77% task-success** (vs 71% for standard DQN), with a diagnostic analysis of why PPO collapsed under sparse, delayed rewards.
PyTorch · Weights & Biases

### 🔬 Neural Networks from Scratch & PyTorch (→ github.com)
Deep learning from first principles: a neural-network engine built **from scratch in NumPy** (hand-derived backprop, dropout, momentum, mini-batch GD) alongside a PyTorch MLP-vs-CNN image classifier.
NumPy · PyTorch

### ⚛️ 3D Particle-Collision Simulator (→ github.com)
High-performance **Newtonian N-body** simulator with merging collisions and reflective walls, implemented **four ways (AOS/SOA × sequential/OpenMP)** to measure the impact of data layout and parallelism on performance.
C++ · OpenMP

### 🩺 ML for Diagnosis & Dysplasia Prediction (→ github.com)
A study benchmarking machine-learning algorithms for predicting diagnosis and dysplasia status, written up as a scientific paper.
scikit-learn · Python

<div align="center">

*More on my repositories page → (→ github.com)*

</div>

---

## 💼 Experience snapshot

**ML & Software Engineer — UBICUA** · *Oct 2024 – May 2026*
One of four engineers on a €1M national R&D connected-vehicle identity platform (TRL 8). Built two full-stack platforms end-to-end, owned four production Linux servers, and shipped a fully offline ES/EN intent classifier **quantised from ~1 GB to 96 MB** running on-device at 90% accuracy.

**Software Engineer Consultant — ALTEN (Airbus SIRTAP)** · *Sep 2023 – Oct 2024*
Developed, verified and validated safety-critical software for an Airbus tactical UAS ground control station, and co-built a Python test-automation framework adopted across four internal projects.

---

<div align="center">

💬 Happy to talk about applied ML, edge deployment, or backend systems — reach me on LinkedIn (→ www.linkedin.com).

</div>
