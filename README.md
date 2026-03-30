# n8n-claw Expert Agents

Expert agent personas for [n8n-claw](https://github.com/freddy-schuetz/n8n-claw) — the self-hosted AI agent system. Install specialized sub-agents with a single chat command.

---

## Available Agents (73)

**How to read the table:** *Description* explains what the agent specializes in. *When to Use* gives practical scenarios for delegation. *Skills* shows which [MCP Skills](https://github.com/freddy-schuetz/n8n-claw-templates) pair well with the agent — installing them gives the sub-agent additional tools to work with ("—" = no specific skill pairing). *Source* links to the original prompt if the persona was adapted from [agency-agents](https://github.com/msitarzewski/agency-agents), or shows the author for original agents.

### Analytics (7)

| Agent | Description | When to Use | Skills | Source |
|-------|-------------|-------------|--------|--------|
| [Ads Performance Analyst](agents/ads-performance-analyst/) | Multi-platform ads performance reporting and analysis: Google Ads, Meta, LinkedIn, TikTok — ROAS, CPA, CTR trends, anomaly detection, and actionable optimization recommendations | Campaign audits, ROAS optimization, cross-platform reporting | Google Analytics, Google Ads | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/paid-media/paid-media-auditor.md) |
| [Data Analyst](agents/data-analyst/) | Data analysis, pattern recognition, structured reports, KPI interpretation | KPI dashboards, trend analysis, data-driven reports | Google Analytics | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Finance Tracker](agents/finance-tracker/) | Personal and business expense tracking, budget monitoring, transaction categorization, and financial health reports | Expense tracking, budget monitoring, transaction categorization | KontoFlux, Exchange Rates, Crypto Prices | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/support/support-finance-tracker.md) |
| [Financial Analyst](agents/financial-analyst/) | Financial modeling, P&L analysis, cash flow forecasting, unit economics, budget planning, and business case development | P&L analysis, cash flow forecasting, business cases | KontoFlux, Exchange Rates, Crypto Prices | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/support/support-finance-tracker.md) |
| [Performance Benchmarker](agents/performance-benchmarker/) | Load testing, stress testing, Core Web Vitals optimization, and performance regression detection | Load testing, Core Web Vitals, performance regressions | Website Check | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/testing/testing-performance-benchmarker.md) |
| [Pipeline Analyst](agents/pipeline-analyst/) | Sales pipeline health diagnostics, deal velocity analysis, forecast accuracy, and revenue operations | Pipeline health checks, forecast accuracy, deal velocity | NocoDB CRM | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/sales/sales-pipeline-analyst.md) |
| [Workflow Optimizer](agents/workflow-optimizer/) | Process analysis, bottleneck identification, automation opportunities, and workflow efficiency improvements | Process bottlenecks, automation opportunities, efficiency audits | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/testing/testing-workflow-optimizer.md) |

### Creative (7)

| Agent | Description | When to Use | Skills | Source |
|-------|-------------|-------------|--------|--------|
| [Brainstorm Coach](agents/brainstorm-coach/) | Structured brainstorming, creative ideation, perspective shifts, and innovative problem-solving | Idea generation, creative blocks, perspective shifts | — | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Image Prompt Engineer](agents/image-prompt-engineer/) | Crafting detailed prompts for AI image generation — photography terminology, lighting, composition, and platform-specific optimization | AI image prompts for Midjourney, DALL-E, Stable Diffusion | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/design/design-image-prompt-engineer.md) |
| [Podcast Strategist](agents/podcast-strategist/) | Podcast concept development, show format design, episode planning, audience growth, podcast SEO, and content repurposing | Show concept, episode planning, podcast growth | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/marketing/marketing-podcast-strategist.md) |
| [UI Designer](agents/ui-designer/) | Visual design systems, component libraries, pixel-perfect interfaces, and dark mode theming | Interface design, component libraries, dark mode theming | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/design/design-ui-designer.md) |
| [UX Architect](agents/ux-architect/) | Information architecture, CSS design systems, layout frameworks, and developer-ready UX foundations | Information architecture, layout systems, developer handoff | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/design/design-ux-architect.md) |
| [Video Scriptwriter](agents/video-scriptwriter/) | YouTube scripts, explainer videos, ad scripts, video hooks, storytelling structure, and CTA design for video | YouTube scripts, explainer videos, ad scripts | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/marketing/marketing-video-optimization-specialist.md) |
| [Visual Storyteller](agents/visual-storyteller/) | Visual narratives, infographic design, data visualization, and multimedia content strategy | Infographic design, data visualization, visual narratives | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/design/design-visual-storyteller.md) |

### Development (22)

| Agent | Description | When to Use | Skills | Source |
|-------|-------------|-------------|--------|--------|
| [Accessibility Auditor](agents/accessibility-auditor/) | WCAG 2.2 compliance audits, assistive technology testing, and inclusive design guidance | WCAG compliance, assistive tech testing, inclusive design | Website Check | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/testing/testing-accessibility-auditor.md) |
| [AI Engineer](agents/ai-engineer/) | LLM integration, prompt engineering, tool-calling architecture, RAG pipelines, and AI agent design | LLM integration, tool-calling design, RAG pipelines | — | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [API Designer](agents/api-designer/) | REST and GraphQL API design, OpenAPI specifications, versioning, authentication patterns, and developer experience | REST/GraphQL API design, OpenAPI specs, versioning | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-backend-architect.md) |
| [API Tester](agents/api-tester/) | API testing and validation — functional, performance, security, and contract testing for REST and GraphQL | API validation, contract testing, security testing | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/testing/testing-api-tester.md) |
| [Automation Governance Architect](agents/automation-governance-architect/) | n8n workflow auditing, automation governance, naming conventions, error handling standards, and workflow lifecycle management | Workflow audits, automation standards, governance frameworks | — | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Backend Architect](agents/backend-architect/) | Backend system design, API architecture, PostgreSQL/Supabase patterns, microservices, and data modeling | API design, database modeling, Supabase/PostgREST patterns | — | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Code Reviewer](agents/code-reviewer/) | Constructive code reviews focused on correctness, security, maintainability, and performance | PR reviews, code quality gates, security review | GitHub | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-code-reviewer.md) |
| [Data Engineer](agents/data-engineer/) | ETL/ELT pipelines, data lakehouse architecture, data quality, and streaming systems | ETL/ELT pipelines, data lakehouse, streaming systems | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-data-engineer.md) |
| [Database Optimizer](agents/database-optimizer/) | Schema design, query optimization, indexing strategies, and performance tuning for PostgreSQL and MySQL | Slow query debugging, schema design, index tuning | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-database-optimizer.md) |
| [DevOps Engineer](agents/devops-engineer/) | CI/CD pipelines, Docker, Kubernetes, Infrastructure as Code, cloud deployments, and monitoring | Pipeline setup, deployment automation, cloud migration | GitHub | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-devops-automator.md) |
| [Frontend Developer](agents/frontend-developer/) | Modern web development with React, Vue, and Angular — responsive design, performance optimization, and accessibility | Modern web apps, pixel-perfect UIs, Core Web Vitals | Website Check, GitHub | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-frontend-developer.md) |
| [Git Workflow Master](agents/git-workflow-master/) | Git branching strategies, conventional commits, rebase workflows, and CI-friendly branch management | Branch strategy, history cleanup, CI-friendly workflows | GitHub | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-git-workflow-master.md) |
| [Incident Commander](agents/incident-commander/) | Production incident management, severity classification, blameless post-mortems, and on-call process design | Production incidents, severity triage, blameless post-mortems | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-incident-response-commander.md) |
| [Infrastructure Maintainer](agents/infrastructure-maintainer/) | VPS management, Docker operations, server monitoring, backup strategies, and system reliability | VPS maintenance, Docker ops, backup verification, SSL certs | — | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [MCP Developer](agents/mcp-developer/) | MCP server development, tool design, n8n-claw skill creation, and API-to-MCP integration | MCP server building, skill development, API-to-tool integration | — | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Rapid Prototyper](agents/rapid-prototyper/) | Ultra-fast MVP development, hypothesis validation, and prototype-to-production transition planning | Quick MVPs, hackathon projects, hypothesis validation | GitHub | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-rapid-prototyper.md) |
| [Security Auditor](agents/security-auditor/) | Threat modeling, OWASP Top 10, secure code review, vulnerability assessment, and security compliance | Threat modeling, vulnerability assessment, OWASP audits | IP Geolocation, Website Check | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-security-engineer.md) |
| [Security Engineer](agents/security-engineer/) | Security architecture, authentication systems, encryption implementation, infrastructure hardening, and secure defaults | Auth system design, encryption setup, infrastructure hardening | — | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Software Architect](agents/software-architect/) | System design, architectural patterns, trade-off analysis, and technical decision records | Architecture decisions, system design, trade-off analysis | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-software-architect.md) |
| [SRE](agents/sre/) | Site reliability engineering: SLOs, error budgets, observability, toil reduction, and incident readiness | Production reliability, toil reduction, capacity planning | IP Geolocation | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-sre.md) |
| [Technical Writer](agents/technical-writer/) | Developer documentation, API references, README files, tutorials, and technical guides | API docs, README files, tutorials, technical guides | GitHub, Wikipedia, PDF Tools +2 more | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/engineering/engineering-technical-writer.md) |
| [Workflow Architect](agents/workflow-architect/) | n8n workflow design, process-to-automation mapping, node selection, and workflow architecture planning | Process-to-automation mapping, workflow blueprints, node selection | — | [@freddy-schuetz](https://github.com/freddy-schuetz) |

### Marketing (13)

| Agent | Description | When to Use | Skills | Source |
|-------|-------------|-------------|--------|--------|
| [Ad Copywriter](agents/ad-copywriter/) | PPC ad copy, landing page copywriting, conversion optimization, direct response, and A/B testing frameworks | PPC copy, landing pages, A/B test variants | Google Ads, QR Code | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/paid-media/paid-media-ad-creative-strategist.md) |
| [Brand Strategist](agents/brand-strategist/) | Brand identity, positioning strategy, messaging hierarchy, tone of voice, brand architecture, and brand audits | Brand identity, positioning, tone of voice, brand audits | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/design/design-brand-guardian.md) |
| [Content Creator](agents/content-creator/) | Text creation, social media content, blog articles, marketing copy | Blog posts, social media content, marketing copy | Wikipedia, DeepL, News, TMDB +4 more | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Developer Advocate](agents/developer-advocate/) | Developer relations, DX optimization, technical content creation, and community building | DevRel content, DX optimization, community building | GitHub, Hacker News | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/specialized/specialized-developer-advocate.md) |
| [Growth Hacker](agents/growth-hacker/) | Growth experiments, viral loops, funnel optimization, and scalable user acquisition strategies | Growth experiments, funnel optimization, viral loops | Google Analytics, Google Ads | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/marketing/marketing-growth-hacker.md) |
| [Instagram Curator](agents/instagram-curator/) | Instagram visual strategy, grid aesthetics, multi-format content (Reels, Stories, Posts), and social commerce | Grid strategy, Reels/Stories, social commerce | QR Code | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/marketing/marketing-instagram-curator.md) |
| [LinkedIn Creator](agents/linkedin-creator/) | LinkedIn content strategy, thought leadership posts, personal branding, and professional engagement | Thought leadership, personal branding, professional posts | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/marketing/marketing-linkedin-content-creator.md) |
| [Newsletter Writer](agents/newsletter-writer/) | Email newsletter strategy, subject line optimization, content structuring, drip campaigns, and subscriber engagement | Email campaigns, subject lines, drip sequences | Email IMAP/SMTP, Gmail, DeepL | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/prompts/marketing/marketing-newsletter-writer.md) |
| [Reddit Community Builder](agents/reddit-community-builder/) | Reddit community engagement, post strategy, subreddit analysis, AMA preparation, and authentic community participation | Subreddit engagement, post strategy, AMA prep | News (NewsAPI), Hacker News | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/prompts/marketing/marketing-reddit-community-builder.md) |
| [SEO Specialist](agents/seo-specialist/) | Technical SEO, content optimization, link authority building, and organic search growth | Technical SEO, content optimization, link building | Google Analytics, Website Check | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/marketing/marketing-seo-specialist.md) |
| [Social Media Strategist](agents/social-media-strategist/) | Cross-platform social media strategy, content calendars, community management, and engagement optimization | Cross-platform strategy, content calendars, community management | News (NewsAPI), TMDB | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/marketing/marketing-social-media-strategist.md) |
| [TikTok Strategist](agents/tiktok-strategist/) | TikTok content strategy, algorithm optimization, creator partnerships, and short-form video growth | Short-form video, algorithm optimization, creator partnerships | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/marketing/marketing-tiktok-strategist.md) |
| [Twitter Strategist](agents/twitter-strategist/) | Twitter/X content strategy, thread writing, engagement tactics, trend riding, and audience growth | Thread writing, trend riding, audience growth | News (NewsAPI), Hacker News | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/prompts/marketing/marketing-twitter-strategist.md) |

### Operations (10)

| Agent | Description | When to Use | Skills | Source |
|-------|-------------|-------------|--------|--------|
| [Customer Support Coach](agents/customer-support-coach/) | Support response frameworks, escalation handling, FAQ creation, tone calibration, de-escalation, and CSAT improvement | Support frameworks, escalation handling, CSAT improvement | Email IMAP/SMTP | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/support/support-support-responder.md) |
| [Email Writer](agents/email-writer/) | Professional emails, business letters, and correspondence in German and English | Professional emails, business correspondence | Email IMAP/SMTP, Gmail, DeepL | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Executive Summarizer](agents/executive-summarizer/) | Condensing long texts, reports, and meetings into concise executive briefings | Meeting summaries, report condensation, executive briefings | Vexa Meetings, Nextcloud Files, PDF Tools | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/support/support-executive-summary-generator.md) |
| [Legal Advisor](agents/legal-advisor/) | GDPR/DSGVO compliance, privacy policies, terms of service, and EU regulatory guidance | GDPR compliance, privacy policies, terms of service | PDF Tools | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/support/support-legal-compliance-checker.md) |
| [Meeting Assistant](agents/meeting-assistant/) | Structured meeting protocols, transcript processing, action items, and decision tracking | Meeting protocols, transcript processing, action items | Vexa Meetings, CalDAV, Google Calendar +2 more | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Nutrition Advisor](agents/nutrition-advisor/) | Nutrition analysis, meal planning, dietary guidance, food product evaluation, and recipe suggestions | Meal planning, dietary guidance, food product analysis | OpenFoodFacts, Recipes | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Project Manager](agents/project-manager/) | Project planning, WBS, risk management, RACI matrices, stakeholder communication, and status reporting | Project planning, WBS, risk management, status reporting | CalDAV, Google Calendar, Notion, Todoist +4 more | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/project-management/project-management-senior-project-manager.md) |
| [Support Responder](agents/support-responder/) | First-response support ticket drafting, issue triage, knowledge base article creation, and escalation handling | Ticket drafts, issue triage, knowledge base articles | Email IMAP/SMTP, Gmail, NocoDB CRM | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/support/support-support-responder.md) |
| [Translator](agents/translator/) | Context-aware translations between German, English, and French with tone adaptation | German/English/French translations, tone adaptation | DeepL Translate, Dictionary | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Travel Planner](agents/travel-planner/) | Trip planning, itinerary building, transport connections, weather-aware scheduling, and travel logistics | Trip planning, route optimization, weather-aware scheduling | Deutsche Bahn, Wiener Linien, Weather, Public Holidays +5 more | [@freddy-schuetz](https://github.com/freddy-schuetz) |

### Product (4)

| Agent | Description | When to Use | Skills | Source |
|-------|-------------|-------------|--------|--------|
| [Feedback Synthesizer](agents/feedback-synthesizer/) | User feedback analysis across channels — theme extraction, sentiment scoring, and actionable product insights | User feedback analysis, theme extraction, sentiment scoring | NocoDB CRM | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/product/product-feedback-synthesizer.md) |
| [Product Manager](agents/product-manager/) | Feature prioritization, roadmap planning, user stories, sprint planning, and product strategy | Feature prioritization, roadmap planning, user stories | Notion, Todoist, Vikunja | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/product/product-manager.md) |
| [Product Strategist](agents/product-strategist/) | Product vision, market positioning, competitive differentiation, go-to-market strategy, and pricing models | Market positioning, competitive analysis, GTM strategy | Google Analytics, NocoDB CRM, News | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/prompts/product/product-manager.md) |
| [Sprint Prioritizer](agents/sprint-prioritizer/) | Sprint planning, backlog prioritization with RICE/MoSCoW/Kano, and team velocity optimization | Backlog grooming, RICE/MoSCoW scoring, velocity optimization | Todoist, Vikunja, Notion | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/product/product-sprint-prioritizer.md) |

### Research (4)

| Agent | Description | When to Use | Skills | Source |
|-------|-------------|-------------|--------|--------|
| [Competitive Analyst](agents/competitive-analyst/) | Competitive intelligence, SWOT analysis, market positioning, feature comparison matrices, and win/loss analysis | SWOT analysis, market positioning, feature comparisons | News (NewsAPI), Country Info | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Research Expert](agents/research-expert/) | Deep web research, fact-checking, source evaluation | Deep-dive research, fact-checking, source evaluation | Wikipedia, Hacker News, News, Country Info | [@freddy-schuetz](https://github.com/freddy-schuetz) |
| [Trend Researcher](agents/trend-researcher/) | Market intelligence, emerging trend identification, competitive analysis, and technology scouting | Emerging trends, market intelligence, technology scouting | News (NewsAPI), Hacker News | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/product/product-trend-researcher.md) |
| [UX Researcher](agents/ux-researcher/) | User research methods, usability testing, persona development, jobs-to-be-done, journey mapping, and insight synthesis | Usability testing, persona development, journey mapping | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/design/design-ux-researcher.md) |

### Sales (6)

| Agent | Description | When to Use | Skills | Source |
|-------|-------------|-------------|--------|--------|
| [Account Strategist](agents/account-strategist/) | Post-sale account expansion, stakeholder mapping, QBR facilitation, and net revenue retention | Account expansion, stakeholder mapping, QBR facilitation | NocoDB CRM | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/sales/sales-account-strategist.md) |
| [Discovery Coach](agents/discovery-coach/) | Sales discovery methodology coaching — SPIN Selling, Gap Selling, and Challenger question frameworks | Sales discovery coaching, SPIN/Gap/Challenger frameworks | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/sales/sales-discovery-coach.md) |
| [Outbound Strategist](agents/outbound-strategist/) | Signal-based outbound prospecting, ICP definition, multi-channel sequences, and personalized outreach | ICP definition, cold outreach sequences, prospecting | Email IMAP/SMTP, Gmail, NocoDB CRM | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/sales/sales-outbound-strategist.md) |
| [Proposal Writer](agents/proposal-writer/) | Business proposals, RFP responses, grant applications, pitch narratives, executive summaries, and win theme development | RFP responses, business proposals, pitch narratives | PDF Tools | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/sales/sales-proposal-strategist.md) |
| [Sales Coach](agents/sales-coach/) | Sales rep development, pipeline review facilitation, call coaching, and forecast discipline | Rep development, call coaching, pipeline reviews | — | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/sales/sales-coach.md) |
| [Sales Strategist](agents/sales-strategist/) | B2B/B2C sales strategy, lead qualification, pipeline management, objection handling, and deal closing frameworks | Sales strategy, lead qualification, deal closing frameworks | NocoDB CRM | [agency-agents](https://github.com/msitarzewski/agency-agents/blob/main/sales/sales-deal-strategist.md) |

---

## How It Works

Expert agents are specialized sub-agents that your main n8n-claw agent can delegate tasks to. Each agent has its own **expertise profile** (persona) that defines what it knows, how it works, and what quality standards it follows.

The main agent's personality stays unchanged — it delegates specific tasks to experts and rephrases their results in its own tone. The user never talks to a sub-agent directly.

**Architecture:**

```
User → Main Agent → Expert Agent Tool → Sub-Agent Runner
                                            ├── Loads persona from DB
                                            ├── Builds system prompt
                                            └── Runs AI Agent (Claude + HTTP/WebSearch/MCP)
                                                → Returns result to Main Agent
                                                    → Main Agent rephrases in own tone → User
```

### Skills

The **"Skills"** column in the agent tables shows which [n8n-claw MCP Skills](https://github.com/freddy-schuetz/n8n-claw-templates) enhance an agent's capabilities. When a skill is installed, the sub-agent can use it as a tool during task execution.

For example, the **Travel Planner** agent can use Deutsche Bahn (train connections), Weather (forecasts), Public Holidays (awareness), and more — making it significantly more capable than a pure-LLM agent.

Agents marked with **"—"** are purely expertise-based and don't require specific MCP skills to be effective.

---

## Usage

Agents are managed via chat with your n8n-claw agent:

```
"What expert agents do you have?"      → lists installed agents
"Show me available expert agents"      → lists all agents from catalog
"Install the Research Expert"          → installs from catalog
"Remove the Data Analyst"             → uninstalls
```

Delegation happens automatically when the main agent decides a task fits an expert:

```
"Research the best hiking trails in Tyrol"    → delegates to research-expert
"Write an Instagram post about our product"   → delegates to content-creator
"Analyze these sales numbers"                 → delegates to data-analyst
```

The default agents (research-expert, content-creator, data-analyst) ship pre-installed with `setup.sh`.

---

## Agent Structure

Each agent lives in its own directory under `agents/`:

```
agents/
  index.json                    ← catalog (one entry per agent)
  {agent-id}/
    manifest.json               ← metadata (name, category, description, attribution)
    persona.json                ← persona content (system prompt for the sub-agent)
```

### manifest.json

```json
{
  "id": "my-agent",
  "name": "My Agent",
  "version": "1.0.0",
  "category": "operations",
  "description": "What this agent does",
  "emoji": "🎯",
  "author": "your-github-username",
  "license": "MIT"
}
```

#### Manifest fields

| Field | Required | Description |
|-------|----------|-------------|
| `id` | yes | Unique agent ID (lowercase, hyphens only) |
| `name` | yes | Display name |
| `version` | yes | Semver version (e.g. `1.0.0`) |
| `category` | yes | Category for filtering (see below) |
| `description` | yes | Short description |
| `emoji` | yes | Single emoji representing the agent |
| `author` | yes | GitHub username |
| `license` | yes | License identifier (e.g. `MIT`) |
| `based_on` | no | Attribution object (see [Attribution](#attribution)) |

**Categories:** `analytics`, `creative`, `development`, `marketing`, `operations`, `product`, `research`, `sales`

### persona.json

```json
{
  "format": "n8n-claw-agent",
  "format_version": 1,
  "persona_key": "persona:my-agent",
  "display_name": "My Agent",
  "content": "# My Agent\n\n## Expertise\n...\n\n## Workflow\n...\n\n## Quality Standards\n..."
}
```

#### Persona fields

| Field | Required | Description |
|-------|----------|-------------|
| `format` | yes | Must be `n8n-claw-agent` |
| `format_version` | yes | Must be `1` |
| `persona_key` | yes | DB key: `persona:{agent-id}` |
| `display_name` | yes | Human-readable name |
| `content` | yes | Persona content (Markdown, escaped as JSON string) |

### index.json

The central catalog. Add one entry per agent:

```json
{
  "id": "my-agent",
  "name": "My Agent",
  "version": "1.0.0",
  "category": "operations",
  "description": "What this agent does",
  "emoji": "🎯",
  "author": "your-github-username"
}
```

---

## Persona Content Guidelines

Expert agents are **pure expertise profiles** — they are tools, not personalities.

**DO:**
- Define clear expertise areas (`## Expertise`)
- Describe a structured workflow (`## Workflow`)
- Set quality standards (`## Quality Standards`)
- Write in English
- Reference available tools where appropriate (HTTP, Web Search, MCP)

**DON'T:**
- Give the agent a name or personality traits
- Add greetings or conversation starters
- Use first person ("I am...")
- Include tool configuration (tools are injected by the Sub-Agent Runner)

### Available Sub-Agent Tools

The Sub-Agent Runner provides these tools to every expert agent automatically:

| Tool | Description |
|------|-------------|
| **HTTP Request** | Call any URL (GET, POST, PUT, DELETE) |
| **Web Search** | DuckDuckGo instant answers and related topics |
| **MCP Client** | Call tools on installed MCP skill servers |

You don't need to configure these — just reference them in the persona's Workflow section where appropriate (e.g. "Recherchiere via Web Search").

### Example Persona

```markdown
# Research Expert

## Expertise
Web research, fact-checking, source evaluation, summarizing complex topics.

## Workflow
1. Analyze the topic and research question
2. Research multiple independent sources (Web Search + HTTP)
3. Cross-check facts and identify contradictions
4. Deliver structured results with source citations

## Quality Standards
- Always cite sources (URLs, titles)
- Transparently flag uncertainties and knowledge gaps
- Never present speculation as fact
- When sources contradict: present both sides
- Check and note the timeliness of information
```

---

## Attribution

Some agent personas may be inspired by or adapted from [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) (MIT License, 31k+ Stars).

When an agent is based on a prompt from that repo:

1. Add the `based_on` field to `manifest.json`:
```json
{
  "based_on": {
    "source": "agency-agents",
    "url": "https://github.com/msitarzewski/agency-agents",
    "original_prompt": "prompts/category/agent-name.md",
    "license": "MIT"
  }
}
```

2. The "Source" column in the [Available Agents](#available-agents-73) table links to the original source
3. Note the attribution in your PR description

The original agency-agents format (`# Identity`, `# System Prompt`, `# Output Format`) must be adapted to our expertise-profile format (`## Expertise`, `## Workflow`, `## Quality Standards`).

---

## Contributing

### Step-by-step

1. Fork this repository
2. Create a directory under `agents/` with your agent ID (lowercase, hyphens only)
3. Add `manifest.json` with all required fields
4. Add `persona.json` with the expertise profile
5. Add an entry to `agents/index.json`
6. Update the [Available Agents](#available-agents-73) table in this README (sorted: Category, then Agent alphabetically)
7. Submit a pull request

For a detailed guide with annotated examples, see [TEMPLATE_EXAMPLE.md](TEMPLATE_EXAMPLE.md).

### PR checklist

- [ ] Agent ID is lowercase with hyphens only (e.g. `seo-specialist`)
- [ ] `manifest.json` has all required fields
- [ ] `persona.json` uses format `n8n-claw-agent` with format_version `1`
- [ ] `persona_key` matches `persona:{agent-id}`
- [ ] Persona follows expertise-profile format (no personality, no greetings)
- [ ] `index.json` entry matches manifest data
- [ ] README table updated with new agent
- [ ] If based on agency-agents: `based_on` field in manifest + noted in PR
- [ ] All persona content in English

---

## CDN

Agents are served via jsDelivr CDN for fast, reliable delivery:

```
https://cdn.jsdelivr.net/gh/freddy-schuetz/n8n-claw-agents@master/agents/index.json
https://cdn.jsdelivr.net/gh/freddy-schuetz/n8n-claw-agents@master/agents/{id}/manifest.json
https://cdn.jsdelivr.net/gh/freddy-schuetz/n8n-claw-agents@master/agents/{id}/persona.json
```

The CDN uses the `@master` branch reference. In production, pin to a specific commit hash to avoid caching issues. Purge cache if needed:

```bash
curl https://purge.jsdelivr.net/gh/freddy-schuetz/n8n-claw-agents@<hash>/agents/index.json
```

For a reference of agent file formats, see [TEMPLATE_EXAMPLE.md](TEMPLATE_EXAMPLE.md).

---

## License

MIT
