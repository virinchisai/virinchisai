<div align="center">

# Virinchi Sai Athmakuri

### GenAI and AI Security Engineer

Building secure RAG systems, agentic AI workflows, and cloud-native ML platforms

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/virinchisaiathmakuri/)
[![Email](https://img.shields.io/badge/Email-saivirinchi103%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saivirinchi103@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-virinchisai-181717?style=for-the-badge&logo=github)](https://github.com/virinchisai)

New York, USA | Open to relocation

</div>

## About Me

I am an AI/ML and cloud engineer focused on building secure, production-minded
GenAI systems. My work spans retrieval-augmented generation, LLM security,
adversarial machine learning, cloud observability, and event-driven security
platforms.

At SUNY Polytechnic Institute, I work on applied AI research involving RAG,
secure inference, deep learning, and adversarial robustness for
cybersecurity-focused applications. I enjoy taking ideas from architecture to a
working system: APIs, retrieval pipelines, model integration, evaluation,
containerization, observability, and security controls.

**Current interests:** secure enterprise AI, agentic workflows on the Model
Context Protocol (MCP), AI red teaming, LLM evaluation, cybersecurity
automation, and scalable MLOps.

## Featured Projects

### [SentinelAI — Secure Enterprise AI Workspace](https://github.com/virinchisai/sentinel-ai)

A self-hostable agent platform that securely connects employees to internal
knowledge, code, email, calendar, and operational tools — built on the
Model Context Protocol (MCP).

- Built a FastAPI gateway with JWT authentication, RBAC, bcrypt password
  hashing, password-strength policy, rate limiting, token revocation, and a
  full audit log.
- Implemented a planner-driven agent loop with retry, structured tool traces,
  human-approval gating on destructive actions, and a provider-agnostic LLM
  layer (Anthropic and OpenAI).
- Shipped 18 MCP tools across 7 connectors: GitHub, Gmail, Calendar,
  sandboxed File System, read-only PostgreSQL, RAG knowledge base, and system
  tools.
- Added RAG over Markdown and PDF docs with heading-aware chunking,
  citations, and Chroma or PGVector backends.
- Built a Next.js 14 frontend (login, chat with tool-call viewer, document
  upload, settings) and one-click Codespaces support for cloud demos.
- Hardened with HSTS, CSP, X-Frame-Options, CodeQL SAST, Dependabot, 16
  security regression tests, and a published SECURITY.md threat model.
- Containerized for Docker Compose and Kubernetes with Prometheus metrics
  and structured logging.

`Python` `FastAPI` `Next.js` `MCP` `JWT` `RBAC` `RAG` `Chroma` `PGVector` `Anthropic` `OpenAI` `Docker` `Kubernetes` `Prometheus` `CodeQL`

### [SecureAI SOC Copilot](https://github.com/virinchisai/secureai-soc-copilot)

A local-first RAG assistant for investigating cybersecurity logs and reports.

- Built a FastAPI and Streamlit application with JWT-protected upload and chat
  workflows.
- Supports PDF, TXT, and LOG ingestion, recursive chunking, per-user FAISS
  indexes, and grounded answers with source citations.
- Includes Ollama, OpenAI, and Claude provider options, prompt-injection
  detection, SHA-256 file metadata, and SQLite audit logging.
- Added Docker Compose, automated tests, GitHub Actions, CodeQL, Dependabot,
  secret-scanning guidance, and an MIT license.

`Python` `FastAPI` `Streamlit` `LangChain` `FAISS` `Ollama` `OpenAI` `Claude` `Docker`

### [Secure Agentic CloudOps SIEM Platform](https://github.com/virinchisai/secure-agentic-cloudops-siem-platform)

An event-driven security and CloudOps platform for log ingestion, streaming,
detection, and alert persistence.

- Designed a decoupled pipeline using FastAPI, Redpanda/Kafka, detection
  services, and PostgreSQL.
- Implemented normalized event ingestion, streaming detection, scored alerts,
  and end-to-end local validation.
- Documented a roadmap for contextual retrieval, agentic reasoning, automated
  remediation, observability, and secure cloud deployment.

`Python` `FastAPI` `Redpanda` `Kafka` `PostgreSQL` `Docker`

### [AI Virtual Mouse](https://github.com/virinchisai/Ai-Virtual-Mouse)

A computer-vision interface that uses hand landmarks and gesture recognition
for real-time cursor control.

`Python` `OpenCV` `MediaPipe` `Computer Vision`

## Technical Focus

| Area | Technologies |
| --- | --- |
| GenAI and LLM systems | RAG, LangChain, LlamaIndex, embeddings, vLLM, LoRA/QLoRA, PEFT, function calling, prompt engineering |
| Machine learning | PyTorch, TensorFlow, scikit-learn, CNN-LSTM, autoencoders, transfer learning, adversarial ML |
| Backend and data | Python, FastAPI, Flask, SQL, PostgreSQL, PGVector, Kafka, Airflow |
| Cloud and MLOps | AWS, GCP, Docker, Kubernetes, Terraform, MLflow, Kubeflow, GitHub Actions, Jenkins |
| Security and observability | LLM red teaming, prompt-injection testing, RBAC, Splunk, ELK, Prometheus, Grafana, Snort, Suricata |

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=virinchisai&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=22D3EE&icon_color=22D3EE" height="165" alt="Virinchi Sai's GitHub stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=virinchisai&theme=tokyonight&hide_border=true&background=0D1117&ring=22D3EE&fire=F97316&currStreakLabel=22D3EE" height="165" alt="Virinchi Sai's GitHub streak" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=virinchisai&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=22D3EE" height="150" alt="Virinchi Sai's top languages" />

### Contribution Game

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/virinchisai/virinchisai/output/pacman-contribution-graph-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/virinchisai/virinchisai/output/pacman-contribution-graph.svg" />
  <img alt="Pac-Man contribution graph animation" src="https://raw.githubusercontent.com/virinchisai/virinchisai/output/pacman-contribution-graph.svg" />
</picture>

</div>

## Experience Highlights

**GenAI Engineer, SUNY Polytechnic Institute**

*January 2026 - Present*

- Developing applied AI systems for contextual retrieval, summarization, and
  grounded question answering using LangChain, LlamaIndex, FastAPI, and
  PostgreSQL/PGVector.
- Building reproducible ML and deep-learning workflows for secure AI and
  cybersecurity research.

**GenAI Systems Research Engineer, SUNY Polytechnic Institute**

*July 2025 - December 2025*

- Built a secure offline LLM platform for privacy-sensitive environments using
  OpenWebUI, RAG, FastAPI, and local model serving.
- Evaluated prompt injection, jailbreak, and red-team attacks and contributed
  to secure API, network, encryption, and containerization strategies.

**Data and Cloud Engineer, ConnX AI**

*April 2023 - July 2023*

- Automated cloud observability and operational diagnostics using Python,
  Prometheus, Grafana, Nagios, Zabbix, and AWS CloudWatch.
- Developed real-time log analytics, anomaly detection, IP reputation, routing
  diagnostics, and containerized CI/CD workflows.

## Research and Publications

- **Video and Audio Deepfake Datasets and Open Issues in Deepfake Technology**
  - *Forensic Sciences, 2024*
- **Design and Implementation of an AI Virtual Mouse Using Hand Gesture
  Recognition**
  - *Volume 14, Number 1, March 2024*
- **An Intelligent Way to Recognize Digits Using Convolutional Neural Networks**
- **Scarlett: Virtual Assistant and Browlett Browser**
- **Tachyon: Bike Rentals Made Easy**

My deepfake-audio research included a survey of more than 30 studies covering
datasets, detection methods, and open challenges in forensic AI.

## Education and Certifications

- **M.S., Network and Computer Security** - SUNY Polytechnic Institute
- **B.E., Computer Science** - Methodist Engineering College
- **CompTIA Security+ (SY0-701)**
- **AWS Academy Cloud Foundations**
- **Google Cloud Ready Facilitator**
- **Cisco DevNet, Cybersecurity, and Networking Essentials**

## What I Am Building Toward

I am interested in engineering roles where AI quality, security, and systems
design matter together. I am especially excited by work involving enterprise
RAG, AI agents, model evaluation, AI security, cybersecurity automation, and
cloud-native ML platforms.

For collaboration or opportunities, reach me at
[saivirinchi103@gmail.com](mailto:saivirinchi103@gmail.com) or connect on
[LinkedIn](https://www.linkedin.com/in/virinchisaiathmakuri/).
