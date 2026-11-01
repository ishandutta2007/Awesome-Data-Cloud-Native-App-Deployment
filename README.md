# Awesome-Data-Cloud-Native-App-Deployment

# Awesome-Data-Cloud-Native-App-Deployment

**Top Data Cloud Native App Deployment (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Data-Native App Frameworks, Marketplace Distribution, Embedded iPaaS & Self-Hosted Developer Platforms*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Cloud Native App Deployment**. These tools enable developers to build applications that run natively inside data platforms—accessing governed data, sharing business logic, and distributing through marketplaces—from fully managed frameworks like Snowflake Native Apps and Databricks Apps to open-source developer portals and embedded integration platforms that give teams control over their deployment infrastructure.



**Examples** include Snowflake Native App Framework, Databricks Lakehouse Apps, Salesforce AppExchange, AWS Marketplace, Shopify App Platform, Workato Embedded, Stripe Apps, Google Cloud Marketplace, Heroku Elements, and Microsoft AppSource (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted data app deployment, developer portals, and open embedded integration infrastructure. **Critical note**: True open-source equivalents to Snowflake Native Apps or Databricks Apps do not exist—these are proprietary frameworks tied to their platforms. The open-source landscape addresses adjacent layers: **Backstage** for developer portals and software catalogs, **OpenChoreo** for Kubernetes-native internal developer platforms, and **Flowfile** for self-hosted data pipelines. For embedded integrations (Workato's domain), no mature open-source alternative exists.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The Data Cloud Native App Deployment and Cloud Marketplace ecosystem represents an estimated **$30B+** addressable market, projected to expand past **$150B+ by 2030** driven by enterprise cloud commitments and data-native AI application frameworks. The infrastructure and marketplace hosting layer is **highly concentrated** among an oligopoly of hyperscalers and data giants (Microsoft, AWS, Google Cloud, Salesforce, Databricks, Snowflake) operating under winner-take-most platform network effects, while the application and embedded integration layer atop them remains **moderately fragmented** with specialized ISVs and developer tooling vendors competing for marketplace distribution.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Market Cap | Pricing (Specific Starting Tiers) | Free Tier Limits (Forever Plan or Free Trial) | Key Capabilities & Ecosystem |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft AppSource](https://appsource.microsoft.com/)** | ~$3.1T Market Cap (Microsoft) | **3%** store service fee on transactable sales; $0 listing fee for non-transacting offers | **30-day free trial** with full software feature access; requires active Microsoft/Azure billing account | Commercial marketplace storefront for Microsoft 365, Dynamics 365, and Power Platform apps. |
| **[AWS Marketplace](https://aws.amazon.com/marketplace)** | ~$2.2T Market Cap (Amazon) | **3.0%** listing fee on SaaS and AWS Data Exchange (<$1M TCV); scales to **2.0%** ($1M–$10M) and **1.5%** (≥$10M); 20% on AMIs/containers | **Free trial configured per seller** (typically 15 to 30 days) covering software fees; AWS infrastructure usage billed separately; $0 marketplace listing creation fee | Central enterprise marketplace offering streamlined procurement, private offers, and automated billing through AWS accounts. |
| **[Google Cloud Marketplace](https://cloud.google.com/marketplace)** | ~$2.1T Market Cap (Alphabet) | **3.0%** publisher revenue share for standard public and private offers under $1M; **2.0%** ($1M–$10M); **1.5%** (≥$10M) | **Free trial with seller-specified credit/days limit** (e.g., 30 days or $100–$500 software credit); underlying GCP compute/storage billed separately; Google Cloud offers 90-day/$300 trial for new GCP accounts (requires upgrade to paid billing for marketplace access) | Cloud software distribution and procurement platform integrated into Google Cloud customer billing. |
| **[Salesforce AppExchange](https://appexchange.salesforce.com/)** | ~$320B Market Cap (Salesforce) | **15%** standard Percentage Net Revenue (PNR) share for paid apps; **$999** security review fee per submission attempt | **Perpetually free tier for free apps** ($0 security review fee, $0 revenue share); 30-day free trials typically offered for paid apps | Leading enterprise SaaS marketplace distributing connected apps and extensions with strict compliance and security reviews. |
| **[Databricks Apps](https://www.databricks.com/)** | ~$134B Valuation (Late 2025 Series K/L) | **$0.07 to $0.55 per DBU** depending on compute tier and workload (Jobs vs. All-Purpose/Serverless Compute) | **14-day free trial** with up to $400 in Databricks usage credits; perpetually free **Community Edition** with single-micro-cluster allocation for non-commercial learning | Serverless application hosting inside Databricks Lakehouse with automatic Unity Catalog governance inheritance and AppKit SDK support. |
| **[Shopify App Platform](https://shopify.dev/docs/apps/build)** | ~$115B Market Cap (Shopify) | **0%** revenue share on first **$1,000,000** lifetime gross revenue; **15%** revenue share above $1M threshold; **$19** one-time developer registration fee; 2.9% payment processing fee | **Perpetually free tier**: 0% rev share on first $1M gross app revenue for eligible partners; unlimited sandbox and development stores under Shopify Partner accounts | App store distribution reaching millions of Shopify merchants with Polaris UI components and checkout extensions. |
| **[Stripe Apps](https://docs.stripe.com/stripe-apps)** | ~$91.5B Valuation (2025 Tender Offer) | **0%** marketplace revenue share; standard Stripe payment processing fee of **2.9% + $0.30** per transaction applies to billed payments | **Perpetually free tier**: $0 developer registration fee, free sandbox testing environment, and $0 platform fee for free marketplace apps | Extensions and custom UI integrations embedded directly inside the Stripe Merchant Dashboard. |
| **[Snowflake Native App Framework](https://docs.snowflake.com/en/developer-guide/native-apps/native-apps-about)** | ~$60B Market Cap (Snowflake) | **$2.00/credit** (Standard Edition), **$3.00/credit** (Enterprise Edition), **$4.00/credit** (Business Critical Edition); compute billed per second (60s minimum) | **30-day free trial** with **$400** in platform credits (expires after 30 days or credit exhaustion) | Build, distribute, and monetize containerized and data applications running natively inside the consumer's Snowflake warehouse. |
| **[Workato Embedded](https://docs.workato.com/en/oem/partner-program)** | ~$5.7B Valuation (Series E) | Base workspace starting at **$10,000/year**; mid-market deployments typically **$30,000–$80,000/year** | **Perpetually free self-service tier with a one-time grant of 50,000 credits** (does not renew monthly; expires once 50,000 credits are consumed across tasks/APIs) | Embedded integration platform (iPaaS) allowing SaaS software vendors to deliver white-labeled customer-facing integrations. |
| **[Heroku Elements](https://elements.heroku.com/)** | Sub-unit of Salesforce (~$320B Parent Market Cap) | **30%** Heroku marketplace revenue share (70% net revenue paid to add-on partner); base developer dynos start at **$5/month** (Eco dynos pool) | **Perpetually free add-on plan tier** available for partner listings; dyno environment offers $5/mo shared pool of 1,000 Eco dyno hours that sleep after 30m inactivity | Add-on and integrations marketplace for Heroku PaaS developers and applications. |

## Open-Source GitHub Projects



- **[Backstage](https://github.com/backstage/backstage)**

  **Open source framework for building developer portals** (Apache-2.0, CNCF Incubation) — **the most widely adopted open-source developer portal**, created by Spotify and now CNCF-hosted . **Features**: **Software Catalog** for managing microservices, libraries, data pipelines, websites, and ML models; **Software Templates** for spinning up new projects with organizational best practices; **TechDocs** for docs-like-code documentation; **plugin ecosystem** for extensibility; unified experience across infrastructure tooling, services, and documentation . **Tech stack**: TypeScript, React, Node.js. **Deploy**: Self-hosted or Backstage Cloud. **Trade-off**: **Portal framework, not a data app deployment platform**—it catalogs and scaffolds apps but does not host them or manage data access like Snowflake Native Apps. **Best for**: platform teams wanting a centralized developer portal to standardize app creation and discovery—the closest open-source analog to an internal app marketplace.



- **[OpenChoreo](https://github.com/openchoreo/openchoreo)**

  **Open-source internal developer platform for Kubernetes** (Apache-2.0, CNCF Sandbox) — **the most complete open-source IDP for deploying apps on Kubernetes** . **Features**: **Multi-plane architecture**—control, runtime, workflows, observability; **CI/CD, GitOps (FluxCD), observability, identity, audit logs, cost insights** included and swappable; **Backstage developer portal** integration; **CLI, API, and MCP servers** for AI agents; **self-service databases, queues, caches**; **AI agents with guardrails** . **Tech stack**: Go, Kubernetes. **Deploy**: Self-hosted (Kubernetes). **Trade-off**: **Kubernetes-native, not data-platform-native**—it deploys containerized apps, not Snowflake/Databricks native apps. **Best for**: platform teams wanting a production-grade IDP with self-service and AI agent support on Kubernetes—the open-source alternative to building a developer platform from scratch.



- **[Flowfile](https://pypi.org/project/Flowfile/)**

  **Open-source data platform with visual pipeline builder** (Apache-2.0) — **the most accessible open-source data app foundation** . **Features**: **Visual pipeline builder** with 30+ nodes (joins, filters, aggregations, fuzzy matching, pivots); **data catalog with Delta Lake storage**, version history, and lineage; **scheduling** (interval or table-trigger); **Kafka/Redpanda ingestion**; **sandboxed Python execution** in Docker containers; **code generation**—export visual flows as standalone Python/Polars scripts; **Polars-compatible Python API**; cloud storage (S3, ADLS, GCS) and database connectivity . **Tech stack**: Python, Polars, Delta Lake. **Deploy**: `pip install Flowfile`; `flowfile run ui` . **Trade-off**: **Data pipeline and catalog, not a deployment platform**—it builds data apps but does not provide app hosting or marketplace distribution. **Best for**: data teams wanting a self-hosted visual ETL and catalog foundation for building data applications—without SaaS costs.



### Additional Strong Open-Source Options



- **Apache Gravitino** — Open-source federated metadata catalog (Apache-2.0, Apache TLP) . **Features**: Unified metadata across data warehouses, lakes, lakehouses, streaming platforms, and AI systems; **MCP Server** for AI agent access; **Model Catalog** for ML models . **Note**: **Catalog, not an app deployment framework**—it manages metadata but does not host or deploy apps. **Best for**: organizations needing unified metadata for data and AI assets before building apps on top.

- **No mature open-source equivalent to Snowflake Native Apps or Databricks Apps exists.** These frameworks are proprietary and tied to their platforms. **Backstage** and **OpenChoreo** address developer portal and Kubernetes deployment layers but not data-platform-native app hosting.



**Frameworks for building custom systems**: Combine **Backstage** for developer portal and app catalog with **OpenChoreo** for Kubernetes-native deployment and **Flowfile** for data pipeline and catalog—creating a limited open-source data app deployment stack. **None of these match Snowflake Native Apps' provider/consumer model or Databricks' Unity Catalog inheritance.**



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data app deployment platforms handling application logic and data access must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "data-platform-native framework" vs. "developer portal" vs. "Kubernetes IDP" vs. "data pipeline tool" distinction is critical.** **Snowflake Native App Framework** and **Databricks Apps** are **data-platform-native frameworks**—they run apps inside the data platform with inherited governance . **Backstage** is a **developer portal**—it catalogs and scaffolds apps but does not host them . **OpenChoreo** is a **Kubernetes IDP**—it deploys containerized apps, not data-platform-native apps . **Flowfile** is a **data pipeline tool**—it builds data flows but does not deploy apps . **Choose based on whether you need native data platform integration, app discovery, Kubernetes deployment, or data pipeline building.**

- **Snowflake Native Apps and Databricks Apps are fundamentally different from open-source tools.** They run inside the data platform, inherit its security model, and distribute through its marketplace. **No open-source project replicates this**—the closest analogs (Backstage, OpenChoreo) address different layers entirely.

- **Workato Embedded is not fully white-labeled.** It surfaces Workato's recipe builder UI to end users, described as "building a Zap inside someone else's product" . **For SaaS vendors prioritizing brand experience, this is a limitation.**

- **Salesforce AppExchange security requirements are tightening.** PKCE, Refresh Token Rotation, Idle Refresh Token TTL, and IP Range Allow List must be implemented by **May 11, 2026**; non-compliance risks de-listing . **ISVs must plan for this compliance deadline.**

- **Backstage is the most widely adopted open-source developer portal** (CNCF Incubation, created by Spotify) . **The trade-off**: it catalogs and scaffolds but does not host apps—pair with OpenChoreo or a deployment platform for the full stack.

- **OpenChoreo is the most complete open-source Kubernetes IDP** (CNCF Sandbox, from WSO2) . **The trade-off**: Kubernetes-native, not data-platform-native—it will not run Snowflake Native Apps.

- **Pricing opacity varies.** Snowflake and Databricks are consumption-based. Workato is enterprise quote-only ($30K–$400K+). Salesforce, Shopify, Stripe, AWS, Google, Microsoft, and Heroku have revenue share or usage-based models. **Validate with direct vendor conversations against your distribution goals and platform requirements.**

- Self-hosted open-source solutions require proper infrastructure (Kubernetes for OpenChoreo, Python for Flowfile, Node.js for Backstage), security hardening, and ongoing maintenance. **App deployment platforms handle application code and data access**—ensure your deployment meets your organization's security and governance requirements before connecting production data.



---



**Made for platform engineers, data app developers, and organizations building transparent deployment solutions.**

Let's make Data Cloud Native App Deployment more open, data-driven, and developer-friendly.
