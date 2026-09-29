<p align='center'>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=Eduarda%20Dias&fontSize=90&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer&descAlignY=51&descAlign=50"/>
</p>

<img src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" min-width="400px" max-width="400px" width="400px" align="right" alt="Computer">

Software Engineer at **Accenture**, working on backend systems for **B3**, Brazil's stock exchange, in the credit card receivables and fraud control domain.

I work mainly with Java and Spring Boot: REST APIs, integrations between systems, messaging, and relational databases. I care about architecture, security, and code that stays easy to maintain.

I'm in the final year of a degree in Systems Analysis and Development at SPTech, São Paulo.

[Versão em português](./README.md)

<br clear="right"/>

## Experience

**Accenture** · Software Engineer · Aug 2026 – present
Backend development for B3 (financial market).

**SPTech** · Backend Developer · until Aug 2026
Built and maintained APIs and integrations, with a lot of autonomy. Led the technical work on a Java service that generates PPTX reports. Built data automations with Apache Airflow, and worked on performance improvements and refactoring of existing systems.

## Stack

| | |
|---|---|
| **Core** | Java · Spring Boot · Spring Security (JWT) · REST APIs · SQL (MySQL, PostgreSQL) · RabbitMQ · Docker |
| **Also used** | Python · Airflow · Node.js / TypeScript (NestJS) · SQL Server · Oracle · AWS · Terraform · GitHub Actions · Grafana |
| **Architecture & practices** | Clean / Hexagonal Architecture · SOLID · Design Patterns · Unit and integration testing · Database migrations · API documentation (OpenAPI) |

## Selected projects

**[Leo Vidros — Business management system](https://github.com/projeto-leo-vidros)**
Team project (Aug 2025 – Jul 2026) built for a real glazing company that ran on spreadsheets. I was the main contributor to the backend API.
Spring Boot · JWT · MySQL + Flyway · RabbitMQ · Redis cache · rate limiting · AWS S3 · Docker
- Main API with Strategy-based flows for orders and scheduling
- Async microservice that generates PDF/DOCX quotes from a queue, built with ports and adapters

**[Notification Service](https://github.com/Diaseduarda01/projeto-notificacao)**
Multichannel notification microservice that consumes events from RabbitMQ and sends each one to the right channel.
Java 21 · Spring Boot · RabbitMQ · Clean Architecture · Strategy · JUnit/Mockito · Testcontainers

**[WhatsApp Chatbot Service](https://github.com/Diaseduarda01/projeto-ms-chatbot)** · **[Platform Infra](https://github.com/Diaseduarda01/projeto-infra-dias-plataform)**
Part of a multi-tenant platform I'm building. A configurable flow engine handles incoming WhatsApp messages through webhooks. The infra repo defines the RabbitMQ topology (with dead-letter exchanges) and provisions each tenant on AWS with Terraform.
Java · Spring Boot · MySQL · RabbitMQ · Terraform · AWS

## How I work

- I start with the problem and the domain rules, then pick the architecture. I write specs before code (spec-driven development).
- I keep business logic separate from frameworks and infrastructure, so it can be tested and changed on its own.
- I treat security, error handling, and database migrations as part of the feature, not as follow-up work.
- I use AI tools like Claude Code and MCP in my workflow to explore options, review code, and speed up routine work. Design decisions and code review stay with me.

## Currently studying

Distributed systems (consistency, idempotency, resilience) · System design · Observability · AWS

## Links

[![Links](https://img.shields.io/badge/Links-000000?style=for-the-badge&logo=linktree&logoColor=white)](https://hub-eduarda-dias.vercel.app/)

## Contact

<div>
<a href="mailto:m.eduardadasilvadias4@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/eduarda-dias-723a7820b/" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
</div>
