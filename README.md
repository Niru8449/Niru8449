# Hi, I'm Nirupama 👋

Software engineer at [Juspay](https://juspay.in), where I build real-time data infrastructure in **Rust**: a Kafka-driven ingestion pipeline that streams payment events into Cassandra, ClickHouse, PostgreSQL and S3 for 50+ services across 14 partner banks. Before that I interned at [Amazon](https://www.amazon.com/), shipping an outage dashboard that went live on Prime Day across 12 marketplaces and is now used by 250+ engineers.

I care about systems that stay correct under load: idempotent writes, dead-letter queues, zero-downtime migrations, and the boring observability that makes 3 a.m. pages short. Lately that interest has turned into building AI agents that can take the 3 a.m. page instead, with enough guardrails that I'd trust one near production.

**B.Tech (IT) + MBA**, ABV-IIITM Gwalior · Mumbai, India

## What I work with

**Languages** `Rust` `Java` `Python` `TypeScript` `SQL` `Bash`

**Data & streaming** `Kafka` `ClickHouse` `Cassandra` `PostgreSQL` `Redis` `MongoDB` `DynamoDB`

**Infra** `Kubernetes` `Helm` `Docker` `AWS` `GCP` `Prometheus` `Jenkins` `GitHub Actions`

**AI** `LLM agents` `tool calling` `RAG` `LangChain` `Pinecone` `Groq`

## Projects worth a look

| Project | What it is | Stack |
|---|---|---|
| [AI On-Call Engineer](https://github.com/Niru8449/AI-On-Call-Engineer) | An LLM agent that triages Prometheus alerts, investigates a Kubernetes cluster through 6 read-only tools, and then fixes, proposes a patch, or escalates. 13 write actions sit behind 4 permission tiers and 8 safety guards, enforced in both code and RBAC. Ships with an evaluation harness that injects 50 reproducible faults into a throwaway cluster and scores from cluster state and audit logs, never from what the agent claims. | Python, Groq, Kubernetes, Helm, Prometheus |
| [CacheFlow](https://github.com/Niru8449/CacheFlow) | A multithreaded distributed cache in Java using consistent hashing, request collapsing and prefetching, with pluggable eviction and write policies. | Java, Redis, MySQL |
| [AeroSense](https://github.com/Niru8449/AeroSense) | Time-series forecasting of air quality with interactive dashboards. | Python |

## Things I've shipped

- At Juspay, A **Rust ingestion pipeline** handling 15+ payload types, with batched multi-store writes that cut end-to-end latency by 90% and ClickHouse query time by 60% at 600 rps peak.
- An **analytics platform** on Kubernetes CronJobs processing 40M+ events a day into 7 fact tables and partner-facing dashboards.
- A **zero-downtime schema migration** on live payment data, using dual writes, reconciliation and safe rollback.
- **Salted SHA-256 protection** for sensitive customer identifiers, with zero-downtime key rotation across all services.
- **40+ integration tests** and CI pipelines on Azure DevOps and Jenkins, plus UAT with partners before go-live.
  
- At Amazon, an **outage dashboard** built with React, Redux and Node.js, adopted by 250+ engineers and launched on Prime Day across 12 marketplaces for real-time outage response.
- Consolidated **300+ mitigation levers** and outage scenarios into a single MongoDB-backed source of truth, improving on-call efficiency by 40%.
- An **intelligent search** with auto-suggestions and advanced filters over that data, supporting 50,000+ concurrent queries.

  
## Elsewhere

[LinkedIn](https://www.linkedin.com/in/nirupamaprofile/) · [LeetCode](https://leetcode.com/u/Nirupama8449/) · [nirupamasingh8449@gmail.com](mailto:nirupamasingh8449@gmail.com)

Most of my day-to-day code lives in private repositories at work, so the activity graph here understates things. The projects above are the ones I'd be happy to walk through in detail.
