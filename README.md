<div align="center">

# Syed Naveed Mahmood

### Machine Learning Researcher | LLM Safety & Unlearning | Mechanistic Interpretability | Explainable Medical AI

B.Sc. in Computer Science and Engineering, BRAC University  
CGPA: **3.95 / 4.00** | Undergraduate Teaching Assistant | PhD Applicant

<a href="mailto:syed.naveed.mahmood@g.bracu.ac.bd">
  <img src="https://img.shields.io/badge/Email-syed.naveed.mahmood%40g.bracu.ac.bd-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/SyedNaveedMahmood">
  <img src="https://img.shields.io/badge/GitHub-SyedNaveedMahmood-181717?style=for-the-badge&logo=github" />
</a>
<a href="https://hypercite.vercel.app/">
  <img src="https://img.shields.io/badge/Featured_Project-HyperCite-111827?style=for-the-badge&logo=vercel" />
</a>

</div>

---

## About Me

I am a final-year Computer Science and Engineering student at **BRAC University** working at the intersection of **LLM safety, machine unlearning, mechanistic interpretability, explainable AI, and medical deep learning**.

My current flagship research direction is **representation-aware machine unlearning**, where I investigate whether an LLM has only learned to avoid mentioning a target entity or whether the underlying activation-level knowledge trace has actually been suppressed or erased. I also work on interpretable deep learning for biomedical signals, especially EEG-based sleep stage classification.

I am currently preparing for PhD-level research in **ML/NLP**, with a long-term focus on building safer, more interpretable, and more controllable AI systems.

---

## Research Interests

- **LLM Safety and Machine Unlearning**
  - Representation-aware unlearning
  - Entity-level forgetting
  - Utility-preserving knowledge removal
  - PEFT/LoRA-based unlearning pipelines

- **Mechanistic Interpretability**
  - Activation signatures
  - Hidden-state probing
  - Representation-level evaluation
  - Model behavior versus internal knowledge traces

- **Explainable Medical AI**
  - EEG sleep stage classification
  - GradCAM-based interpretation
  - Morphology-aware signal modeling
  - Clinically meaningful representation analysis

- **Applied AI Systems**
  - AI-assisted literature review
  - Research collaboration tools
  - Retrieval-grounded summarization
  - Full-stack ML-integrated applications

---

## Featured Research

### 1. Knowledge Immunization Framework (KIF)
**Representation-Aware Unlearning via Activation Signatures: From Suppression to Knowledge-Signature Erasure**  
Submitted to **ACL Rolling Review, May 2026 Cycle**

KIF is a representation-aware LLM unlearning pipeline designed to distinguish **surface-level behavioral suppression** from deeper **representation-level knowledge-signature removal**.

**Core idea:**  
Rather than only checking whether a model avoids saying a target subject, KIF mines activation signatures associated with target knowledge, suppresses those signatures, and distills the suppression behavior into LoRA adapters.

**Main components:**
- Activation-signature mining over hidden representations
- Signature-guided suppression capsules
- PEFT/LoRA-based unlearning loop
- DPO, unlikelihood loss, KL regularization, and EWC-style utility preservation
- Dual evaluation through:
  - **SMR:** Subject Mention Rate
  - **EL10:** Extraction Likelihood over autoregressive steps

**Repository:** [Representation-Aware-Unlearning-via-Activation-Signatures-KIF](https://github.com/SyedNaveedMahmood/Representation-Aware-Unlearning-via-Activation-Signatures-KIF)

---

### 2. GradG-AttnSleep
**GradG-AttnSleep: Dual-Mode GradCAM for Interpretable Sleep Staging with an Attention-Based CNN**  
Published in **IEEE ICITEE 2025** | **Scopus Indexed**  
DOI: `10.1109/ICITEE66631.2025.11338388`

This project introduces an attention-based CNN architecture with **branch-aware Dual-Mode GradCAM** for interpretable sleep stage classification from EEG signals.

**Highlights:**
- EEG-based automated sleep staging
- Attention-based CNN backbone
- Dual-Mode GradCAM for interpretability
- Sleep-EDF-20 evaluation under LOSO setting
- Reported accuracy: **87.33%**

---

### 3. Frequency-Aware MRCNN and Morphographic Wave-Sensing
Ongoing research on interpretable sleep stage classification using:
- Frequency-aware MRCNN pipelines
- Morphographic wave-sensing modules
- Prototype-based interpretability heads
- Cross-dataset robustness analysis
- GradCAM ablation studies aligned with EEG morphology

---

### 4. EEG-Based ADHD Cognitive Training
Ongoing neuro-gamification project designing an **N-Back cognitive training game** with integrated EEG monitoring to analyze cognitive load variation and training effectiveness for youth with ADHD.

---

## Featured Projects

### HyperCite - AI Research Summarization and Collaboration Hub
**Award:** CSE471 Best Project Award, Fall 2025, BRAC University  
**Live:** [hypercite.vercel.app](https://hypercite.vercel.app/)

HyperCite is an AI-powered research workspace for summarizing, organizing, and collaborating on academic papers. It combines PDF ingestion, evidence-grounded summaries, excerpts, claim panels, citation export, knowledge graphs, and collaborative notebooks.

**Tech stack:** React, TypeScript, Vite, Express, MongoDB, Vercel, Render

---

### Dual-MPU Kyphotic-Lordotic Posture Monitor
**Repository:** [Posture-Corrector](https://github.com/SyedNaveedMahmood/Posture-Corrector)

A wearable posture monitoring system using dual MPU6050 sensors to track upper-back kyphosis and lower-back lordosis. It provides haptic feedback, sitting/walking mode detection, calibration, and cloud analytics.

**Tech stack:** Arduino, MPU6050, ESP8266, ThingSpeak, Embedded Systems

---

### E-Commerce Platform with ML Integration
**Repository:** [Ecommerce_Website_with-ML-implementation_-CSE370-](https://github.com/SyedNaveedMahmood/Ecommerce_Website_with-ML-implementation_-CSE370-)

A full-stack e-commerce platform with product recommendation and user behavior analysis.

**Tech stack:** PHP, MySQL, Machine Learning

---

### Travel Agency Management System
**Repository:** [CSE470_Project](https://github.com/SyedNaveedMahmood/CSE470_Project)

A MERN-stack travel booking application with secure authentication, reservation management, and booking workflows.

**Tech stack:** MongoDB, Express.js, React, Node.js

---

### Additional GitHub Projects
- [GridDown - Offline Apocalypse Survival App](https://github.com/SyedNaveedMahmood/GridDown-Offline-Apocalypse-Survival-App)
- [codesage](https://github.com/SyedNaveedMahmood/codesage)
- [Pacman Game in Assembly](https://github.com/SyedNaveedMahmood/Pacman-Game-in-Assembly)
- [file_checker_fixer_CSE321_project2](https://github.com/SyedNaveedMahmood/file_checker_fixer_CSE321_project2)

---

## Publications

**Mahmood, S. N., Ferdous, T., & Zereen, A. N.**  
*GradG-AttnSleep: Dual-Mode GradCAM for interpretable sleep staging with an attention-based CNN.*  
Proceedings of the International Conference on Information Technology and Electrical Engineering, IEEE ICITEE 2025.  
DOI: `10.1109/ICITEE66631.2025.11338388`  
**Scopus Indexed**

**Mahmood, S. N.**  
*Representation-Aware Unlearning via Activation Signatures: From Suppression to Knowledge-Signature Erasure.*  
Submitted to ACL Rolling Review, May 2026 Cycle.

---

## Experience

### Undergraduate Teaching Assistant - BRAC University
**Fall 2024 - Fall 2025**

- Delivered lab sessions and academic support for **CSE220: Data Structures** and **CSE251: Electronic Devices and Circuits**
- Supported 100+ students across multiple semesters
- Evaluated assignments, quizzes, and exams
- Conducted one-on-one and small-group problem-solving sessions as a Student Tutor

---

## Technical Skills

### Machine Learning and AI
`Machine Unlearning` `LLM Safety` `Mechanistic Interpretability` `Explainable AI` `NLP` `Computer Vision` `Medical AI` `EEG Analysis`

### Frameworks and Libraries
`PyTorch` `TensorFlow` `Keras` `Scikit-learn` `HuggingFace Transformers` `PEFT/LoRA` `Pandas` `NumPy` `GradCAM`

### Programming Languages
`Python` `Java` `C` `C++` `JavaScript` `TypeScript` `PHP` `SQL` `Assembly`

### Web and Systems
`React` `Node.js` `Express.js` `MongoDB` `MySQL` `Vite` `Vercel` `Linux` `Git` `LaTeX`

---

## Awards and Honors

- Dean's List and VC's List Honoree, **10 consecutive semesters**, BRAC University
- **75% Merit-Based Tuition Waiver**, BRAC University
- **Second Place**, Undergraduate Thesis Poster Presentation, Summer 2025, BRAC University
- **CSE471 Best Project Award**, Fall 2025, BRAC University - HyperCite
- **Scopus-Indexed IEEE Publication**, ICITEE 2025 - GradG-AttnSleep

---

## GitHub Overview

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SyedNaveedMahmood&show_icons=true&theme=default&hide_border=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SyedNaveedMahmood&layout=compact&hide_border=true" height="165" />

</div>

---

## Suggested Pinned Repositories

For a research-oriented GitHub portfolio, I recommend pinning:

1. [Representation-Aware-Unlearning-via-Activation-Signatures-KIF](https://github.com/SyedNaveedMahmood/Representation-Aware-Unlearning-via-Activation-Signatures-KIF)
2. [Posture-Corrector](https://github.com/SyedNaveedMahmood/Posture-Corrector)
3. [CSE470_Project](https://github.com/SyedNaveedMahmood/CSE470_Project)
4. [Ecommerce_Website_with-ML-implementation_-CSE370-](https://github.com/SyedNaveedMahmood/Ecommerce_Website_with-ML-implementation_-CSE370-)
5. [GridDown-Offline-Apocalypse-Survival-App](https://github.com/SyedNaveedMahmood/GridDown-Offline-Apocalypse-Survival-App)
6. [codesage](https://github.com/SyedNaveedMahmood/codesage)

HyperCite should remain highlighted through the live deployment link if the repository is private.

---

## Contact

I am open to research collaboration, graduate research opportunities, and projects related to LLM safety, mechanistic interpretability, machine unlearning, and interpretable medical AI.

**Email:** [syed.naveed.mahmood@g.bracu.ac.bd](mailto:syed.naveed.mahmood@g.bracu.ac.bd)  
**GitHub:** [github.com/SyedNaveedMahmood](https://github.com/SyedNaveedMahmood)  
**Featured Project:** [HyperCite](https://hypercite.vercel.app/)

---
