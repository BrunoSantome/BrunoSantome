<div align="center">

# Hi, I'm Bruno Santomé 👋

### ML / AI Engineer with a software-engineering backbone

Building applied ML that ships — from production backends to on-device deep learning.
Currently completing an **MSc in Artificial Intelligence** (London) while specialising in **Edge AI**.

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

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

*Focus areas: knowledge distillation · quantisation · on-device / edge deployment · offline speech (Vosk) · intent classification*

**MLOps & Tooling**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Backend & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Quarkus](https://img.shields.io/badge/Quarkus-4695EB?style=flat-square&logo=quarkus&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-008AAA?style=flat-square&logo=keycloak&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

---

## 📌 Featured Projects

### 🛰️ [ViT-UNet for Marine-Debris Semantic Segmentation](https://github.com/BrunoSantome/ViT-Unet-Semantic-Segmentation-for-Marine-Debris-detection)
Hybrid ViT-UNet for detecting marine plastic on Sentinel-2 satellite imagery. Adapted an ImageNet ViT-B/16 encoder from 3 RGB to **11 spectral bands** via weight surgery and positional-embedding interpolation — **beating the published MARIDA baselines** (Random Forest & U-Net) on mean IoU (0.73 vs 0.69 and 0.57).
`PyTorch` · `timm` · `Weights & Biases`

### 🧠 [Knowledge Distillation from Multilingual Transformers](https://github.com/BrunoSantome/knowledge_distillation_multilingual_transformers)
Distilled an XLM-RoBERTa-Large teacher into a **22M-parameter MiniLM-L6 student** on the MASSIVE dataset (EN/ES, 60 intents), lifting macro-F1 from 0.80 → 0.82 and **surpassing the larger DistilmBERT on English** despite the student having no multilingual pre-training — surfacing a teacher–student compatibility insight.
`PyTorch` · `Hugging Face Transformers` · `Weights & Biases`

### 🌊 [Deep RL for Ocean-Plastic Interception](https://github.com/BrunoSantome/deep-rl-ocean-cleanup)
Custom **stochastic grid environment** (646k states, battery constraint) with Q-learning, Double + Dueling DQN and PPO implemented and compared from scratch. Dueling Double DQN reached **77% task-success** (vs 71% for standard DQN), with a diagnostic analysis of why PPO collapsed under sparse, delayed rewards.
`PyTorch` · `Weights & Biases`

### 🔬 [Neural Networks from Scratch & PyTorch](https://github.com/BrunoSantome/neural-networks-from-scratch-and-pytorch)
Deep learning from first principles: a neural-network engine built **from scratch in NumPy** (hand-derived backprop, dropout, momentum, mini-batch GD) alongside a PyTorch MLP-vs-CNN image classifier.
`NumPy` · `PyTorch`

### ⚛️ [3D Particle-Collision Simulator](https://github.com/BrunoSantome/3D-Particles-Collision-Simulator)
High-performance **Newtonian N-body** simulator with merging collisions and reflective walls, implemented **four ways (AOS/SOA × sequential/OpenMP)** to measure the impact of data layout and parallelism on performance.
`C++` · `OpenMP`

### 🩺 [ML for Diagnosis & Dysplasia Prediction](https://github.com/BrunoSantome/Machine-Learning-Algorithms-for-Predicting-Diagnosis-and-Dysplasia-Status)
A study benchmarking machine-learning algorithms for predicting diagnosis and dysplasia status, written up as a scientific paper.
`scikit-learn` · `Python`

<div align="center">

*More on my [repositories page →](https://github.com/BrunoSantome?tab=repositories)*

</div>

---

## 💼 Experience snapshot

**ML & Software Engineer — UBICUA** · *Oct 2024 – May 2026*
One of three engineers on a €1M national R&D connected-vehicle identity platform (TRL 8). Built two full-stack platforms end-to-end, owned four production Linux servers, and shipped a fully offline ES/EN intent classifier **quantised from ~1 GB to 96 MB** running on-device at 90% accuracy.

**Software Engineer Consultant — ALTEN (Airbus SIRTAP)** · *Sep 2023 – Oct 2024*
Developed, verified and validated safety-critical software for an Airbus tactical UAS ground control station, and co-built a Python test-automation framework adopted across four internal projects.

---

<div align="center">

💬 Happy to talk about applied ML, edge deployment, or backend systems — reach me on [LinkedIn](https://www.linkedin.com/in/bruno-santome-antolin-es/).

</div>
