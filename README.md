<div align="center">
  
  # ⚡ Rhutvij Dharme
  ### Backend Software Development Engineer | Distributed Systems
  
  *Engineering high-throughput, low-latency, mission-critical backend architectures.*
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rhutvij-dharme-96590824a/)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rhutvijrsd10@gmail.com)
  [![LeetCode](https://img.shields.io/badge/LeetCode_1807-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/rd_05/)

</div>

---

## 🧠 Engineering Manifesto

I treat system stability and speed as absolutes. If you check my contribution graph, you won't see a wall of automated daily green squares. **I optimize for deep work, architectural integrity, and systemic problem-solving over micro-commits.** My development lifecycle revolves around whiteboarding complex state transitions, building cohesive features locally, and stress-testing them (via `k6`) before pushing. My primary focus is writing clean, idempotent APIs, designing scalable distributed systems, and eliminating race conditions at the database level.

---

## 🛠️ Core Arsenal

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Java 21](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) |
| **Frameworks** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot) |
| **Data & Cache** | ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) |
| **Infrastructure**| ![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) |

---

## 🚀 Architectural Showcases

I build systems designed to solve real-world concurrency, race conditions, and scaling bottlenecks. 

### 🎟️ [TookMyShow: High-Throughput Reservation Engine](https://github.com/rdmaR-05/TookMyShow)
A scalable ticketing system architected to eliminate the "double-booking" anomaly during high-traffic flash sales.
* **Tech Stack:** Go, PostgreSQL, Redis, RabbitMQ, Docker, Kubernetes
* **Engineering Impact:** Engineered Redis-based distributed locks and idempotent Stripe webhook processing to guarantee 100% ACID compliance and data integrity. Successfully load-tested to handle 10,000 concurrent user requests with sub-second latency.

### 🍃 [Thinkboard: Enterprise Collaborative Workspace](https://github.com/rdmaR-05/Thinkboard-Spring)
A full-stack, real-time multi-user collaborative platform utilizing an event-driven Spring architecture.
* **Tech Stack:** Java 21, Spring Boot, Spring Security, WebSockets, PostgreSQL, Redis, RabbitMQ
* **Engineering Impact:** Maintained strictly non-blocking request threads by decoupling background tasks (email dispatch, data pipelines) into RabbitMQ message queues. Secured stateless REST endpoints via JWT and implemented Redis for lightning-fast session and board state caching.

### 📝 [Thinkboard: Node.js Microservice Variant](https://github.com/rdmaR-05/Thinkboard)
A low-latency, real-time state synchronization engine for multi-user collaboration.
* **Tech Stack:** Node.js, WebSockets, MongoDB, React
* **Engineering Impact:** Restructured WebSocket payload routing and optimized MongoDB indexing strategies to achieve seamless, low-latency state synchronization across heavily concurrent user sessions.

### 🔒 AI-Powered Privacy Compliance Auditor
A Retrieval-Augmented Generation (RAG) pipeline designed to strictly audit datasets for Personally Identifiable Information (PII) and privacy risks.
* **Tech Stack:** Python, Pandas, Pinecone (Vector DB), Llama3 (Ollama)
* **Engineering Impact:** Built a localized semantic retrieval system capable of parsing unstructured data and generating deterministic, structured compliance reports via local LLM outputs, ensuring zero data leakage.

---

## 📊 Algorithmic Proficiency

| Platform | Standing | Link |
| :--- | :--- | :--- |
| **LeetCode** | Rating 1807 *(Top 7.5% Globally)* | [View Profile](https://leetcode.com/u/rd_05/) |
| **CodeChef** | 2-Star *(Max 1551)* | - |
| **Codeforces** | Pupil *(Max 1391)* | - |
