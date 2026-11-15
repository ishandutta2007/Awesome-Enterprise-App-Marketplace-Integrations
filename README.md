# Awesome-Enterprise-App-Marketplace-Integrations

# Top Enterprise App Marketplace & Integrations Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Ecosystem Extension, Embedded Integration Catalogs & Self-Hosted Marketplaces*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise App Marketplace & Integrations**. These tools help organizations extend their software stack through third-party apps, connectors, and AI agents—covering everything from massive proprietary marketplaces like Salesforce AppExchange to open-source frameworks for building your own integration catalog or federated app store.

**Examples** include Salesforce AgentExchange, Freshworks Marketplace, Atlassian Marketplace, HubSpot App Marketplace, Slack App Directory, Zoho Marketplace, Microsoft AppSource, and open-source alternatives like Panora and Mercur (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted integration catalogs, open-source marketplace platforms, and federated app stores—ideal for SaaS builders seeking to embed integrations without per-tenant fees and organizations wanting to avoid vendor lock-in from proprietary marketplaces. The open-source landscape is genuinely functional: **Panora** provides an embedded integration catalog for SaaS products , **Mercur** offers an open-core marketplace platform built on Medusa , and **World Vibe Web** demonstrates a federated app store model .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Salesforce AgentExchange](https://www.salesforce.com/)** | **The largest enterprise app marketplace, now unified with AI agents.** Relaunched April 2026 merging AppExchange, Slack Marketplace, and Agentforce into one catalog: **10,000+ Salesforce apps, 1,000+ Agentforce agents, and 2,600+ Slack apps**. Semantic search via Data 360, unified billing, and a **$50M builder fund**. Every submission passes security review . **Forrester warns** the convenience deepens data gravity and lock-in—once agents live in Salesforce, moving them is expensive . | App prices set by publishers; AgentExchange purchases at list or custom quote | Free to browse; paid apps priced individually |
| **[Freshworks Marketplace](https://www.freshworks.com/)** | App marketplace for Freshworks products (Freshdesk, Freshservice, Freshsales). Extends CRM, support, and IT service workflows with third-party integrations. | App prices set by publishers | Free to browse; many free apps available |
| **[Atlassian Marketplace](https://marketplace.atlassian.com/)** | Marketplace for Jira, Confluence, and other Atlassian products with thousands of apps. **Cloud and Data Center pricing varies by user tier**; premium apps scale from ~$250/year (50 users) to $19,000+/year (10,000 users). | Variable by app and user tier | Many apps offer **30-day free trials** |
| **[HubSpot App Marketplace](https://www.hubspot.com/)** | Marketplace for HubSpot CRM integrations. Extends marketing, sales, and service hubs with third-party tools. | App prices set by publishers | Free to browse; free and paid apps available |
| **[Slack App Directory](https://slack.com/apps)** | Directory of Slack apps for workflow automation, notifications, and collaboration. **2,600+ apps** now discoverable via AgentExchange for Salesforce users . | Free to browse; app pricing varies | Free Slack workspace available |
| **[Zoho Marketplace](https://marketplace.zoho.com/)** | **2,500+ extensions** for Zoho products. Extends Zoho CRM, Desk, and other apps with integrations for Looker Studio, Dropbox, Intercom, and more . | Extension prices set by publishers | Free to browse; many free extensions |
| **[Microsoft AppSource](https://appsource.microsoft.com/)** | Microsoft's marketplace for business apps, add-ins, and AI agents across Dynamics 365, Power Platform, Microsoft 365, and Azure. | App prices set by publishers | Free to browse; trials vary by app |
| **[Workato AI Marketplace](https://www.workato.com/)** | Curated catalog of enterprise AI solutions—**Genies** (purpose-built AI agents), MCP Servers, and partner accelerators. Vetted for real business value; partner-built solutions from LTM and TCS included . | Included with Workato subscription | Free tier available for Workato platform |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Panora](https://github.com/panoratech/Panora)** | [![Stars](https://img.shields.io/github/stars/panoratech/Panora?style=social&color=white)](https://github.com/panoratech/Panora/stargazers) | **The most complete open-source integration catalog for SaaS products.** AGPL-3.0, Node.js/TypeScript with Docker. **Open-source alternative to Merge.dev**. Pre-built integration catalog with a **unified API layer** for connecting to multiple third-party services. **Multi-tenant architecture** with customer integration management, white-label customization, tenant isolation, and self-service setup. Features: real-time data sync, webhook management, integration lifecycle management, SDKs, and enterprise controls (rate limiting, audit logging, compliance) . **Best for SaaS companies wanting to embed an integration marketplace directly into their product** without per-tenant commercial fees. |
| **[Mercur](https://github.com/mercurjs/mercur)** | [![Stars](https://img.shields.io/github/stars/mercurjs/mercur?style=social&color=white)](https://github.com/mercurjs/mercur/stargazers) | **Open-core marketplace platform built on Medusa.** MIT-licensed, TypeScript. **Block-based architecture**—install only the modules, workflows, API routes, and UI extensions you need directly into your project with **full code ownership** (no black-box dependencies). Provides the marketplace domain layer on top of Medusa's commerce engine: sellers, onboarding, product requests, commissions, reviews, vendor payouts, and dedicated Admin, Vendor, and Storefront APIs. **No transaction fees, no commercial lock-in**. Designed for AI agents to build and extend safely through typed contracts and CLI-driven blocks . **Best for teams building multi-vendor marketplaces** rather than app stores, but the block architecture is adaptable. |
| **[World Vibe Web (WVW)](https://github.com/f/wvw.dev)** | [![Stars](https://img.shields.io/github/stars/f/wvw.dev?style=social&color=white)](https://github.com/f/wvw.dev/stargazers) | **Federated app store demonstrating a no-gatekeeper marketplace model.** Each developer maintains their own `apps.json` in their own repo; a GitHub Action aggregates them into a unified catalog every 6 hours. **No central authority, no review queue, no 30% cut**. AI-curated featured apps daily via GitHub Agentic Workflows. **Guardrails**: stars/forks fetched live from GitHub API (cannot be inflated), owner attribution injected by build, deduplication enforced. **WVW does not audit or verify app safety**—it is a directory, not a distributor. **Best as a reference architecture for federated, open-source app discovery** rather than a turnkey enterprise solution . |
| **[Prismatic Components](https://github.com/prismatic-io/components)** | [![Stars](https://img.shields.io/github/stars/prismatic-io/components?style=social&color=white)](https://github.com/prismatic-io/components/stargazers) | **Production-grade connector library, open-sourced under Apache-2.0 (June 2026).** The code **automatically synchronizes with Prismatic's internal production code on every release**—it is identical to active production versions. B2B developers can use it as a **baseline reference framework** to clone, fork, and extend existing enterprise connectors (Salesforce, NetSuite, HubSpot) or build unique integration blocks from scratch. Prismatic's CEO notes that **raw connector counts no longer differentiate** because AI can scaffold working connectors from API docs in an afternoon—the value is in production-hardened patterns . **Best for teams building or extending their own integration catalog** with battle-tested component implementations. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Cenit IO](https://github.com/cenit-io/cenit)** | [![Stars](https://img.shields.io/github/stars/cenit-io/cenit?style=social&color=white)](https://github.com/cenit-io/cenit/stargazers) | **100% open-source iPaaS (MIT, Ruby, 505 stars).** Full integration platform with a React UI and Odoo ERP client addons. **Production readiness rated medium**—suitable for prototypes or internal workflows, with dependency and maintenance checks before production. **Best for organizations wanting a self-hosted iPaaS foundation** rather than a turnkey marketplace . |
| **[Activepieces](https://github.com/activepieces/activepieces)** | [![Stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | **Open-source automation platform with an expanding "pieces" (connector) library.** Self-hostable with a visual flow builder. Reviewers praise **ease of use over Zapier/Make**, generous free tier, and AI/MCP workflow support. **Trade-off**: connector library smaller than Zapier/Make; custom piece flexibility requires workarounds for advanced use cases . **Best for teams wanting a self-hosted integration catalog** with active development. |

**Frameworks for building custom systems**: Choose **Panora** for embedding an integration catalog directly into a SaaS product with multi-tenant support , **Mercur** for building a marketplace with full code ownership and no transaction fees , or **Prismatic Components** as a production-grade reference library for building your own connectors —all without the data gravity and lock-in that Forrester warns accompany proprietary marketplaces like Salesforce AgentExchange .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- App marketplaces and integration catalogs handle third-party credentials and data flows between systems; enforce least-privilege OAuth scopes, secret rotation, and audit logging for all connector activity.
- **Proprietary marketplaces create a hidden "verification tax" and deepen lock-in.** Salesforce AgentExchange reduces search friction and pre-vets listings, but **Forrester warns that every agent deployed inside Salesforce makes leaving harder**—the convenience compounds into dependency, and enterprises still bear the ongoing burden of monitoring performance and unintended behavior . **Open-source alternatives offer escape velocity**: **Panora** provides an embedded catalog with multi-tenant isolation and white-labeling , **Mercur** delivers full code ownership with zero transaction fees , and **Prismatic's open-sourced component library** (Apache-2.0, production-synchronized) lets teams build on battle-tested connector patterns rather than proprietary black boxes . **Validate integration depth, security review requirements, and long-term data portability** before committing to any marketplace strategy.

---

**Made for platform engineers, SaaS builders, and organizations building integration ecosystems.**  
Let's make enterprise app marketplaces more open, portable, and developer-friendly.
