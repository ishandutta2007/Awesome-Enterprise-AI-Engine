# Awesome-Enterprise-AI-Engine

# Top Enterprise AI Engine Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Self-Hosted RAG, Agentic Workflows & Data-Sovereign AI Assistants*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise AI Engines**. These tools help organizations deploy AI assistants that connect to internal knowledge, automate workflows, and answer questions securely—covering everything from polished proprietary copilots to self-hosted RAG platforms that keep sensitive data entirely within your infrastructure.

**Examples** include Microsoft Copilot, Salesforce Einstein, ServiceNow Now Assist, OpenAI ChatGPT Enterprise, Onyx, Open WebUI, Dify, and RAGFlow (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted enterprise AI, open-source RAG engines, and community-driven agent platforms—ideal for organizations seeking data sovereignty and avoiding per-seat SaaS pricing that scales across headcount. The open-source landscape is genuinely mature: **Onyx** provides a complete enterprise AI platform with 40+ connectors and cited answers , **Open WebUI** is the most widely deployed self-hosted ChatGPT alternative with 124K+ stars , and **Dify** offers a visual LLMOps platform for agentic workflows .

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
| **[Salesforce Einstein](https://www.salesforce.com/)** | AI embedded across the Salesforce platform for sales, service, and marketing. Predictive scoring, generative AI (Einstein GPT), and workflow automation. | Quote-only (bundled with Salesforce licensing) | No free tier; demo via sales |
| **[ServiceNow Now Assist](https://www.servicenow.com/)** | Generative AI capabilities embedded in the ServiceNow platform for IT, HR, and customer service workflows. Summarization, code generation, and case resolution. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Google Gemini Enterprise](https://cloud.google.com/gemini)** | Enterprise AI assistant integrated with Google Workspace and Google Cloud. Grounded in organizational data, with Vertex AI model garden access. | Quote-only (Workspace/Cloud add-on) | No free tier; trial via Google Cloud |
| **[Claude for Work](https://www.anthropic.com/)** | Enterprise Claude access with admin controls, SSO, and data privacy guarantees. Positioned for teams wanting Anthropic's model with enterprise governance. | Quote-only | No free tier; demo via sales |
| **[Kore.ai](https://kore.ai/)** | Enterprise conversational AI platform for building, deploying, and managing AI assistants across voice and digital channels. **Pay-as-you-go with 5,000 free sessions per account** (up to 5 bots) . | Pay-as-you-go (from $100 reload); Enterprise: quote-only | **Free**: 5,000 sessions per account (up to 5 bots) |
| **[Yellow.ai](https://yellow.ai/)** | Conversational AI platform for customer support automation across voice and chat. Includes AI agents, campaign orchestration, and analytics. | Quote-only (enterprise subscription) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Open WebUI](https://github.com/open-webui/open-webui)** | [![Stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social&color=white)](https://github.com/open-webui/open-webui/stargazers) | **The most deployed self-hosted AI chat platform.** MIT licensed, **124K+ GitHub stars** . Supports **Ollama, OpenAI-compatible APIs, MCP servers, and RAG with 9+ vector databases**. **Multi-user RBAC and LDAP/SSO** built in. Self-hosted ChatGPT-style UI with complete data sovereignty—no data leaves your environment . **Best for organizations wanting a proven, widely-adopted self-hosted ChatGPT alternative** with enterprise auth. |
| **[Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx)** | [![Stars](https://img.shields.io/github/stars/onyx-dot-app/onyx?style=social&color=white)](https://github.com/onyx-dot-app/onyx/stargazers) | **The leading open-source enterprise AI assistant with 40+ connectors.** Connects to **Slack, Google Drive, Confluence, Jira, Notion, and more**; indexes knowledge; provides **reliable answers with cited sources** so your team can check facts . Includes Chat, Internal Search, Web Search, Deep Research, Agents, Code Interpreter, Image Generation, Projects, and Plugins . **Hybrid keyword and vector search** gives the LLM relevant context . **Best for enterprises needing a comprehensive AI platform** that unifies search, chat, and agents across internal knowledge. |
| **[Dify](https://github.com/langgenius/dify)** | [![Stars](https://img.shields.io/github/stars/langgenius/dify?style=social&color=white)](https://github.com/langgenius/dify/stargazers) | **LLMOps platform with agentic workflows and visual builder.** Apache-2.0, **40K+ GitHub stars** . **Visual workflow builder combining LLM nodes, knowledge retrieval, tools, and conditional logic**—self-hosted or Dify Cloud . **Best for teams wanting to design and orchestrate AI workflows visually** without building orchestration code from scratch. |
| **[RAGFlow](https://github.com/infiniflow/ragflow)** | [![Stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social&color=white)](https://github.com/infiniflow/ragflow/stargazers) | **Open-source RAG engine based on deep document understanding.** Apache-2.0, **40K+ GitHub stars** . **Template-based chunking and grounded citations**—produces answers with traceable evidence . **Best for document-heavy enterprise knowledge bases** where citation accuracy matters. |
| **[Quivr](https://github.com/QuivrHQ/quivr)** | [![Stars](https://img.shields.io/github/stars/QuivrHQ/quivr?style=social&color=white)](https://github.com/QuivrHQ/quivr/stargazers) | **Opinionated RAG for enterprise data.** Apache-2.0, **38K+ GitHub stars** . **Multi-modal RAG with any LLM**—acts as a "second brain for enterprise data" . **Best for teams wanting a focused RAG engine** with multi-modal support and enterprise data integration. |
| **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)** | [![Stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=social&color=white)](https://github.com/Mintplex-Labs/anything-llm/stargazers) | **All-in-one desktop and Docker AI application.** MIT licensed, **30K+ GitHub stars** . **RAG, AI agents, and multi-model support**—works with any LLM. Document ingestion with vector databases . **Best for teams wanting a complete, self-contained AI workspace** that runs anywhere. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[LibreChat](https://github.com/danny-avila/LibreChat)** | [![Stars](https://img.shields.io/github/stars/danny-avila/LibreChat?style=social&color=white)](https://github.com/danny-avila/LibreChat/stargazers) | **Enhanced ChatGPT clone with multi-model support.** MIT licensed, **25K+ GitHub stars** . Supports **OpenAI, Anthropic, Google, and local models**. Agents, code interpreter, and file uploads . **Best for teams wanting a polished chat UI** with flexibility across model providers. |
| **[Khoj](https://github.com/khoj-ai/khoj)** | [![Stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social&color=white)](https://github.com/khoj-ai/khoj/stargazers) | **Self-hosted AI second brain.** AGPL-3.0, **28K+ GitHub stars** . Searches across **documents, notes, and the web**—supports local LLMs (Llama, Mistral) and cloud models (GPT-4, Claude). WhatsApp, Emacs, Obsidian, and browser integration . **Best for personal and team knowledge management** with broad integrations. |
| **[PrivateGPT](https://github.com/zylon-ai/private-gpt)** | [![Stars](https://img.shields.io/github/stars/zylon-ai/private-gpt?style=social&color=white)](https://github.com/zylon-ai/private-gpt/stargazers) | **Interact with your documents using local LLMs.** Apache-2.0, **55K+ GitHub stars** . **100% private—no data leaves your environment** . RAG pipeline with local embeddings and LLMs . **Best for maximum privacy** where even self-hosted cloud calls are unacceptable. |
| **[LocalAI](https://github.com/mudler/LocalAI)** | [![Stars](https://img.shields.io/github/stars/mudler/LocalAI?style=social&color=white)](https://github.com/mudler/LocalAI/stargazers) | **OpenAI-compatible API for local inference.** MIT licensed, **30K+ GitHub stars** . Drop-in replacement for OpenAI API—runs LLMs, image generation, and speech on consumer hardware . **Best for teams wanting OpenAI API compatibility** with fully local inference. |
| **[Thunderbolt (Mozilla)](https://github.com/thunderbird/thunderbolt)** | — | **Mozilla's sovereign AI client**—open-source, self-hosted alternative to Microsoft Copilot, ChatGPT Enterprise, and Claude Enterprise. Connects to **MCP servers, ACP agents, and deepset's Haystack** for orchestration. Can run on a single machine for sensitive data. Launched 2026 . **Best for organizations prioritizing sovereignty** and wanting a Firefox-era alternative to proprietary AI. |

**Frameworks for building custom systems**: Choose **Onyx** for a comprehensive enterprise AI platform with 40+ connectors and cited answers , **Open WebUI** for the most widely-deployed self-hosted ChatGPT alternative , **Dify** for visual LLM workflow orchestration , and **RAGFlow** for citation-accurate document RAG —all without per-seat SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise AI platforms process sensitive organizational knowledge and potentially PII; enforce access controls, audit logging, and compliance with applicable data protection regulations. **Self-hosted solutions keep data in your infrastructure but require you to secure it.**
- **Open-source enterprise AI has matured to genuine viability, but the category splits into distinct approaches.** **Onyx** is the most complete enterprise assistant with 40+ connectors, cited answers, and a full feature set (agents, deep research, code interpreter) —best for organizations wanting a unified AI platform across internal knowledge . **Open WebUI** is the most widely deployed self-hosted chat platform (124K+ stars) but is primarily a UI layer requiring separate RAG/agent infrastructure . **Dify and RAGFlow** are building blocks for custom workflows rather than turnkey assistants . **PrivateGPT** offers maximum privacy (100% local) at the cost of broader integrations . **Commercial platforms are quote-only at enterprise scale** except Kore.ai's **5,000 free sessions** . **Validate data residency requirements, connector needs, and operational capacity** before committing—self-hosted AI requires significant engineering effort for production hardening.

---

**Made for AI engineers, platform teams, and organizations building sovereign AI infrastructure.**  
Let's make enterprise AI engines more open, grounded, and data-sovereign.
