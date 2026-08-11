<div align="center">

<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="GitHub contribution snake animation"/>

# Hi, I'm Steve Philip

### AI/ML Engineer · Generative AI · RAG · Multi-Agent Systems

I build **AI-powered applications and production ML systems** using Python, LLMs, RAG, multi-agent architectures, and computer vision.

My work focuses on taking AI systems beyond simple model calls — designing **retrieval pipelines, agent workflows, evaluation frameworks, APIs, and scalable deployments**.

<p>
  <a href="mailto:stevephilip.me86@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/steve-p-25459021a/">LinkedIn</a> ·
  <a href="https://github.com/stevephilipgit">GitHub</a>
</p>

<img src="https://komarev.com/ghpvc/?username=stevephilipgit&label=Profile%20Views&color=blueviolet&style=flat" alt="Profile Views"/>

</div>

---

## About Me

I'm an **AI/ML Engineer** interested in building practical AI systems that combine machine learning, LLMs, retrieval, reasoning, and software engineering.

I work across the AI development lifecycle:

* Designing and building **LLM-powered applications**
* Developing **Retrieval-Augmented Generation (RAG)** systems
* Building **multi-agent workflows** with LangGraph
* Developing **ML pipelines** from preprocessing to deployment
* Building **Computer Vision** applications
* Designing **REST APIs** for AI systems
* Working with **vector databases and retrieval systems**
* Evaluating retrieval quality, grounding, and hallucination
* Containerizing and deploying AI applications

My engineering interests currently sit at the intersection of:

**AI Engineering × Generative AI × Machine Learning × Backend Engineering**

---

## Core Technologies

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)

### AI / Machine Learning

![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge\&logo=opencv\&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge\&logo=huggingface\&logoColor=black)

**Machine Learning · Deep Learning · NLP · Computer Vision · Generative AI · Model Evaluation**

### Generative AI & Agentic Systems

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)

**LLMs · RAG · Hybrid Retrieval · Reranking · Prompt Engineering · Agentic AI · Multi-Agent Systems · Tool Calling · AI Evaluation**

### Data & Vector Databases

![Qdrant](https://img.shields.io/badge/Qdrant-D61F2C?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge\&logo=mongodb\&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-5A45FF?style=for-the-badge)

**Qdrant · ChromaDB · FAISS · MongoDB · SQL · Vector Search · Embeddings**

### Backend & Engineering

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

**FastAPI · REST APIs · Docker · Git · GitHub · Redis · Supabase**

---

# Featured Projects

## [Research Knowledge Retrieval Platform](https://github.com/stevephilipgit/research-agent-rag-app)

An **enterprise-oriented RAG platform** designed for research and knowledge retrieval across large document collections.

### Highlights

* Built agent workflows using **LangGraph**
* Implemented **hybrid retrieval and reranking**
* Designed a **multi-tenant architecture**
* Built a grounding evaluation framework
* Evaluated retrieval accuracy and hallucination rates
* Deployed using Docker, Redis, and Supabase

**Stack:** `Python` `FastAPI` `LangGraph` `Qdrant` `Redis` `Supabase` `Docker`

---

## [AgentFlow — Multi-Agent AI Orchestration](https://github.com/stevephilipgit/agentflow)

A multi-agent orchestration system designed to decompose complex goals into smaller tasks and execute them through specialized agents.

### Architecture

```text
                    ┌──────────────┐
                    │    Planner   │
                    └──────┬───────┘
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
         ┌─────────┐  ┌─────────┐  ┌─────────┐
         │ Worker  │  │ Worker  │  │ Worker  │
         └────┬────┘  └────┬────┘  └────┬────┘
              │            │            │
              └────────────┼────────────┘
                           ▼
                    ┌──────────────┐
                    │  Synthesizer │
                    └──────────────┘
```

### Highlights

* Planner → Worker → Synthesizer architecture
* Parallel task execution
* Asynchronous orchestration
* Intelligent task scheduling
* Reduced execution latency from **40s → 10s**

**Stack:** `Python` `FastAPI` `LangGraph` `React` `LLMs`

---

## [AI Safety Monitoring System](https://github.com/stevephilipgit/ai-safety-cv-llm)

A real-time **computer vision safety monitoring system** designed to detect PPE violations and support industrial safety compliance.

### Highlights

* Real-time PPE detection
* Deep-learning-based computer vision
* OpenCV-based video processing
* AI-generated compliance reports
* Designed for industrial safety monitoring

**Stack:** `Python` `OpenCV` `TensorFlow` `Computer Vision` `LLMs`

---

## [AI HR Policy Assistant — RAG](https://github.com/stevephilipgit/hr_domain_rag_chat)

A document-based RAG application that enables users to query HR policy documents and receive grounded answers.

### Pipeline

```text
PDF Documents
      ↓
Document Processing
      ↓
Chunking & Embeddings
      ↓
Vector Database
      ↓
Semantic Retrieval
      ↓
Relevant Context
      ↓
LLM
      ↓
Grounded Answer
```

**Stack:** `Python` `LangChain` `Embeddings` `Vector Database` `LLMs`

---

# Engineering Experience

My professional experience spans **AI engineering and full-stack engineering**, allowing me to work across the complete lifecycle of AI products.

### AI Engineering

* Built and deployed AI/ML solutions using Python, FastAPI, LLMs, RAG, and Computer Vision
* Developed end-to-end ML pipelines covering preprocessing, feature engineering, training, evaluation, and deployment
* Designed REST APIs for integrating AI models into production applications
* Automated business workflows, reducing manual effort by approximately **40%**
* Worked in Agile development environments and contributed to technical documentation

### Software Engineering

* Developed enterprise applications using React, Next.js, and TypeScript
* Integrated REST APIs and backend services
* Worked with databases and document-processing workflows
* Debugged production issues and performed API analysis and optimization
* Contributed to code reviews, testing, and performance improvements
* Worked within a large monorepo environment

---

# GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=stevephilipgit&show_icons=true&theme=radical&hide_border=true" alt="Steve's GitHub Stats" height="170"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=stevephilipgit&layout=compact&theme=radical&hide_border=true" alt="Top Languages" height="170"/>

</div>

---

# Current Focus

I'm currently exploring and building systems around:

* **Agentic AI**
* **RAG architectures**
* **Multi-agent orchestration**
* **LLM evaluation**
* **AI reliability and grounding**
* **Computer Vision**
* **Production AI systems**
* **AI-powered developer tools**

---

# Connect With Me

<div align="center">

<a href="https://www.linkedin.com/in/steve-p-25459021a/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<a href="https://github.com/stevephilipgit">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<a href="mailto:stevephilip.me86@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

</div>

---

<div align="center">

### Building AI systems that are useful, grounded, and production-ready.

</div>
