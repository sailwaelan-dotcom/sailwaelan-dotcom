# Souhail Chafai

**Clinical AI Safety, Evaluation & Agentic Systems** · Medical Background (UMONS) × Google Cloud Professional Agentic Architect

[![Google Cloud Professional Agentic Architect](https://img.shields.io/badge/Google_Cloud-Professional_Agentic_Architect_(Nov_2026)-4285F4?style=flat&logo=googlecloud&logoColor=white)](https://www.credly.com/badges/2998e0a2-d881-4384-9b8b-753379f39c03)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Souhail_Chafai-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/souhail-chafai-8911b2403)

> **Profile:** 5 years of medical studies (UMONS, Bachelor of Medicine 2023, hospital clinical rotations at CHU Helora Mons) combined with Google Cloud **Professional Agentic Architect** certification (Nov 2026).  
> **Languages & Location:** French (native), English (fluent) · Belgium · Open to Brussels, Wallonia, France, EU & Worldwide Remote (available Dec 2026).  
> **Target Roles:** Medical Operations · Clinical AI Safety & Evaluation · Clinical Implementation / Deployment · Technical AI Product Management (Healthtech / EHR) · Healthcare GenAI Consulting.
>
> *Profil francophone (Belgique / France) : 5 ans d'études de médecine (UMONS) + architecte agentique certifié Google Cloud (nov. 2026), focalisé sur l'évaluation, les garde-fous déterministes et le déploiement d'IA en santé.*

---

## Featured Work

| Repository | Domain | What It Proves |
| :--- | :--- | :--- |
| **[medgemma-dermato](https://github.com/sailwaelan-dotcom/medgemma-dermato)** | Clinical VLM Safety & Evaluation *(RUO)* | Feasibility stress-test of `MedGemma 1.5 4B` on a locked blind hospital cohort (**MSKCC `n=200`**). Catches silent `-31.4 pts` 4-bit clinical collapse, enforces a **6-barrier deterministic safety harness** + SHA-256 DB↔Model bridge, Policy-as-Code CI (4 green jobs), and **ADR-001 / ADR-002**. |
| **[orthopy-architecture](https://github.com/sailwaelan-dotcom/orthopy-architecture)** | Clinical SaaS Architecture *(Closed Beta, Private Code)* | Architecture & safety case study for a Belgian speech-therapy EHR/billing SaaS (**123 INAMI codes**, **61 ADRs**, **3,300+ server tests**): 3-layer PHI confinement (scrub → runtime `Clean` type-gate → independent egress verifier), quasi-identifier budget, and EU MDR / AI Act intended-purpose boundary. |
| **[paa-coach](https://github.com/sailwaelan-dotcom/paa-coach)** | Google Cloud Multi-Agent Systems *(ADK)* | Multi-agent system (`LlmAgent` + `LoopAgent` + `AgentTool`) deployed on **Cloud Run** behind **IAP**, with **Model Armor** prompt/response filtering, **OpenTelemetry / Cloud Trace**, **MCP**, **69 unit tests**, and **8/8 `adk eval`** cases passing on Vertex AI. |
| **[the-agency](https://github.com/sailwaelan-dotcom/the-agency)** & **[pentacore-in-n8n](https://github.com/sailwaelan-dotcom/pentacore-in-n8n)** | Deterministic Agent Tooling & Verification | Harness-agnostic skills + 13-tool MCP server with automated CI security & regulatory freshness gates (MIT); model-free anti-cheat verification gates rebuilt as **n8n** workflows. |

---

## Core Focus Areas

- **Clinical AI Evaluation & Failure-Mode Containment:** Blind external hold-out benchmarking, calibration/ECE checks, contradiction detection, and automated `BLOCK_DEPLOY` policy-as-code gates.
- **Deterministic Guardrails & Regulatory Boundaries:** Practical application of **GDPR** (PHI confinement, quasi-identifier budgets), **EU AI Act**, and **EU MDR / MDCG 2019-11** intended-purpose boundaries in software design.
- **Production Agentic Architecture:** **Google Cloud ADK**, **MCP**, **Cloud Run**, **IAP**, **Model Armor**, **OpenTelemetry**, structured `adk eval` trajectory/quality suites, and deterministic verification loops.
