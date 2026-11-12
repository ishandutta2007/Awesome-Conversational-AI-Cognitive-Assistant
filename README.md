# Awesome-Conversational-AI-Cognitive-Assistant

# Top Conversational AI & Cognitive Assistant Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Enterprise Assistants, Multi-Channel Bots & Retrieval-Augmented Knowledge Agents*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Conversational AI & Cognitive Assistants**. These tools help organizations deploy AI-powered assistants that understand natural language, retrieve knowledge from internal systems, automate workflows, and engage users across chat, voice, and messaging channels—covering everything from enterprise copilots to self-hosted RAG pipelines.

**Examples** include Zoho Zia, Microsoft Copilot, OpenAI ChatGPT Enterprise, Google Gemini Enterprise, IBM watsonx Assistant, Kore.ai, Amelia, Yellow.ai, Aisera, and open-source alternatives like Rasa and Botpress (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted conversational AI, open-source RAG engines, and community-driven assistant frameworks—ideal for organizations seeking data sovereignty and transparent model behavior over opaque enterprise SaaS.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Microsoft Copilot](https://www.microsoft.com/en-us/microsoft-copilot)** | Enterprise AI assistant integrated across Microsoft 365 (Word, Excel, Teams, Outlook) and Windows. Grounded in organizational data via Microsoft Graph. Requires Microsoft 365 licensing plus Copilot add-on. | Quote-only (add-on to M365 subscription) | No free tier for enterprise Copilot; consumer Copilot free |
| **[OpenAI ChatGPT Enterprise](https://openai.com/enterprise)** | Enterprise-grade ChatGPT with advanced security, admin controls, unlimited high-speed GPT access, and data analysis. Does not train on business data. | Quote-only (custom enterprise contract) | No free tier; demo via sales |
| **[Google Gemini Enterprise](https://cloud.google.com/gemini)** | Enterprise AI assistant integrated with Google Workspace and Google Cloud. Grounded in organizational data, with Vertex AI model garden access. | Quote-only (Workspace/Cloud add-on) | No free tier; trial via Google Cloud |
| **[IBM watsonx Assistant](https://www.ibm.com/products/watsonx-assistant)** | Enterprise conversational AI platform for building AI assistants across channels. Includes intent recognition, dialog management, and integration with enterprise systems. | Quote-only (per-usage or subscription) | No free tier; trial via IBM Cloud |
| **[Kore.ai](https://kore.ai/)** | Enterprise conversational AI platform for building, deploying, and managing AI assistants across voice and digital channels. Includes AI Agent platform, contact center automation, and workflow integration. | Quote-only (enterprise subscription) | No free tier; demo via sales |
| **[Amelia](https://amelia.ai/)** | Enterprise AI assistant (IPsoft) for IT operations, customer service, and HR. Positioned for large-scale automation with natural language understanding. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Yellow.ai](https://yellow.ai/)** | Conversational AI platform for customer support automation across voice and chat. Includes AI agents, campaign orchestration, and analytics. | Quote-only (enterprise subscription) | No free tier; demo via sales |
| **[Aisera](https://aisera.com/)** | AI service management platform with conversational AI for IT, HR, and customer service. Grounded in enterprise knowledge bases. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Zoho Zia](https://www.zoho.com/zia/)** | AI assistant embedded across Zoho applications. Includes predictive analytics, voice assistant, and workflow automation within the Zoho ecosystem. | Included with Zoho subscriptions | **Free** with Zoho free plans; limited AI capabilities |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Rasa](https://github.com/RasaHQ/rasa)** | [![Stars](https://img.shields.io/github/stars/RasaHQ/rasa?style=social&color=white)](https://github.com/RasaHQ/rasa/stargazers) | Open-source (Apache-2.0) conversational AI framework for text- and voice-based assistants. Includes NLU, dialogue management, and integrations with Slack, Facebook, and messaging channels. **Note: in maintenance mode as of last release January 2025; Rasa CALM is the successor** [citation:8][citation:10]. |
| **[RAGFlow](https://github.com/infiniflow/ragflow)** | [![Stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social&color=white)](https://github.com/infiniflow/ragflow/stargazers) | Leading open-source RAG engine fusing retrieval-augmented generation with agent capabilities. Provides a superior context layer for LLMs. Docker Compose deployment with Elasticsearch/Infinity, MinIO, Redis, and MySQL. Apache-2.0 [citation:6]. |
| **[Botpress](https://github.com/botpress/botpress)** | [![Stars](https://img.shields.io/github/stars/botpress/botpress?style=social&color=white)](https://github.com/botpress/botpress/stargazers) | Open-source conversational AI platform built with TypeScript. Built-in NLU, visual flow builder, and deployment to Slack, MS Teams, website, Telegram, and other channels. Self-hostable or cloud [citation:4][citation:11]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Khoj](https://github.com/khoj-ai/khoj)** | [![Stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social&color=white)](https://github.com/khoj-ai/khoj/stargazers) | Self-hostable personal AI assistant that searches and chats across notes, documents, and images. Acts as a "second brain" for local knowledge bases. ~37.9k stars [citation:15]. |
| **[Leon](https://github.com/leon-ai/leon)** | [![Stars](https://img.shields.io/github/stars/leon-ai/leon?style=social&color=white)](https://github.com/leon-ai/leon/stargazers) | Open-source personal assistant that runs on your own server. Supports custom modules and integrations for automation, reminders, and information retrieval. ~17.6k stars [citation:15]. |
| **[Pipecat](https://github.com/pipecat-ai/pipecat)** | [![Stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=social&color=white)](https://github.com/pipecat-ai/pipecat/stargazers) | Production-grade voice AI framework with sub-250ms latency, WebRTC support, multimodal interaction (voice, vision, text), and 70+ language compatibility. ~16.9k stars [citation:15]. |
| **[IntelligenceSuite](https://pypi.org/project/intelligence-suite/)** | — | Python-based local RAG suite with CodeIntelligence, DocIntelligence, and MentorIntelligence modules. Runs on Ollama with ChromaDB; OpenAI-compatible gateway for OpenWebUI/LibreChat integration. No cloud, no API key required [citation:5]. |
| **[Flexible GraphRAG](https://pypi.org/project/flexible-graphrag/)** | — | Open-source AI context platform with document processing (Docling/LlamaParse), knowledge graph auto-building, hybrid semantic search (fulltext, vector, property graph, RDF/SPARQL), and AI chat. Supports 14 data sources and 15 graph databases [citation:12]. |

**Frameworks for building custom systems**: Combine **RAGFlow** for enterprise-grade retrieval-augmented generation, **Rasa** (or its CALM successor) for conversational flow management, and **IntelligenceSuite** or **Khoj** for local-first knowledge grounding—all deployable via Docker without per-seat SaaS licensing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Conversational AI assistants process potentially sensitive organizational knowledge and user conversations; enforce data residency controls, access logging, and compliance with applicable privacy regulations.
- **Rasa is in maintenance mode** as of January 2025; new projects should evaluate Rasa CALM or alternative frameworks [citation:8]. Enterprise SaaS platforms (Microsoft Copilot, ChatGPT Enterprise, Kore.ai, Amelia, Yellow.ai, Aisera) are universally quote-only with no public pricing. Open-source alternatives provide genuine RAG and dialogue capabilities but require engineering effort for production hardening, observability, and security controls.

---

**Made for AI engineers, platform teams, customer experience leaders, and developers building conversational assistants.**  
Let's make conversational AI more open, grounded, and controllable.
