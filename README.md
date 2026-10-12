# Awesome-Collaborative-Sales-In-Slack

# Awesome-Collaborative-Sales-In-Slack

# Top Collaborative Sales In Slack Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Pipeline Management, Deal Collaboration & Sales Automation Inside Slack*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Collaborative Sales in Slack**. These tools enable sales teams, SDRs, and revenue leaders to manage pipelines, update CRM records, receive deal alerts, and collaborate on opportunities without leaving Slack.

**Examples** include Salesforce Slack Sales Elevate, Troops.ai, Scratchpad, Halp, Workbot, Aviso for Slack, Gong for Slack, Clari for Slack, HubSpot for Slack, and Salesloft for Slack (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom Slack bot development, and open sales data pipelines — ideal for teams seeking transparent, vendor-independent sales collaboration.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Slack Sales Elevate](https://www.salesforce.com/slack/)**  
  Native Slack integration bringing Salesforce CRM data, deal alerts, and pipeline management directly into Slack. Includes Agentforce Sales AI agents that prioritize leads and advance deals automatically.

- **[Troops.ai / Slack Sales Elevate](https://www.salesforce.com/slack/)**  
  Acquired by Salesforce in 2022. Enables Salesforce record search/edit, deal alerts, and sales workflow automation inside Slack. No longer available to new standalone customers.

- **[Scratchpad](https://scratchpad.com/)**  
  Fast Salesforce update and sales workflow platform in Slack. Provides actionable alerts for stale opportunities, pipeline hygiene, and deal reminders.

- **[Floworks](https://www.ycombinator.com/launches/ICx-floworks-close-more-deals-with-crm-on-slack)**  
  YC-backed CRM-on-Slack solution. Integrates Salesforce, HubSpot, and Pipedrive with Slack for bi-directional deal updates, meeting notes, and follow-up reminders. Claims 15-25% more deals closed monthly.

- **[HubSpot for Slack](https://www.hubspot.com/)**  
  CRM notifications, deal updates, and contact management within Slack. Supports lead capture from Slack conversations and bidirectional data sync.

- **[Salesloft for Slack](https://salesloft.com/)**  
  Sales engagement platform integration with Slack for cadence notifications, deal alerts, and team collaboration on prospect outreach.

- **[Clari for Slack](https://www.clari.com/)**  
  Revenue operations platform bringing forecast updates, pipeline alerts, and deal risk notifications into Slack channels.

- **[Gong for Slack](https://www.gong.io/)**  
  Revenue intelligence platform with Slack integration for deal alerts, call insights, and pipeline collaboration.

- **[Aviso for Slack](https://aviso.com/)**  
  AI-powered sales forecasting and pipeline management with Slack notifications for deal risks and forecast changes.

- **[Workbot for Slack](https://www.workato.com/)**  
  Workato's Slack bot enabling no-code automation between Slack and 400+ business apps, including CRM platforms.

## Open-Source GitHub Projects

- **[OpenClaw](https://github.com/openclaw/openclaw)**  
  Open-source AI gateway (MIT) connecting LLMs to Slack, WhatsApp, and Telegram with built-in memory and scheduling. Can build AI sales agents that monitor pipelines, identify stalled deals, generate personalized follow-ups, and send Slack alerts. Full tutorial available for building a sales agent in 30 minutes.

- **[MemMachine CRM Agent](https://github.com/MemMachine/MemMachine)**  
  Open-source CRM agent with full Slack integration (license varies). Features real-time message processing, historical message ingestion, memory storage/retrieval through Slack commands, AI-powered responses using OpenAI, and smart deduplication. Built with FastAPI, PostgreSQL, and Slack SDK.

- **[Comp AI CRM](https://github.com/trycompai/crm)**  
  Open-source CRM built around autonomous agents (license varies). Agents read team inbox, pull contacts from email threads, enrich company profiles, and schedule follow-ups. Features Slack integration where agents ping team members or create channels based on deal events like closed-won.

- **[OpenCRM by Clawnify](https://github.com/clawnify/OpenCRM)**  
  Lightweight open-source HubSpot alternative (license varies) for SaaS teams. Manages contacts, companies, deals, and custom attributes with full REST API and webhook support. Includes OpenClaw integration for AI-powered sales workflows.

- **[Twenty](https://github.com/twentyhq/twenty)**  
  Modern open-source CRM (AGPL-3.0) built as a Salesforce alternative. Features customizable data models, Kanban views, workflow automation, and native Slack integration. 57k+ GitHub stars.

- **[Nexus Agent](https://github.com/tobekami/nexus-agent)**  
  Autonomous sales agent (license varies) powered by IBM watsonx Orchestrate. Scans inboxes for high-value opportunities, enforces pricing policies via RAG, logs leads in CRM, and alerts sales team via Slack webhooks.

- **[LifeOS Slack CRM Linker](https://github.com/nbramia/LifeOS)**  
  Open-source script (license varies) linking Slack users to CRM person entities by exact email matching. Updates source entities to set canonical person IDs, enabling unified customer views across Slack and CRM systems.

- **[n8n Workflow Templates](https://n8n.io/)**  
  Open-source workflow automation platform (Sustainable Use License) with community-contributed templates for Slack + CRM integration. Includes Slack-based CRM assistant with HubSpot and Google Gemini for natural language CRM queries, and pipeline stall detection with Slack alerts.

### Additional Strong Open-Source Options

- **[Frappe CRM](https://github.com/frappe/crm)** — Open CRM for leads, contacts, pipelines, and account workflows.
- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)** — Self-hosted CRM for sales, service, and marketing operations.
- **[EspoCRM](https://github.com/espocrm/espocrm)** — CRM for accounts, contacts, deals, and workflow automation with REST API for Slack bots.
- **[Krayin CRM](https://github.com/krayin/laravel-crm)** — Laravel-based open-source CRM with extensible API for custom Slack integrations.
- **[Chatwoot](https://github.com/chatwoot/chatwoot)** — Open-source customer engagement platform with Slack integration for sales conversations.
- Community **Slack Bolt** projects for building custom CRM bots with Python/Node.js.

**Frameworks for building custom systems**: Combine **Twenty** or **Frappe CRM** as the CRM backend with **OpenClaw** for AI agent orchestration, **n8n** for workflow automation, **MemMachine** for conversational memory, and **Slack Bolt** for custom bot development — creating a fully self-hosted collaborative sales platform in Slack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Sales data in Slack must comply with data protection regulations (GDPR, CCPA, etc.).
- Self-hosted open-source solutions require proper security hardening, CRM data synchronization, and ongoing maintenance.

---

**Made for sales teams, SDRs, RevOps professionals, and developers building transparent sales collaboration solutions.**  
Let's make collaborative sales in Slack more open, data-driven, and efficient.
