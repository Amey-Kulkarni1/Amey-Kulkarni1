# Hi, I'm Amey Kulkarni 👋

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ameykulkarni7)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Amey-Kulkarni1)

**Software & Security Integrations Engineer** building distributed telemetry pipelines, resilient API collectors, and fault-tolerant backend systems.

Currently engineering high-throughput SIEM/XDR ingestion pipelines—owning integrations end-to-end from **upstream API & event streams → normalization & enrichment → production deployment**.

---

## 🚀 Engineering Impact & Highlights

- **35+ End-to-End Security Integrations:** Designed, built, and shipped full collector + parser stacks (Python collectors, Logstash/Ruby normalization, and release packaging) across EDR/XDR, CSPM, cloud, email/DLP, OT/IoT, and network/SASE platforms.
- **Event-Driven & Cloud-Native Ingestion:**
  - **AWS:** Built event-driven CloudTrail & Radware WAF consumers over **SQS/SNS** (S3 notification unwrapping, object decoding, digest filtering), hardened **GuardDuty, Inspector, SecurityHub** (S3 + Firehose), and engineered dynamic multi-cluster **Kubernetes S3** prefix discovery.
  - **Microsoft / Azure:** Built **Microsoft Defender XDR** ingestion from scratch (OAuth2, 429 backoff, multi-table watermarking), **Azure AD / Entra ID** async collectors (`asyncio`/`aiohttp`, proactive JWT refresh, persistent disk-backed deduplication), **M365 Copilot/Intune** pipelines, and byte-offset **Azure Blob Storage** streaming (>80% redundant egress reduction).
- **Resilient Distributed Collectors:** Implemented exponential backoff with jitter for HTTP 429 rate limits, sliding lag/backfill windows (CrowdStrike Falcon & FDR), enterprise proxy support, **Kafka-orchestrated** dynamic cron scheduling, and offline Python wheel packaging for air-gapped environments.
- **CSPM, AI/API Security & Network Telemetry:** Delivered collectors and parsers for **Prisma Cloud, Orca Security, Traceable AI, Armis Centrix (OT/IoT), Cisco Meraki, Aruba Central, Cato Networks, Wallarm, Cloudflare, Akamai, Proofpoint, and Trend Micro Vision One**.
- **Production Reliability & Core Pipelines:** Maintained core Ruby/Logstash event classification and schema normalization engines; diagnosed and resolved production issues including Redis null-field crashes, regex-engine restarts, IP-space deduplication bugs, and packaging/compile failures.

---

## 🛠️ Tech Stack

| Area | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python (`asyncio`, `aiohttp`, `tenacity`, `boto3`), Ruby (Logstash plugins), Bash |
| **Backend & APIs** | FastAPI, SQLAlchemy (Async), Alembic, Pydantic, REST / OAuth2 / JWT, Graph API |
| **Streaming & Messaging** | Apache Kafka, Logstash, RabbitMQ (AMQP, DLX/TTL), AWS SQS/SNS, Redis |
| **Databases & Storage** | PostgreSQL, SQLite, AWS S3, Azure Blob Storage |
| **Cloud & Security** | AWS (WAF, GuardDuty, Inspector, SecurityHub, CloudTrail, Firehose), Azure / Entra ID, SIEM/XDR, CSPM, WAAP |
| **DevOps & Observability** | Docker, Docker Compose, GitHub Actions (CI), Prometheus, Grafana, Linux, systemd |
| **Testing & Quality** | Pytest, `pytest-asyncio`, Ruff, Mypy |
| **Security Tooling** | Wireshark, Nmap, Nessus, pfSense, Metasploit |

---

## 💻 Featured Projects

- **[Ingestly](https://github.com/Amey-Kulkarni1/ingestly)** — Fault-tolerant webhook & event ingestion service built with FastAPI, PostgreSQL, RabbitMQ, and Docker. Features a transactional outbox (`FOR UPDATE SKIP LOCKED`), two-tier idempotency, multi-tier TTL retry queues & DLQ replay, Prometheus/Grafana observability, and GitHub Actions CI.
- **SOC Lab** — Hands-on network monitoring, traffic analysis, and incident response lab environment.

---

## 📜 Certifications

- [CompTIA Security+](https://drive.google.com/file/d/1jlXe7Y-hcdg2zlLflYfWWZDUgitSGuru/view?usp=sharing)
