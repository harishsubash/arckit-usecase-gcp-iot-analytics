# Fleet IoT Analytics Platform — GCP Architecture Governance

An [ArcKit](https://arckit.org/)-style architecture governance demonstration project: a curated set of AI-assisted governance artifacts for a **real-time IoT fleet analytics platform on Google Cloud**, for a fictional mid-size logistics company.

📖 **[View the documentation site](https://harishsubash.github.io/arckit-usecase-gcp-iot-analytics/)**

## Use Case

The company is moving from nightly CSV batch uploads to real-time streaming analytics for its delivery fleet — Pub/Sub, Dataflow, BigQuery, Bigtable, Cloud Functions, Vertex AI, and Looker Studio — to power geofence alerting, predictive maintenance, and live fleet dashboards.

## What's in Here

This repo follows the ArcKit convention of one governance artifact per architectural concern, versioned and cross-referenced:

| Artifact | Description |
|----------|-------------|
| Architecture Principles | Foundational decisions that constrain every downstream choice |
| Stakeholder Analysis | Who cares about this platform and how they're engaged |
| Requirements | Functional and non-functional requirements, MoSCoW-prioritised |
| Risk Register | Identified risks, likelihood/impact scoring, mitigations |
| Business Case | Strategic, economic, commercial, financial and management case |
| Architecture Strategy | Target state and migration approach from nightly batch |
| Platform Design | Service-level design with architecture and sequence diagrams |
| Architecture Decision Records | Key technology choices with rationale and alternatives considered |

Browse them all in the [documentation site](https://harishsubash.github.io/arckit-usecase-gcp-iot-analytics/), or read the source markdown under [`projects/`](projects/).

## About This Project

This is a **demonstration/portfolio project**, not a real client deliverable. The fictional company, its numbers, and its stakeholders are illustrative. All artifacts were drafted with AI assistance (Claude) and reviewed by [Harish Subash](https://github.com/harishsubash) — always validate AI-generated architecture output with human expertise before using it for real decisions.

The documentation viewer (`docs/index.html`) is reused from the MIT-licensed [ArcKit](https://github.com/tractorjuice/arc-kit) project — see [NOTICE.md](NOTICE.md) for attribution.

## License

MIT — see [LICENSE](LICENSE).
