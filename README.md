# Awesome-AI-Powered-Analytics-Platform

# Top AI-Powered Analytics Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Natural Language Querying, Automated Insights & Embedded Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI-Powered Analytics Platforms**. These tools enable organizations to move beyond static dashboards—letting users ask questions in plain language, receive automated insights with explanations, and trigger actions directly from analytics workflows.

**Examples** include Databox, ThoughtSpot, Sisense, Power BI Copilot, Tableau Pulse, Julius AI, Akkio, Polymer Search, Domo AI, and Polymer (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, MCP-based analytics, and open AI-powered BI—ideal for data teams, developers, and organizations seeking transparent, vendor-independent analytics.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Databox](https://databox.com/)**  
  Agentic analytics platform with Genie AI analyst for natural language questions across 130+ integrations. Features AI Performance Summaries explaining why metrics changed, MCP integration for Claude/ChatGPT/n8n, and automated routines for recurring reports .

- **[ThoughtSpot](https://www.thoughtspot.com/)**  
  2025 Gartner Magic Quadrant Leader for Agentic Analytics. Spotter 3 AI agent blends structured and unstructured data, acts as MCP host for Slack/Salesforce, and embeds intelligence into apps via SDK/API/MCP. Odido reported 15-minute insights (down from days) and 40 hours/month analyst time saved .

- **[Sisense](https://www.sisense.com/)**  
  AI-first analytics with Sisense Intelligence assistant for natural language model/dashboard creation, MCP server for ChatGPT/Claude integration with governance, and Managed LLM for simplified AI deployment. 24 patents, ISO 27701 certified. Bioforum uses it for clinical trial data with regulatory compliance .

- **[Power BI Copilot](https://powerbi.microsoft.com/)**  
  Microsoft's generative AI assistant for Power BI. Standalone Copilot experience (default-on since September 2025) for full-screen chat, report Copilot for visual generation, DAX query writing, and remote MCP server for data chat via Entra ID. Requires paid Fabric capacity (F2+) .

- **[Tableau Pulse](https://www.tableau.com/products/tableau-pulse)**  
  AI-powered insights experience delivering personalized metrics in workflow (Slack, Teams, email). Features Enhanced Q&A (Tableau+), correlated metrics for relationship discovery, geo-aware LLM routing, and Agentforce Trust Layer foundation for security .

- **[Julius AI](https://julius.ai/)**  
  AI workspace for statistical analysis and data science. Upload CSV/Excel/PDF, ask natural language questions, get visualizations and code. Connects to Snowflake, BigQuery, Postgres. Teams feature with 50 members, custom agents, and scheduled reports .

- **[Akkio](https://www.akkio.com/)**  
  AI analytics platform with Chat Engine purpose-built for media teams. RAG-based multi-table analysis, media-specific terminology understanding, live web data via Strategy Agent, and flexible output formats. Horizon Media partnership cut campaign work from hours to minutes .

- **[Polymer Search](https://polymersearch.com/)**  
  No-code analytics tool transforming spreadsheets into interactive dashboards automatically. AI reads columns, suggests visualizations, and answers plain-language questions. Best for marketers and small teams—trades depth for speed .

- **[Domo AI](https://www.domo.com/)**  
  AI agents and MCP server enabling AI assistants to take action directly in Domo (build cards, trigger workflows). AI Toolkits package workflows as reusable building blocks. AI Library manages models, agents, and Toolkits centrally. DomoGPT supports multi-step tasks with Anthropic models .

- **[Polymer](https://polymersearch.com/)**  
  Spreadsheet-to-dashboard automation with AI-assisted insights and shareable live links for teams .

## Open-Source GitHub Projects

- **[Zaturn](https://pypi.org/project/zaturn/)**  
  Open-source AI-powered data analysis/BI tool available as MCP Server for Claude/Cursor. Connects to SQL databases (PostgreSQL, SQLite, DuckDB, MySQL) and files (CSV, Parquet). Runs SQL queries on data sources and returns tabular/text summaries with scatter/line/histogram/box/bar visualizations. Keeps data in place—LLM drafts queries rather than processing entire datasets .

- **[Orion](https://pypi.org/project/orion-data-analyst/)**  
  AI-powered data analysis agent transforming natural language to SQL on BigQuery. Powered by Google Gemini with LangGraph architecture. Features intelligent SQL generation, self-healing query retries, statistical analysis (ranking, trends, segmentation, RFM), conversation memory, visualizations, query caching, and safety validation (blocks DROP/DELETE, cost estimation, row limits) .

- **[Metabase](https://github.com/metabase/metabase)**  
  Easy-to-use open-source BI tool (AGPL-3.0) with Query Builder for non-SQL users, Metabot AI assistant, and self-service analytics. Connects to 25+ data sources. Ships as single JVM container plus Postgres—simpler deployment than Superset .

- **[Apache Superset](https://github.com/apache/superset)**  
  Enterprise-ready open-source BI (Apache-2.0) with no-code chart builder, SQL Editor, 40+ visualization types, and 40+ SQL database connectors. Can integrate LLM-based natural language querying via custom plugins.

- **[Lightdash](https://github.com/lightdash/lightdash)**  
  Open-source BI built natively for dbt users (MIT). dbt project is the semantic layer—no parallel modeling to maintain. Warehouse coverage matches dbt support.

- **[Cube.js](https://github.com/cube-js/cube)**  
  Open-source semantic layer (Apache-2.0) for headless BI. Provides SQL generation, caching, and API for custom AI analytics frontends.

### Additional Strong Open-Source Options

- **[Grafana](https://github.com/grafana/grafana)** — Open-source observability and analytics (AGPL-3.0) with plugin ecosystem for AI-powered dashboards.
- **[DataEase](https://github.com/dataease/dataease)** — Open-source data visualization (GPL-3.0) with drag-and-drop interface.
- **[Knowage](https://github.com/KnowageLabs/Knowage-Server)** — Full open-source BI suite (AGPL-3.0) with self-service and custom analytics.
- Community **n8n** workflows for AI analytics automation and MCP-based insight delivery.

**Frameworks for building custom systems**: Combine **Zaturn** or **Orion** as the MCP-based AI analyst with **Metabase** or **Apache Superset** for visualization and dashboards, **Cube.js** for semantic layer, and **PostgreSQL/ClickHouse** for persistence—creating a fully self-hosted, enterprise-grade AI-powered analytics platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI analytics platforms handling business data must comply with data protection regulations (GDPR, CCPA, etc.) and ensure AI-generated insights are validated before business decisions.
- Self-hosted open-source solutions require proper security hardening, LLM infrastructure (or MCP client), and ongoing maintenance. LLM hallucinations and query errors remain risks—human review of critical insights is recommended. Data source connectivity and semantic layer quality directly impact answer accuracy.

---

**Made for data teams, analysts, product engineers, and developers building transparent AI-powered analytics solutions.**  
Let's make AI-Powered Analytics more open, data-driven, and actionable.
