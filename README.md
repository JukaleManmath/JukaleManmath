<!-- 
  GitHub Profile README for Jukale Manmath
  Focus: Backend Engineering · Distributed Systems · Platform Reliability
-->

<div align="center">

```
                        ┌──────────────────────────────────────────────────────────────────────────────┐
                        │                                                                              │
                        │  ███╗   ███╗ █████╗ ███╗   ██╗███╗   ███╗ █████╗ ████████╗██╗  ██╗           │
                        │  ████╗ ████║██╔══██╗████╗  ██║████╗ ████║██╔══██╗╚══██╔══╝██║  ██║           │
                        │  ██╔████╔██║███████║██╔██╗ ██║██╔████╔██║███████║   ██║   ███████║           │
                        │  ██║╚██╔╝██║██╔══██║██║╚██╗██║██║╚██╔╝██║██╔══██║   ██║   ██╔══██║           │
                        │  ██║ ╚═╝ ██║██║  ██║██║ ╚████║██║ ╚═╝ ██║██║  ██║   ██║   ██║  ██║           │
                        │  ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝     ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝           │
                        │                                                                              │
                        │              MANMATH JUKALE · BACKEND ENGINEER · DISTRIBUTED SYSTEMS         │
                        │                          MS CS @ BINGHAMTON UNIVERSITY                       │
                        │                                                                              │
                        └──────────────────────────────────────────────────────────────────────────────┘
```

<p align="center">
  <strong>Building production systems that don't break at 3 AM</strong>
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/JukaleManmath)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jukalemanmath@example.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-500+-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/your-handle)
![Profile Views](https://komarev.com/ghpvc/?username=JukaleManmath&style=flat-square&color=blue)

</div>

---

## 🎯 What I Do

I architect **backend systems that scale under pressure** and **stay reliable when it matters**.

My work sits at the intersection of:
- **Systems thinking** → designing for failure modes, latency budgets, and operational reality
- **Production ownership** → shipping features, debugging incidents, optimizing hot paths
- **AI integration** → making LLMs useful in real applications (not just demos)

**Current focus:** M.S. Computer Science @ Binghamton University (May 2026) | **500+ LeetCode problems** | Building with **Kafka, Redis, Postgres & LLMs**

---

## 💼 Engineering Philosophy

```python
def build_system(requirements):
    """
    My approach to backend engineering:
    - Start with clear contracts (APIs that don't surprise users)
    - Design for observability (logs, metrics, traces from day 1)
    - Plan for failure (retries, idempotency, circuit breakers)
    - Ship incrementally (feature flags, safe rollouts, rollback plans)
    - Measure everything (latency, throughput, error rates, cost)
    """
    return production_ready_system
```

I believe in:
- **Strong data models** over clever abstractions
- **Boring technology** for critical paths
- **Operational empathy** → if you built it, you support it
- **Intentional complexity** → every dependency must earn its place

---

## 🛠️ Technical Arsenal

<table>
<tr>
<td width="33%" valign="top">

### Languages & Core
```yaml
Primary:
  - Python (FastAPI, Flask, Django)
  - Java (Spring Boot)
  - SQL (PostgreSQL expert)

Also:
  - C++ (systems, performance)
  - JavaScript/TypeScript (Node.js)
  - Bash (automation, ops)
```

</td>
<td width="33%" valign="top">

### Backend & Data
```yaml
API Design:
  - REST, gRPC, WebSockets
  - OpenAPI, JWT, OAuth2

Datastores:
  - PostgreSQL, MySQL
  - Redis (caching, queues)
  - MongoDB, Elasticsearch
  - pgvector (embeddings)

Processing:
  - Celery, Kafka
  - SQS/SNS, Lambda
```

</td>
<td width="33%" valign="top">

### Infrastructure & AI
```yaml
Cloud & DevOps:
  - AWS (Lambda, RDS, S3, ECS)
  - Docker, Kubernetes
  - CloudFormation, Terraform
  - CI/CD pipelines

AI/LLM Stack:
  - OpenAI, Anthropic APIs
  - LangChain, LangGraph
  - RAG, Vector Search
  - Tool calling, MCP
  - Evaluation frameworks
```

</td>
</tr>
</table>

<details>
<summary><strong>📐 System Design Patterns I Apply</strong></summary>

<br>

**Scalability:**
- Horizontal scaling strategies (stateless services, session management)
- Database sharding, read replicas, connection pooling
- Caching layers (Redis, CDN, application-level)
- Load balancing, service discovery

**Reliability:**
- Retry logic with exponential backoff & jitter
- Circuit breakers, bulkheads, timeouts
- Idempotency keys, exactly-once delivery patterns
- Graceful degradation, fallback mechanisms

**Observability:**
- Structured logging (JSON, correlation IDs)
- Metrics (RED/USE method, SLIs/SLOs)
- Distributed tracing (OpenTelemetry)
- Alerting that doesn't cry wolf

**Data Integrity:**
- ACID transactions, isolation levels
- Optimistic/pessimistic locking
- Event sourcing, outbox pattern
- Schema versioning, migrations

**Performance:**
- N+1 query prevention, query optimization
- Database indexing strategies
- Rate limiting (token bucket, sliding window)
- Backpressure handling

</details>

---

## 🚀 Featured Projects

> **These projects demonstrate production-grade thinking:** scalability, reliability, clear contracts, and operational awareness.

<table>
<tr>
<td width="50%" valign="top">

### 📊 Trading Signal & Risk API
**Real-time market data platform**

`Kafka` `Redis` `PostgreSQL` `Docker` `Python`

- **Streaming architecture:** Kafka consumers → normalized storage → materialized views
- **Low-latency caching:** Sub-10ms reads via Redis for hot data
- **Risk engine:** Portfolio calculations, position limits, exposure tracking
- **Observability:** Full request tracing, P99 latency tracking

**Why it matters:** Handles 10K+ events/sec with strict SLA requirements

</td>
<td width="50%" valign="top">

### 🤖 AgentEval
**AI agent evaluation framework**

`Python` `YAML` `LLM APIs` `CI/CD` `Open Source`

- **Repeatable testing:** YAML test cases for agent behavior
- **Automatic scoring:** Correctness, quality, safety metrics
- **Regression detection:** CI/CD integration for eval gates
- **Metrics-driven iteration:** Track improvements over time

**Why it matters:** Makes LLM application development measurable

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚦 Throttlex
**Rate limiting gateway**

`Java` `Spring Boot` `Redis` `Docker`

- **Multiple algorithms:** Token bucket, fixed/sliding window
- **Distributed state:** Redis-backed rate limiters
- **Policy engine:** Configurable limits per endpoint/user
- **Backpressure handling:** 429 responses with Retry-After

**Why it matters:** Protects downstream services from overload

</td>
<td width="50%" valign="top">

### 🏥 MedGuard
**AI-powered de-identification**

`FastAPI` `NLP` `LLM Validation` `HIPAA`

- **Multi-stage pipeline:** NER → LLM validation → redaction
- **Accuracy focus:** Precision/recall optimization
- **Secure handling:** Patterns for sensitive data workflows
- **Audit trails:** Full lineage tracking

**Why it matters:** Production-grade healthcare data handling

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### Rainbow Table Cracker (Rust)
**High-performance password recovery with B-Tree indexing**

`Rust` `B-Tree` `Concurrency` `Systems Programming`

- **Performance-first design:** Custom B-Tree for billion-scale hash lookups
- **Concurrency:** Lock-free data structures, parallel hash generation
- **Pipeline architecture:** Generator → Reducer → Lookup stages
- **Memory efficiency:** Minimal allocation, cache-friendly layouts

**Why it matters:** Low-level systems work, performance optimization under constraints

</td>
</tr>
</table>

---

## 📈 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=JukaleManmath&show_icons=true&theme=nord&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=79c0ff&text_color=c9d1d9&ring_color=58a6ff" height="170" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com?user=JukaleManmath&theme=nord&hide_border=true&background=0d1117&ring=58a6ff&fire=ff7b72&currStreakLabel=c9d1d9&sideNums=c9d1d9&currStreakNum=c9d1d9&dates=8b949e&sideLabels=c9d1d9" height="170" alt="GitHub Streak" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JukaleManmath&layout=compact&theme=nord&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" alt="Top Languages" />

</div>

---

## 🧩 Problem Solving

<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║  LeetCode: Knight Coder(1904+ Contest Rating)            ║
║             500+ problems solved                          ║
║  ──────────────────────────────────────────────────      ║
║  Strengths: Graphs · DP · Greedy · Intervals             ║
║  Focus: System design patterns in code                   ║
╚══════════════════════════════════════════════════════════╝
```

**Pattern mastery:** Sliding window · Two pointers · DFS/BFS · Backtracking · Union-Find · Topological sort · Bit manipulation · Binary search variations

**Concurrency:** Producer-consumer · Reader-writer locks · Semaphores · Deadlock prevention

**SQL:** Window functions · CTEs · Query optimization · Index design

🔗 [View LeetCode Profile](https://leetcode.com/ManmathJukale)

</div>

---

## 📚 Continuous Learning

**Currently exploring:**
- Advanced Kafka patterns (exactly-once semantics, stream processing)
- Database internals (B-trees, LSM trees, MVCC)
- Rust for systems programming (ownership model, zero-cost abstractions)
- LLM evaluation methodologies (beyond vibes-based testing)

**Recent deep dives:**
- Consistency models in distributed systems (eventual → strong)
- PostgreSQL performance tuning (EXPLAIN ANALYZE, index strategies)
- OpenTelemetry instrumentation patterns

---

## 🤝 Let's Connect

I'm interested in:
- **Backend/Platform engineering roles** where reliability and scale matter
- **Distributed systems problems** that keep you up at night (in a good way)
- **AI infrastructure** challenges beyond just API calls
- **Technical discussions** about trade-offs, failure modes, and operational reality

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/JukaleManmath)
[![Email](https://img.shields.io/badge/Email-jukalemanmath@example.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jukalemanmath@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/JukaleManmath)

</div>

---

<div align="center">

**"Good code is boring code that works when it's supposed to"**

<sub>Profile last updated: April 2026 • Made with ☕ and late-night debugging sessions</sub>

</div>
