# The International Chasquis — Showcase & Architectural Overview

Welcome to the public technical showcase for **The International Chasquis**, a web platform engineered for financial orientation and cross-border remittance facilitation (Europe – Peru).

> **Project Scope Notice:** This repository serves strictly as a **public showcase and technical evolution log**. To protect proprietary business logic and commercial security, the full codebase, core rate calculation engine, and internal services reside in a private repository.

---

## 🚀 Project Purpose
Demonstrate the progressive development of a scalable and secure web solution, applying software engineering best practices, clean architecture, and continuous deployment.

---

## 📐 Spec-Driven Development (SDD) & AI Orchestration

This project is built using **Spec-Driven Development (SDD)** principles to ensure architectural consistency, maintainability, and enterprise-grade software standards:

* **Specification First:** Detailed technical requirements, database schemas, and system workflows are fully documented prior to code implementation.
* **Structured AI Orchestration:** Generative AI is leveraged as a high-velocity execution engine, guided under strict architectural guardrails, specification constraints, and human code reviews.
* **Session & State Continuity:** Rigorous session logging and handoff tracking to eliminate technical debt and ensure predictable, scalable evolution.

---

## 🛠️ Tech Stack & Engineering Tools

### Backend & Database
* **Python 3.13+** — Core development language.
* **Django Web Framework** — Component-based architecture & ORM integration.
* **Custom User Model** — Extended authentication architecture implemented early in development.
* **PostgreSQL** — Relational database management system for both local development and production.

### Infrastructure, DevOps & Local Environment
* **WSL2 (Ubuntu)** — Native Linux environment on Windows.
* **Docker & Docker Engine** — Containerization for local database instances and services.
* **Gunicorn & WhiteNoise** — Production WSGI HTTP server and static asset management.
* **Render & Cloud Infrastructure** — Automated cloud deployment with SSL/HTTPS certificates and custom domain routing.

### Frontend
* **HTML5 / CSS3** — Responsive layout, custom styling, and brand identity.

---

## 🔒 Security Practices & Standards
* **Secret Isolation:** Strict environment variable isolation using `django-environ` to prevent credential exposure (`DJANGO_SECRET_KEY`, DB secrets).
* **Git Hygiene:** Rigorous exclusion of sensitive runtime files (`.env`, local databases) via `.gitignore`.
* **Production Hardening:** `DEBUG = False` in live environments with enforced HTTPS routing.

---

## 📈 Project Roadmap & Evolution

- [x] **Phase 1: Environment Setup & Core Architecture**
  - Configured WSL2, Docker Desktop, and local PostgreSQL instance.
  - Implemented custom user authentication models in Django.
- [x] **Phase 2: Production Deployment & Domain Routing**
  - Configured Gunicorn WSGI server and WhiteNoise static file handling.
  - Deployed to cloud infrastructure (Render) with custom SSL domain (`https://theinternationalchasquis.com`).
- [/] **Phase 3: Public Interface & Core Services** *(In Progress)*
  - Brand identity integration and responsive homepage layout.
  - Public currency estimation interface.
- [ ] **Phase 4: Service Integration & User Dashboard**
  - Authentication flows, transaction history, and operational logging.

---

## 👨‍💻 Developer Profile
* **Cristhian Hernández** — Full Stack Software Developer.
* **Contact:** `contacto@theinternationalchasquis.com`
* **Live Application:** [theinternationalchasquis.com](https://theinternationalchasquis.com)
