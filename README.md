# AI Systems Fundamentals

> A practical guide to understanding modern AI systems from a business and finance perspective.

## 🎯 Purpose

This project documents my hands-on journey learning how modern AI systems work and how they can be applied to real-world business problems.

Rather than focusing only on AI theory, the goal is to understand the architecture behind practical AI applications and eventually build production-ready AI workflows, agents, and business applications.

---

## 🧠 Modern AI System — Mental Model

A modern AI application is much more than an LLM.

```text
                    USER
                      │
                      ▼
               AI APPLICATION
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
       LLM          MEMORY        TOOLS
        │                           │
        │                     APIs / Code
        │                           │
        ▼                           ▼
     CONTEXT                 BUSINESS SYSTEMS
        ▲
        │
       RAG
        │
        ▼
 KNOWLEDGE / DATA
