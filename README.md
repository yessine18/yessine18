<div align="center">

# Yessine Fakhfakh

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=21&duration=3000&pause=1200&color=00D9FF&center=true&vCenter=true&width=820&lines=Agentic+AI+Engineer;Enterprise+AI+%26+Microsoft+Ecosystem;RAG+%7C+Multi-Agent+Systems+%7C+Knowledge+Graphs;Building+Production-Grade+Intelligent+Workflows" alt="Typing banner" />

```bash
$ whoami
Software Engineer — Sfax, Tunisia 🇹🇳 — ENIS

$ current_focus
Production-grade agentic platforms across the Microsoft ecosystem
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B1120?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://www.linkedin.com/in/yessine-fakhfakh-470145298/)
[![Email](https://img.shields.io/badge/Email-0B1120?style=for-the-badge&logo=gmail&logoColor=00D9FF)](mailto:yessine.fakhfakh@enis.tn)
[![Portfolio](https://img.shields.io/badge/Portfolio-0B1120?style=for-the-badge&logo=readdotcv&logoColor=00D9FF)](https://yessine18.github.io/yessine-portfolio)
[![Location](https://img.shields.io/badge/Sfax%2C%20Tunisia-0B1120?style=for-the-badge&logo=mapbox&logoColor=39D2C0)](#)

<sub>Last updated · 2026-06-30</sub>

</div>

<br/>

## 🏅 Credentials

<div align="center">

[![Microsoft Certified](https://img.shields.io/badge/Microsoft%20Certified-Agentic%20AI%20Business%20Solutions%20Architect%20(AB--100)-0B1120?style=for-the-badge&logo=microsoft&logoColor=00D9FF)](#)
[![Microsoft Applied Skills](https://img.shields.io/badge/Microsoft%20Applied%20Skills-Identities%20%26%20Access%20with%20Microsoft%20Entra-0B1120?style=for-the-badge&logo=microsoftazure&logoColor=39D2C0)](#)

</div>

<br/>

## 👋 About

I build **enterprise-grade, autonomous AI systems** — the kind that sit inside real business workflows, not just demos. My work centers on agentic AI and multi-agent orchestration, enterprise RAG and knowledge graphs, and end-to-end automation across the Microsoft ecosystem.

| Focus Area | What I Build |
|---|---|
| **Agentic Systems** | Multi-agent AI with RAG, LLM orchestration, and knowledge-graph grounding |
| **Hybrid Workflows** | RAG + n8n + Neo4j pipelines that bridge unstructured and structured data |
| **Microsoft Automation** | Outlook, Graph API, Entra, and Azure DevOps integration end to end |
| **Full-Stack Delivery** | React, Angular, and .NET applications that ship and support the above |

<br/>

## 🏗️ How I Architect Agentic Systems

**Pattern A — Inbox-to-Resolution Agent** *(production implementation)*

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#13192B','primaryTextColor':'#C9D1D9','primaryBorderColor':'#00D9FF','lineColor':'#39D2C0','secondaryColor':'#1B2333','tertiaryColor':'#0B1120'}}}%%
flowchart LR
    A["📥 Outlook Inbox"] --> B["🔗 Microsoft Graph API"]
    B --> C["🧠 LLM Triage Agent"]
    C --> D["🔍 GraphRAG Retrieval"]
    D --> E[("🕸️ Neo4j Knowledge Graph")]
    C --> F["📋 Azure DevOps Work Item"]
    F --> G["📨 Automated Reply / Teams Alert"]

    classDef store fill:#1B2333,stroke:#39D2C0,stroke-width:2px,color:#C9D1D9;
    class E store;
```

**Pattern B — Generic Reasoning Loop** *(reusable orchestration shape)*

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#13192B','primaryTextColor':'#C9D1D9','primaryBorderColor':'#00D9FF','lineColor':'#39D2C0','secondaryColor':'#1B2333','tertiaryColor':'#0B1120'}}}%%
flowchart LR
    U["🧑 User Request"] --> O{"🧭 LangGraph Orchestrator"}
    O --> R["🔎 Retrieval Agent"]
    R --> K[("🕸️ Knowledge Graph")]
    O --> L["🤖 Reasoning Agent"]
    L --> AC["⚙️ Action Agent"]
    AC --> S["🗄️ Azure DevOps / API / DB"]

    classDef store fill:#1B2333,stroke:#39D2C0,stroke-width:2px,color:#C9D1D9;
    class K store;
```

<br/>

## 📚 Repository Gallery

<details open>
<summary><strong>🤖 AI & Agentic Systems</strong></summary>
<br/>

| Project | Description | Stack |
|---|---|---|
| [Outlook-TFS-automation](https://github.com/yessine18/Outlook-TFS-automation) | .NET + AI pipeline analyzing Outlook support emails, performing RAG-based auto-resolve, and creating Azure DevOps work items | C# · Python · PostgreSQL |
| [Brain-tumor-Multi-Agent](https://github.com/yessine18/Brain-tumor-Multi-Agent) | Multi-agent medical AI: VGG19 classifier + Neo4j knowledge graph + Grad-CAM visualization | Python |
| [Chatbot-RAG](https://github.com/yessine18/Chatbot-RAG) | RAG chatbot with PostgreSQL vector search for university enrollment Q&A | Jupyter · Python |
| [AI-Receipt-Processing-Automation](https://github.com/yessine18/AI-Receipt-Processing-Automation) | Self-hosted receipt OCR + LLM parsing, DB & bot integration | Python · JavaScript |
| [Motivation-Letter-email-Generator](https://github.com/yessine18/Motivation-Letter-email-Generator) | AI-powered motivation letter generator using Gemini LLM | Python · HTML |
| [ML-Analyse-de-Churn](https://github.com/yessine18/ML-Analyse-de-Churn) | Churn analysis experiments and dashboards | HTML · Python · CSS |

</details>

<details>
<summary><strong>🌐 Full-Stack Web Development</strong></summary>
<br/>

| Project | Description | Stack |
|---|---|---|
| [adaptive-backend](https://github.com/yessine18/adaptive-backend) | Node.js backend service for adaptive web platform workflows | JavaScript |
| [yessine-portfolio](https://github.com/yessine18/yessine-portfolio) | Personal portfolio site | HTML · CSS · JavaScript |
| [TecWeek](https://github.com/yessine18/TecWeek) | Event website for the IEEE engineering congress | TypeScript · CSS |
| [Angular](https://github.com/yessine18/Angular) | Angular full-stack application with backend integration | TypeScript |
| [Spring](https://github.com/yessine18/Spring) | Java Spring microservices workspace (gateway, registry, domain services) | Java |
| [PHP-project](https://github.com/yessine18/PHP-project) | Web project in PHP | PHP · CSS |

</details>

<details>
<summary><strong>🧪 Testing & Quality Assurance</strong></summary>
<br/>

| Project | Description | Stack |
|---|---|---|
| [PlayWright-test](https://github.com/yessine18/PlayWright-test) | Comprehensive Playwright E2E suite: smoke, integration, visual regression, a11y checks | JavaScript |

</details>

<details>
<summary><strong>🛰️ IoT & Environmental Monitoring</strong></summary>
<br/>

| Project | Description | Stack |
|---|---|---|
| [TerraNova-2056](https://github.com/yessine18/TerraNova-2056) | Satellite imagery & CanSat research for environmental monitoring with NDVI analysis | — |

</details>

<details>
<summary><strong>📖 Learning & Profile</strong></summary>
<br/>

| Project | Description |
|---|---|
| [skills-introduction-to-github](https://github.com/yessine18/skills-introduction-to-github) | GitHub learning exercises |
| [yessine18.github.io](https://github.com/yessine18/yessine18.github.io) | GitHub Pages profile website repository |
| [yessine18](https://github.com/yessine18/yessine18) | Profile README & portfolio hub (this repo) |

</details>

<br/>

## 🌟 Featured Projects

### 🧠 Brain-tumor-Multi-Agent
> A production-grade multi-agent AI system for medical imaging analysis.

- **Agent 1** — VGG19-based binary classifier with Grad-CAM explainability
- **Agent 2** — Neo4j knowledge graph integration for medical context
- **Agent 3** — LLM-powered comprehensive report generation (Groq/Llama)

[View repository →](https://github.com/yessine18/Brain-tumor-Multi-Agent)

---

### 📧 Outlook-TFS-automation
> Enterprise automation stack that converts support emails into trackable DevOps workflows.

- Outlook mailbox polling with Microsoft Graph API
- LLM extraction for severity, intent, and routing context
- RAG retrieval from Microsoft documentation using PostgreSQL pgvector
- Azure DevOps issue creation with automated reply/notification flows

[View repository →](https://github.com/yessine18/Outlook-TFS-automation)

---

### 🧾 AI-Receipt-Processing-Automation
> Self-hosted pipeline for intelligent receipt processing.

- Tesseract OCR preprocessing with image enhancement
- LLM parsing using Gemini-compatible patterns
- Local file storage plus PostgreSQL database
- RESTful API and Telegram bot integration

[View repository →](https://github.com/yessine18/AI-Receipt-Processing-Automation)

---

### 🌐 Adaptive Web Stack
> Backend and web engineering projects focused on scalable service architecture.

- Node.js backend workflows for adaptive platform logic
- Spring microservice experiments (gateway + service registry)
- Frontend/backend integration patterns across React, Angular, and Java services

[View Node.js repo →](https://github.com/yessine18/adaptive-backend) · [View Spring repo →](https://github.com/yessine18/Spring)

---

### 🛰️ TerraNova 2056
> Satellite imagery analytics combined with IoT sensor data.

- NDVI and environmental-index computation
- CanSat data integration for smart-city prototypes

[View repository →](https://github.com/yessine18/TerraNova-2056)

<br/>

## 🛠️ Skills & Technologies

| Category | Stack |
|---|---|
| **Agentic AI** | LangGraph · LangChain · RAG · Multi-Agent Orchestration |
| **Microsoft Ecosystem** | Microsoft Graph · Microsoft Entra · Azure DevOps |
| **Databases & Knowledge** | Neo4j · PostgreSQL · pgvector |
| **Automation** | n8n · FastAPI · Workflow Orchestration |
| **ML / Data** | TensorFlow · scikit-learn · Computer Vision |
| **Languages** | Python · TypeScript · JavaScript · C# · Java |
| **Frontend & Backend** | React · Angular · .NET · Node.js · Spring |

<br/>

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=yessine18&show_icons=true&hide_border=true&bg_color=0B1120&title_color=00D9FF&icon_color=39D2C0&text_color=C9D1D9" alt="GitHub Stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yessine18&layout=compact&hide_border=true&bg_color=0B1120&title_color=00D9FF&text_color=C9D1D9" alt="Top Languages" />

<br/><br/>

<img height="170" src="https://streak-stats.demolab.com?user=yessine18&hide_border=true&background=0B1120&ring=00D9FF&fire=FFB454&currStreakLabel=C9D1D9&sideLabels=C9D1D9&dates=6C7589" alt="GitHub Streak" />

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=yessine18&bg_color=0B1120&color=00D9FF&line=39D2C0&point=FFB454&area=true&hide_border=true&custom_title=Contribution%20Graph" alt="Activity Graph" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=yessine18&theme=onedark&no-frame=true&no-bg=true&column=4&margin-w=10&margin-h=10" alt="GitHub Trophies" />

</div>

> [!NOTE]
> The cards above are served by free, community-run instances (`vercel.app` / `demolab.com`). They can occasionally rate-limit or timeout. If that happens, wait a few minutes and refresh.

<br/>

## 🏆 Highlights & Achievements

- 🥇 **TSYP Best Video Award** — 2024
- 🏆 **Best IEEE Technical Chapter**, Tunisia Section — 2024
- 🤖 **Autonomous Robot Competition Winner** — 2024
- 👨‍💼 **Technical Team Lead**, IEEE Tunisian Engineering Congress Week 1.0 — Mar 2023 – Sep 2024
- 📢 **Media & Content Roles** — PYANGO, IEEE ENIS, TSYP, ENIS Forum

<br/>

## 📫 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B1120?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://www.linkedin.com/in/yessine-fakhfakh-470145298/)
[![Email](https://img.shields.io/badge/Email-0B1120?style=for-the-badge&logo=gmail&logoColor=00D9FF)](mailto:yessine.fakhfakh@enis.tn)
[![Portfolio](https://img.shields.io/badge/Portfolio-0B1120?style=for-the-badge&logo=readdotcv&logoColor=00D9FF)](https://yessine18.github.io/yessine-portfolio)

*"Building intelligent systems that solve real business problems."*

![Profile Views](https://komarev.com/ghpvc/?username=yessine18&color=00D9FF&style=flat-square&label=Profile+Views)

</div>
