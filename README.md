# Nick Bellows

**Senior marketing manager in the soccer industry transitioning into software and data engineering.**

I currently work as Senior Marketing Manager at U.S. Youth Soccer. Across more than ten years in the U.S. soccer ecosystem, my work has included managing websites and web platforms serving 1M+ annual viewers, writing website code, maintaining site architecture and performance, building analytics and executive reports, and translating business requirements into technical tasks.

I pair that domain experience with an MS and BS in Software Engineering and hands-on portfolio work in Go, TypeScript, Python, SQL, PostgreSQL, APIs, data pipelines, Docker, testing, CI/CD, and AWS-oriented architecture. These repositories demonstrate the engineering work behind my career transition; they are independent portfolio/reference implementations, not systems built for my employer.

## Start here

| Reviewer path | First project | What it demonstrates |
| --- | --- | --- |
| Software engineering | [Learning Center Reference](https://github.com/nick-bellows/learning-center-reference) | Working Go/Next.js/PostgreSQL learner and administrator workflow with OIDC verification, RBAC, persisted progress, derived eligibility, tests, and accessibility automation |
| Data engineering | [Fan Unification Platform](https://github.com/nick-bellows/fan-unification-platform) · [live dashboards](https://nick-bellows.github.io/fan-unification-platform/) | Prefect-orchestrated ingestion, explainable identity resolution, SCD2, dimensional modeling, SQL quality gates, measured linkage, and BI-ready marts |

My current technical focus is deliberately narrow: multi-role learning and eligibility workflows, and trustworthy identity/data integration across disconnected soccer systems.

## Selected engineering work

### [Learning Center Reference](https://github.com/nick-bellows/learning-center-reference)

A fictional soccer-federation learning and eligibility platform. Its working vertical slice verifies identities, resolves database roles, persists course enrollment and ordered lesson progress, projects a learner dashboard, and derives an administrator compliance view from expiring credentials and holds. The stack is Go, Next.js/TypeScript, PostgreSQL, OpenAPI, Docker, and GitHub Actions.

### [Fan Unification Platform](https://github.com/nick-bellows/fan-unification-platform)

A Prefect-orchestrated identity-resolution and dimensional-warehouse pipeline over four synthetic source systems, including a Salesforce-shaped API. It demonstrates incremental and idempotent ingestion, quarantine, explainable matching, SCD2, SQL quality gates, Redshift-oriented design, scheduled CI, and BI-ready marts. Linkage accuracy is measured against generated ground truth, including a published result where the first probabilistic approach lost to the deterministic baseline.

### [Compliance Intelligence Platform](https://github.com/nick-bellows/compliance-intelligence-platform)

An auditable FastAPI reference system for public sanctions-list ingestion, explainable entity matching, information extraction, retrieval, evaluation, and human-review exports. It fails closed when verified source data is unavailable and clearly separates fictional examples from public-source adapters.

### [Airspace Conformance Platform](https://github.com/nick-bellows/airspace-conformance-platform)

Four event-driven Python services use Kafka, PostgreSQL, Redis, OpenAPI, WebSockets, observability, Docker, and Kubernetes to turn synthetic surveillance reports into tracks and advisory alerts. The repository includes contract, integration, end-to-end, performance, and failure-mode evidence, including a model improvement that did not replicate under shifted scenarios.

## Supporting engineering evidence

| Project | Status and engineering signal | Implemented stack |
| --- | --- | --- |
| [Detection Engineering Lab](https://github.com/nick-bellows/detection-engineering-lab) | Fixture-validated Sigma detections, target compilation, evidence manifests, and explicit telemetry-validation limits | Python, Sigma, Elasticsearch, CrowdStrike LogScale, Docker, pytest, GitHub Actions |
| [ES Futures RL Trading Bot](https://github.com/nick-bellows/ES-Futures-RL-TradingBot) | Archived learning project retained for its Python/C# integration boundary and failure analysis—not as a trading-performance claim | Python, PyTorch, Stable-Baselines3, Gymnasium, Pandas, NumPy, NinjaScript/C# |
| [NitroGen Gaming Agents](https://github.com/nick-bellows/nitrogen-gaming-agents) | NVIDIA NitroGen fork with separately identified custom data, configuration, DAgger, and multi-frame tooling | Python, PyTorch, Hugging Face tooling, OpenCV, Windows game integration |
| [Cybersecurity Writeups](https://github.com/nick-bellows/cyber-security-writeups) | Authorized-lab reports retained as supporting evidence; an automated publication audit keeps them de-emphasized pending source redaction | Python, pypdf, PDF content/metadata auditing, GitHub Actions |

## Technologies demonstrated in the repositories

| Area | Evidence |
| --- | --- |
| Application engineering | Go, chi, pgx, TypeScript, Next.js, Python, FastAPI, REST, OpenAPI, OIDC, RBAC |
| Data engineering | Python, SQL, PostgreSQL, Prefect, Pandera, Splink, dimensional modeling, SCD2, ETL, identity resolution |
| Streaming and operations | Kafka, Redis, WebSockets, Prometheus-compatible metrics, OpenTelemetry traces, structured logging |
| ML and experimentation | PyTorch, Stable-Baselines3, Gymnasium, spaCy, sentence transformers, BM25, reproducible evaluation |
| Security engineering | Sigma, Elasticsearch, CrowdStrike LogScale, threat modeling, secret scanning, dependency auditing |
| Cloud and delivery | AWS-oriented Terraform and Redshift designs, Docker, Kubernetes manifests, GitHub Actions, GitHub Pages |
| Quality | Unit, integration, contract, end-to-end, accessibility, performance, data-quality, and evidence-drift tests |

AWS and Kubernetes work is presented at the boundary actually demonstrated: local or CI validation and deployment design, not a paid production deployment. Portfolio soccer/member records are synthetic, and none of these projects is affiliated with or endorsed by U.S. Soccer or any member organization.

## Education and certifications

- MS Software Engineering, AI specialization; BS Software Engineering
- MS Sport Management; BS Parks, Recreation & Tourism Management
- AWS Certified Machine Learning - Specialty and AWS Certified Cloud Practitioner
- CompTIA Data+, Security+, PenTest+, A+, and Project+
- Microsoft Certified: Azure Fundamentals; Practical Junior Penetration Tester
