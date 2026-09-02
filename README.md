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

## Technologies demonstrated in the repositories

| Area | Evidence |
| --- | --- |
| Application engineering | Go, TypeScript, Next.js, Python, FastAPI, REST, OpenAPI |
| Data engineering | Python, SQL, PostgreSQL, Prefect, dimensional modeling, ETL, identity resolution |
| Cloud and delivery | AWS-oriented Terraform and deployment designs, Docker, Kubernetes, GitHub Actions, GitHub Pages |
| Quality and operations | Unit/integration/end-to-end tests, data-quality gates, structured logs, metrics, traces, runbooks, and evidence-backed failure analysis |

AWS and Kubernetes work is presented at the boundary actually demonstrated: local or CI validation and deployment design, not a paid production deployment. Portfolio soccer/member records are synthetic, and none of these projects is affiliated with or endorsed by U.S. Soccer or any member organization.

## Education and certifications

- MS Software Engineering, AI specialization; BS Software Engineering
- MS Sport Management; BS Parks, Recreation & Tourism Management
- AWS Certified Machine Learning - Specialty and AWS Certified Cloud Practitioner
- CompTIA Data+, Security+, PenTest+, A+, and Project+
- Microsoft Certified: Azure Fundamentals; Practical Junior Penetration Tester
