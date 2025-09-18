# kyndryl_15th_platform

```
Platform Engineering Perspective:
•	Four pillars:
o	Abstraction (scaffolds, templates)
o	Standardization (CI/CD, GitOps-ready pipelines)
o	Self-Service (Backstage UI + plugins)
o	Observability (Prometheus + Grafana)

•	Training is designed to align directly with your TOC objectives. Each hands-on lab mapped to a core pillar of platform engineering — including service scaffolding, CI/CD standardization, secure infrastructure, observability, and Backstage-based developer self-service. Labs  covers GitHub OAuth, CI/CD with security scans, click-to-deploy pipelines, metrics collection with Prometheus, dashboarding with Grafana, and TechDocs — all within a IDP-powered platform. This ensures the team not only will learn the concepts but also implement a full-stack Internal Developer Platform (IDP) prototype, exactly as defined in the training scope.

•	Training fully aligns with the Platform Engineering Certified Practitioner (PECP) exam domains. Trainees will have hands-on exposure to platform foundations, Golden Paths, GitOps-based CI/CD, secure infra provisioning, observability, and internal developer portals via Backstage. Each lab maps directly to PECP core competencies — including service scaffolding, SAST/DAST integration, policy enforcement, and TechDocs. With these real-world labs and architectural discussions, trainees are not only exam-ready but also equipped for immediate platform implementation in production environments.
```



```
📅 Day 1 – Foundations of Platform Engineering & Developer Portals
🎯 Goal: Establish a shared understanding of Platform Engineering, developer pain points, and set the foundation for building an Internal Developer Platform (IDP) with Backstage.
________________________________________
🧠 Key Concepts
•	Platform Engineering 101 – Core principles & benefits
•	Platform Engineering vs DevOps – Why IDPs are the next evolution
•	Developer Pain Points & Value Proposition – one click deploys, unified portals, observability
•	What is an Internal Developer Platform (IDP)?
•	Why Backstage is the “frontend” of a modern platform
•	IDP Reference Architecture 
•	🌟 Platform Success Metrics (DORA, MTTR, Deployment Frequency) (Discuss measuring developer productivity and IDP impact on business goals.)
o	MVP lifecycle: Discover → Design → Build → Validate

________________________________________
🧪 Hands On Labs
Lab	Description
Lab 1 – Set up Backstage Developer Portal (Local/Cloud)	Install Backstage as the face of the IDP. Configure for local/cloud access.
Lab 2 – Explore Backstage UI	Explore Service Catalog, TechDocs, and plugin architecture.
Lab 3 – Add GitHub Pull Requests Plugin	Integrate the PR plugin and view repo PR metrics.
Lab 4 – Register a Sample Service	Add a service with catalog-info.yaml into Backstage catalog.
Lab 5 – Enable GitHub OAuth Login	Configure OAuth so users can log in and see personalized PR data.
```
```
________________________________________
📅 Day 2 – Golden Paths & Developer Self-Service Workflows
🧠 Key Concepts
•	Golden Paths: What, Why, and How to Design for Developer Experience (DevEx)
•	Service Scaffolding in IDPs (Backstage Software Templates)
•	AI-Assisted Template Scaffolding and Recommendations 
•	Chatops provisioning
•	Slack bot suggests correct template via OpenAI
•	🌟 Backstage IDP Plugin Ecosystem Overview (Briefly introduce key Backstage plugins developers can explore to extend the IDP in the future.)
🧪 Hands-On Labs
✅ Lab 4: Golden Path Demo using backstage software Template
Scaffold a microservice with standard template.
🔗 Backstage Integration:
Register scaffolded service as a Component in Backstage Catalog for discoverability.
✅ Lab 5: Containerize Service & Run in Docker
Package and run containerized service.
```

```
________________________________________
📅 Day 3 – Infrastructure, Security & Catalog Expansion
🎯 Goal: Provision secure infrastructure with guardrails and integrate resources & pipelines into Backstage for unified visibility.
🧠 Key Concepts
•	Infrastructure as Code (IaC): Terraform Modules
•	CI/CD as Self-Service Offerings in an IDP
o	GitHub Actions, Jenkins, GitLab CI/CD
•	Auto-triggered tests, rollbacks, and security scanning
•	Secure Pipelines: SBOM, SAST/DAST, CVE scanning
•	Expanding the IDP Catalog with infrastructure and pipelines
🧪 Hands-On Labs
✅ Lab 7: Terraform Secured Infra Module (VPC, S3 with encryption)
Provision secured infra.
🔗 Backstage Integration:
•	Register provisioned infra as Resource entities in Catalog.
✅ Lab 8: Build Reusable CI/CD Pipeline with GitHub Actions (SBOM + SAST)
Set up secure CI/CD pipelines.
🔗 Backstage Integration:
Expose pipeline status in Backstage using GitHub Actions plugin.
Lab 8.1: Secure Secrets Management in Pipelines & Backstage Catalog (NEW)
•	Store secrets (e.g., API keys) in GitHub Actions Encrypted Secrets.
•	Update pipeline to consume secrets securely.
•	🔗 Backstage Integration: Annotate Catalog to link pipeline secrets metadata and provide developers visibility.

✅ Lab 9: Add TechDocs for Service Documentation
Publish API and service documentation into Backstage TechDocs for easy consumption.
```

```
________________________________________
📅 Day 4 – Observability, Plugins & Team Enablement
🎯 Goal: Enable observability, monitoring, and enhance the IDP with plugins for developer self-service.
🧠 Key Concepts
•	Observability Stack: Prometheus, Grafana , EFK/ELK, OpenTelemetry
•	Self-Service Developer Portals in Action:
o	Service Catalog
o	Pipeline Triggers
o	Secrets Management
🧪 Hands-On Labs
✅ Lab 10: Instrument Flask App with Prometheus Metrics & Build Grafana Dashboards
🔗 Backstage Integration:
Configure Backstage Grafana plugin to view dashboards directly from Catalog.
✅ Lab 11: Add More Backstage Entities (Group, User, Resource, System, Domain)
Organize Backstage Catalog for teams and systems alignment.
```

```
📊 Why This Structure Wows
✅ Strong focus on IDP concepts and hands-on workflows
✅ Backstage integrated side-by-side across all labs
✅ Highlights Developer Experience (DevEx) and platform as a product mindset
✅ Trainees leave with a working IDP prototype and a clear understanding of its architecture and operation
```


