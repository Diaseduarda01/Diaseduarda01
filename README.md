<p align='center'>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=Eduarda%20Dias&fontSize=90&animation=fadeIn&fontAlignY=38&desc=Engenheira%20de%20Software%20Pleno&descAlignY=51&descAlign=50"/>
</p>

<img src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador">

Engenheira de Software na **Accenture**, atuando no backend de sistemas da **B3** no domínio de recebíveis de cartão e controle de fraude.

Trabalho principalmente com Java e Spring Boot: APIs REST, integração entre sistemas, mensageria e bancos de dados relacionais. Me preocupo com arquitetura, segurança e código fácil de manter.

Estou no último ano de Análise e Desenvolvimento de Sistemas na SPTech, em São Paulo.

[English version](./README.en.md)

<br clear="right"/>

## Experiência

**Accenture** · Engenheira de Software · ago/2026 – atual
Desenvolvimento backend para a B3 (mercado financeiro).

**SPTech** · Desenvolvedora Backend · até ago/2026
Desenvolvi e mantive APIs e integrações, com bastante autonomia. Liderei a parte técnica de um serviço em Java que gera relatórios em PPTX. Criei automações de dados com Apache Airflow e trabalhei em melhorias de performance e refatoração de sistemas existentes.

## Stack

| | |
|---|---|
| **Principal** | Java · Spring Boot · Spring Security (JWT) · APIs REST · SQL (MySQL, PostgreSQL) · RabbitMQ · Docker |
| **Também utilizo** | Python · Airflow · Node.js / TypeScript (NestJS) · SQL Server · Oracle · AWS · Terraform · GitHub Actions · Grafana |
| **Arquitetura e práticas** | Clean / Hexagonal Architecture · SOLID · Design Patterns · Testes unitários e de integração · Migrations · Documentação de API (OpenAPI) |

## Projetos selecionados

**[Leo Vidros — Sistema de gestão empresarial](https://github.com/projeto-leo-vidros)**
Projeto em equipe (ago/2025 – jul/2026) feito para uma vidraçaria real que dependia de planilhas. Fui a principal contribuidora da API backend.
Spring Boot · JWT · MySQL + Flyway · RabbitMQ · cache com Redis · rate limiting · AWS S3 · Docker
- API principal com fluxos de pedidos e agendamentos baseados em Strategy
- Microsserviço assíncrono que gera orçamentos em PDF/DOCX a partir de uma fila, construído com ports and adapters

**[Notification Service](https://github.com/Diaseduarda01/projeto-notificacao)**
Microsserviço de notificações multicanal que consome eventos do RabbitMQ e envia cada um pelo canal certo.
Java 21 · Spring Boot · RabbitMQ · Clean Architecture · Strategy · JUnit/Mockito · Testcontainers

**[Chatbot WhatsApp](https://github.com/Diaseduarda01/projeto-ms-chatbot)** · **[Infra da plataforma](https://github.com/Diaseduarda01/projeto-infra-dias-plataform)**
Parte de uma plataforma multi-tenant que estou construindo. Um motor de fluxos configurável trata as mensagens do WhatsApp recebidas por webhook. O repositório de infra define a topologia do RabbitMQ (com dead-letter exchanges) e provisiona cada tenant na AWS com Terraform.
Java · Spring Boot · MySQL · RabbitMQ · Terraform · AWS

## Como trabalho

- Começo pelo problema e pelas regras de negócio, e só depois escolho a arquitetura. Escrevo a especificação antes do código (desenvolvimento orientado a especificação).
- Mantenho a regra de negócio separada de framework e infraestrutura, para que ela possa ser testada e alterada de forma independente.
- Trato segurança, tratamento de erros e migrations como parte da funcionalidade, e não como algo para depois.
- Uso ferramentas de IA como Claude Code e MCP para explorar alternativas, revisar código e acelerar tarefas repetitivas. As decisões de design e a revisão do código continuam sendo minhas.

## Estudando atualmente

Sistemas distribuídos (consistência, idempotência, resiliência) · System design · Observabilidade · AWS

## Portfólio

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://eduarda-dias-portifolio.vercel.app/)

## Contato

<div>
<a href="mailto:m.eduardadasilvadias4@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/eduarda-dias-723a7820b/" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
</div>
