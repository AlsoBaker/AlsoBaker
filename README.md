<div align="center">

# Vijayesh Thiyagarajan

**Robotics & AI undergrad · Part-time SDE · I build ML and LLM systems and ship them**

[![Portfolio](https://img.shields.io/badge/Portfolio-alsobaker.github.io-8B5CF6?style=for-the-badge&logo=githubpages&logoColor=white)](https://alsobaker.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vijayesh-thiyagarajan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vijayesh684@gmail.com)

</div>

---

## About

Third-year B.Tech student in **Robotics and Artificial Intelligence** at SASTRA Deemed University (graduating May 2028), working part-time as a **Software Development Engineer at JIME Developers**.

Most of my work sits where a model meets a real interface: a trained classifier behind a REST API, an LLM inside an automation workflow, a retrieval system behind access control. I care about whether the thing runs end to end, and about being exact on what it can and cannot do.

**Looking for:** Summer 2027 internships in software engineering and AI/ML engineering.

---

## Now

- 🏗️ **Building** a hybrid due diligence engine on Google Cloud: structured queries (BigQuery) plus vector search over documents, routed by a ReAct agent, served through FastAPI with role-based access
- 💼 **Shipping** client web projects at JIME Developers on a Laravel stack
- 📚 **Learning** RAG evaluation, LLM orchestration, and production FastAPI backends

---

## Experience

### Software Development Engineer (Part-time) · JIME Developers
<!-- TODO: add start month, e.g. `Mar 2026 – Present` -->
`Present`

- Deliver paid client projects alongside a full course load, working 2–4 hours a day, five days a week
- Developed the company website for a residential construction and apartment development business: server-rendered Laravel with Blade, Alpine.js, Tailwind CSS, Vite and Eloquent
- Implemented a scroll-driven, image-first hero with pinned parallax that respects reduced-motion preferences, plus a responsive project portfolio
<!-- TODO: add the live URL once public, and one line per additional project delivered -->

---

## Projects

### 🫁 Chest X-Ray Pneumonia Detection
**[Live demo](https://chest-xray-pneumonia-detection-bice.vercel.app/) · [Code](https://github.com/AlsoBaker/chest-xray-pneumonia-detection)**

An EfficientNetB4 classifier with Grad-CAM heatmaps, deployed end to end: upload an X-ray, get a prediction and a visual explanation of the regions behind it.

| | |
|---|---|
| **Results** | 93.59% accuracy · 0.9834 ROC-AUC · 94.36% sensitivity · 0.9485 F1 |
| **Training** | 5,863 labeled chest X-rays · two-phase transfer learning (frozen base, then top 100 layers fine-tuned) |
| **Deployment** | Dockerized Flask API on Hugging Face Spaces with lazy model loading · React + Vite frontend on Vercel |
| **Stack** | TensorFlow · Keras · Flask · React · Docker |

> A learning and research project. It is not a medical device and has not been clinically validated.

### 📡 AI Content Publishing Pipeline
**Private repository**

An event-driven n8n workflow on AWS EC2. Dropping a video into a Google Drive folder triggers an LLM to write the title and description, publishes the video, and sends a confirmation email.

| | |
|---|---|
| **Status** | YouTube publishing live · Instagram and Facebook integrations built, pending Meta business account approval |
| **Stack** | n8n · AWS EC2 · Google Drive API · YouTube Data API · Meta Graph API · LLM API |

### 🔥 Multi-Agent Firefighter Rescue Simulation
**[Code](https://github.com/AlsoBaker/AI-Firefighter-Rescue-Simulation)**

Up to 8 autonomous agents navigating a 3-floor, 1,200-cell building while fire spreads probabilistically. Four pathfinding algorithms (A\*, BFS, Dijkstra, D\* Lite) implemented from scratch and benchmarked under identical conditions.

| | |
|---|---|
| **Result** | D\* Lite scored 1,286 against BFS at 921 (out of 2,000), a 39.6% improvement from incremental replanning |
| **Context** | Graded project, Introduction to Artificial Intelligence, SASTRA (2025) |
| **Stack** | Python · Pygame · NumPy |

### 🧩 Hybrid Due Diligence Engine &nbsp;`in progress`

Answers financial and legal diligence questions that need both tables and documents. A ReAct router agent decides whether a question goes to SQL over BigQuery, to vector search over unstructured filings, or to both, and the FastAPI layer enforces role-based access to sources.

| | |
|---|---|
| **Stack** | Google Cloud · BigQuery · vector search · FastAPI |

### Smaller builds

- **[AI Fitness Planner](https://github.com/AlsoBaker/AI_fitness_tracker)** · Streamlit app that turns age, budget, diet and workout location into a personalized plan via the Groq API. Built for my IBM SkillsBuild AI Developer certification.
- **[Handwritten Digit Classifier](https://github.com/AlsoBaker/handwritten-digit-classifier-cnn)** · CNN with batch normalization and dropout, 99.64% validation accuracy on MNIST.

---

## Recognition

- **Amazon ML Summer School 2026** · ranked in the top 12% at the assessment stage
- **NIT Pragyan 2026** · shortlisted for the National Hackathon
- **IBM SkillsBuild AI Developer certification** · AICTE and Edunet Foundation program (Dec 2025 – Jan 2026)

---

## Stack

<p>
<img src="https://skillicons.dev/icons?i=python,cpp,js,php,tensorflow,opencv,flask,react,laravel,tailwind,docker,aws,gcp,mysql,git&theme=dark&perline=15" alt="Tech stack icons" />
</p>

| | |
|---|---|
| **Languages** | Python · C++ · C · JavaScript · PHP · SQL |
| **ML and AI** | TensorFlow · Keras · OpenCV · scikit-learn · NumPy · Pandas · Grad-CAM · Groq API |
| **Web** | Laravel · Blade · Alpine.js · Tailwind CSS · React · Flask · Streamlit |
| **Infra and automation** | Docker · AWS EC2 · Hugging Face Spaces · Vercel · n8n · Git |
| **Currently learning** | Google Cloud (BigQuery) · FastAPI · LangChain · vector databases |

---

<div align="center">

**Open to Summer 2027 internships.** The fastest way to reach me is [email](mailto:vijayesh684@gmail.com) or [LinkedIn](https://www.linkedin.com/in/vijayesh-thiyagarajan).

</div>
