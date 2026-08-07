# Awesome-Spend-Analytics

## Top Spend Analytics Tools Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on Spend Classification, Visibility, Tail Spend Analysis, Procurement Intelligence & Savings Identification*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Spend Analytics**. These tools help procurement and finance teams cleanse, classify, and analyze purchasing data to gain visibility into spend, identify savings opportunities, detect maverick buying, and support strategic sourcing decisions.

**Examples** include Sievo, Coupa Spend Guard / Spend Analysis, GEP SMART, SAP Ariba Spend Analysis, Simfoni, Rosslyn Data Technologies, SpendHQ, Zycus, Medius Analytics, Proactis, Ivalua, Procurify Analytics, and Tableau Procurement Analytics (the category leaders).

**Open-source emphasis**: This section is heavily expanded with available projects. Mature, enterprise-grade open-source spend analytics platforms are limited. Most practical open-source approaches combine data pipelines, classification models, and BI tools, or focus on specific domains such as SaaS spend.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Sievo](https://sievo.com/)**  
  Leading dedicated spend analytics platform specializing in AI-powered classification, multi-ERP data unification, and procurement intelligence for complex organizations.

- **[Coupa Spend Analysis / Spend Guard](https://www.coupa.com/)**  
  Spend analytics capabilities embedded within the Coupa Business Spend Management suite, providing visibility and controls around transactional spend.

- **[GEP SMART](https://www.gep.com/)**  
  Unified source-to-pay platform with strong spend analytics, strategic sourcing, and procurement transformation capabilities.

- **[SAP Ariba Spend Analysis](https://www.sap.com/products/spend-management/ariba.html)**  
  Enterprise spend analysis tightly integrated with SAP Ariba and broader SAP procurement ecosystems.

- **[Simfoni](https://simfoni.com/)**, **[Rosslyn Analytics / Rosslyn Data Technologies](https://www.rosslynanalytics.com/)**, **[SpendHQ](https://spendhq.com/)**, **[Zycus](https://www.zycus.com/)**  
  Additional specialized or suite-based platforms focused on spend visibility, classification, and procurement insights.

- **[Medius Analytics](https://www.medius.com/)**, **[Proactis](https://www.proactis.com/)**, **[Ivalua](https://www.ivalua.com/)**, **[Procurify Analytics](https://www.procurify.com/)**, **[Tableau Procurement Analytics](https://www.tableau.com/)**  
  Further options covering invoice-to-pay analytics, mid-market spend visibility, configurable procurement analytics, and general BI applied to procurement data.

## Open-Source GitHub Projects

- **[saaslens](https://github.com/Wondermove-Inc/saaslens)**  
  Open-source SaaS spend intelligence platform for discovering unused subscriptions, matching payments to apps, tracking seats, and analyzing departmental SaaS costs — fully self-hosted.

- **[Procurement Optimization / Spend Analytics projects](https://github.com/virbahu/procurement-optimization)**  
  AI-driven open-source initiatives that include spend classification, tail-spend analysis, maverick spend detection, and strategic sourcing optimization components.

- **[Apache Superset](https://github.com/apache/superset)** & **[Metabase](https://github.com/metabase/metabase)**  
  Leading open-source BI and data visualization platforms frequently used to build custom spend dashboards and analytics on top of cleaned procurement data.

- **[ERPNext & Odoo Procurement modules](https://github.com/frappe/erpnext)**  
  Open-source ERPs with purchasing, supplier, and basic spend reporting capabilities that can serve as data sources or lightweight analytics foundations.

- **[Local AI Vendor Spend Analyst and similar tools](https://github.com/)**  
  Emerging open-source projects that use local LLMs or classical ML for vendor spend trend analysis, risk flagging, and summarization.

- **[Personal / departmental spend trackers](https://github.com/)**  
  Self-hosted expense and purchase analytics tools that can be adapted for smaller-scale or departmental spend visibility use cases.

- **[Data pipeline & classification frameworks](https://github.com/)**  
  Open-source ETL/ELT tools (Airbyte, dbt, etc.) combined with classification models for building custom spend data platforms.

### Additional Strong Open-Source Options

- Custom UNSPSC or commodity classification models trained on open or internal datasets.
- dbt projects and SQL models for spend cube construction and hierarchy management.
- Integration of open procurement data with modern lakehouse architectures.
- Many research and internal tools for tail-spend analysis that are partially released as open source.

**Frameworks for building custom systems**: Most open-source spend analytics implementations start with data extraction from ERPs/P2P systems → cleansing & classification (rules + ML) → dimensional modeling → visualization in **Superset** or **Metabase**. For SaaS-specific spend, **saaslens** provides a ready self-hosted foundation. Enterprise-scale multi-ERP classification, enrichment, and continuous intelligence still typically rely on commercial platforms such as Sievo or suite-embedded analytics.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Effective spend analytics depends heavily on data quality, taxonomy management, and multi-source integration. Open-source tools and BI platforms can deliver strong visibility when properly implemented, but dedicated commercial solutions often provide superior classification accuracy, enrichment services, and procurement-specific workflows out of the box.
- Always validate classification results and savings opportunities with procurement and finance stakeholders before acting on insights.

---

**Made for procurement analysts, spend managers, and data teams seeking greater transparency and control over spend data.**  
Let's make procurement intelligence more open and accessible.