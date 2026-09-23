# Backend Engineer

#### Technical Skills: Go, Python, TypeScript, SQL, AWS, Docker, Kubernetes, PostgreSQL, Redis, Terraform, OpenTelemetry

## Education

* B.S., Computer Science, Minor in Mathematics | University of Massachusetts Amherst (*May 2026*) | GPA: 3.75/4.0

## Work Experience

**Open Source Contributor @ Stripe (*September 2026 - Present*)**

* Resolved three backend issues in Stripe CLI involving API error propagation, resource routing, and metadata serialization.
* Standardized HTTP error handling across three command paths, returning nonzero exit codes for failed Stripe API requests.
* Extended Identity Verification Session routing and corrected serialization of punctuated metadata keys.

**Open Source Contributor @ Datadog (*August 2026 - Present*)**

* Standardized AWS ECS cluster-name normalization in Go OpenTelemetry mapping to ensure consistent resource grouping.
* Fixed a serverless log-flushing race by synchronizing asynchronous batch workers during shutdown to prevent log loss.

**Open Source Contributor @ Google (*July 2026 - Present*)**

* Implemented exponential-backoff retries in Google AX’s controller to handle worker resource exhaustion.
* Enabled concurrent gRPC process I/O with cancellation, EOF handling, and race-tested regression coverage.

**Software Engineer Intern @ Finbud AI (*January 2025 - September 2025*)**

* Built a multi-agent financial research service using AutoGen and RAG over 1,000+ pages, reducing research generation from hours to an average of two minutes.
* Developed an event-driven pipeline using MongoDB CDC, RabbitMQ, AWS Lambda, and Qdrant to synchronize retrieval data without full-corpus reindexing.
* Automated CI/CD with GitHub Actions and Amazon ECR to deploy crawler services to AWS Lambda with traceable releases.

**Independent Study @ University of Massachusetts Amherst (*June 2025 - September 2025*)**

* Accelerated preprocessing of 1M+ records by 10× using Pandas and distributed PySpark workflows.
* Orchestrated data ingestion, preprocessing, and model-training dependencies with Apache Airflow.
* Tracked BERT fine-tuning experiments and versioned checkpoints with MLflow, reducing model development cycles by 50%.

## Projects

### Stripe B2B SaaS Billing Dashboard

Developed a full-stack billing platform using **React, Next.js, NestJS, and PostgreSQL**, with tenant isolation, role-based access, and transactional seat allocation designed for 1,000 businesses and 20,000 memberships. Integrated the **Stripe API** for subscription management with idempotent webhook processing, retries, and reconciliation. Added **Redis** caching and **OpenTelemetry** instrumentation, provisioned **AWS ECS** infrastructure with **Terraform**, and built 50+ **Jest and Supertest** tests achieving 85% backend service coverage.

### GoogleDoc — Collaborative Document Editor

Built a Google Docs clone using **Go, WebSockets, and Operational Transformation** to synchronize concurrent document edits. Implemented **PostgreSQL** operation logs and **Amazon S3** snapshots for durable storage and crash recovery. Designed distributed session management with **Kubernetes and etcd leases**, and monitored throughput, latency, and failures using **Prometheus and Grafana**.

## Achievements

* 2nd Place and Best Use of Qualcomm Edge AI — Hackathon at New York University, 300+ participants.
* 47th Place — ICPC Northeast Regional.

## Connect

* [GitHub](https://github.com/giaphoang)
* [LinkedIn](https://www.linkedin.com/in/giapnh/)
* [Email](mailto:giaphnguyen@gmail.com)
