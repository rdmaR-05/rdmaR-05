<div align="center">

# Rhutvij Dharme
### Backend Engineer — Distributed Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rhutvij-dharme-96590824a/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rhutvijrsd10@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode_1864-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/rd_05/)

</div>

---

## About

I work on backend systems that have to stay correct under concurrent load — booking flows, payment webhooks, real-time collaboration. Most of what I do sits at the intersection of correctness (locking, idempotency, transactions) and throughput (caching, queueing, indexing). I load-test with `k6` before anything ships.

---

## Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Java 21](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) |
| **Frameworks** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot) |
| **Data & Cache** | ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) |
| **Infra** | ![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) |

---

## Projects

### [TookMyShow](https://github.com/rdmaR-05/TookMyShow) — reservation engine
`Go` `PostgreSQL` `Redis` `RabbitMQ` `Docker` `Kubernetes`

Ticket booking system built around the double-booking problem you get during flash sales. Seat holds go through Redis-based distributed locks, and Stripe webhook handling is idempotent so a retried payment event can't create a duplicate booking. Load-tested with k6 at 10k concurrent requests, holding sub-second latency.

### [Thinkboard — Spring](https://github.com/rdmaR-05/Thinkboard-Spring) — collaborative workspace
`Java 21` `Spring Boot` `Spring Security` `WebSockets` `PostgreSQL` `Redis` `RabbitMQ`

Multi-user board app with an event-driven backend. Background work — email dispatch, data pipelines — runs through RabbitMQ so request threads stay non-blocking. REST endpoints are stateless and JWT-secured; Redis handles session and board-state caching.

### [Thinkboard — Node](https://github.com/rdmaR-05/Thinkboard) — WebSocket sync engine
`Node.js` `WebSockets` `MongoDB` `React`

An earlier pass at the same problem, focused on low-latency state sync. Reworked WebSocket payload routing and MongoDB indexing to keep sync smooth across concurrent sessions.

### Privacy Compliance Auditor
`Python` `Pandas` `Pinecone` `Llama3 (Ollama)`

RAG pipeline that scans datasets for PII and generates structured compliance reports. Runs entirely on local models via Ollama, so nothing leaves the machine.

---

## Competitive Programming

| Platform | Rating |
| :--- | :--- |
| [LeetCode](https://leetcode.com/u/rd_05/) | 1864 (Top 5.68%) |
| [CodeChef](https://www.codechef.com/users/rhutvijnoobie) | 2★ (max 1551) |
| [Codeforces](https://codeforces.com/profile/Rd_05) | Pupil (max 1391) |
