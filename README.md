# Awesome-Insurance-Rating-Engine

### Top Insurance Rating Engine Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Premium Calculation, Rate Modeling, Tariff Construction & Pricing Automation*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Insurance Rating Engines**. These tools help insurers, MGAs, and actuaries calculate premiums, build rating models, construct tariff classes, and deploy pricing logic into production systems.

**Examples** include Insurity Rating, Guidewire Rating, Duck Creek Rating, Akur8, Quantee, INSTANDA, EIS Rating, Sapiens Rating, Majesco Rating, OneShield Rating, Earnix, and Oracle Health Insurance Rating (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom rating logic, and transparent actuarial modeling — ideal for insurers, insurtech builders, and pricing teams who need full control over rate calculation without proprietary vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Insurity Rating](https://insurity.com/)**
  Cloud-based rating engine for P&C insurers. The Andromeda release (2025) introduced full premium calculation transparency, showing every rate, rule, and factor behind the number. Ratio Content and Rating Engine (2026) is an API-first externalized rating engine for commercial P&C, ingesting ISO, NCCI, and AAIS bureau content into production-ready policy logic .

- **[Guidewire Rating](https://www.guidewire.com/)**
  Rating management component within Guidewire InsuranceSuite. Handles rate tables, rating formulas, and product definition for P&C insurers. Integrates with Guidewire PolicyCenter for quote, rate, and issue workflows.

- **[Duck Creek Rating](https://www.duckcreek.com/)**
  Rating module within Duck Creek's suite for P&C insurers. Provides rating calculations, rules, and workflow automation for personal and commercial lines.

- **[Akur8](https://www.akur8.com/)**
  Global Actuarial AI Platform for P&C and L&A insurers. Uses proprietary machine learning for transparent, explainable rate modeling. Rate Repo manages rate assets; Deploy moves models into production. Serves 300+ customers including AXA, Generali, and Munich Re .

- **[Quantee](https://quantee.ai/)**
  Pricing platform for general insurance using machine learning and automation. Provides real-time rating, model deployment, and portfolio optimization capabilities.

- **[INSTANDA](https://instanda.com/)**
  No-code insurance platform with rating engine, product builder, and underwriting rules. Enables insurers to design, build, and launch products without traditional IT development cycles.

- **[EIS Rating](https://eisgroup.com/)**
  Rating and policy administration component within EIS's core insurance platform. Supports life, health, and P&C lines with configurable rating rules.

- **[Sapiens Rating](https://sapiens.com/)**
  Rating solution within Sapiens' insurance suite. Provides rating calculations, rate management, and integration with core policy administration. The Earnix Price-It Connector for Sapiens IDITSuite enables external rating with bi-directional data flow .

- **[Majesco Rating](https://majesco.com/)**
  Rating management for P&C and life insurers. Integrates with Majesco's core suite for quote, rate, and issue workflows.

- **[OneShield Rating](https://oneshield.com/)**
  Rating and policy administration for P&C insurers. Provides configurable rating rules and real-time premium calculation.

- **[Earnix](https://earnix.com/)**
  AI-based SaaS solutions for pricing, rating, underwriting, and product personalization. Earnix Price-It is a cloud-native rating engine. Partners with Guidewire, Sapiens, and HCLTech for enterprise integrations. Used by GEICO, USAA, and Co-operators .

- **[Oracle Health Insurance Rating](https://www.oracle.com/)**
  Rating component within Oracle Health Insurance suite. Handles premium calculation for health and life insurance products.

## Open-Source GitHub Projects

- **[ratingtables](https://github.com/gs-actuary/ratingtables)**
  Table-driven insurance rating engine for R. Executes ordered rating specifications against factor tables, supports coverage-specific plans, entity aggregation, caps and rounding rules, and trace output for auditing. Custom rating functions allow arbitrary R code for complex calculations. MIT licensed, published on CRAN .

- **[insurancerating](https://cran.r-project.org/web/packages/insurancerating/)**
  R package for actuarial risk classification and tariff construction. Provides GAM-based risk factor modeling, evolutionary tree binning for continuous variables, and GLM tariff class construction. Implements Henckaerts et al. (2018) binning methodology. Used by actuaries for building rating classes .

- **[Insolver](https://github.com/MindSetLib/Insolver)**
  Low-code machine learning library for insurance tasks: data preparation, model building, and production deployment. Supports pricing, reserving, and risk modeling workflows. Jupyter Notebook-based with 18 stars .

- **[Burning Cost](https://burningcost.github.io/about/)**
  Suite of thirteen open-source Python tools for UK personal lines and commercial pricing teams. Covers GLMs, GBMs, SHAP relativities extraction from CatBoost, credibility modeling, rate optimization, and FCA compliance. Includes shap-relativities for extracting multiplicative rating factor tables from GBM models in GLM-compatible format .

- **[ACTUS Insurance Core](https://www.nuget.org/packages?q=Tags%3A%22insurance%22)**
  .NET library for ACTUS-based insurance contract modelling, providing contract terms, state spaces, and schedule generation. Includes PAM and other ACTUS contract implementations for premium calculation .

- **[Premium Calculation Engine](https://www.nuget.org/packages?q=Tags%3A%22insurance%22)**
  Flexible .NET premium calculation engine supporting defined benefit, defined contribution, multi-factor rating, and discounting logic. Configurable rating rules for life and health insurance products .

### Additional Strong Open-Source Options

- **Rating Engines**: **ratingtables** (R, table-driven), **Premium Calculation Engine** (.NET, multi-factor).
- **Tariff Construction**: **insurancerating** (GAM-based binning, evolutionary trees).
- **ML for Pricing**: **Insolver** (low-code ML for insurance), **Burning Cost** (SHAP relativities, rate optimization).
- **Contract Modeling**: **ACTUS Insurance Core** (ACTUS standard, .NET).

**Frameworks for building custom systems**: Combine **ratingtables** for table-driven premium calculation, **insurancerating** for tariff class construction, **Burning Cost** for GBM-to-rating-table extraction, and **PostgreSQL** for policy data. Add **Docker** for deployment and **REST APIs** for integration with policy administration systems.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Insurance rating engines handle sensitive financial and actuarial data; ensure compliance with relevant insurance regulations and actuarial standards.
- Self-hosted open-source solutions require proper security hardening, actuarial validation, and regular model audits.

---

**Made for insurance actuaries, pricing analysts, insurtech builders, and product managers.**
Let's make insurance rating more open, transparent, and data-driven.
