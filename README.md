# Randy Gregory Rozario

### Solution Developer → Enterprise Solution Architect | Cloud & Platform Engineering | Distributed Systems | AI | Security

I design and deliver **enterprise business solutions that transform fragmented, manual and legacy operational processes into secure, data-driven digital platforms**.

My production experience spans commercial operations, fleet management, procurement, courier performance, expense management and supplies management, supporting **multiple business functions and hundreds of users**.

Alongside my production engineering experience, I maintain an architecture portfolio exploring **distributed systems, cloud platforms, AI, security, DevSecOps, observability, resilience and platform engineering**.

> **My goal is to become a platform-agnostic Enterprise Solution Architect capable of designing solutions based on business requirements, architectural principles and trade-offs—not vendor preference.**

---

## What I Do

I work at the intersection of:

- Business process transformation
- Enterprise application architecture
- Cloud & platform engineering
- Data & analytics
- Integration architecture
- Security & identity
- AI solution architecture
- DevSecOps
- Observability & SRE
- Resilience engineering

My approach is:

**Business Problem → Requirements → Architecture → Engineering → Security → Data → Operations → Measurement → Continuous Improvement**

---

# Production Architecture Experience

## DHL Express — Enterprise Digital Solutions

I have designed and delivered business applications used by operational and commercial teams, transforming paper-based, Excel-driven and legacy processes into digital workflows, centralized data platforms and decision-support systems.

### Selected Production Solutions

| Solution | Users | Business Problem | Outcome |
|---|---:|---|---|
| **BD Cash Lead Navigator** | ~50 | Fragmented Excel, Access, shipment tracking and manual reporting | Reporting effort reduced from **198 → 50 hours/month**; SLA visibility introduced; reported revenue increased ~30% and conversion ~40% |
| **Expense Mobile Claim Approval** | ~200 | Paper-based approval process | Approval turnaround reduced from **~1 week → ~2 hours**; paper processing eliminated |
| **Gemba Ride Tool** | ~100 | Paper-based courier efficiency assessment | Assessment time reduced from **3–4 hours → ~1 hour**; reported route efficiency +30%; SLA compliance +20% |
| **Fleet Expense Management** | 30+ | Scattered Excel records across ~150 vehicles and ~1,000 requisitions | Duplicate/missing records reduced to **<1%**; vehicle and vendor cost visibility enabled |
| **Supplies Management System** | ~100 | Legacy desktop system with limited resilience and centralized dependency | Digital requisition, inventory and consumption management across stakeholders |

> Business metrics are presented as observed or reported outcomes associated with the solutions; they are not intended to imply that every business result was caused solely by the software.

---

# Selected Architecture Case Studies

My GitHub projects are **portfolio and architecture exploration projects** designed to demonstrate architectural reasoning, engineering implementation, controlled testing and measurable technical behaviour.

They are not presented as production systems operating at enterprise scale.

---

## 01 — Distributed Systems & Event-Driven Architecture

### [`microservices-arch`](https://github.com/RandyRozario/microservices-arch)

A distributed inventory and reservation system exploring **concurrency, consistency, event-driven processing and failure handling**.

**Architecture**

`Fastify → Kafka → PostgreSQL → Redis → Consumers → DLQ`

**Controlled test evidence**

- 1,000 concurrent reservation requests
- 244 req/s observed during controlled local load testing
- Zero overselling observed across concurrency tests
- Kafka-based durable event processing
- Dead-letter handling for failed events

**Architecture questions explored**

- Microservices vs modular monolith
- Event-driven vs synchronous integration
- Idempotency
- Distributed locking
- Consistency models
- Failure recovery

---

## 02 — Secure Multi-Tenant SaaS

### [`multitenant-saas`](https://github.com/RandyRozario/multitenant-saas)

A multi-tenant SaaS architecture using **PostgreSQL Row-Level Security** as a database-enforced tenant isolation boundary.

**Architecture**

`Application → PostgreSQL → RLS → Tenant-Isolated Data`

**Controlled security testing**

- 24 cross-tenant security scenarios
- Unauthorized cross-tenant access blocked
- Legitimate tenant access validated
- Database-level isolation enforced through RLS

**Architecture questions explored**

- Shared database vs database-per-tenant
- Application vs database security boundaries
- Tenant isolation
- Least privilege
- SaaS scalability

---

## 03 — Cloud & Platform Architecture

### [`platform-fabric`](https://github.com/RandyRozario/platform-fabric)

A cloud platform engineering exploration demonstrating **Infrastructure as Code, Kubernetes, network segmentation, secrets management and platform automation**.

**Architecture**

`Terraform → Network → Kubernetes → Services → Data → Secrets → Observability`

**Focus**

- Infrastructure as Code
- Kubernetes
- Network segmentation
- Private data tiers
- Secrets management
- Ingress
- Platform automation

---

## 04 — Multi-Agent AI Architecture

### [`ai-agent-fleet`](https://github.com/RandyRozario/ai-agent-fleet)

A stateful multi-agent architecture exploring **agent orchestration, specialization, retrieval grounding and persistent execution state**.

**Architecture**

`API → Orchestrator → Specialized Agents → RAG → Persistent State`

**Controlled testing**

- Four specialized agent nodes
- Stateful multi-turn execution
- Persistent execution state
- 1,001 processed messages
- ~800 ms average response benchmark under the project's test conditions

**Architecture questions explored**

- Single-agent vs multi-agent systems
- Agent specialization
- State management
- Retrieval grounding
- AI reliability
- Model abstraction

---

## 05 — DevSecOps & Software Supply Chain Security

### [`secure-supply-chain`](https://github.com/RandyRozario/secure-supply-chain)

A CI/CD security architecture designed to prevent vulnerable or compromised artifacts from reaching deployment environments.

**Pipeline**

`Secret Detection → SAST → SBOM → Container Scanning → Image Validation → Deployment`

**Security tooling**

`Gitleaks · Semgrep · Syft · Trivy · Hadolint`

**Focus**

- Shift-left security
- Software supply-chain security
- SBOM
- Vulnerability gates
- Container security
- Automated policy enforcement

---

# Complete Architecture Portfolio

The broader portfolio contains additional architecture explorations across AI, data, security, platform engineering, SRE and cloud.

| Domain | Project | Focus |
|---|---|---|
| Distributed Systems | [`microservices-arch`](https://github.com/RandyRozario/microservices-arch) | Kafka, concurrency, event-driven architecture |
| FinOps | [`finops-anomaly-engine`](https://github.com/RandyRozario/finops-anomaly-engine) | Cloud cost anomaly detection |
| AI | [`ai-agent-fleet`](https://github.com/RandyRozario/ai-agent-fleet) | Multi-agent orchestration |
| AI / Data | [`rag-engine`](https://github.com/RandyRozario/rag-engine) | RAG, vector search, grounding |
| SaaS Architecture | [`multitenant-saas`](https://github.com/RandyRozario/multitenant-saas) | Multi-tenancy, PostgreSQL RLS |
| Identity & Security | [`rbac-engine`](https://github.com/RandyRozario/rbac-engine) | RBAC, JWT, auditability |
| Application Architecture | [`lead-navigator`](https://github.com/RandyRozario/lead-navigator) | React, TypeScript, application architecture |
| Observability | [`observability-stack`](https://github.com/RandyRozario/observability-stack) | Prometheus, Grafana, golden signals |
| Disaster Recovery | [`dr-pipeline`](https://github.com/RandyRozario/dr-pipeline) | Multi-region DR and failover |
| DevSecOps | [`secure-supply-chain`](https://github.com/RandyRozario/secure-supply-chain) | Software supply-chain security |
| Platform Engineering | [`enterprise-platform`](https://github.com/RandyRozario/enterprise-platform) | Kubernetes, Terraform, platform automation |
| Cloud Architecture | [`platform-fabric`](https://github.com/RandyRozario/platform-fabric) | Cloud infrastructure, networking, Vault |
| SRE / Governance | [`chaos-mesh`](https://github.com/RandyRozario/chaos-mesh) | Chaos engineering, resilience, policy-as-code |

---

# Architecture Domains

```text
                         ENTERPRISE
                         ARCHITECTURE
                              │
       ┌──────────────────────┼──────────────────────┐
       │                      │                      │
 APPLICATION              DATA & AI              SECURITY
 ARCHITECTURE            ARCHITECTURE           ARCHITECTURE
       │                      │                      │
 Microservices              RAG                   IAM / RBAC
 Event-Driven              Agents                 Zero Trust
 APIs                      Vector DB              DevSecOps
 Kafka                     Analytics              Supply Chain
       │                      │                      │
       └──────────────────────┼──────────────────────┘
                              │
                     CLOUD & PLATFORM
                       ARCHITECTURE
                              │
                 Kubernetes · Terraform
                              │
       ┌──────────────────────┼──────────────────────┐
       │                      │                      │
      SRE               OBSERVABILITY           RESILIENCE
       │                      │                      │
   Reliability            Metrics              Chaos Testing
   Recovery               Dashboards            DR / Failover
   Governance             Golden Signals        Recovery
       │                      │                      │
       └──────────────────────┼──────────────────────┘
                              │
                        BUSINESS VALUE
```

---

# Architecture Philosophy

> **Technology is an implementation choice. Architecture is the discipline of making the right trade-offs.**

I evaluate architectural decisions across:

**Business Value · Security · Scalability · Reliability · Performance · Cost · Operability · Governance · Vendor Portability**

For every significant architectural decision, I ask:

- What business requirement drives this decision?
- What alternatives were considered?
- What trade-off are we accepting?
- What happens when a dependency fails?
- Where is the security boundary?
- What are the consistency guarantees?
- How does the architecture behave at 10× scale?
- What are the operational and financial implications?
- How does the design evolve across cloud providers?
- Which components should remain vendor-neutral?

---

# Engineering Principles

1. **Business requirements drive architecture.**
2. **Security is an architectural property, not an afterthought.**
3. **Every critical dependency requires a failure strategy.**
4. **Observability must be designed into the system.**
5. **Infrastructure should be reproducible.**
6. **Resilience should be tested, not assumed.**
7. **Architecture decisions should be explicit and reviewable.**
8. **Vendor services are implementation choices, not architectural principles.**
9. **Performance claims should be supported by measurable evidence.**
10. **Enterprise architecture must balance technology, risk, cost and business value.**

---

# Technology Domains

### Cloud & Infrastructure

`AWS` · `Terraform` · `Kubernetes` · `Docker` · `LocalStack` · `Vault` · `NGINX`

### Distributed Systems

`Kafka` · `Redis` · `Fastify` · `Node.js` · `PostgreSQL`

### AI Engineering

`Python` · `LangGraph` · `LangChain` · `RAG` · `ChromaDB` · `LLMs` · `FastAPI`

### Security

`RBAC` · `JWT RS256` · `PostgreSQL RLS` · `Gitleaks` · `Semgrep` · `Trivy` · `Syft` · `OPA/Rego`

### Observability & SRE

`Prometheus` · `Grafana` · `Chaos Engineering` · `Golden Signals`

### Application Engineering

`React` · `TypeScript` · `Vite` · `Storybook` · `Zustand`

### Enterprise Platforms

`Microsoft 365` · `Power Platform` · `Power Apps` · `Power Automate` · `Power BI` · `Dataverse` · `SharePoint`

---

# Professional Direction

I am progressing from hands-on **Solution Development toward Enterprise Solution Architecture**, with a focus on becoming capable of designing platform-agnostic solutions across:

`AWS` · `Azure` · `GCP` · `SAP` · `Oracle` · `Salesforce` · `ServiceNow` · `Microsoft`

My objective is not to optimize for a specific vendor.

It is to understand the **business, architectural and engineering principles behind technology choices**, and select the appropriate implementation based on requirements, constraints, risk and value.

---

# Connect

- [GitHub](https://github.com/RandyRozario)
- [LinkedIn](https://www.linkedin.com/in/randygregoryrozario)
- [LeetCode](https://leetcode.com/u/randyrozario/)

---

> **Architecture is not about choosing the most powerful technology. It is about making the right trade-offs for the business, the system and the people who operate it.**
