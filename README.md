<div align="center">

# Agentic AI Engineering — From Foundations to Production

### A 12-Week Open Curriculum for Senior Agentic AI Engineers

*A structured, opinionated, project-driven path from Python foundations through production multi-agent systems on Kubernetes.*

[![Curriculum](https://img.shields.io/badge/Curriculum-12_Weeks-9333ea?style=for-the-badge&labelColor=000000)](#curriculum)
[![Capstone](https://img.shields.io/badge/Capstone-AgentForge-e91e8c?style=for-the-badge&labelColor=000000)](#capstone)
[![Hours](https://img.shields.io/badge/Estimated_Hours-390-22d3ee?style=for-the-badge&labelColor=000000)](#curriculum)
[![License](https://img.shields.io/badge/License-MIT-fbbf24?style=for-the-badge&labelColor=000000)](LICENSE)

[**Curriculum**](#-curriculum) ·
[**Capstone**](#-capstone-agentforge) ·
[**Resources**](#-curated-resources) ·
[**Methodology**](#-methodology) ·
[**Author**](#-author)

</div>

---

## 🎯 Why This Curriculum Exists

Most "Agentic AI" learning content in 2026 falls into one of two failure modes:

1. **Surface-level demos** that wire up LangChain in 50 lines and call it production-ready
2. **Theory-heavy academic courses** that never touch Kubernetes, observability, evaluation, or red-teaming

Neither prepares an engineer for the Senior Agentic AI Engineer role at the $130K+ remote tier. The role demands fluency across **the full stack** — modern Python internals, transformer architecture, retrieval systems, agentic orchestration patterns, production infrastructure, and rigorous evaluation discipline.

This is a 12-week, **opinionated**, **resource-curated**, **project-driven** curriculum that closes that gap. The methodology is explicit. The resources are verified. The endpoint is a deployable, observable, evaluated agentic AI capstone in production.

This curriculum is for:

- Working engineers transitioning into Agentic AI Engineering
- Senior engineers with LLM-mediated workflows who want to re-ground their foundations
- Self-taught learners who need a structured curriculum with verified resources
- Students and career-switchers targeting senior remote roles in 2026

---

## 🧭 Curriculum Overview

The curriculum runs **12 weeks of structured learning** plus **2 weeks of interview preparation and applications**. Each phase builds strictly on the previous — no skipping forward.

```
Phase 1  ▸  Foundations          Weeks 1–3   ▸  Python: basics → intermediate → advanced + Pydantic v2
Phase 2  ▸  LLMs & Transformers  Weeks 4–5   ▸  PyTorch essentials → Karpathy GPT → Hugging Face ecosystem
Phase 3  ▸  Retrieval (RAG)      Weeks 6–7   ▸  Chunking, hybrid search, reranking, RAGAS evaluation
Phase 4  ▸  Agentic AI           Weeks 8–9   ▸  LangChain LCEL → LangGraph (supervisor, HITL, subgraphs)
Phase 5  ▸  Production Infra     Weeks 10–11 ▸  FastAPI, Docker, Kubernetes, GitHub Actions, Cloud
Phase 6  ▸  Advanced Integration Week 12     ▸  MCP, multi-agent, evals, LLMOps, distributed systems
Job Prep ▸  Interview Readiness  Weeks 13–14 ▸  System design rehearsal, applications, networking
```

**Total committed time:** approximately **390 hours** over 12 weeks at 25–35 hours per week.

### Pedagogical Principles

- **One topic at a time** — no parallel-processing across phases
- **Beginner → Intermediate → Advanced subtopic decomposition** — every concept broken into three difficulty tiers
- **One verified resource per subtopic** — no shopping for tutorials, no "alternatively try X"
- **"Watched and understood" vs "Can do without looking" checklists** — separating passive consumption from active mastery
- **3–5 self-test drills per subtopic** — solved without notes, without LLM autocomplete
- **Phase-end gates** — pass-or-redo checkpoints that prevent advancing on shaky foundations
- **Forward-dependency mapping** — every subtopic explicitly states what later weeks will fail if it is skipped

---

## 📚 Curriculum

### Phase 1: Foundations · Weeks 1–3

**Objective:** Build unshakeable Python foundations that support every framework introduced in later phases.

| Week | Theme | Primary Topic | Secondary Topic |
| ---- | ----- | ------------- | --------------- |
| 1 | Python Basics | Variables, types, control flow, functions, files, errors | Reading Python code fluently |
| 2 | Python Intermediate | OOP, comprehensions, advanced functions | Virtual environments, packaging, modern tooling (uv, ruff) |
| 3 | Python Advanced + Pydantic v2 | Decorators, generators, async/await, context managers | Pydantic v2, advanced type hints (TypeVar, Protocol, ParamSpec) |

**Phase 1 Gate.** Live mock conversation testing async, decorators, OOP, type hints, and error handling. From-scratch typed async API client built in 2 hours. Written reflection. Job-description calibration against 3 real Senior Agentic AI Engineer postings.

### Phase 2: LLMs & Transformers · Weeks 4–5

**Objective:** Move from black-box LLM API consumer to engineer who understands the architecture under the hood.

| Week | Theme | Primary Topic | Secondary Topic |
| ---- | ----- | ------------- | --------------- |
| 4 | PyTorch Essentials | Tensors, autograd, training loops (compressed) | High-level transformer concepts (attention, encoder-decoder) |
| 5 | Karpathy GPT + Hugging Face | nanoGPT from scratch (Karpathy) | Hugging Face transformers, fine-tuning, prompt patterns |

**Phase 2 Gate.** Whiteboard explanation of attention mechanism. Implement self-attention from scratch in 60 minutes without references. Published fine-tuned classifier on Hugging Face Hub.

### Phase 3: Retrieval (RAG) · Weeks 6–7 — *Capstone begins*

**Objective:** Build production-grade retrieval systems with rigorous evaluation discipline.

| Week | Theme | Primary Topic | Secondary Topic |
| ---- | ----- | ------------- | --------------- |
| 6 | RAG Fundamentals | Chunking, embeddings, vector similarity, FAISS / Chroma | PDF and document processing |
| 7 | Production RAG | Hybrid retrieval (BM25 + dense), reranking, RAGAS evaluation | LlamaIndex pipelines |

**Phase 3 Gate.** Defend every architectural choice in a recorded walkthrough. Build a working RAG pipeline over an unseen document set in 2 hours. First mid-roadmap job-description calibration: target 30–40% match against senior postings.

### Phase 4: Agentic AI · Weeks 8–9

**Objective:** Master the agentic patterns that distinguish senior engineers in 2026 hiring loops.

| Week | Theme | Primary Topic | Secondary Topic |
| ---- | ----- | ------------- | --------------- |
| 8 | LangChain + LangGraph Basics | LCEL, Runnables, tool calling, structured outputs | Pydantic schemas for agent I/O |
| 9 | LangGraph Advanced | StateGraph, persistence, HITL with `interrupt()`, supervisor patterns, subgraphs, `Send()` fan-out | LangSmith debugging and tracing |

**Phase 4 Gate.** Senior-level mock conversation explaining supervisor vs. swarm vs. hierarchical patterns. Design a multi-agent workflow for a novel domain in 90 minutes. Job-description calibration: target 50–60% match.

### Phase 5: Production Infrastructure · Weeks 10–11

**Objective:** Ship the capstone to a real cloud cluster with real CI/CD and real observability.

| Week | Theme | Primary Topic | Secondary Topic |
| ---- | ----- | ------------- | --------------- |
| 10 | FastAPI for Async LLM APIs | Async routes, dependency injection, JWT, rate limiting, SSE/WebSocket streaming | Pytest for API testing |
| 11 | Docker, Kubernetes, CI/CD | Dockerfiles, multi-stage builds, K8s manifests, ingress | GitHub Actions workflows, AWS/GCP free tier |

**Phase 5 Gate.** Whiteboard the production architecture for the capstone from scratch. Containerize a novel Python application and deploy to Kubernetes in 90 minutes. Job-description calibration: target 70–80% match.

### Phase 6: Advanced Integration · Week 12

**Objective:** Connect every previous phase into one production-grade artifact and stress-test for senior interviews.

| Sub-topic | Resource |
| --------- | -------- |
| Model Context Protocol (MCP) | Anthropic Academy: Introduction to MCP |
| Multi-agent (CrewAI) | DeepLearning.AI: Multi AI Agent Systems with crewAI |
| Red-teaming + evaluations | DeepLearning.AI: Red Teaming LLM Applications |
| LLMOps + system design | Chip Huyen: *Designing Machine Learning Systems* (selected chapters) |
| Mock system design | Hello Interview AI/ML system design library |

**Phase 6 Gate.** Two-hour full mock interview loop (technical + system design + behavioral). Capstone live demo runs flawlessly. `ARCHITECTURE.md` reads like senior engineering work. Job-description calibration: target 85%+ match.

### Job Preparation · Weeks 13–14

| Week | Focus |
| ---- | ----- |
| 13 | Mock system design interviews, LeetCode mediums (graphs, strings, BFS/DFS), STAR-format behavioral stories, resume polish, application infrastructure setup |
| 14 | High-quality applications (10/week), targeted networking, 1 PR/week to a major OSS framework, lightning-talk submissions |

---

## 🚀 Capstone: AgentForge

The capstone is **AgentForge** — an enterprise-grade multi-agent research platform built incrementally from Week 6 through Week 12.

### Architectural Increments

```
Week 6   ▸  Single-tenant naive RAG over arXiv ML papers (CLI)
Week 7   ▸  Hybrid retrieval, cross-encoder reranking, RAGAS evaluation suite
Week 8   ▸  LCEL refactor, structured outputs, tool calling, initial LangGraph
Week 9   ▸  Full LangGraph state machine: critic loop, HITL, supervisor pattern, streaming
Week 10  ▸  FastAPI service: JWT auth, rate limiting, SSE streaming, Pydantic everywhere
Week 11  ▸  Multi-stage Dockerfile, Kubernetes manifests, GitHub Actions CI/CD
Week 12  ▸  MCP server, CrewAI deep-research subgraph, red-team report,
            Langfuse observability, vLLM self-hosted fallback, Redis semantic cache,
            ARCHITECTURE.md system design document, 5-minute Loom walkthrough
```

### Final-State Specification

By the end of Week 12, AgentForge meets the following acceptance criteria:

- **Public GitHub repository** with clean weekly commit history and comprehensive README
- **Live demo URL** deployed to a managed Kubernetes cluster
- **Public Langfuse dashboard** with real production traces
- **`ARCHITECTURE.md`** — 2,000-word system design document with Mermaid diagrams, latency analysis, cost analysis, and a scaling plan to 10,000 requests per minute
- **5-minute Loom walkthrough** demonstrating end-to-end functionality
- **RAGAS evaluation report** on a 30-question gold dataset with documented thresholds
- **Red-team report** with 20+ adversarial prompts and documented mitigations

This single artifact replaces a portfolio of five mediocre projects. It demonstrates the entire production agentic AI lifecycle.

---

## 📖 Curated Resources

The curriculum's central design principle is **one verified resource per subtopic**. The table below summarizes the spine.

| Phase | Resource | Author | Format | Cost |
| ----- | -------- | ------ | ------ | ---- |
| 1 | Python for Everybody | Dr. Charles Severance | Book + video | Free |
| 1 | Real Python (decorators, async) | Real Python team | Long-form articles | Free |
| 1 | mypy cheat sheet | mypy maintainers | Reference | Free |
| 1 | Pydantic v2 docs | Pydantic team | Official documentation | Free |
| 2 | Learn PyTorch for Deep Learning | Daniel Bourke | Interactive book + video | Free |
| 2 | Neural Networks: Zero to Hero | Andrej Karpathy | Video + GitHub | Free |
| 2 | Hugging Face LLM Course | Hugging Face team | Interactive course | Free |
| 3 | Retrieval Augmented Generation | Zain Hasan (DeepLearning.AI) | Video + Jupyter labs | Free to audit |
| 3 | Building Agentic RAG with LlamaIndex | Jerry Liu | Video + Jupyter labs | Free |
| 3 | RAGAS official documentation | RAGAS team | Documentation | Free |
| 4 | LangChain Academy | LangChain team | Video + notebooks | Free |
| 4 | LangGraph official documentation | LangChain team | Documentation | Free |
| 5 | FastAPI: The Complete Course 2026 | Eric Roby & Chad Darby | Video | ~$15 |
| 5 | Docker / Kubernetes Tutorial | Nana Janashia (TechWorld with Nana) | Video | Free |
| 6 | Introduction to Model Context Protocol | Anthropic | Video + labs | Free |
| 6 | Multi AI Agent Systems with crewAI | João Moura (DeepLearning.AI) | Video + labs | Free |
| 6 | Red Teaming LLM Applications | Giskard team (DeepLearning.AI) | Video + labs | Free |
| 6 | *Designing Machine Learning Systems* | Chip Huyen | Book | ~$45 |

**Total estimated paid resources:** approximately **$140 USD** including API credits and cloud hosting.

---

## 🛡️ Methodology

This curriculum is engineered around **18 explicit anti-failure layers**, each designed to prevent a known failure mode of self-directed learning.

<details>
<summary><b>Resource integrity (3 layers)</b></summary>

- **L1** — Resource freshness audit. Every URL verified live; content-currency dated.
- **L2** — Backup resource per subtopic. No single point of failure.
- **L3** — Smell-test warnings. Known weaknesses of any resource are flagged before consumption.

</details>

<details>
<summary><b>False-fluency prevention (3 layers)</b></summary>

- **L4** — Two-tier completion checklists. *Watched and understood* is separated from *can do without looking*.
- **L5** — 3–5 self-test drills per subtopic. Solved without notes, without LLM autocomplete.
- **L6** — Rubber-duck recordings. 60-second voice memos explaining concepts. Listen back. Re-record if confused.

</details>

<details>
<summary><b>Drift prevention (3 layers)</b></summary>

- **L7** — Weekly interview-readiness probe. Five 200-word answers, scored 0–2.
- **L8** — Phase-end gates. Mock conversation + from-scratch build + reflection. Pass or redo.
- **L9** — Forward-dependency map. Every subtopic states what later weeks will break if skipped.

</details>

<details>
<summary><b>Endpoint calibration (3 layers)</b></summary>

- **L13** — Monthly job-description gradient calibration. Five real postings; honest match percentage.
- **L14** — Senior-engineer day-in-the-life research at end of Phase 3.
- **L15** — Pre-committed kill criteria. Defined remediation triggers for falling behind.

</details>

<details>
<summary><b>Author-failure prevention (3 layers)</b></summary>

- **L16** — Adversarial review per phase. Devil's-advocate version of every plan.
- **L17** — Confidence ratings (High / Medium / Low) on every recommendation.
- **L18** — Domain-knowledge override. Production knowledge wins over curriculum recommendation when they conflict.

</details>

<details>
<summary><b>Visibility & isolation prevention (3 layers)</b></summary>

- **L10** — Public commitment via this repository. Phase-end deliverables are committed publicly.
- **L11** — One human conversation per week with a working engineer. Real check against blind spots.
- **L12** — Weekly 3-minute Loom video explaining the week's code. Surfaces shaky understanding immediately.

</details>

These layers are operational, not aspirational. Failure to honor them invalidates the curriculum's claims and triggers gate remediation.

---

## 🗂️ Repository Structure

```
agentic-ai/
├── README.md                          # This document
├── LICENSE                            # MIT
├── phase-1-foundations/
│   ├── week-01/                       # Python basics
│   ├── week-02/                       # Python intermediate
│   └── week-03/                       # Python advanced + Pydantic
├── phase-2-llms/
│   ├── week-04/
│   └── week-05/
├── phase-3-rag/
│   ├── week-06/
│   └── week-07/
├── phase-4-agentic-ai/
│   ├── week-08/
│   └── week-09/
├── phase-5-production/
│   ├── week-10/
│   └── week-11/
├── phase-6-advanced/
│   └── week-12/
├── capstone/                          # AgentForge — see capstone/README.md
└── docs/
    ├── METHODOLOGY.md                 # Detailed pedagogical principles
    └── RESOURCES.md                   # Full curated resource list
```

---

## 🤝 Contributing

The most valuable contributions are:

- **Verified resource updates.** If a linked resource breaks, becomes outdated, or is superseded by a better alternative, open an issue.
- **Curriculum corrections.** If a recommendation is technically inaccurate or pedagogically suboptimal, open an issue with reasoning.
- **Implementation forks.** If you walk this path, document your version of each phase and link your fork in the discussions.

Pull requests should reference an issue and explain the reasoning, not just the change.

---

## 📜 License

This curriculum is licensed under the **MIT License**. Free to use, fork, and adapt — including for paid teaching, corporate training, and commercial cohort programs. Attribution is appreciated but not required.

---

## 👤 Author

**Akash Chaudhari**

Agentic AI Engineer · Building Production Multi-Agent Systems · Open to Senior Remote Roles

> *"Most senior agentic AI engineers in 2026 can use LangChain. Few can explain async internals when an agent deadlocks at 100 concurrent users. This curriculum prioritizes depth over speed."*

**Background.** Agentic AI Engineer at Deloitte South Asia LLP (Assistant Manager, Data Scientist GenAI). Previously a PC GenAI Analyst at the Government of Maharashtra (3.5 years). Currently pursuing an MS in AI & Cybersecurity at IIT Patna.

**Production work.** Multi-agent LangGraph orchestration at enterprise scale. RAG systems with hybrid retrieval and reranking. MCP protocol implementations. HITL workflow design. Azure OpenAI on Kubernetes AKS.

**Connect.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-akash1512-0a66c2?style=flat-square&logo=linkedin&logoColor=white&labelColor=000000)](https://linkedin.com/in/akash1512)
[![Portfolio](https://img.shields.io/badge/Portfolio-ai--akash.netlify.app-9333ea?style=flat-square&logo=googlechrome&logoColor=white&labelColor=000000)](https://ai-akash.netlify.app)
[![Email](https://img.shields.io/badge/Email-ag.chaudhari.1512-e91e8c?style=flat-square&logo=gmail&logoColor=white&labelColor=000000)](mailto:ag.chaudhari.1512@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Akash--1512-22d3ee?style=flat-square&logo=github&logoColor=white&labelColor=000000)](https://github.com/Akash-1512)

---

<div align="center">

**If this curriculum helps you, star the repository so others walking the same path can find it.**

⭐ **Star** · 🍴 **Fork** · 👀 **Watch**

*Mumbai, India · 2026*

</div>