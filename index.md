---
layout: default
title: Md Hasibul Amin
---

# Md Hasibul Amin

**Software Engineer — Distributed Systems, Cloud Infrastructure & AI/ML**  
Houston, TX, USA

[Email](mailto:hasibulamin.cse@gmail.com) ·
[Google Scholar](https://scholar.google.com/citations?user=C8gkK7sAAAAJ&hl=en) ·
[GitHub](https://github.com/AminHasibul) ·
[LinkedIn](https://linkedin.com/in/aminhasibul) ·
[Hugging Face](https://huggingface.co/AminHasibul)

---

## About

I’m a software engineer with 10+ years of experience designing and building distributed backend systems, cloud infrastructure, data platforms, and production-critical services.

My engineering work spans event-driven architectures, Kafka and CDC pipelines, CQRS, scalable APIs, multi-tenant systems, Kubernetes, infrastructure-as-code, observability, incident response, and production reliability across AWS and Azure.

I have also led and mentored engineering teams, owned backend and database architecture, and worked on systems serving hundreds of thousands of daily requests.

Alongside my full-time engineering work, I conduct and collaborate on applied AI/ML research in continual learning, model reliability, NLP, medical imaging, and LLM adaptation and evaluation.

I earned an M.S. in Computer Science from the University of Houston, where I worked on GPU-accelerated medical-imaging and applied AI systems.

---

## Engineering Experience

### Software Engineer
**Crane Worldwide Logistics** · Houston, TX · Jul 2023 — Present

- Designed and built from scratch a resilient Kafka-based billing platform automating invoice validation, document retrieval and assembly, downstream delivery, and notifications
- Implemented idempotent processing, retry policies, and DLQ-backed recovery, with 99% of requests completing within 90 seconds
- Built Kafka CDC pipelines synchronizing tens of millions of production records and propagating ongoing changes within a 30-second latency SLA
- Designed CQRS-based PostgreSQL read models to offload read-heavy workloads from Oracle, improving query response time by approximately 15–18%
- Serve as production DRI across mission-critical platforms, handling incident response, debugging, root-cause analysis, and reliability improvements
- Lead architecture, design, and code reviews for C#/ASP.NET and F# services across AWS and Azure
- Build secure multi-tenant APIs with configuration-driven behavior, database-per-client isolation, and least-privilege RBAC
- Work with CI/CD, Terragrunt, Bicep, Kubernetes, OpenTelemetry, and distributed tracing
- Use Claude Code, GitHub Copilot, and MCP-based workflows for requirements analysis, implementation, testing, debugging, and code review

### Lead Software Engineer
**Truck Lagbe Ltd.** · Dhaka, Bangladesh · Sep 2019 — Jul 2021

- Led and mentored a 12-engineer cross-functional team while owning backend and database architecture for a freight marketplace handling 400K+ daily requests and 5K+ concurrent users
- Built a multilingual geo-search engine mapping informal landmarks to formal addresses using trie-based search, inverted indexing, spatial hashing, and fuzzy matching
- Achieved approximately 95–97% search accuracy and reduced external mapping costs by approximately $35K annually
- Designed high-availability database architecture using CQRS, replication, age-based trip partitioning, caching, and recovery workflows
- Architected the core backend and reusable Node.js framework used across engineering teams
- Built an adaptive pricing engine using distance, time, demand, weather, vehicle type, and historical trip data; rollout testing increased successful bookings by 20–23%
- Migrated production workloads to AWS and Kubernetes, reducing deployment time from 2–3 hours to approximately 20–30 minutes
- Served as Acting CTO for two months, setting engineering priorities and leading a major cross-platform release

### Associate Senior Software Engineer
**CSL Software Resources Ltd.** · Dhaka, Bangladesh · Feb 2017 — Aug 2019

- Built a reusable C++ access-control library for C#/ASP.NET applications, reducing development and maintenance effort by approximately 10%
- Developed ERP and POS systems used by 400+ companies and 250+ retail outlets
- Optimized APIs and SQL workloads, improving dashboard response time by approximately 35%

### Software Engineer
**GOBD (Startup)** · Dhaka, Bangladesh · Jan 2015 — Jan 2016

- Built route-optimization logic combining live tracking, traffic-signal, mobile-app, and third-party location data
- Weighted data sources by priority to identify alternate routes under changing traffic conditions

---

## Research Experience

### Independent AI/ML Research Collaborator
**Late 2024 — Present**

Conducted alongside full-time software engineering work with multi-institution collaborators.

- Develop and evaluate continual-learning methods in Python and PyTorch to reduce catastrophic forgetting
- Study model-update reliability and failure modes in replay-based continual learning
- Identified a readout-dependent failure mode that can reverse the measured benefit of knowledge distillation under controlled multi-seed evaluation
- Collaborate on research in breast-cancer segmentation, medical LLM fine-tuning, NLP, and trustworthy AI
- Built a BERT-based pipeline for COVID-19 vaccine conspiracy and misinformation detection using Google Perspective API signals for content-quality analysis

### Graduate Research Assistant
**University of Houston — Imaging Innovations Laboratory** · Houston, TX · 2021 — 2023

- Built an automated GPU-accelerated CT acquisition and reconstruction pipeline in Python
- Integrated 360° acquisition and precise positional control
- Reduced end-to-end processing time by approximately 35–40%
- Worked on biomedical image analysis and applied AI research

---

## Selected Engineering & AI Projects

### Event-Driven Logistics and Billing Platform

Designed production-critical event-driven workflows using Kafka, CDC, C#, F#, SQL, PostgreSQL, Oracle, AWS, Azure, and Kubernetes.

**Focus areas:**
- Event-driven architecture
- Idempotency
- Retry and DLQ recovery
- Data synchronization
- Distributed tracing
- Production reliability
- Multi-tenant service design

> Proprietary implementation. Public descriptions intentionally exclude confidential business details.

### Continual Learning and Model Reliability

**Research repository:**  
[Continual-Learning-UsingInterClusterDistance](https://github.com/AminHasibul/Continual-Learning-UsingInterClusterDistance)

**Preprint:**  
[Failure Modes of Always-On Inter-Cluster Repulsion in Replay-Based Continual Learning](https://arxiv.org/abs/2510.07648)

Research areas include:

- Catastrophic forgetting
- Replay-based continual learning
- Knowledge distillation
- Geometric representation analysis
- Multi-seed evaluation
- Ablation studies
- Reproducible experimentation
- Failure-mode analysis

### COVID-19 Vaccine Misinformation NLP

First-author research on detecting COVID-19 vaccine conspiracy and misinformation content.

- BERT-based NLP experimentation
- Manually labeled social-media dataset
- Google Perspective API signals
- Content-quality and misinformation analysis
- Public dataset release through Hugging Face

[Hugging Face Dataset](https://huggingface.co/datasets/AminHasibul/covid-vaccine-conspiracy) ·
[arXiv Paper](https://arxiv.org/abs/2211.13003)

---

## Technical Expertise

**Languages:**  
Python, C#, F#, C++, Java, JavaScript, SQL

**Backend & Distributed Systems:**  
Kafka, CDC, Microservices, CQRS, REST APIs, Event-Driven Architecture, Workflow Orchestration, Multi-Tenant Systems, Idempotency, Retry/DLQ, High Availability, System Design

**Cloud & Platform:**  
AWS, Azure, Kubernetes, Docker, Terraform/Terragrunt, Bicep, Lambda, Azure Functions, CI/CD

**Data & Observability:**  
PostgreSQL, Oracle, SQL Server, MongoDB, Redis, OpenTelemetry, Distributed Tracing, Structured Logging, Incident Response, RCA

**AI/ML & Search:**  
PyTorch, TensorFlow, Continual Learning, NLP, BERT, LLMs, RAG, Model Evaluation, Information Retrieval, Trie, Inverted Index, Spatial Hashing, Fuzzy Matching, OpenCV

**AI-Assisted Development:**  
Claude Code, GitHub Copilot, MCP workflows

---

## Selected Publications

### 2027 — Under Review

**Residual Stream Rebalancing: Training-Free Hallucination Mitigation in Vision-Language Models**  
*Niamul Hassan Samin, Md Hasibul Amin, et al.*  
WACV 2027 — Under Review  
[OpenReview](https://openreview.net/forum?id=Cl0TWcT3wn)

**When Detector-Based Grounding Metrics Measure Vocabulary: A Cautionary Audit of Entity Claims in Video-QA Reasoning Traces**  
*Md Ashikur Rahman, Md Hasibul Amin, et al.*  
WACV 2027 — Under Review  
[OpenReview](https://openreview.net/forum?id=rJFxezNBiu)

### 2026

**Boundary-Aware Deep Learning Framework for Breast Cancer Image Segmentation: Enhancing Tumor Delineation Through BIOU-Driven Evaluation**  
IEEE CICN 2026  
[IEEE Xplore](https://ieeexplore.ieee.org/document/11594147)

**Evaluating Parameter-Efficient Fine-Tuning of Open-Weight LLMs for Medical Question Answering**  
IEEE CICN 2026  
[IEEE Xplore](https://ieeexplore.ieee.org/document/11594337)

**Multilingual Financial Fraud Detection Using Machine Learning and Transformer Models: A Bangla-English Study**  
IEEE CICN 2026  
[IEEE Xplore](https://ieeexplore.ieee.org/document/11594250)

### Preprints

**Failure Modes of Always-On Inter-Cluster Repulsion in Replay-Based Continual Learning**  
Md Hasibul Amin, Tamzid Tanvi Alam  
[arXiv](https://arxiv.org/abs/2510.07648) ·
[GitHub](https://github.com/AminHasibul/Continual-Learning-UsingInterClusterDistance)

**Detecting Conspiracy Theory Against COVID-19 Vaccines**  
Md Hasibul Amin, et al.  
[arXiv](https://arxiv.org/abs/2211.13003) ·
[Dataset](https://huggingface.co/datasets/AminHasibul/covid-vaccine-conspiracy)

---

## Professional Service

- **Technical Program Committee Member**, IEEE CICN 2026
- **Peer Reviewer**, PLOS ONE

---

## Education

### Master of Science in Computer Science
**University of Houston** · 2023

Relevant areas: Machine Learning, Deep Learning, NLP, Cloud Computing, Digital Image Processing

### Bachelor of Science in Computer Science and Engineering
**American International University-Bangladesh (AIUB)** · 2015

Relevant areas: Algorithms, Data Structures, OOP, C++, C#, Java

---

## Contact

**Email:** [hasibulamin.cse@gmail.com](mailto:hasibulamin.cse@gmail.com)  
**Location:** Houston, TX, USA

Open to opportunities and collaborations in distributed systems, cloud infrastructure, AI infrastructure, continual learning, model reliability, and applied AI research.

---

*Last updated: October 2026*
