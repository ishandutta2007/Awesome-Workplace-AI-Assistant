# Awesome-Workplace-AI-Assistant

## Top Workplace AI Assistant Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Enterprise Knowledge Q&A, AI Copilots & Workflow Automation*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Workplace AI Assistants**. These tools connect to an organization's existing data sources — documents, emails, chat, tickets, and apps — to provide grounded answers, draft content, automate tasks, and surface organizational knowledge without requiring users to hunt across tools.



**Examples** include Microsoft 365 Copilot, Google Workspace Gemini, Salesforce Agentforce, Slack AI, Zoom AI Companion, Notion AI, Glean, Amazon Q Business, Atlassian Intelligence, and Box AI (the category leaders).



**Open-source emphasis**: The open-source ecosystem for workplace AI is exceptionally strong. **Onyx** (formerly Danswer) leads as the de facto open-source Glean alternative, with **Mewbo**, **Bionic**, and **Xyne** providing production-grade agentic platforms for self-hosted enterprise knowledge work . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Microsoft 365 Copilot](https://www.microsoft.com/microsoft-365/copilot)**  

  Integrated AI assistant across Word, Excel, PowerPoint, Outlook, and Teams. Grounded in Microsoft Graph data with enterprise controls. Monthly per-user licensing ($30/user/month typical) or pay-as-you-go consumption model . Free Copilot Chat available without organizational data access .



- **[Google Workspace Gemini](https://workspace.google.com/solutions/ai/)**  

  AI assistant integrated across Gmail, Docs, Sheets, Slides, and Meet. Gemini Business and Enterprise add-ons provide usage limits and enterprise-grade data protection. Gemini Advanced offers Deep Research, NotebookLM Plus, and seamless workflow integration across 45+ languages .



- **[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**  

  Enterprise AI assistant (formerly Einstein Copilot) natively integrated across Salesforce applications. Uses organization's own CRM data for grounded insights without expensive model training. Library of pre-built actions for sales, service, marketing, commerce, and industry-specific workflows .



- **[Slack AI](https://slack.com/features/ai)**  

  Native Slack assistant for conversation summaries, search, and task automation. August 2026 release added Slack Code (team-visible agentic coding), Agents tab, Deep Research, and Slackbot "Big Mode" for research and file generation. Salesforce approvals and Seismic enterprise search integrated .



- **[Zoom AI Companion](https://www.zoom.com/en/products/ai-assistant/)**  

  Agentic AI solution evolving from assistant to workplace collaborator. Features My notes (cross-platform meeting capture), Personal workflows (natural language automation), and Team Chat data integration. Included with paid Zoom Workplace accounts .



- **[Notion AI](https://www.notion.com/product/ai)**  

  Workspace AI with Q&A, writing assistance, and database automation. Notion 3.6 added External Agents (Claude, Cursor), AI Meeting Notes with speaker labels, interactive HTML blocks, and Microsoft file support (PPTX, XLSX, DOCX). MCP connections for Mercury, Mixpanel, Miro, Box, and ClickHouse .



- **[Glean](https://www.glean.com/)**  

  Enterprise AI coworker connecting to all company apps and documents. Permission-aware search, grounded answers with citations, and knowledge-to-work-product generation. Works across browser, desktop, Slack, and MCP-enabled AI tools. Designed to support human decision-makers, not replace them .



- **[Amazon Q Business](https://aws.amazon.com/q/business/)**  

  AWS-native generative AI assistant with 40+ connectors (Slack, Teams, Smartsheet, browser extensions). Extracts semantic meaning from embedded visual content, supports cross-region inference, and provides Q Apps for custom AI-powered applications .



- **[Atlassian Intelligence](https://www.atlassian.com/software/artificial-intelligence)**  

  AI features across Jira, Confluence, and Jira Service Management. Natural language to JQL/SQL conversion, meeting summarization, virtual agent in Slack/Teams, and incident response automation. Built on the Teamwork Graph combining 20+ years of team collaboration data .



- **[Box AI](https://www.box.com/ai)**  

  Secure, permissions-aware AI for Box content. Query single or multiple documents, extract metadata with AI Extract Agents, generate content in Box Notes, and create custom AI agents in Box AI Studio (Enterprise Advanced). Available across Business, Enterprise, and Enterprise Plus plans .



## Open-Source GitHub Projects



- **[Onyx](https://github.com/onyx-dot-app/onyx)**  

  **The leading open-source AI assistant and enterprise search platform**, formerly Danswer. 40+ connectors including Slack, Google Drive, Confluence, Jira, GitHub, Notion, and SharePoint. Provides Chat UI with document selection, custom AI Assistants with different prompts and knowledge sets, and any-LLM support (self-host fully airgapped). Community Edition is MIT licensed with all core features; Enterprise Edition adds SSO, RBAC, document permission inheritance, and analytics. Deployable via single `docker compose` command or Kubernetes for high-scale production .



- **[Mewbo](https://github.com/bearlike/Assistant)**  

  Open stack for agentic work grounded in your own knowledge. Agent hypervisor splits goals into parallel sub-agents, each carrying only needed tools, with live agent tree visualization and mid-run branch steering. Three products on one harness: Agentic Automation (isolated Git worktree per change), Agentic Wiki (AST-to-memory-graph documentation with cited Q&A), and Agentic Search (cross-system routing via reachability graph). Identity, roles, grants, and audit trail with OIDC/LDAP/SAML. Sandboxed execution with Landlock. Android client registered as device assistant. Any model behind LiteLLM .



- **[Bionic](https://github.com/bionic-gpt/bionic-gpt)**  

  Sovereign agentic AI for the enterprise. Rust-based agentic harness for internal AI teams building on-premise, private cloud, or air-gapped deployments. Provides AI workspace, model connectivity (hosted/private/local), RAG and dataset-backed knowledge, built-in tool runtime, sandboxed code execution, virtual filesystem, integrations, reusable skills, and Kubernetes deployment. SSO/OIDC, team permissions, and audit trails included. Apache 2.0 licensed .



- **[Xyne](https://hub.docker.com/r/xynehq/xyne)**  

  AI-first Search & Answer Engine for work, positioned as OSS alternative to Glean, Gemini, and MS Copilot. Connects to Google Workspace, Atlassian, Slack, GitHub, and more; securely indexes data and maps relationship graphs. Delivers Google+ChatGPT-like experience for finding anything across fragmented work information with up-to-date answers and sources .



- **[OpenBeam](https://github.com/kuluruvineeth/openbeam)**  

  Open-source Glean for SaaS and the physical world. 87 connectors spanning digital knowledge (Notion, Confluence, Slack, GitHub) and IoT/industrial (AWS IoT, MQTT, OPC-UA, BACnet, Samsara, Verkada). Hybrid semantic + keyword search with sub-200ms p99 latency. Six pre-built autonomous agents (Knowledge Digest, Stale Content Detector, Connector Health, Search Quality, Onboarding Curator, Compliance Watchdog) on Temporal cron schedules with approval gating. MCP server for Claude Code, Cursor, and other agent clients. Permission-aware, self-hostable with Docker Compose .



- **[eXo Platform AI](https://www.exoplatform.com/)**  

  Open-source sovereign digital workplace with multi-model AI integrated at the core. Context-aware assistants respecting access rights, operating in project spaces, documents, and discussions. RAG-based retrieval grounding responses in organizational knowledge. Multi-LLM architecture supporting Mistral, OpenAI, Anthropic, Gemini, and self-hosted models for fully on-premises deployments. Available in eXo Hubs cloud offering and Enterprise edition; on-premise in 7.2 release .



- **[Vexa](https://github.com/shaneholloman/vexa)**  

  Meeting notetaker and knowledge chat for teams. Joins Google Meet, Teams, Zoom, and Jitsi with real-time Whisper transcription and speaker attribution. Agent API for chat over workspace, one-shot invocations, scheduled routines, and event-driven dispatch (email triage, post-meeting reports). Air-gapped deployment on OpenShift with local LLMs. MCP endpoint for agent clients. Apache-2.0 licensed with security review artifacts included (FINOS CALM architecture, OpenSSF Security Insights) .



- **[Dotstell](https://github.com/dotstell/dotstell)**  

  Open-source personal knowledge graph connecting notes, people, tasks, and bookmarks in a living graph. AI layer works with Ollama (local), OpenAI, Anthropic, Gemini, or Groq. Features AI writing assistant with templates, RAG-grounded chat across knowledge, inline assist, smart title/auto-tags, note summaries, semantic related notes, and Person Intelligence. API keys stored only in browser localStorage, never sent to servers .



- **[The Curator](https://github.com/talirezun/the-curator)**  

  Domain-agnostic knowledge organization tool ingesting text/markdown into structured entity/concept/summary pages with YAML frontmatter. Builds visual knowledge graph via Obsidian with auto-colored nodes. Multi-turn AI chat with persistent history and GitHub sync. Supports Google Gemini and Anthropic Claude. Use cases for content creators, researchers, executives, software architects, and medical researchers .



### Additional Strong Open-Source Options



- **AI ChatOps Assistant** — Enterprise AI assistant with RAG, RBAC (Admin, HR, Engineering roles), Google OAuth SSO, local LLM (Mistral/Zephyr GGUF), ChromaDB vector storage, and analytics dashboard. Demonstrates end-to-end system design: ingestion → embedding → retrieval → generation → analytics .

- **mindroom** — AI-native interface on Matrix protocol with sandboxed execution (secrets isolation), 100+ tool integrations, and OpenClaw-compatible skills. Bridges to WhatsApp, Signal, and Telegram. macOS menu bar app .

- **the-curator** — Open-source knowledge graph with AI chat, Obsidian integration, and multi-domain templates .



**Frameworks for building custom workplace AI solutions**: Combine **Onyx** for comprehensive enterprise search and Q&A across 40+ connectors with MIT-licensed core . Use **Mewbo** for agentic task automation with parallel sub-agent execution, sandboxed code execution, and audit trails . Deploy **Bionic** for sovereign air-gapped deployments requiring Rust-based agentic runtime with Kubernetes orchestration . Choose **Xyne** for a lightweight Glean-style search and answer engine . Integrate **OpenBeam** for bridging digital SaaS and physical IoT/industrial systems in one query layer . For meeting-centric workflows, **Vexa** provides cross-platform notetaking with agent API . Note that true enterprise workplace AI with validated benchmark data, pre-built industry connectors, and global compliance certifications remains primarily commercial territory; open-source stacks provide strong knowledge retrieval, agent orchestration, and multi-model foundations that require integration for complete enterprise deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workplace AI assistants access sensitive organizational data and must comply with data privacy regulations (GDPR, CCPA) and enterprise security policies. Self-hosted solutions require proper security hardening, access controls, and audit logging.

- AI assistants ground responses in connected data but can hallucinate or miss context. Human review remains essential for high-stakes decisions. Glean explicitly states its systems are "not intended to perform high-risk operations" like hiring or termination decisions .

- The open-source ecosystem provides strong knowledge retrieval, agent orchestration, and multi-model foundations, but enterprise support, compliance certifications, and pre-built industry connectors remain primarily commercial offerings.



---



**Made for IT leaders, knowledge managers, platform engineers, and enterprise AI teams.**  

Let's make workplace AI more open, transparent, and knowledge-grounded.
