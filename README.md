# Awesome-Enterprise-App-Marketplace-Integrations

## Top Enterprise App Marketplace & Integrations Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Ecosystem Extension, Embedded Integration Catalogs & Self-Hosted Marketplaces*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise App Marketplace & Integrations**. These tools help organizations extend their software stack through third-party apps, connectors, and AI agents—covering everything from massive proprietary marketplaces like Salesforce AppExchange to open-source frameworks for building your own integration catalog or federated app store.

**Examples** include Salesforce AgentExchange, Freshworks Marketplace, Atlassian Marketplace, HubSpot App Marketplace, Slack App Directory, Zoho Marketplace, Microsoft AppSource, and open-source alternatives like Panora and Mercur (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted integration catalogs, open-source marketplace platforms, and federated app stores—ideal for SaaS builders seeking to embed integrations without per-tenant fees and organizations wanting to avoid vendor lock-in from proprietary marketplaces. The open-source landscape is genuinely functional: **Panora** provides an embedded integration catalog for SaaS products , **Mercur** offers an open-core marketplace platform built on Medusa , and **World Vibe Web** demonstrates a federated app store model .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The enterprise app marketplace and integration platform ecosystem (spanning enterprise iPaaS and B2B app marketplaces) represents an estimated market size of **$14B to $18B+**, projected to exceed **$40B–$50B+** by the early 2030s at an aggressive 30%+ CAGR driven by AI agent orchestration and API-first SaaS ecosystems. The market is **moderately concentrated among winner-take-most hyperscalers and dominant platform anchors** (Microsoft, Salesforce) whose immense data gravity and proprietary app ecosystems capture the lion's share of enterprise budgets, while remaining **fragmented at the application connector and specialized integration layer** where open-source frameworks and independent platforms compete to prevent vendor lock-in.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Description | Starting Pricing | Free Tier / Trial Limits |
|---------|-----------------------------------|-------------|------------------|--------------------------|
| **[Microsoft AppSource](https://appsource.microsoft.com/)** | **~$3.89T Market Cap** (~$270B+ annual revenue) | Microsoft's marketplace for business apps, add-ins, and AI agents across Dynamics 365, Power Platform, Microsoft 365, and Azure. | Free to browse; underlying platform apps (e.g. Microsoft 365 Business Basic) start at **$7.00/user/month** (annual commitment) | **30-day free trial** with up to 25 users (requires credit card/payment verification, includes 1 TB OneDrive storage and 100 GB mailbox) |
| **[Salesforce AgentExchange](https://www.salesforce.com/)** | **~$179B Market Cap** (~$43.9B annual revenue) | **The largest enterprise app marketplace, now unified with AI agents.** Relaunched April 2026 merging AppExchange, Slack Marketplace, and Agentforce into one catalog: **10,000+ Salesforce apps, 1,000+ Agentforce agents, and 2,600+ Slack apps**. | Free to browse; underlying Salesforce Starter Suite starts at **$25.00/user/month** (billed annually or monthly) | **30-day free trial** for up to 10 users (capped at 2,000 combined leads/contacts and 10 emails/day; permanent Free Suite tier capped at 2 users) |
| **[Atlassian Marketplace](https://marketplace.atlassian.com/)** | **~$38B Market Cap** (~$6.9B annual revenue) | Marketplace for Jira, Confluence, and Atlassian products with thousands of apps. Extends issue tracking and collaboration with third-party extensions. | Free to browse; underlying Jira Cloud Standard tier starts at **$7.91/user/month** (monthly) or **$6.52/user/month** (annual) | **Free forever plan** for up to 10 users with 2 GB total storage and 150 automation executions/month; most paid marketplace apps include **30-day free trials** |
| **[Zoho Marketplace](https://marketplace.zoho.com/)** | **~$12.5B Valuation** (~$1.5B annual revenue, bootstrapped) | **2,500+ extensions** for Zoho products. Extends Zoho CRM, Desk, and other apps with integrations for Looker Studio, Dropbox, Intercom, and more. | Free to browse; underlying Zoho CRM Standard tier starts at **$14.00/user/month** (annual) or **$20.00/user/month** (monthly) | **Free forever plan** for up to 3 users with 5,000 records, 1 GB storage, and 5,000 API credits/day; paid tiers offer a **15-day free trial** |
| **[HubSpot App Marketplace](https://www.hubspot.com/)** | **~$10.6B Market Cap** (~$3.58B annual revenue) | Marketplace for HubSpot CRM integrations. Extends marketing, sales, and service hubs with third-party tools. | Free to browse; underlying HubSpot Starter tier starts at **$20.00/seat/month** | **Free forever plan** for up to 2 users with 1,000 contacts, 2,000 email sends/month, and basic pipelines; premium tiers offer a **14-day free trial** |
| **[Slack App Directory](https://slack.com/apps)** | Part of Salesforce (acquired for **$27.7B Valuation**) | Directory of Slack apps for workflow automation, notifications, and collaboration. **2,600+ apps** discoverable via AgentExchange for Salesforce users. | Free to browse; Slack Pro tier starts at **$7.25/active user/month** (annual) or **$8.75/active user/month** (monthly) | **Free forever plan** with 90-day message/file history retention, 10 app integrations limit, 5 GB total storage, and 1:1 huddles |
| **[Workato AI Marketplace](https://www.workato.com/)** | **~$5.7B Valuation** (~$150M–$190M ARR) | Curated catalog of enterprise AI solutions—**Genies** (purpose-built AI agents), MCP Servers, and partner accelerators. | Included with Workato platform; self-serve Workato Pro starts at **$75.00/month** (credit-based self-serve slider) | **Free plan** with a one-time grant of 50,000 credits for platform testing; Otto AI add-on includes a **30-day free trial** with 500 credits |
| **[Freshworks Marketplace](https://www.freshworks.com/)** | **~$3.15B Market Cap** (~$930M annual revenue) | App marketplace for Freshworks products (Freshdesk, Freshservice, Freshsales). Extends CRM, support, and IT service workflows with third-party integrations. | Free to browse; underlying Freshdesk Growth tier starts at **$19.00/agent/month** (annual) or **$23.00/agent/month** (monthly) | **14-day free trial** of Enterprise edition (no credit card required); limited Startup Free program offers 6 months free for up to 2 agents |

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
