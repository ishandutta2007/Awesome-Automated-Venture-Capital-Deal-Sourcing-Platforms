# Awesome-Automated-Venture-Capital-Deal-Sourcing-Platforms

## Top Automated Venture Capital Deal Sourcing Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Signal Detection, Relationship Intelligence & Thesis-Based Discovery*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Venture Capital Deal Sourcing**. These tools enable investors to surface emerging companies earlier—matching thesis criteria against proprietary data, open-source momentum, and talent movement signals before deals hit traditional channels.



**Examples** include Harmonic, Affinity, DealCloud, SourceScrub, Cyndx, Tracxn, PitchBook, Crunchbase, Grata, and Specter (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, MCP-based signal detection, and open VC intelligence—ideal for investors, scouts, and developers seeking transparent, vendor-independent deal sourcing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Harmonic](https://harmonic.ai/)**  

  AI-powered deal sourcing with **Scout** natural language assistant backed by **35M companies and 195M people** database . Features thesis exploration, deal data filtering, and automated saved searches for monitoring investor activity. Scout reasons across proprietary data, network data, and web information to surface answers . **Investor Search** enables filtering by investment activity, focus areas, and network connections . **Deal Data Search** supports granular filtering by investors, roles, round details, and co-investment patterns .



- **[Affinity](https://www.affinity.co/)**  

  Relationship intelligence platform trusted by **3,000+ investment teams** globally . **Affinity Sourcing** provides curated access to **200,000+ high-growth startups** with CRM-integrated profiles, growth scoring, and automated watchlists . Tracks headcount shifts, executive hires/departures, and web traffic spikes. **Relationship scoring** quantifies who knows whom best based on recency and frequency of interactions . **Deal Assist** parses pitch decks and notes, **Industry Insights** generates market maps in one click .



- **[DealCloud (Intapp)](https://www.intapp.com/)**  

  Deal and relationship management platform for investment banks, private equity, and venture capital. Centralizes deal pipeline, contact management, and firm-wide relationship intelligence.



- **[SourceScrub](https://www.sourcescrub.com/)**  

  Private company data platform for deal sourcing and market mapping. Features company discovery, industry classification, and CRM enrichment for M&A and investment workflows.



- **[Cyndx](https://www.cyndx.com/)**  

  AI-powered deal sourcing and capital raising platform. Features semantic search, company matching, and investor-company pairing algorithms.



- **[Tracxn](https://tracxn.com/)**  

  Global startup data platform tracking emerging companies across sectors and geographies. Features funding data, investor profiles, and market maps.



- **[PitchBook](https://pitchbook.com/)**  

  Institutional-grade private market data with company profiles, funding history, investor databases, and deal analytics. Widely used by VCs, PE firms, and investment banks.



- **[Crunchbase](https://www.crunchbase.com/)**  

  Private company data platform with **30M+ verified annual updates** and **seven prediction models** forecasting funding rounds, acquisitions, IPOs, closures, and layoffs . **84% of funding rounds correctly predicted**, **72% of acquisition events correctly predicted** . API access for integrating predictions into custom workflows. Remote MCP server with 14 documented tools for AI agent integration .



- **[Grata](https://grata.com/)**  

  Private company search and deal sourcing platform for private equity, investment banking, and corporate development. Features AI-powered company discovery, industry classification, and intent signals.



- **[Specter](https://www.tryspecter.com/)**  

  Private markets intelligence platform tracking talent movement, investor interest, and growth signals. **300+ firms** rely on Specter for deal sourcing . **Estimated Stealth Industries** decodes stealth startups by analyzing founder breadcrumbs and estimating industry/tech vertical . **AI Signal Summaries** provide context for talent moves and investor interest signals directly in the feed . API spans enrichment, core data, signals, network mapping, and AI search .



## Open-Source GitHub Projects



- **[@gitdealflow/mcp-signal](https://www.npmjs.com/package/@gitdealflow/mcp-signal)**  

  MCP server for **startup engineering velocity signals** for AI agents (free, read-only). Tracks **commit velocity, contributor growth, and repository expansion** for **350+ GitHub orgs** across 15 sectors . Features **predict_funding** for transparent, citable funding-likelihood scores with full evidence chains, **shortlist_signals** with sector/geography filters, and **get_scout_receipts** to validate pattern recognition against 75+ unicorns . One-click install for Claude Desktop, Cursor, Cline, and Continue via Smithery (98/100 quality score). **The most mature open-source MCP signal tool for VC deal sourcing** .



- **[Apify GitHub Startup & Emerging Company Finder](https://apify.com/coolinbex/github-startup-emerging-company-finder)**  

  Actor for discovering emerging technology companies through **real public GitHub development activity** (from $8/1,000 results) . Features **deterministic classification** (likely_startup, emerging_company, established_company, open_source_project) with confidence scores and inspectable reasons . Tracks public repositories, active contributors, releases, languages, and activity trends. Calculates **emergingCompanyScore** and **commercialRelevanceScore**. Partitions discovery by repository creation date and language to work around GitHub's 1,000-result search cap . Outputs structured JSON with website enrichment, contact pages, and funding information when explicitly stated .



- **[NUVC MCP Server](https://github.com/nuvcai/nuvc-mcp)**  

  VC-grade startup intelligence for Claude, Cursor, and any MCP-compatible agent . For **founders**: `nuvc_score` (VCGrade 0-10 across 5 dimensions), `nuvc_match_investors` (3,700+ investor database), `nuvc_roast` (brutally honest VC-perspective startup roast) . For **VCs/LPs**: `nuvc_screen_fund` (6-dimension LP screen), `nuvc_fund_economics` (fee drag, GP alignment, J-curve), `nuvc_venture_math` (burn multiple, LTV/CAC, Rule of 40) . Free tier: 25 AI calls/month .



- **[Frontrun MCP](https://www.npmjs.com/package/frontrun-mcp-server)**  

  VC follow-signal intelligence for AI agents (29 tools) . Tracks **pre-round VC signal from 1,000+ investor follow graphs on X** . Available as MCP server, Claude Code plugin marketplace, and agent skills for Cursor and MCP-capable agents .



- **[VC Intelligence Skills for Claude](https://github.com/topics/deal-sourcing)**  

  Nine skills for venture capital intelligence (March 2026) . Three run on pure Claude reasoning; six run Claude + Python for deterministic outputs. Skills cover: **screening startups, modeling financials, sizing markets, computing cap table waterfalls, scanning deal signals, and generating LP fund reports** .



- **[Private Equity Deal Sourcing RAG Platform](https://github.com/topics/deal-sourcing)**  

  Institutional-grade PE deal sourcing and financial due diligence RAG platform (August 2026) . Combines **automated web scraping, deterministic thesis scoring (0-100), LBO covenant & CFADS stress modeling, and table-aware confidential Data Room Q&A**. **100% on-premise GPU inference** .



- **[Claude Code Deal Origination System](https://github.com/topics/deal-sourcing)**  

  Deal origination system for PE, search funds, and holdcos (September 2026) . **Six agents and nine skills**: target discovery, founder research, verified contacts, personalized owner outreach, and deal pipeline. **No database, no API keys** required .



- **[VentureRadar MCP](https://github.com/topics/deal-sourcing)**  

  Startup database API on Apify (August 2026) . Send VentureRadar company profile URLs, get JSON with **funding signals, sector focus, milestones, and scores**. Python (uv) quick start plus MCP install steps for Claude, Cursor, and ChatGPT .



### Additional Strong Open-Source Options



- **[DealScale](https://github.com/topics/deal-sourcing)** — AI platform transforming business operations with intelligent deal management, customer engagement, and data-driven decision making (TypeScript) .

- **[AI-Powered VC Deal Screening](https://github.com/topics/deal-sourcing)** — Startups submit pitch deck, agent extracts structured data using Claude AI, validates it, asks follow-up questions, generates investor-ready summary (March 2026) .

- **[Autonomous Deal Intelligence System](https://github.com/topics/deal-sourcing)** — 4 AI agents, 12 data sources, configurable thesis for venture capital (March 2026) .

- **[EU Public Procurement Deal Sourcing](https://github.com/topics/deal-sourcing)** — Ranks PE/corp-dev sourcing targets from live EU public-procurement (TED v3) data: contract-win momentum + scale + institutional diversity (May 2026) .

- Community **n8n** workflows for VC signal routing and portfolio monitoring alerts.



**Frameworks for building custom systems**: Combine **@gitdealflow/mcp-signal** for GitHub engineering velocity signals with **Apify GitHub Startup Finder** for organization discovery, **NUVC MCP** for founder scoring and investor matching, **Frontrun MCP** for VC follow signals, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade VC deal sourcing platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- VC deal sourcing platforms handling founder and company data must comply with data protection regulations (GDPR, CCPA, etc.).

- **GitHub activity is an engineering signal, not legal or financial proof.** The Apify actor explicitly notes: "GitHub does not reliably expose incorporation, funding, revenue, employee count, founder, or company-age data" . Classifications are deterministic and inspectable, not authoritative .

- **Prediction models have accuracy limits.** Crunchbase predicts 84% of funding rounds and 72% of acquisitions correctly . These are probabilistic forecasts, not certainties—always validate predictions against additional signals before making investment decisions.

- **Open-source VC tools are emerging.** The most mature options are MCP servers designed for AI agent integration (Claude, Cursor, ChatGPT) rather than standalone platforms. They provide signal detection and scoring, not full CRM or pipeline management. Self-hosted open-source solutions require proper security hardening, API key management, and ongoing maintenance.



---



**Made for venture investors, scouts, angel investors, and developers building transparent deal sourcing solutions.**  

Let's make Automated VC Deal Sourcing more open, data-driven, and signal-rich.
