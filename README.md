🌟 Nguakaaga Mvendaga

LLM Engineer (Applied Systems) — RAG · Agents · Tool Calling · FastAPI · Local LLMs

I design and build production-style LLM systems with explicit reliability guarantees:
grounded retrieval, deterministic pipelines, schema validation, safety gates, and human-in-the-loop workflows.

I focus on how LLMs actually ship — not prompt demos.

🚀 Flagship LLM Systems (Start Here)
🔥 1. Customer Support RAG Bot (Reliability-First)

FastAPI · FAISS · SentenceTransformers · RAG · JSON Validation

A production-style customer support assistant that answers only when evidence exists and returns null instead of hallucinating.

What this demonstrates

Evidence-only RAG (retrieve → threshold → generate)

Explicit hallucination prevention (confidence gating + null responses)

Strict JSON response schema (validated with Pydantic)

Deterministic failure handling (no malformed output escapes)

Local-run, reproducible system

🔗 Code: https://github.com/fidelisnguakaaga20/customer-support-rag-bot

🎥 Loom Demo: https://www.loom.com/share/c9190d1c34054f3b84576e29ec832c67

🎥 YouTube (Unlisted): https://youtu.be/QnsbyYltVDo

🔥 2. SQL Query Agent (Deterministic + Safe)

FastAPI · SQL · Intent Classification · Safety Gates · JSON Contracts

A natural-language-to-SQL system built as a query compiler, not a chatbot.

What this demonstrates

Intent-first pipeline (READ_ONLY vs WRITE vs AMBIGUOUS)

Hard SQL safety gates (blocks destructive queries)

Strict JSON output with validation

Controlled execution + result previews

Deterministic behavior under failure

🔗 Code: https://github.com/fidelisnguakaaga20/sql-query-agent

🎥 Loom Demo: https://www.loom.com/share/e3a2411a42d94286a27dd4b4659949d2

🎥 YouTube (Unlisted): https://youtu.be/c-xbEQ5KEEk

🔥 3. Email Reply Assistant (Human-in-the-Loop)

FastAPI · RAG · Safety Flags · Draft-Only Workflow

A production-style email drafting assistant that never auto-sends, flags risk, and asks for missing information.

What this demonstrates

Draft-only policy (human review enforced)

Safety flags + refusal handling

RAG-grounded replies with citations

Deterministic JSON output + validation gates

Real SaaS-ready workflow design

🔗 Code: https://github.com/fidelisnguakaaga20/email-reply-assistant-llm

🎥 Loom Demo: https://www.loom.com/share/71132b23d4f448349eaa9f91ef52524a

🎥 YouTube (Unlisted): https://youtu.be/f-vXtWoVBO8

🔥 4. Full AI SaaS Platform — Capstone

FastAPI · Next.js · JWT · Chroma · RAG · Tool-Using Agents

A full-stack AI SaaS platform combining authentication, user-isolated vector stores, RAG chat, and deterministic agents in a single workspace.

What this demonstrates

SaaS authentication + user isolation

Per-user vector collections

RAG + tool routing before LLM calls

Clean backend/frontend integration

Production-style architecture (local-run)

🔗 Code: https://github.com/fidelisnguakaaga20/ai-saas-platform-capstone

🎥 Loom Demo: https://www.loom.com/share/d87162195b774dbda47fd3f09f1c3b75

🎥 YouTube (Unlisted): https://youtu.be/wNZ4honPCjM

🔬 Additional LLM Systems

Offline Voice Assistant — fully local STT → LLM → TTS
Faster-Whisper · TinyLlama · Tool Routing
🔗 https://github.com/fidelisnguakaaga20/project-8-offline-voice-assistant

LoRA Fine-Tuned LLM — instruction tuning + local inference
Transformers · PEFT · Colab GPU
🔗 https://github.com/fidelisnguakaaga20/lora-finetuned-llm

Multi-Tool AI Agent — RAG + SQL + tools
🔗 https://github.com/fidelisnguakaaga20/project-7-multi-tool-agent

Resume RAG Chatbot
🔗 https://github.com/fidelisnguakaaga20/resume-rag-chatbot

Embedding Search Engine — semantic vector search
🔗 https://github.com/fidelisnguakaaga20/embedding-search-engine

AI Content Generator
🔗 https://github.com/fidelisnguakaaga20/llm-ai-content-generator

🧱 Prior Production SaaS Experience

Before specializing in LLM systems, I built production SaaS platforms involving:

Multi-tenant architectures

Role-based access control

Stripe & Paystack billing

Secure dashboards and APIs

Selected projects

FLEX FOAM — B2B E-Commerce SaaS
Live: https://flex-foam-b2b.vercel.app

Code: https://github.com/fidelisnguakaaga20/flex-foam-b2b

Multi-Tenant AI SaaS
Live: https://multi-tenant-ai-saas.vercel.app

Code: https://github.com/fidelisnguakaaga20/multi-tenant-ai-saas

Stripe Revenue Copilot
Live: https://stripe-revenue-copilot.vercel.app

Code: https://github.com/fidelisnguakaaga20/stripe-revenue-copilot

🧠 How I Think About LLM Systems

LLMs are unreliable by default

Reliability comes from system design, not prompts

Determinism > cleverness

Null is better than hallucination

Humans stay in the loop where risk exists

📫 Contact

📧 Email: fidelisnguakaaga20@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/nguakaaga-mvendaga

💻 GitHub: https://github.com/fidelisnguakaaga20
