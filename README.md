# Hi, I'm Kunal Sengupta

Backend Engineer focused on Python, FastAPI, and applied GenAI/RAG systems. Based in Bengaluru, India.

I have 3+ years of production backend experience across Node.js and Drupal. Since September 2025, I've been self-directed in Python and GenAI infrastructure: designing, building, and operating Appx end to end, a Kubernetes-orchestrated AI EdTech platform with a custom RAG pipeline.

## What I'm building

**[Appx](https://appx.kunalbuilds.dev)**, a RAG-based curriculum platform, is a multi-service system I run solo:
- Async FastAPI backend (asyncpg, SQLAlchemy async) serving 15 routers for RAG chat, curriculum, quizzes, and admin
- A separate ingestion service with a 5-phase pipeline (parse, chunk, extract, embed, write) and checkpoint/resume support
- A standalone embedding microservice serving BGE-M3
- An LLM fallback chain (Gemini, Groq, Ollama, OpenAI) with per-provider circuit breakers
- GitOps deployment on self-managed k3s via ArgoCD, Helm, and Sealed Secrets, with observability through OpenTelemetry, Grafana Cloud, and Sentry

**[SchemaGuard](https://github.com/kunalsengupta)** is a GitHub Action that parses PostgreSQL migrations with pglast (a real AST parser) to catch unsafe schema changes before merge, with an LLM layer for plain-language risk explanations.

## Background

Before this, I led a team of 6 engineers through a full monolith-to-microservices rebuild of a real-time platform at my last role, personally proposing the architecture and building the core RabbitMQ messaging and shared middleware layers. Earlier roles moved between Node.js backend work and Drupal development.

## Stack

`Python` `FastAPI` `PostgreSQL` `Qdrant` `Redis` `RabbitMQ` `Docker` `Kubernetes (k3s)` `ArgoCD` `GitHub Actions`

## Elsewhere

- Portfolio: [agentk.kunalbuilds.dev](https://agentk.kunalbuilds.dev)
- LinkedIn: [kunal-sengupta-b3616015a](https://www.linkedin.com/in/kunal-sengupta-b3616015a/)
- Email: kunal.sengupta852@gmail.com
