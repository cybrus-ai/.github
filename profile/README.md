<div align="center">

<img src="https://raw.githubusercontent.com/cybrus-ai/.github/main/profile/cybrus.png" alt="Cybrus logo" width="180" />

# Cybrus

**An Autonomous Secure AI Agent for Industry & Cyber Defence**

*Cyber + Cerberus — a multi-headed guardian that watches your systems 24/7.*

![Status](https://img.shields.io/badge/status-in%20development-7c5cbf)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

</div>

---

## 🌐 Why Cybrus

Traditional security is slow, expensive, and reactive — and out of reach for most small and mid-sized organizations. Cybrus aims to change that with a self-sufficient AI agent that:

- **Operates autonomously** with minimal human oversight
- **Detects threats in real time** across logs, processes, and network activity
- **Explains every decision** with evidence and confidence scores
- **Responds immediately** — and logs every action it takes

## 🧱 How It Works

```
 ┌──────────────────┐   REST / WebSocket   ┌──────────────────────┐
 │  Cybrus Portal   │ ◄──────────────────► │   Cybrus Core API    │
 │  (Dashboard UI)  │                      │  detection · alerts  │
 └──────────────────┘                      └──────────┬───────────┘
          ▲                                           │  telemetry ▲
          │ JWT / RBAC                                ▼  commands  │
 ┌──────────────────┐                      ┌──────────────────────┐
 │   Auth Service   │                      │    Cybrus Agent(s)   │
 └──────────────────┘                      │ logs · procs · net   │
                                           └──────────────────────┘
```

| Component | Role |
|---|---|
| **Agent** | Lightweight Python daemon on servers/endpoints — collects telemetry, executes response actions |
| **Core API** | FastAPI backend — ingests telemetry, runs detection, raises alerts, dispatches responses |
| **Auth Service** | Multi-tenant authentication with JWT and role-based access control |
| **Portal** | Real-time dashboard for alerts, agent health, assets, and analytics |

## 🗺️ Roadmap

- [ ] **v0.1 — MVP:** agent → backend → dashboard flow, JWT auth & RBAC
- [ ] **v0.2 — Detection:** rule engine mapped to MITRE ATT&CK, alert prioritization
- [ ] **v0.3 — ML & Threat Intel:** anomaly detection models, IOC feeds
- [ ] **v0.4 — RL Agent:** reinforcement learning that adapts detection and response
- [ ] **v1.0 — Beta:** stable, tested platform ready for pilot deployments

## 🛠️ Tech Stack

**Backend:** Python · FastAPI · SQLAlchemy · Alembic · PostgreSQL
**Frontend:** Next.js · React · TypeScript · Tailwind CSS
**Planned:** Kafka · Redis · Docker · scikit-learn · PyTorch

---

<div align="center">

Built by [Kunal Borade](https://github.com/KUNALBORADEGIT) · Feedback and collaboration welcome

</div>
