# VERITAS-AIDB

**Trust First, Ontology-Aware, Agentic AI-Powered, Fully Connected Polyglot DataOps Ecosystem**

> A single source of truth for autonomous industrial systems and linked agentic AI.

---

## What is VERITAS?

VERITAS is an open-source architecture for **industrial DataOps** that intelligently routes heterogeneous data across specialized databases using trust scoring and domain ontologies. Designed for wind energy, extensible to any industrial domain.

### Core Capabilities

- **Ontology-Driven Routing** — Data validated against domain ontologies (OWL/RDF) and routed to the right database
- **Dual-Uncertainty Trust Scoring** — Quality assessment with confidence bounds, not just point estimates
- **Polyglot Persistence** — 7 specialized databases (PostgreSQL, Neo4j, Qdrant, OpenSearch, TimescaleDB, Redis, Hyperledger Fabric)
- **Cross-Database Provenance** — Global UUID linkage tracking data lineage across all stores
- **GraphRAG Retrieval** — Knowledge graph + vector + full-text fusion for grounded AI reasoning
- **Agentic AI Orchestration** — Multi-agent systems with memory management and trace observability
- **Blockchain Trust Anchoring** — Hybrid on-chain/off-chain architecture with trust-scored routing

### Extended Medallion Architecture

| Layer | Description | Trust Level |
|-------|-------------|-------------|
| Bronze | Data Lake (MinIO/S3) — raw, immutable | Unvalidated |
| Silver | Quality Pipeline Output — validated, standardized | Assessed |
| Gold | Analytics Products — pre-computed, optimized | Verified |
| Platinum | Blockchain-anchored — immutable audit trail | Trusted |

## Repositories

| Repository | Purpose | License | Status |
|-----------|---------|---------|--------|
| [veritas-spec](https://github.com/Veritas-aidb/veritas-spec) | Architecture specifications, RFCs, ADRs | Apache 2.0 | Available |
| [veritas-ontology](https://github.com/Veritas-aidb/veritas-ontology) | Wind energy domain ontology (OWL/RDF) | CC BY 4.0 | Available |
| [veritas-adapters](https://github.com/Veritas-aidb/veritas-adapters) | Database connectors and integration code | Apache 2.0 | Available |
| [veritas-core](https://github.com/Veritas-aidb/veritas-core) | Core orchestrator, trust scoring, routing engine | Apache 2.0 | Coming Q1 2026 |
| [veritas-examples](https://github.com/Veritas-aidb/veritas-examples) | Tutorials, quickstart, Jupyter notebooks | MIT | Coming Q2 2026 |

## Research Foundation

Architecture validated against **40+ academic papers** across data engineering, agentic AI, polyglot persistence, uncertainty quantification, and industrial cybersecurity. Eight novel contributions confirmed — see [veritas-spec](https://github.com/Veritas-aidb/veritas-spec) for details.

## Affiliations

- [**IntelliWind**](https://www.intelliwind.eu/danyalkhansage) — EU MSCA Project (Universidad de Granada)
- [**IPM Labs**](https://ipmlab.ugr.es/es/principal/) - Universidad de Granada
- [**CD Foundation**](cd.foundation/dataops) — DataOps Initiative Contributor
- **Linux Foundation** — Open-source governance and community

## Get Involved

We welcome contributions across database adapters, ontology extensions, evaluation frameworks, and documentation. See individual repository CONTRIBUTING.md files for guidelines.

- **Discussions**: [GitHub Discussions](https://github.com/orgs/Veritas-aidb/discussions)
- **Issues**: Check repos for `good first issue` labels
- **Contact**: [Dan Sage Khan](https://www.linkedin.com/in/sagekhan) (MSCA Scholar, Universidad de Granada)
