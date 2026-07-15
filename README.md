<div align="center">

# Hi, I'm Yusuf Adamu

Software engineer building at the intersection of backend infrastructure, distributed systems, and applied machine learning.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yusuf-adamu-9b3472115/)
[![Portfolio](https://img.shields.io/badge/Portfolio-yusufadamu.dev-24292F?style=flat-square&logo=safari&logoColor=white)](https://yusufadamu.dev)
[![Email](https://img.shields.io/badge/Email-meetyusufadamu%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:meetyusufadamu@gmail.com)

</div>

## Career brief

I build backend and AI-enabled systems that are secure, testable, and maintainable. My experience spans financial services, QA automation, technical education, and product engineering, backed by bachelor's and master's degrees in Computer Science.

- **Backend systems** — Built Java and Spring Boot services supporting **1M+ daily financial transactions**, a **99.9% uptime target**, and payment and core-banking integrations. Backend optimization improved transaction processing by **30%**.
- **Automation and reliability** — Turned recurring validation work into repeatable automation, reducing manual workflow effort by **50%** while improving regression coverage and release confidence.
- **Applied AI and ML** — Engineer agentic RAG, retrieval, memory, safety controls, and evaluation workflows with Python. I focus on inspectable architectures, reproducible experiments, and measured failure modes—not demo-only model calls.

## Featured repositories

### [Inventory Lifecycle Engine](https://github.com/TechCeo/inventory-lifecycle-engine)

A multi-user inventory platform evolved from a PyQt and SQLite desktop application into a containerized React and FastAPI system.

**Architectural highlight:** Enforces tenant boundaries at the schema and service layers with organization-scoped constraints, OIDC/PKCE authentication, hierarchical roles, and audit events committed in the same PostgreSQL transaction as inventory mutations. Its legacy importer is idempotent, supports dry runs, and reports source-to-destination totals.

`Python` · `FastAPI` · `React` · `TypeScript` · `PostgreSQL` · `Alembic` · `Keycloak` · `Docker Compose`

---

### [MediBot Agentic RAG](https://github.com/TechCeo/medibot-agentic-rag)

An educational medical-information assistant that routes symptom, severity, description, and precaution queries through specialized tools.

**Architectural highlight:** Combines a LangGraph ReAct orchestrator with per-session memory and a local TF-IDF/FAISS retrieval layer, keeping offline verification deterministic. A 60-case adversarial suite reports **97.67% Recall@k**, **100% out-of-scope detection**, and a **0% harmful-response rate**.

`Python` · `LangGraph` · `LangChain` · `FAISS` · `scikit-learn` · `Gradio` · `pytest` · `Docker`

---

### [Merchants API](https://github.com/TechCeo/Merchants-API)

A merchant and payment-transaction REST API modernized from Java 8 to Java 21 and Spring Boot 3.5.

**Architectural highlight:** Treats Flyway migrations as the schema authority, validates the migrated schema through Hibernate, and runs tests against H2 in Oracle compatibility mode. The API uses resource-oriented routes, immutable records, RFC 7807 error responses, and decoupled slice tests.

`Java 21` · `Spring Boot 3.5` · `Spring Data JPA` · `Hibernate` · `Oracle` · `Flyway` · `H2` · `Maven`

## Tech stack

| Area | Technologies |
| --- | --- |
| **Languages** | Java, Python, TypeScript, JavaScript, SQL |
| **Backend and architecture** | Spring Boot, FastAPI, Flask, REST APIs, Hibernate, SQLAlchemy, service-oriented architecture |
| **AI and machine learning** | LangGraph, LangChain, FAISS, PyTorch, TensorFlow, scikit-learn, retrieval and evaluation pipelines |
| **Data and identity** | PostgreSQL, Oracle, SQLite, Alembic, Flyway, Keycloak, OAuth 2.0, OIDC/PKCE, JWT |
| **DevOps and infrastructure** | AWS, Docker, Docker Compose, GitHub Actions, CI/CD, integration testing |

## Contact

(mailto:meetyusufadamu@gmail.com) or [connect with me on LinkedIn](https://www.linkedin.com/in/yusuf-adamu-9b3472115/).
