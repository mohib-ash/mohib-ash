# Mohib Ashfaq Butt

### Backend & AI Engineer

I build **production-oriented AI systems**, with a focus on backend architecture, RAG, LLM infrastructure, retrieval systems, and distributed processing.

I’m particularly interested in the engineering problems behind AI applications: **latency, retrieval quality, caching, asynchronous workloads, isolation, reliability, and maintainable system design.**

---

## What I Build

### 🧠 AI & RAG Systems

I work on systems that go beyond the basic:

`documents → embeddings → LLM`

My current work explores:

* Hybrid lexical + semantic retrieval
* Multi-index RAG architectures
* Query transformation and retrieval strategies
* Reranking pipelines
* Grounded question answering
* Semantic response caching
* Persistent AI memory and context systems
* LLM application infrastructure

### ⚙️ Backend & Distributed Systems

I build backend systems around:

* FastAPI
* Async Python
* PostgreSQL
* SQLAlchemy
* Redis
* Celery
* Nginx
* Docker
* REST APIs
* Background workers
* Structured error handling
* Service-oriented architecture

I care about keeping **HTTP orchestration, business logic, infrastructure, and background processing properly separated.**

---

## Featured Projects

### 🚀 Talk2Docs

**Production-oriented document intelligence & RAG backend**

A full document Q&A system built around asynchronous ingestion and adaptive retrieval.

**Highlights**

* FastAPI async backend
* Celery-based document processing
* Docling document parsing
* Hybrid BM25 + vector retrieval
* Multi-index architecture
* Raw, Summary, and Explanation representations
* Query transformation strategies
* Cohere reranking
* ChromaDB vector infrastructure
* PostgreSQL + SQLAlchemy
* Redis caching
* User-isolated document knowledge bases
* File-content and signature validation
* Grounded AI responses

The goal is to treat RAG as a **system engineering problem**, not simply an embedding pipeline.

---

### ⚡ TriCacheLLM_MMA

**Portable 3-Tier Semantic Cache for LLM Applications**

An independent caching system designed to reduce unnecessary LLM inference.

```text
                USER QUESTION
                     │
                     ▼
             ┌───────────────┐
             │   TIER 1      │
             │ Exact Redis   │
             └───────┬───────┘
                     │ MISS
                     ▼
             ┌───────────────┐
             │   TIER 2      │
             │ Redis HNSW    │
             │ Semantic      │
             └───────┬───────┘
                     │ MISS
                     ▼
             ┌───────────────┐
             │   TIER 3      │
             │ Persistent VDB│
             │ + Reranking   │
             └───────┬───────┘
                     │ MISS
                     ▼
                LLM PIPELINE
```

**Highlights**

* Exact Redis lookup
* Semantic Redis HNSW search
* Persistent ChromaDB cache
* Cohere reranking
* Automatic cache promotion
* Per-user / per-tenant isolation
* Celery background workers
* Async Python APIs
* Persistent infrastructure state

The design follows a simple principle:

> **Cheap exact lookup first. Cheap semantic lookup second. Expensive retrieval last. LLM inference only after a genuine cache miss.**

---

### 🏗️ Production-Inspired AI Blog Backend

An earlier backend engineering project focused on understanding how production-style AI services are structured.

**Highlights**

* Async FastAPI
* PostgreSQL
* SQLAlchemy
* Redis sessions
* JWT authentication
* Celery workers
* Distributed AI processing
* AI usage quotas
* Reservation-based quota handling
* Structured LLM outputs
* Centralized exception handling
* Service-layer architecture
* Rate limiting
* Nginx reverse proxy

This project became the foundation for how I approach larger AI backend systems.

---

## 🧰 Technology

### Languages

`Python` `SQL` `Bash` `c++` 

### Backend

`FastAPI` `SQLAlchemy` `PostgreSQL` `Alembic`

### AI / RAG

`LangChain` `LLMs` `RAG` `ChromaDB` `BM25` `Embeddings` `Reranking` `Pandas` `Numpy` `scikit-learn`

### Infrastructure

`Redis` `Celery` `Nginx` `Docker` `Linux`

### Engineering

`Async Programming` `Distributed Processing` `Caching` `API Design` `System Architecture`

---

## 🧭 Currently Building

I'm currently deepening my work in **production AI engineering**.

```text
RAG Engineering
      ↓
AI Infrastructure
      ↓
Caching & Memory
      ↓
LangGraph
      ↓
Agentic AI Systems
      ↓
MCP & Tool-Using Systems
```

The long-term goal is to build AI systems that can **retrieve, reason, remember, execute, and interact with real-world infrastructure reliably.**

---

## 🧠 Engineering Philosophy

I don't want to just learn how to use a library.

I want to understand:

* Why the abstraction exists
* What problem it solves
* Where it breaks
* What it costs
* How it behaves under load
* How its responsibilities should be separated
* What a production system would actually need around it

That means I spend a lot of time thinking about **architecture, failure modes, latency, lifecycle management, and system boundaries**, not just model calls.

---

## 📈 Current Direction

**Backend Engineering → RAG → AI Infrastructure → Agentic Systems**

I'm building toward systems where AI isn't just generating text, but is part of a larger reliable software system.

---

## 🤝 Let's Build

I'm interested in:

* AI engineering
* Backend systems
* RAG & retrieval
* LLM infrastructure
* Distributed systems
* AI agents
* Open-source engineering

If you're building something interesting in this space, feel free to connect.

[LinkedIn](https://www.linkedin.com/in/mohib-ashfaq-4a682b407/)
