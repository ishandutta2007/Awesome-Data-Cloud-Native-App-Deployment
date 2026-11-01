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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Snowflake Native App Framework](https://docs.snowflake.com/en/developer-guide/native-apps/native-apps-about)**

  **Framework for building data applications that run natively inside Snowflake**. **Features**: Provider/consumer model—providers share data and business logic via application packages; consumers install as database objects . Supports Streamlit apps, stored procedures, and Snowpark functions. Distribution via **Snowflake Marketplace** (free or paid listings) or private listings. **Snowpark Container Services** enables containerized workloads . **Pricing**: Consumption-based (Snowflake credits); Marketplace listings can be paid. **Free tier**: Trial credits. **Best for**: Snowflake customers wanting to monetize data apps without data leaving the warehouse—**trade-off**: requires Snowflake ecosystem; application packages have manifest/install script complexity.



- **[Databricks Apps](https://www.databricks.com/)**

  **Serverless app hosting within Databricks Lakehouse**. **Features**: Build with Streamlit, Dash, or Gradio; deploy via Databricks CLI; **Unity Catalog integration** ensures apps inherit granular data permissions—users only access authorized data, all interactions auditable . **AppKit SDK** forwards user tokens so row/column-level security applies automatically . **Pricing**: Consumption-based (DBUs). **Free tier**: Community Edition limited. **Best for**: Databricks customers wanting secure internal data apps without separate infrastructure—**trade-off**: Python frameworks only; requires Databricks workspace.



- **[Workato Embedded](https://docs.workato.com/en/oem/partner-program)**

  **Embedded iPaaS for SaaS vendors**. **Features**: Integrate Workato into your product via iframe, branded redirect, or managed integration model; **recipe compliance checks** ensure recipes only interact with your app; referral program earns 10% of customer's first-year ARR as credit . **Pricing**: Enterprise pricing; base workspace ~$10K/year, mid-market $30K–$80K, enterprise $150K–$400K+ . **Free tier**: None. **Best for**: SaaS vendors wanting customer-facing integrations without building connector infrastructure—**trade-off**: exposes Workato's recipe builder UI, not fully white-labeled .



- **[Salesforce AppExchange](https://appexchange.salesforce.com/)**

  **Enterprise app marketplace** for Salesforce ecosystem. **Features**: Partners must follow security requirements including **PKCE and Refresh Token Rotation** for Connected Apps/ECAs by May 2026; non-compliance risks de-listing . **Pricing**: Revenue share; security review required. **Free tier**: Free apps available. **Best for**: ISVs building on Salesforce wanting enterprise distribution—**trade-off**: strict security compliance; revenue share.



- **[Shopify App Platform](https://shopify.dev/docs/apps/build)**

  **App development for Shopify merchants**. **Features**: Apps run inside Shopify surfaces using Polaris web components; extensions for Admin, Checkout, Customer Accounts, POS; **Shopify CLI** scaffolds and deploys; **Dev Dashboard** manages credentials and logs . **Pricing**: 15% revenue share (0% for first $1M for eligible developers from 2025) . **Free tier**: Yes, for eligible developers. **Best for**: developers wanting distribution to millions of Shopify merchants—**trade-off**: review process; surface-specific rules.



- **[Stripe Apps](https://docs.stripe.com/stripe-apps)**

  **Custom UI and integrations inside Stripe Dashboard**. **Features**: Build custom interfaces; authenticate third-party users; listen for events; automate workflows; distribute privately or via Stripe Apps Marketplace . **Pricing**: Free to develop; revenue share for paid apps. **Free tier**: Yes. **Best for**: developers wanting to extend Stripe for merchants—**trade-off**: Stripe ecosystem lock-in.



- **[AWS Marketplace](https://aws.amazon.com/marketplace)**

  **Cloud software marketplace** with enterprise procurement integration. **Pricing**: AWS takes a percentage of sales; private offers available. **Free tier**: Free trials available. **Best for**: software vendors wanting enterprise distribution through AWS procurement.



- **[Google Cloud Marketplace](https://cloud.google.com/marketplace)**

  **Cloud software marketplace** for GCP customers. **Pricing**: Revenue share model. **Free tier**: Free trials available. **Best for**: vendors wanting GCP customer distribution.



- **[Microsoft AppSource](https://appsource.microsoft.com/)**

  **Business app marketplace** for Microsoft 365, Dynamics 365, and Power Platform. **Pricing**: Revenue share model. **Free tier**: Free trials available. **Best for**: Microsoft partners wanting enterprise distribution.



- **[Heroku Elements](https://elements.heroku.com/)**

  **Add-on marketplace for Heroku apps**. **Pricing**: Revenue share; add-on pricing varies. **Free tier**: Free add-ons available. **Best for**: developers wanting to extend Heroku apps with third-party services.



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
