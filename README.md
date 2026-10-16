# Hi, I'm Suprit U

**B.E. Computer Science '26 — VTU (9.12 / 10.0) | Backend + AI | Bengaluru, India**

Building backend-heavy systems: Node.js APIs, PostgreSQL with Row Level Security, OAuth 2.0 / PKCE, WebSockets, Docker. A conference paper, a journal paper and one Indian patent application in Zero Trust access.

**[Portfolio](https://suprit-u.github.io)** · **[LinkedIn](https://linkedin.com/in/suprit-u)** · **[GitHub](https://github.com/Suprit-U)**

---

## Projects

### ZTNA — AI-Powered Zero Trust Access Gateway

OAuth 2.0 / PKCE authentication against Zitadel with role validation and country-based access control. Every successful login is scored by a weighted rule engine (off-hours +20, unapproved country +30, admin role +20, capped at 100), and an `/analyze` endpoint sends each session to a locally hosted LLM (Ollama) for a risk summary.

[Repo](https://github.com/Suprit-U/ZTNA) · IEEE DOI 10.1109/GSEACT68539.2026.11620242 · Patent App. 202541112150 A

### NexBoard — Real-Time Collaborative Canvas

React + TypeScript + Socket.IO room broadcasting, Fabric.js canvas, Appwrite persistent chat, password-protected rooms, PNG export. Screenshots in `Images/`.

[Live demo](https://nex-board-xi.vercel.app) · [Repo](https://github.com/Suprit-U/NexBoard)

### Sanchalana — Type-Safe Multi-Tenant Web Platform

React 18 + Vite + Supabase / PostgreSQL, Zod runtime validation, Row Level Security for tenant isolation, realtime subscriptions, Radix + Tailwind.

[Repo](https://github.com/Suprit-U/Sanchalana)

### Real-Time Traffic Sign Detection

Custom YOLOv8 training in PyTorch, OpenCV inference pipeline, NMS tuning, automatic CUDA / CPU fallback.

[Repo](https://github.com/Suprit-U/Real-Time-Traffic-Sign)

### VTU Diary Automation

Selenium + Flask + Gemini prompt-chain pipeline that automates academic diary entries. Headless, credentials via `.env`.

[Repo](https://github.com/Suprit-U/VTU-Diary-Automation)

### Kaushalya Karnataka — Skill Platform (Android)

Official Karnataka skill application. Kotlin MVVM, Firebase Auth + Cloud Firestore with offline-first sync, separate Admin and Candidate portals, certificate generation. Built during a six-month internship, Jan–Jun 2026.

[Repo](https://github.com/Suprit-U/Kaushalya-Karnataka)

### CiteKit — Verifiable RAG

Hybrid BM25 + dense retrieval fused with reciprocal rank fusion. Every answer carries a citation; five guardrails abstain when the corpus does not support the question. Ships an evaluation harness (MRR@5 0.700, recall@5 0.667, correct refusal on 3/3 unanswerable questions). Zero dependencies, offline. 48 tests.

[Repo](https://github.com/Suprit-U/CiteKit)

### PulseWatch — Change Detection & Alerts

Conditional GET, token-level diffing, a noise floor that ignores reformatting, cooldowns and change fingerprints, SQLite WAL state, Telegram/webhook alerters, Prometheus status API. One-word change on a live page caught in ~3 ms. 56 tests.

[Repo](https://github.com/Suprit-U/PulseWatch)

### signlab-eval — Detection Evaluation & Dataset QA

Seventeen YOLO dataset checks including train/val leakage detection by perceptual hashing, plus pure-Python mAP@50 / mAP@50-95 with a `--fail-under` CI gate. Exit codes separate model regression from dataset breakage. 53 tests.

[Repo](https://github.com/Suprit-U/signlab-eval)

---

## Open source

- **[marshmallow #3078](https://github.com/marshmallow-code/marshmallow/pull/3078)** — fixed `validate.Email` accepting a leading or trailing hyphen in the final domain label (and missing the 63-character cap). Reproduced on 4.3.1, punycode TLDs kept valid, regression tests added.

---

## Stack

| Area | |
| :--- | :--- |
| Languages | TypeScript, Python, JavaScript, SQL, Kotlin, C++ |
| Backend | Node.js, Express, Flask, Socket.IO, REST, OAuth 2.0 / PKCE, RBAC, JWT |
| Data | PostgreSQL, Supabase, Cloud Firestore, MongoDB, Redis (basic), RLS, migrations |
| AI | PyTorch, YOLOv8, OpenCV, Google Gemini API, prompt engineering |
| Tools | Docker, Git, Linux, Postman, Selenium WebDriver |

## Certifications

- **freeCodeCamp** — Machine Learning with Python (~300 hrs)
- **NPTEL** — Introduction to Machine Learning (43.11 / 75)
- **NPTEL** — Cloud Computing (60.64 / 75)
- **Google Cloud Career Launchpad** — Generative AI Leader track
- **IBM SkillsBuild** — AI Fundamentals

## Publications & IP

- **IEEE GSEACT 2026** — *"Next-Gen Secure Access Using Intelligent Zero Trust Network Architecture"*, pp. 1–6. DOI [10.1109/GSEACT68539.2026.11620242](https://doi.org/10.1109/GSEACT68539.2026.11620242). Presented at the conference, 12–13 June 2026. Co-authored with faculty.
- **IJNRD**, Vol. 11 Issue 1, January 2026 — *"End-to-End Secure Access using ZTNA Framework"*. Paper ID IJNRD2601087.
- **Indian Patent Application 202541112150 A** — *"Enhancing End-to-End Secure Access with AI-Powered Zero Trust Network Access"*. Filed 15 Nov 2025, published 5 Dec 2025. One of seven inventors.

## Connect

[Portfolio](https://suprit-u.github.io) · [LinkedIn](https://linkedin.com/in/suprit-u) · supritu4@gmail.com · Bengaluru, India