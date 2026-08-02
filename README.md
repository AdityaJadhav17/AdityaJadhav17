<div align="center">

<img src="media/team-pic.jpeg" alt="UCSD CSE 110 Team 09, the WatchTower project team" width="720" />

# Aditya Jadhav

CS student at UC San Diego building software across enterprise security, AI, and full-stack systems.

<br />

[![Location](https://img.shields.io/badge/Location-San%20Diego%2C%20CA-87CEEB?style=for-the-badge&labelColor=1C1C1C)](https://github.com/AdityaJadhav17)
[![Website](https://img.shields.io/badge/Website-adityajadhav17.github.io-90EE90?style=for-the-badge&labelColor=1C1C1C)](https://adityajadhav17.github.io/)
[![Email](https://img.shields.io/badge/Email-aditya.jadhav7910%40gmail.com-E07A5F?style=for-the-badge&labelColor=1C1C1C)](mailto:aditya.jadhav7910@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aditya%20Jadhav-0A66C2?style=for-the-badge&labelColor=1C1C1C)](https://www.linkedin.com/in/aditya-jadhav-06484123a/)
[![Resume](https://img.shields.io/badge/Resume-PDF-F4A261?style=for-the-badge&labelColor=1C1C1C)](https://adityajadhav17.github.io/Aditya_Jadhav_Resume.pdf)

</div>

---

## Current Focus

- **Security automation at UC San Diego Enterprise IT:** Python pipelines, SQL workflows, and REST components that cut manual review effort by ~30% and added 20+ automated test cases
- **Hardware-facing desktop software at Lumulus Technologies:** Windows tooling for hardware programming workflows (PySide6); details kept public-safe under internship constraints
- **AI systems and production-minded backends:** multi-agent services, APIs, containerized deployments, and observability
- **B.S. in Computer Science @ UC San Diego** (expected June 2027)

---

## Selected Engineering Work

### [AI-Powered Travel Planning Platform](https://github.com/AdityaJadhav17/Travel-Agntcy)
**Problem:** Travel planning spans flights, hotels, and activities, but stitching those sources into a coherent plan is slow and fragmented.

**What I built:** A distributed multi-agent travel planner with a LangGraph supervisor, FastAPI services, and a React/TypeScript UI. Containerized the stack with Docker, used NATS for inter-service messaging, and added Grafana/ClickHouse observability.

**Stack:** Python · FastAPI · LangGraph · React · TypeScript · Docker · NATS · Grafana

**Result:** Cut inter-service latency by ~40% with containerized microservices and NATS messaging. Demo: [YouTube walkthrough](https://youtu.be/T0EkJ9J_IQU)

---

### [WatchTower](https://github.com/cse110-sp26-group09/Watchtower-Course-Project)
**Problem:** Web teams need lightweight production visibility for JS errors, latency, and user activity without a heavyweight vendor agent.

**What I engineered:** As Team Leader and Technical Lead (CI/CD and architecture) for UCSD CSE 110 Team 09, directed delivery and system design for a browser SDK, Node.js ingest API, Supabase/Postgres persistence, and a Clerk-authenticated real-time dashboard. Shipped CI with Jest and Playwright, plus a deployed Render backend.

**Stack:** JavaScript · Node.js · Supabase · Clerk · Jest · Playwright · Render

**Result:** Deployable observability platform with live backend and SDK test app. Live: [backend](https://watchtower-course-project-g8dv.onrender.com) · [test app](https://cse110-sp26-group09.github.io/Watchtower-test-app/) · [demo video](https://youtu.be/tCBGQJBaOEo)

---

### [Talk-to-Robot](https://github.com/YangLin14/Talk-to-Robot)
**Problem:** Natural-language robot commands fail when spatial grounding is mixed with control, making it hard to see where LLM understanding breaks.

**What I engineered:** Team project (CSE 190) with a decoupled LLM grounder and SAC+HER controller in MuJoCo FetchPush. Evaluated instruction tiers from literal coordinates to functional intent, isolating grounding failures from policy errors.

**Stack:** Python · Gemini · MuJoCo · Gymnasium · Stable-Baselines3 (SAC + HER)

**Result:** End-to-end success near-solved on literal/region tiers (T0 ~98%, T1 ~93%), with a clear cliff on relative and intent-heavy instructions (T2 ~77% LLM, T4 ~45-55%).

---

### [Synthetic-to-Real Object Detection](https://github.com/AdityaJadhav17/Synthetic-to-Real-Object-Detection)
**Problem:** Models trained only on synthetic images often fail on real photos; this Kaggle challenge measured that sim-to-real gap directly.

**What I built:** An end-to-end YOLOv8 detection pipeline with training, augmentation/domain randomization experiments, inference, and Kaggle submission tooling.

**Stack:** Python · PyTorch · YOLOv8 · Albumentations

**Result:** Public LB mAP **0.9175** / Private LB mAP **0.9074**. Competition: [Kaggle challenge](https://www.kaggle.com/competitions/synthetic-2-real-object-detection-challenge)

---

<details>
<summary><strong>Additional work</strong> (workplace + projects without a public code repo)</summary>

<br>

**AI Chat Assistant (IBM Cloud)**  
Designed a Watson Assistant + Node.js/Express conversational system; handled 150+ test queries at 90%+ response accuracy. Demo: [YouTube](https://youtu.be/9sRefMjn5Es)

**Web Development Intern, NutrifitWorld**  
Shipped a responsive business platform with CRM, scheduling, and analytics workflows (Jun-Oct 2025).

</details>

---

## Technical Toolkit

| Area | Tools |
|------|--------|
| **Languages** | Python, C++, Java, C, JavaScript/TypeScript, SQL |
| **Backend & APIs** | FastAPI, Node.js, Express, REST, MySQL, MongoDB, Supabase |
| **Frontend** | React, Vite, HTML/CSS |
| **AI & Data** | PyTorch, TensorFlow, YOLOv8, LangGraph, MuJoCo, NumPy, Pandas |
| **Infra & Tools** | Docker, NATS, Grafana, AWS, IBM Cloud, Git, Linux, Windows, CI/CD |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Engineering Interests

Problems I want to keep working on:

- AI-enabled products with clear system boundaries (agents, APIs, evaluation)
- Reliable backend systems: latency, observability, and maintainable interfaces
- Security automation that reduces manual toil without hiding risk
- Developer tooling that shortens feedback loops
- Hardware/software integration where desktop apps meet physical devices

---

## Let's Connect

Open to **software engineering internships**, **AI/ML engineering**, and **security-focused software** conversations.

Prefer a short technical discussion over a cold pitch. Reach me via:

- **Email:** [aditya.jadhav7910@gmail.com](mailto:aditya.jadhav7910@gmail.com)
- **LinkedIn:** [linkedin.com/in/aditya-jadhav-06484123a](https://www.linkedin.com/in/aditya-jadhav-06484123a/)
- **Portfolio / Resume:** [adityajadhav17.github.io](https://adityajadhav17.github.io/) · [PDF resume](https://adityajadhav17.github.io/Aditya_Jadhav_Resume.pdf)
