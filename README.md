# Ishak Abdiaziz Hussein

### Backend Software Engineer | AI Engineer

High-growth-capacity Web Systems • API Design • Backend Architecture • AI Engineering

I build production-ready backend systems and APIs with clean architecture, maintainable code, and scalable infrastructure — and I'm extending that into AI-powered applications.

## Focus

- Backend architecture
- REST API development
- Authentication and authorization
- Database design and optimization
- Full-stack application development
- AI engineering — RAG, LLMs, and AI agents

## Tech Stack

**Backend:** Python • FastAPI • Prisma • Redis
**Frontend:** Next.js • Tailwind CSS
**Data:** pgVector • Supabase • MongoDB • PostgreSQL
**AI:** RAG • LLMs • AI Agents • Embeddings • Tools • Memory • LangGraph
**Languages:** JavaScript • C++ • C • Python

## Featured Projects

### AI Document Assistant
Repo: https://github.com/IshakAbdiazizHussen/Ai-Document-Assistant

A RAG-powered assistant that lets users upload documents (PDF, Word) and query them in natural language — get direct answers, summaries, or extracted data without manually searching through the file.

**Stack:** Python, FastAPI, RAG pipeline, LLMs

**Highlights:**
- Retrieval-augmented Q&A over uploaded documents, not just static text search
- Multi-format ingestion (PDF, DOCX, and more)
- Automated summarization of long documents
- Structured key-data extraction, removing manual copy-paste work

---

### Research Agent
Repo: https://github.com/IshakAbdiazizHussen/Research-Agent

A web-grounded research agent that answers questions using live sources instead of relying on static training data — every answer comes with citations back to the original source.

**Stack:** Python, FastAPI, LangGraph, tool calling

**Highlights:**
- Agentic loop: query → live web search → relevance-graded sources → automatic query refinement and retry on weak results → cited, grounded answer
- Streams reasoning and search progress in real time
- Maintains context across related follow-up questions
- Explicitly reports when no reliable answer is found, instead of hallucinating one

---

### AI Image Classifier
Repo: https://github.com/IshakAbdiazizHussen/Ai-image-classifer-

A full-stack web application that classifies images into 10 categories (CIFAR-10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck), using a PyTorch-trained model served via ONNX Runtime.

**Stack:** Next.js (frontend, Vercel) • FastAPI + Uvicorn (backend, Render/Docker) • PyTorch (timm) exported to ONNX • PostgreSQL via SQLAlchemy + Alembic (Supabase) • Redis (Upstash) • Docker Compose (local dev)

**Highlights:**
- Upload a JPEG/PNG/WebP image and get a predicted class with confidence scores across all 10 categories
- Prediction history persisted to Postgres
- Redis-backed rate limiting that fails closed — blocks requests rather than silently allowing unlimited traffic if Redis is unreachable
- Result caching by image hash to avoid redundant inference
- `/healthz` endpoint reporting live status of database, Redis, and model artifact

---

### FastAPI Authentication API
Production-style authentication service with JWT-based auth, role-based access control, and secure password handling.

**Stack:** Python, FastAPI, PostgreSQL

---

### PostgreSQL REST API
A RESTful API built on a normalized PostgreSQL schema, focused on clean data modeling and query performance.

**Stack:** Python, FastAPI, PostgreSQL

---

### Full-Stack Dashboard
End-to-end web dashboard with a React/Next.js frontend backed by a REST API.

**Stack:** React, Next.js, Node.js/FastAPI, PostgreSQL

---

## Mindset

Build with purpose. Learn with discipline. Improve with consistency.
