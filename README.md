# Michał Perczak

**Python backend developer** · FastAPI, PostgreSQL, AWS · agentic spec-driven development

Computer Science student (cloud specialization), EPAM trainee program graduate. **Open to junior backend roles:** remote, or hybrid / on-site around Wrocław.

[Email](mailto:perczak.michal.pl@gmail.com)

## [Inventory Management with Demand Forecasting](https://github.com/mperpl/inventory-forecasting)

Records warehouse movements and forecasts **when each stock item will run out**. Solo project, deployed to AWS.

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL` `AWS` `React` `TypeScript`

- **Forecasts that are checked:** SES, Holt or Holt-Winters, chosen per item and tested on held-back weeks, recalculated nightly
- **Traceable stock:** immutable movements with reversals, automatic change log, permission-based access
- **Cloud:** Lambda, API Gateway, RDS, Cognito, CloudFront, EventBridge and SES, with scripted deploy and destroy
- **Tested:** 699 Python and 742 frontend tests, plus 12 architecture decision records

**How I built it:** I wrote the spec, made the design decisions and reviewed the backend. AI agents wrote much of the backend code and all of the frontend and Terraform code.

## EPAM training projects (private code)

- **Restaurant booking platform** (team): authentication and event-driven reporting on AWS Lambda; later, in FastAPI microservices, an **MCP server** that turns the backend's OpenAPI into 38 tools for AI agents
- **Postal service app** (solo): built twice with Claude Code agent workflows I designed, with planner, implementation, review and QA agents

## Skills

| | |
| :--- | :--- |
| **Backend** | Python, FastAPI, SQLAlchemy, Pydantic, Alembic, Pytest, JWT, OAuth2 |
| **Data** | PostgreSQL, Valkey/Redis, NoSQL basics (DynamoDB, MongoDB) |
| **AWS** | Lambda, API Gateway, S3, SQS, RDS, Cognito, SES, EventBridge, EC2 |
| **AI** | Claude Code (subagents, hooks, skills), MCP servers, LLM API integration |
| **Tools** | Docker, Docker Compose, Git, Linux |
