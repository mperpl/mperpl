# Hi, I'm Michał 👋

I'm a **Python backend developer** and a part-time **Computer Science student** (Cloud Applications and Systems Engineering). I build APIs with **FastAPI, SQLAlchemy and PostgreSQL**, run them on **AWS**, and work in an **agentic, spec-driven** way: I write the spec and the design decisions, direct AI agents, and review the result.

---

## 🌟 Featured: [Inventory Management with Demand Forecasting](https://github.com/mperpl/inventory-forecasting)

An app that records warehouse movements for a construction-chemicals producer and forecasts **when each stock item will run out**. A solo university project, designed and delivered with AI-assisted development.

* **Backend:** Python 3.13, FastAPI, SQLAlchemy, PostgreSQL 17, Alembic. Permission-based access, immutable movements with reversals, automatic change log.
* **Forecasting:** SES, Holt and Holt-Winters, with the method chosen per item and checked on held-back weeks. Nightly recalculation and an emailed daily report.
* **AWS:** Lambda, API Gateway, RDS, Cognito, CloudFront, S3, EventBridge Scheduler and SES, with scripted deploy and destroy.
* **Web app:** React and TypeScript, with OIDC login.
* **Quality:** 699 Python and 742 frontend tests, 12 architecture decision records, lint, type checks and tests in GitHub Actions.

*How it was made: I wrote the spec, made the design decisions and reviewed the backend. AI agents wrote much of the backend code and all of the frontend and Terraform code.*

---

## 🚀 More work

### 📁 [Project and Document Management API](https://github.com/mperpl/epam-final-assigment)
Solo final project of the EPAM Python Specialization.
* FastAPI, async SQLAlchemy, PostgreSQL, Alembic, Valkey, Docker Compose
* JWT access and refresh tokens, logout from all devices, Owner / Editor / Viewer roles
* S3 document storage, with a Lambda that processes images and enforces storage quotas
* 68 tests; GitHub Actions pipeline that deploys to AWS EC2

### 🍽️ Restaurant booking app (EPAM trainee team project, private code)
* Serverless phase on AWS: authentication, event-driven reporting, deployment resources
* Microservices phase: an **MCP server** that turns the backend's OpenAPI into 38 tools for AI agents, plus event-handling and reporting services

---

## ⚙️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Backend** | **Python**, **FastAPI**, SQLAlchemy (async), Pydantic, Alembic |
| **Data & Cache** | **PostgreSQL**, Valkey/Redis, NoSQL basics (DynamoDB, MongoDB) |
| **AWS** | Lambda, S3, API Gateway, SQS, Cognito, SES, RDS, EC2, EventBridge |
| **AI tooling** | Claude Code (subagents, hooks, skills), MCP, LLM API integration |
| **Testing & tools** | Pytest, Docker, Docker Compose, Git, Ruff, uv, Linux CLI |
| **Security** | JWT, OAuth2, Role-Based Access Control |

---

## 🎨 Earlier frontend work

* **[MyDuoLife Landing Page](https://mperczak-myduolifeinfo.netlify.app/)**: marketing site built with React
* **[Kaizen App](https://mperczak-kaizen.netlify.app/)**: productivity web app

---

## 📬 Let's Connect

* **Email:** [perczak.michal.pl@gmail.com](mailto:perczak.michal.pl@gmail.com)
* **Location:** Strzegom / Wrocław (remote, hybrid or on-site)
* **GitHub:** [github.com/mperpl](https://github.com/mperpl)
