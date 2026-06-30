<div align="center">

# Yessine Fakhfakh

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=21&duration=3000&pause=1200&color=00D9FF&center=true&vCenter=true&width=820&lines=Agentic+AI+Engineer;Enterprise+AI+%26+Microsoft+Ecosystem;LLMs+%E2%80%A2+RAG+%E2%80%A2+LangGraph+%E2%80%A2+Knowledge+Graphs;Building+Autonomous+Systems+for+Real+Businesses" alt="Typing SVG" />

$ whoami
Software Engineer — Sfax, Tunisia 🇹🇳 — ENIS

$ current_focus
Production-grade agentic platforms across the Microsoft ecosystem

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B1120?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://www.linkedin.com/in/yessine-fakhfakh-470145298/)
[![Email](https://img.shields.io/badge/Email-0B1120?style=for-the-badge&logo=gmail&logoColor=00D9FF)](mailto:yessine.fakhfakh@enis.tn)
[![Portfolio](https://img.shields.io/badge/Portfolio-0B1120?style=for-the-badge&logo=readdotcv&logoColor=00D9FF)](https://yessine18.github.io/yessine-portfolio)
[![Location](https://img.shields.io/badge/Sfax%2C%20Tunisia-0B1120?style=for-the-badge&logo=mapbox&logoColor=39D2C0)](#)

<sub>Last updated · 2026‑06‑30</sub>

</div>

<br/>

## 🏅 Credentials

<div align="center">

[![Microsoft Certified](https://img.shields.io/badge/Microsoft%20Certified-Agentic%20AI%20Business%20Solutions%20Architect%20(AB--100)-0B1120?style=for-the-badge&logo=microsoft&logoColor=00D9FF)](#)
[![Microsoft Applied Skills](https://img.shields.io/badge/Microsoft%20Applied%20Skills-Identities%20%26%20Access%20with%20Microsoft%20Entra-0B1120?style=for-the-badge&logo=microsoftazure&logoColor=39D2C0)](#)

</div>

<br/>

## 👋 About

I build **enterprise-grade, autonomous AI systems** — the kind that sit inside real business workflows, not just demos. My work centers on agentic AI and multi-agent orchestration, enterprise RAG and GraphRAG pipelines, knowledge graphs for grounded and explainable AI, and Microsoft-ecosystem automation across Graph API, Entra, and Azure DevOps. I enjoy turning messy, manual business processes into intelligent, autonomous systems, and I'm currently deepening my focus on production-grade agentic platforms across the Microsoft ecosystem.

| | |
|---|---|
| **Agentic Systems** | Multi-agent AI with RAG, LLM orchestration, and knowledge-graph grounding |
| **Hybrid Workflows** | RAG + n8n + Neo4j pipelines that bridge unstructured and structured data |
| **Microsoft Automation** | Outlook, Graph API, Entra, and Azure DevOps integration end to end |
| **Full-Stack Delivery** | React, Angular, and .NET applications that ship and support the above |

<br/>

## 🏗️ How I Architect Agentic Systems

**Pattern A — Inbox-to-Resolution Agent** *(production implementation)*

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#13192B','primaryTextColor':'#C9D1D9','primaryBorderColor':'#00D9FF','lineColor':'#39D2C0','secondaryColor':'#1B2333','tertiaryColor':'#0B1120','fontFamily':'Fira Code, monospace'}}}%%
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
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#13192B','primaryTextColor':'#C9D1D9','primaryBorderColor':'#00D9FF','lineColor':'#39D2C0','secondaryColor':'#1B2333','tertiaryColor':'#0B1120','fontFamily':'Fira Code, monospace'}}}%%
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
| [Outlook-TFS-automation](https://github.com/yessine18/Outlook-TFS-automation) | .NET + AI pipeline analyzing Outlook support emails, performing RAG-based auto-resolve, and creating Azure DevOps work items | C# · Python |
| [Brain-tumor-Multi-Agent](https://github.com/yessine18/Brain-tumor-Multi-Agent) | Multi-agent medical AI: VGG19 classifier + Neo4j knowledge graph + Grad-CAM visualization | Python |
| [Chatbot-RAG](https://github.com/yessine18/Chatbot-RAG) | RAG chatbot with PostgreSQL vector search for university enrollment Q&A | Jupyter · Python |
| [AI-Receipt-Processing-Automation](https://github.com/yessine18/AI-Receipt-Processing-Automation) | Self-hosted receipt OCR + LLM parsing, DB & bot integration | Python · JavaScript |
| [Motivation-Letter-email-Generator](https://github.com/yessine18/Motivation-Letter-email-Generator) | AI-powered motivation letter generator using Gemini LLM — [live demo](https://motivation-letter-email-generator.streamlit.app/) | Python |
| [ML-Analyse-de-Churn](https://github.com/yessine18/ML-Analyse-de-Churn) | Churn analysis experiments and dashboards | HTML · Python · CSS |

</details>

<details>
<summary><strong>🌐 Full-Stack Web Development</strong></summary>
<br/>

| Project | Description | Stack |
|---|---|---|
| [adaptive-backend](https://github.com/yessine18/adaptive-backend) | Node.js backend service for adaptive web platform workflows | JavaScript |
| [yessine-portfolio](https://github.com/yessine18/yessine-portfolio) | Personal portfolio site — [live](https://yessine18.github.io/yessine-portfolio) | HTML · CSS · JavaScript |
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

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-111827?style=flat-square&logo=langchain&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-000000?style=flat-square&logo=groq&logoColor=white)

- **Agent 1** — VGG19-based binary classifier with Grad-CAM explainability
- **Agent 2** — Neo4j knowledge graph integration for medical context
- **Agent 3** — LLM-powered comprehensive report generation (Groq/Llama)

[View repository →](https://github.com/yessine18/Brain-tumor-Multi-Agent)

---

### 📧 Outlook-TFS-automation
> Enterprise automation stack that converts support emails into trackable DevOps workflows.

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-316192?style=flat-square&logo=postgresql&logoColor=white)

- Outlook mailbox polling with Microsoft Graph API
- LLM extraction for severity, intent, and routing context
- RAG retrieval from Microsoft documentation using PostgreSQL pgvector
- Azure DevOps issue creation with automated reply/notification flows

[View repository →](https://github.com/yessine18/Outlook-TFS-automation)

---

### 🧾 AI-Receipt-Processing-Automation
> Self-hosted pipeline for intelligent receipt processing.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Tesseract](https://img.shields.io/badge/Tesseract_OCR-4285F4?style=flat-square&logo=googletesseract&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Telegram](https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white)

- Tesseract OCR preprocessing with image enhancement
- LLM parsing using Gemini-compatible patterns
- Local file storage plus PostgreSQL database
- RESTful API and Telegram bot integration

[View repository →](https://github.com/yessine18/AI-Receipt-Processing-Automation)

---

### 🌐 Adaptive Web Stack
> Backend and web engineering projects focused on scalable service architecture.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

- Node.js backend workflows for adaptive platform logic
- Spring microservice experiments (gateway + service registry)
- Frontend/backend integration patterns across React, Angular, and Java services

[View Node.js repo →](https://github.com/yessine18/adaptive-backend) · [View Spring repo →](https://github.com/yessine18/Spring)

---

### 🛰️ TerraNova 2056
> Satellite imagery analytics combined with IoT sensor data.

![NDVI](https://img.shields.io/badge/NDVI-2E7D32?style=flat-square) ![CanSat](https://img.shields.io/badge/CanSat-455A64?style=flat-square) ![Environmental Monitoring](https://img.shields.io/badge/Environmental_Monitoring-00838F?style=flat-square)

- NDVI and environmental-index computation
- CanSat data integration for smart-city prototypes

[View repository →](https://github.com/yessine18/TerraNova-2056)

<br/>

## 🛠️ Skills & Technologies

| Category | Stack |
|---|---|
| **Agentic AI** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-111827?style=flat-square&logo=langchain&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-000000?style=flat-square&logo=groq&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logoColor=white) |
| **Microsoft Ecosystem** | ![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Microsoft Entra](https://img.shields.io/badge/Microsoft_Entra-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white) |
| **Databases & Knowledge** | ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **Automation** | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **ML / Data** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logoColor=white) |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) |
| **Frontend & Backend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yessine18&show_icons=true&hide_border=true&bg_color=0B1120&title_color=00D9FF&icon_color=39D2C0&text_color=C9D1D9&border_color=1B2333" alt="GitHub Stats" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yessine18&layout=compact&hide_border=true&bg_color=0B1120&title_color=00D9FF&text_color=C9D1D9&border_color=1B2333" alt="Top Languages" height="170"/>

<br/>

<img src="https://streak-stats.demolab.com/?user=yessine18&hide_border=true&background=0B1120&ring=00D9FF&fire=FFB454&currStreakLabel=C9D1D9&sideLabels=C9D1D9&dates=6C7589&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=1B2333" alt="GitHub Streak" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=yessine18&bg_color=0B1120&color=00D9FF&line=39D2C0&point=FFB454&area=true&area_color=39D2C0&hide_border=true&custom_title=Contribution%20Activity" alt="Contribution Graph" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=yessine18&theme=onedark&no-frame=true&column=4&margin-w=12&margin-h=12" alt="GitHub Trophies" />

</div>

> [!NOTE]
> The cards above are served by free, community-run instances (`vercel.app` / `demolab.com`). They're the current, working domains — the originals pointed at `herokuapp.com` endpoints that went offline after Heroku discontinued free dynos. They're generally reliable but can occasionally rate-limit under heavy traffic; if a card ever goes blank, a refresh usually fixes it. For guaranteed uptime long-term, each project also supports generating a static SVG via a GitHub Actions workflow committed to this repo — worth doing later if you want zero dependency on third-party uptime.

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
