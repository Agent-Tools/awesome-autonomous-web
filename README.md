# 🤖🛜 Awesome AI Agent Tools for the Web

A curated list of tools that empower AI agents to interact with the web — from cloud browsers and authentication to automation frameworks, enterprise packages, benchmarks, and search.

---

## 💻 Browsers for AI

Cloud-hosted and open-source browsers designed for AI agents.

- **[Anchor Browser](https://anchorbrowser.io/)** — Cloud browser built for AI agents. Handles sessions, CAPTCHAs, MFA, and proxies automatically. Free tier available.
- **[Steel](https://steel.dev/)** — Open-source headless browser API for AI agents. Self-hostable or cloud. 6k+ GitHub stars. ([GitHub](https://github.com/steel-dev/steel))
- **[Browserbase](https://www.browserbase.com/)** — Cloud browser platform with session replay, stealth mode, and Playwright/Puppeteer support. Paid.
- **[Browserless](https://www.browserless.io/)** — Scalable headless Chrome in the cloud. Paid.
- **[APIFY](https://apify.com/)** — Browser automation + web scraping platform. Paid.

---

## 🔌 MCP Servers for Browser Automation

Model Context Protocol servers that give LLMs (Claude, GPT-4, etc.) direct browser control.

- **[Playwright MCP](https://playwright.dev/agents)** — Official Playwright MCP server. Uses accessibility snapshots (not screenshots) for fast, reliable LLM-driven automation. Open-source.
- **[Steel MCP Server](https://github.com/steel-dev/steel-mcp-server)** — Puppeteer-based MCP server backed by Steel cloud or local Docker. Open-source.
- **[Anchor Browser MCP](https://anchorbrowser.io/)** — MCP server for Anchor Browser cloud sessions. Handles auth, CAPTCHAs, and concurrent sessions.

---

## 🪪 Web Authentication

Tools that enable AI agents to access authenticated websites and sessions.

- **[Anchor Browser](https://anchorbrowser.io/)** — Built-in MFA handling, cookie/session persistence, and fingerprint management for agents.

---

## 👤 AI Web Copilots

Autonomous AI agents that navigate and complete tasks on the web.

- **[Please (formerly MultiOn)](https://please.ai/)** — Consumer AI agent for web tasks (travel booking, forms, shopping). Rebranded from MultiOn in 2025.
- **[Jace.AI](https://www.jace.ai/)** — AI agent for complex multi-step web workflows. Paid.

---

## 📝 AI Web Automation Frameworks

Tools and SDKs that power web automation with AI.

### Open Source

- **[Stagehand](https://stagehand.dev/)** by Browserbase — AI-native browser automation SDK. Built on Playwright with `act()`, `extract()`, `observe()`, and `agent()` primitives. Works with Claude, GPT-4, Gemini. ([GitHub](https://github.com/browserbase/stagehand))
- **[Browser-use](https://github.com/browser-use/browser-use)** — Python library connecting LLMs to browser actions. High-level task interface over Playwright.
- **[Skyvern-AI](https://github.com/Skyvern-AI/skyvern)** — Visual LLM-driven browser agent. Understands pages through screenshots rather than DOM.
- **[Agent-E](https://github.com/EmergenceAI/Agent-E)** — Hierarchical AI agent for browser automation tasks.
- **[LaVague](https://github.com/lavague-ai/LaVague)** — Natural language browser control using text language models.
- **[Tarsier](https://github.com/reworkd/tarsier)** by Reworkd — Vision utilities for web agents (element tagging, OCR).
- **[Notte](https://notte.cc/)** — Framework for building web agents with planning, vision, and LLM reasoning.

### Paid Platforms

- **[Axiom.ai](https://axiom.ai/)** — No-code browser automation bots. Paid.
- **[Browse.ai](https://browse.ai/)** — Extract and monitor web data without code. Paid.
- **[ZeroStep](https://zerostep.com/)** — AI-powered test automation using plain English assertions. Paid.

---

## 🏢 Enterprise System Automation Packages

Pre-built, open-source browser automation for enterprise platforms. Powered by Puppeteer and [Anchor Browser](https://anchorbrowser.io) cloud. Published as `@browser-automation-hub/*` npm packages.

| System | npm Package | Category |
|--------|------------|----------|
| [Epic EHR](https://github.com/Browser-Automation-Hub/epic-ehr-browser-automation) | `@browser-automation-hub/epic-ehr-browser-automation` | Healthcare |
| [Cerner Powerchart](https://github.com/Browser-Automation-Hub/cerner-powerchart-browser-automation) | `@browser-automation-hub/cerner-powerchart-browser-automation` | Healthcare |
| [Workday HCM](https://github.com/Browser-Automation-Hub/workday-hcm-browser-automation) | `@browser-automation-hub/workday-hcm-browser-automation` | HR |
| [ADP Workforce Now](https://github.com/Browser-Automation-Hub/adp-workforce-now-browser-automation) | `@browser-automation-hub/adp-workforce-now-browser-automation` | HR |
| [Salesforce Classic](https://github.com/Browser-Automation-Hub/salesforce-classic-browser-automation) | `@browser-automation-hub/salesforce-classic-browser-automation` | CRM |
| [ServiceNow](https://github.com/Browser-Automation-Hub/servicenow-browser-automation) | `@browser-automation-hub/servicenow-browser-automation` | ITSM |
| [SAP Concur](https://github.com/Browser-Automation-Hub/sap-concur-browser-automation) | `@browser-automation-hub/sap-concur-browser-automation` | ERP |
| [SAP Fiori](https://github.com/Browser-Automation-Hub/sap-fiori-browser-automation) | `@browser-automation-hub/sap-fiori-browser-automation` | ERP |
| [Oracle EBS](https://github.com/Browser-Automation-Hub/oracle-ebs-browser-automation) | `@browser-automation-hub/oracle-ebs-browser-automation` | ERP |
| [PeopleSoft](https://github.com/Browser-Automation-Hub/peoplesoft-browser-automation) | `@browser-automation-hub/peoplesoft-browser-automation` | ERP |
| [Veeva Vault](https://github.com/Browser-Automation-Hub/veeva-vault-browser-automation) | `@browser-automation-hub/veeva-vault-browser-automation` | Life Sciences |
| [Veeva CRM](https://github.com/Browser-Automation-Hub/veeva-crm-browser-automation) | `@browser-automation-hub/veeva-crm-browser-automation` | Life Sciences |
| [Yardi Voyager](https://github.com/Browser-Automation-Hub/yardi-voyager-browser-automation) | `@browser-automation-hub/yardi-voyager-browser-automation` | Real Estate |
| [Procore](https://github.com/Browser-Automation-Hub/procore-browser-automation) | `@browser-automation-hub/procore-browser-automation` | Construction |
| [SuccessFactors](https://github.com/Browser-Automation-Hub/successfactors-browser-automation) | `@browser-automation-hub/successfactors-browser-automation` | HR |

→ [View all 30 packages on GitHub](https://github.com/Browser-Automation-Hub) · [Postman Collections](https://www.postman.com/idan-775bed48-7905039/browser-automation-hub)

---

## 🔬 Web Agent Benchmarks

Datasets and leaderboards for evaluating web agents.

- **[WebArena](https://github.com/web-arena-x/webarena)** — Realistic web tasks across multiple sites. Open-source.
- **[WebArena Leaderboard](https://docs.google.com/spreadsheets/d/1M801lEpBbKSNwP-vDBkC_pF7LdyGU1f_ufZb_NWNBZQ/edit?gid=0#gid=0)** — Live rankings.
- **[VisualWebArena](https://jykoh.com/vwa)** — Multimodal extension of WebArena with image-based tasks. Open-source.
- **[WebCanvas](https://github.com/iMeanAI/WebCanvas)** — Online web agent evaluation with live environments. Open-source.
- **[WorkArena](https://github.com/ServiceNow/WorkArena)** — Benchmark for enterprise web tasks (ServiceNow). Open-source.
- **[Mind2Web](https://github.com/OSU-NLP-Group/Mind2Web)** — Cross-task, cross-website generalization benchmark. Open-source.
- **[Bananalyzer](https://github.com/reworkd/bananalyzer)** by Reworkd — Web agent evaluation framework. Open-source.

---

## 🖼️ Visual Web Automation

Computer vision and multimodal approaches to web interaction.

- **[Skyvern-AI](https://github.com/Skyvern-AI/skyvern)** — Visual LLM agent that reads pages as screenshots. Open-source.
- **[VimGPT](https://github.com/ishan0102/vimGPT/)** — GPT-4V driving a browser via keyboard shortcuts. Open-source.

---

## 🕷️ AI Web Crawlers

Intelligent crawlers for data extraction at scale.

- **[FireCrawl](https://www.firecrawl.dev/)** — LLM-ready web crawling and scraping with Markdown output. Paid.
- **[Crawlee](https://crawlee.dev/)** — Open-source web scraping and crawling library by APIFY. Supports Playwright, Puppeteer, Cheerio. Open-source.
- **[Spider](https://spider.cloud/)** — Fast AI web crawler with agent mode. Paid.
- **[Reworkd](https://www.reworkd.ai/)** — AI-driven data extraction pipelines. Paid.

---

## 🔍 Web Search Tools

Search APIs for giving agents real-time web access.

- **[Tavily](https://tavily.com/)** — Search API built for AI agents. Returns clean, LLM-optimized results. Paid (free tier).
- **[Exa](https://exa.ai/)** — Neural search API for web content. Semantic search + keyword. Paid.
- **[Serper.dev](https://serper.dev/)** — Google Search API for AI agents. Paid.
- **[Brave Search API](https://brave.com/search/api/)** — Independent search index with AI-ready API. Paid (free tier).

---

## 🔓 CAPTCHA Solving

Tools for AI agents to handle CAPTCHAs and bot detection.

- **[Anchor Browser](https://anchorbrowser.io/)** — Automatic CAPTCHA solving built into the cloud browser runtime.
- **[Capsolver](https://www.capsolver.com/)** — CAPTCHA solving API and browser extension. Paid.
- **[2captcha](https://2captcha.com/)** — Human-powered CAPTCHA solving API. Paid.

---

## 🛠️ GraphQL Consumption Tools

- **[GraphQL.Chat](https://graphql.chat/)** — Explore and query GraphQL APIs with natural language. Free, closed source.
- **[GQLPT.dev](https://gqlpt.dev/)** — Generate GraphQL queries from plain text. Free, closed source.

---

*Feel free to open a PR to add tools or update descriptions. This list is maintained by the community.*
