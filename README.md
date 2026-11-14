# Awesome-Dynamic-Product-Plan-Catalog

# Top Dynamic Product & Plan Catalog Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on PIM, Product Information Enrichment & Multi-Channel Catalog Syndication*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Dynamic Product & Plan Catalog**. These tools help organizations centralize product data, enrich attributes, manage digital assets, and syndicate accurate catalogs across e-commerce storefronts, marketplaces, and sales channels—covering everything from enterprise PIM suites to open-source Laravel-based alternatives.

**Examples** include Akeneo, Salsify, inRiver, Pimcore, Shopify Catalog, BigCommerce, Salesforce Commerce Cloud, and open-source alternatives like UnoPim and Pimcore Community (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted PIM, open-source catalog management, and community-driven product data enrichment—ideal for organizations seeking data sovereignty and avoiding six-figure enterprise licensing. The open-source landscape is genuinely functional: **UnoPim** provides a Laravel-based PIM with AI agents and 10M+ product scalability , and **Pimcore** offers a free community edition with no product or user limits .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Akeneo](https://www.akeneo.com/)** | Enterprise PIM and product experience platform. Centralizes product data, enriches attributes, and syndicates to channels. **Implementation costs up to half of total TCO**—partner work and data migration often exceed subscription costs [citation:15]. | **$45,000/year** (Software Advice listing) [citation:1] | Free trial available; no permanent free tier [citation:1] |
| **[Salsify](https://www.salsify.com/)** | PIM and digital shelf analytics platform. **Record and locale caps per edition** make sizing easier to predict; Enhanced Content and GDSN sold separately [citation:15]. | **$1,500/month** (Software Advice listing) [citation:3][citation:14] | Free trial available; no permanent free tier |
| **[inRiver](https://www.inriver.com/)** | Relation-based PIM with syndication and content onboarding. **Syndication included in higher tiers**; no public connector pricing [citation:15]. On-premise version notably behind cloud [citation:4]. | Quote-only (tiered by company profile) | Free trial available; no permanent free tier [citation:4] |
| **[Pimcore](https://pimcore.com/)** | Open-core PIM/MDM/DXP platform. **No limits on products, assets, sites, or users**—even at 10 million products [citation:2]. Professional (on-premises) from **$29,900/year**; Enterprise PaaS from **$39,900/year** [citation:13]. | Professional: **$29,900/year**; Enterprise PaaS: **$39,900/year** | **Community Edition**: free (GPLv3); commercial editions for enterprise features |
| **[Shopify Catalog](https://www.shopify.com/)** | Product catalog within Shopify commerce platform. **B2B plans support up to 3 catalogs**; Plus plans unlimited [citation:6]. Catalog is bundled with storefront subscription. | Included with Shopify plans (Basic from **$29/month** annual) [citation:6] | No separate catalog fee; storefront plan required |
| **[BigCommerce](https://www.bigcommerce.com/)** | Commerce platform with catalog management. **GMV-based plan thresholds**; overage rates apply on Scale/Performance [citation:7]. | Core: **$39/month** ($29 annual); Growth: **$105/month** | **15-day free trial** [citation:7] |
| **[Salesforce Commerce Cloud](https://www.salesforce.com/)** | Enterprise commerce with catalog and pricing management. **B2C Commerce: 1% of GMV** (annual billing); includes 2 price catalogs and 750K sandbox credits [citation:10]. | **1% of GMV** (B2C Commerce, annual) [citation:10] | No free tier; demo via sales |
| **[Adobe Commerce](https://business.adobe.com/)** | Enterprise commerce with **shared catalogs for B2B**—custom pricing per company, fixed or percentage-based [citation:9]. | Quote-only (enterprise; Magento Open Source free but high TCO) | No free tier for Adobe Commerce; Magento Open Source free |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[UnoPim](https://github.com/unopim/unopim)** | [![Stars](https://img.shields.io/github/stars/unopim/unopim?style=social&color=white)](https://github.com/unopim/unopim/stargazers) | **The most complete open-source PIM with built-in AI agents.** Laravel 13, MariaDB/MySQL/PostgreSQL. **Scales to 10M+ products** with optional Elasticsearch indexing. Features: **AI Agent Chat** (conversational product management—search, create, bulk edit, categorize), Magic AI with 10+ providers for content/image generation, localization (33 languages), multi-currency, import/export (CSV/XLSX/ZIP) with real-time tracking, version control, product completeness scoring, and webhooks. Free Shopify and Bagisto connectors; DAM extension available. **No license fees, no user limits** [citation:11]. **Best for teams wanting a modern, AI-capable self-hosted PIM.** |
| **[Pimcore (Community Edition)](https://github.com/pimcore/pimcore)** | [![Stars](https://img.shields.io/github/stars/pimcore/pimcore?style=social&color=white)](https://github.com/pimcore/pimcore/stargazers) | **The most mature open-source PIM/MDM platform.** GPLv3 Community Edition is free for commercial use. **No limits on products, assets, sites, or users**—whether managing 10 or 10 million products [citation:2]. Combines PIM, MDM, DAM, and DXP in one platform. **Professional Edition ($29,900/year)** adds LTS support and enterprise extensions; **Enterprise Edition ($39,900/year)** adds e-commerce framework and CDP [citation:13]. **Best for organizations needing a proven, scalable PIM with a clear commercial upgrade path.** |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Akeneo Community Edition](https://github.com/akeneo/pim-community-dev)** | — | **Open-source edition of Akeneo PIM.** Free to self-host with core PIM features. Lacks some enterprise features (advanced AI, supplier onboarding, premium connectors). **Best for teams wanting Akeneo's data model without the $45K/year subscription** [citation:1]. |

**Frameworks for building custom systems**: Choose **UnoPim** for a Laravel-based PIM with AI agents and modern developer experience , **Pimcore Community Edition** for a proven GPLv3 platform with no product/user limits and a clear commercial upgrade path , or **Akeneo Community Edition** if you're already familiar with Akeneo's data model. **None of these matches Akeneo/Salsify enterprise connectors and digital shelf analytics out of the box**—expect to build integrations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- PIM and catalog platforms handle product data, pricing, and potentially customer-specific catalogs; enforce role-based access and audit logging for data changes.
- **PIM total cost extends far beyond subscription.** Implementation partners, data migration, enrichment, and connector add-ons can **exceed subscription costs**—Akeneo and Salsify quote implementations separately, and Salsify caps records/locales per edition [citation:15]. **Open-source PIM is genuinely viable for organizations with technical resources**: UnoPim is Laravel-based with AI agents and 10M+ product scalability , and Pimcore's Community Edition has **no product or user limits** [citation:2]. **Validate your actual connector requirements**—Shopify/Bagisto connectors exist for UnoPim, but enterprise ERP/CRM integrations may require custom development or paid extensions.

---

**Made for product data managers, e-commerce operations teams, and developers building catalog infrastructure.**  
Let's make dynamic product and plan catalogs more open, accurate, and scalable.
