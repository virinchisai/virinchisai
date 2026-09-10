<div align="center">

# Virinchi Sai Athmakuri

### GenAI and AI Security Engineer

Building AI agents, evidence-backed RAG systems, and tools for AI reliability

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/virinchisaiathmakuri/)
[![Email](https://img.shields.io/badge/Email-saivirinchi103%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saivirinchi103@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-virinchisai-181717?style=for-the-badge&logo=github)](https://github.com/virinchisai)

New York, USA | Open to relocation

</div>

## About Me

I am an AI/ML and cloud engineer focused on making AI systems useful,
inspectable, and secure. My projects span MCP agents, retrieval-augmented
generation, knowledge validation, test automation, and adversarial audio ML.

At SUNY Polytechnic Institute, I work on applied AI research involving RAG,
secure inference, deep learning, and adversarial robustness for
cybersecurity-focused applications. Across my public projects, I connect
working applications with source provenance, explicit permissions, evaluation,
and reproducible evidence.

**Current interests:** local AI, agentic workflows on the Model Context
Protocol (MCP), RAG evaluation, AI red teaming, knowledge reliability,
cybersecurity automation, and MLOps.

## Featured Projects

### [SentinelAI — Secure Enterprise AI Workspace](https://github.com/virinchisai/sentinel-ai)

A self-hostable AI workspace for document investigation and approved actions
across connected tools. The current v2 release targets a small-team pilot.

- Built local Ollama inference, streamed responses, persistent conversations,
  and MCP tool execution with inspectable traces.
- Added workspace-scoped retrieval, document previews and versioning, durable
  ingestion jobs, and optional hybrid search with PostgreSQL/pgvector.
- Implemented exact, expiring action approvals, encrypted per-user connector
  credentials, JWT/RBAC, and audit records.

[Architecture](https://github.com/virinchisai/sentinel-ai/blob/main/docs/architecture.md)
· [v2 validation evidence](https://github.com/virinchisai/sentinel-ai/blob/main/docs/release-validation.md)

`Python` `FastAPI` `Next.js` `MCP` `Ollama` `PostgreSQL` `pgvector` `Docker`

### [AmendLens — Financial Evidence Workspace](https://github.com/virinchisai/amendlens)

A local application for tracing financial figures to source documents and
seeing how corrections change a report.

- Built document import, source quotes, human fact review, and deterministic
  financial calculations using Python Decimal.
- Preserved dated report snapshots and source hashes so comparisons distinguish
  changed values from changed supporting evidence.
- Added cited retrieval with optional local Ollama inference, SQLite
  persistence, and Markdown/JSON exports.

[Demo walkthrough](https://github.com/virinchisai/amendlens/blob/main/demo/walkthrough.mp4)
· [Release scope and validation](https://github.com/virinchisai/amendlens/blob/main/STATUS.md)

`Python` `SQLite` `JavaScript` `Ollama` `Document Processing` `Source Provenance`

### [Knowledge Reliability CI](https://github.com/virinchisai/knowledge-reliability-ci)

A model-independent quality gate for knowledge before it reaches RAG systems
and AI agents.

- Implemented deterministic checks for stale, unsupported, contradictory, and
  improperly classified claims, plus common prompt-injection indicators.
- Added SHA-256 source-drift checks, knowledge regression tests, and
  source-to-claim impact analysis.
- Exported SARIF findings, a Knowledge Bill of Materials (KBOM), and portable
  Markdown bundles using a Python standard-library core.

[Architecture](https://github.com/virinchisai/knowledge-reliability-ci/blob/main/docs/ARCHITECTURE.md)
· [Seeded benchmark and limits](https://github.com/virinchisai/knowledge-reliability-ci/blob/main/docs/BENCHMARK.md)

`Python` `GitHub Actions` `SARIF` `SHA-256` `Knowledge Validation`

### [QualityPilot — TestOps and Release Evidence](https://github.com/virinchisai/QualityPilot)

A local testing platform connecting requirements, automated checks, execution
evidence, and release decisions.

- Converts requirements into structured test cases and Gherkin with traceability
  back to the original requirement.
- Exercises a JWT/RBAC demo application through API, browser, BDD, security,
  and accessibility checks.
- Records test history and artifacts, analyzes failures and likely flaky tests,
  and applies configurable release gates. Optional Ollama summaries support
  the deterministic analysis.

[Demo](https://github.com/virinchisai/QualityPilot/blob/master/docs/assets/qualitypilot-demo.gif)
· [Architecture](https://github.com/virinchisai/QualityPilot/blob/master/ARCHITECTURE.md)

`Python` `FastAPI` `Streamlit` `pytest` `Playwright` `Behave` `SQLite`

### [GhostPrint — Voice Disguise Research](https://github.com/virinchisai/ghostprint)

An experimental speaker re-identification project studying whether prosody and
rhythm complement conventional voiceprints under simulated voice disguise.

- Built a PyTorch BiGRU prosody encoder and compared it with ECAPA voiceprints
  and score fusion on held-out LibriSpeech speakers.
- Evaluated pitch, formant, and tempo transformations with rank-1 identification
  and equal-error-rate measurements.
- Published result tables and a formant sweep, including the limits of weak
  standalone prosody accuracy and simulated attacks.

[Results and figures](https://github.com/virinchisai/ghostprint/blob/main/RESULTS.md)
· [Project guide](https://github.com/virinchisai/ghostprint/blob/main/PROJECT_GUIDE.md)

`Python` `PyTorch` `SpeechBrain` `BiGRU` `Audio ML` `Adversarial Evaluation`

### [SecureAI SOC Copilot](https://github.com/virinchisai/secureai-soc-copilot)

A local-first RAG assistant for asking evidence-backed questions over
cybersecurity logs and reports.

- Built PDF/TXT/LOG ingestion, per-user FAISS indexes, and answers with
  citations and the exact retrieved source excerpts.
- Added JWT-protected workflows, file hashes, SQLite audit records,
  authenticated system status, and CSV audit export.
- Supports local Ollama or hosted providers, Docker Compose, and automated
  checks. The MVP uses a demo account and a basic phrase-based injection guard.

[Setup and demo flow](https://github.com/virinchisai/secureai-soc-copilot#demo-flow)

`Python` `FastAPI` `Streamlit` `LangChain` `FAISS` `Ollama` `Docker`

## Technical Focus

| Area | Technologies |
| --- | --- |
| GenAI and LLM systems | MCP, RAG, LangChain, Ollama, OpenAI/Anthropic adapters, tool calling, hybrid retrieval |
| Machine learning and research | PyTorch, TensorFlow/Keras, SpeechBrain, BiGRU, CNNs, OpenCV, MediaPipe, adversarial evaluation |
| Backend and data | Python, FastAPI, Flask, Node.js, PostgreSQL, pgvector, SQLite, FAISS, Kafka/Redpanda |
| Interfaces and delivery | Next.js, React, TypeScript, JavaScript, Streamlit, Docker Compose, GitHub Actions |
| Quality and reliability | pytest, Playwright, Behave, Gherkin, SARIF, release gates, source provenance, knowledge regression tests |
| Security and observability | JWT, RBAC, action approvals, prompt-injection indicators, audit logging, CodeQL, Prometheus, Grafana |

## GitHub Arcade

<div align="center">

### Mission Control

<img src="https://github-readme-stats.vercel.app/api?username=virinchisai&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF4ECD&text_color=E5F7FF&icon_color=FFE66D" height="165" alt="Virinchi Sai's GitHub stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=virinchisai&theme=radical&hide_border=true&background=0D1117&ring=FF4ECD&fire=FFE66D&currStreakLabel=00F5D4&sideNums=FFE66D&sideLabels=E5F7FF&dates=A78BFA" height="165" alt="Virinchi Sai's GitHub streak" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=virinchisai&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00F5D4&text_color=E5F7FF" height="150" alt="Virinchi Sai's top languages" />

### Build Dashboard

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=virinchisai&theme=dracula" alt="GitHub profile summary" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=virinchisai&theme=dracula" height="180" alt="Repositories per language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=virinchisai&theme=dracula" height="180" alt="Most committed languages" />

### Pac-Man Contribution Run

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/virinchisai/virinchisai/output/pacman-contribution-graph-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/virinchisai/virinchisai/output/pacman-contribution-graph.svg" />
  <img alt="Pac-Man contribution graph animation" src="https://raw.githubusercontent.com/virinchisai/virinchisai/output/pacman-contribution-graph.svg" />
</picture>

### Activity Radar

<img src="https://github-readme-activity-graph.vercel.app/graph?username=virinchisai&theme=react-dark&hide_border=true&bg_color=0D1117&color=FF4ECD&line=00F5D4&point=FFE66D&area=true&area_color=7C3AED" alt="GitHub activity graph" />

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

