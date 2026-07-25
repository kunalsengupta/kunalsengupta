# Kunal Sengupta

**Backend & AI Engineer** · Python · FastAPI · RAG Pipelines · Kubernetes  
📍 Bengaluru, India · 🌍 Open to Remote · Available immediately

---

## What I'm Building

### 🎓 EdTech AI Learning Platform — *Live in Production*
Full-stack AI adaptive learning platform for Grade 8–12 students 
across all major Indian boards (CBSE, ICSE, IGCSE, IB, State) 
and undergraduate courses. Built and operated solo — end to end.

**Live:** https://appx.kunalbuilds.dev 
**Private repo** — available on request

**Stack:**
- 3 FastAPI microservices on self-managed k3s (Kubernetes)
- BGE-M3 int8 embeddings + Qdrant semantic search
- Multi-LLM orchestration: Gemini → Groq → Ollama/Qwen failover
- GitOps via ArgoCD · KEDA autoscaling · Terraform provisioned
- Full OpenTelemetry + Grafana + Prometheus + Sentry observability
- Supabase auth · Role-based access · LaTeX/KaTeX math rendering

**Scale:** 34 boards · 772 chapters (K12) · 
182 universities · 1,820 programmes (UG)

---

### 🛡️ SmartSchema — *CI-Native PostgreSQL Migration Guardrail*
GitHub Action that catches dangerous PostgreSQL migrations 
before they reach production — using AST analysis, not regex.

**Repo:** https://github.com/kunalsengupta/SmartSchema

- Deterministic pglast AST engine — zero false negatives on 
  table locks, missing rollbacks, destructive drops
- BYOK LLM fix suggestions via LiteLLM — schema data never 
  leaves the CI runner
- Security by architecture, not by policy

---

## Tech Stack

**AI & RAG**
BGE-M3 · Qdrant · pgVector · LiteLLM · OpenRouter ·  
Gemini · Groq · Ollama · Pydantic Output Parsers

**Backend**
Python 3.12 · FastAPI · SQLAlchemy 2.0 (async) · asyncpg ·  
Node.js · TypeScript · NestJS · Express.js

**Infrastructure**
Kubernetes (k3s) · ArgoCD · Terraform · KEDA · Helm ·  
Docker · GitHub Actions · Sealed Secrets · Traefik

**Databases & Messaging**
PostgreSQL · Redis · RabbitMQ · Qdrant · MongoDB

**Cloud & Observability**
AWS (ECS, Lambda, RDS, S3) · OpenTelemetry ·  
Grafana · Prometheus · Sentry

---

## Professional Highlights

- Built and deployed a production AI platform solo —  
  infrastructure to frontend, RAG pipeline to GitOps CI/CD
- Cut CI/CD pipeline time **73%** (45m → 12m) at Anotech
- Reduced PostgreSQL P95 latency **850ms → 580ms** at Blufig
- Scaled API throughput **200 → 500 RPS** at Store Apps
- Decoupled fintech monolith into event-driven microservices  
  handling **10K+ daily transactions**

---

## Currently

- 🚀 Shipping the EdTech platform to real students
- 🔧 Actively developing SmartSchema
- 👀 Open to remote backend/AI engineering roles

---

## Contact

📧 kunal.sengupta852@gmail.com  
💼 [LinkedIn](https://linkedin.com/in/kunal-sengupta-b3616015a/)  
🌐 [Portfolio](https://portfolio-xi-five-64.vercel.app/)
