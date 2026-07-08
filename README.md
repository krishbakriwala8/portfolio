# Krish Bakriwala — ML & AI Engineering Portfolio

<div align="center">

![Portfolio](https://img.shields.io/badge/Status-Live-32b8c6?style=for-the-badge&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-181717?style=for-the-badge&logo=github)
![Firebase](https://img.shields.io/badge/Analytics-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Projects](https://img.shields.io/badge/Projects-10-a855f7?style=for-the-badge)
![Available](https://img.shields.io/badge/Available-August_2026-4ade80?style=for-the-badge)

**M.Sc. Artificial Intelligence · Brandenburg University of Technology · Germany**
**Available from August 2026 — Seeking ML / Data Science / AI Engineering Roles in Europe**

[🌐 Live Portfolio](https://krishbakriwala8.github.io/portfolio) · [🤖 Live AI Agent Demo](https://krishbakriwala8.github.io/portfolio/agent.html) · [💼 LinkedIn](https://www.linkedin.com/in/krish-akshay-bakriwala-3885a61b8) · [🐙 GitHub](https://github.com/krishbakriwala8) · [📧 Email](mailto:krishbakriwala8@gmail.com)

</div>

---

## About

M.Sc. AI student at Brandenburg University of Technology (BTU Cottbus, Germany) with a background in Computer Engineering. This portfolio covers work across both data science and applied AI engineering — real projects with honest evaluation, not just demo notebooks.

On the **data science side**: experiment design, EDA on messy real-world datasets, statistical validation, predictive modelling with ensemble methods, feature engineering, and analytical dashboards.

On the **AI engineering side**: RAG pipelines, LLM-powered tools, backend services with FastAPI and Docker, and LLM evaluation frameworks using Ragas and Langfuse.

---

## Portfolio Features

- **Neural network canvas** — interactive hero animation
- **Live AI Research Agent** — production ReAct agent with 4 tools and session memory ([demo](https://krishbakriwala8.github.io/portfolio/agent.html))
- **AI Portfolio Assistant** — LLaMA 3.3 70B via Groq with full conversation history
- **10 focused projects** — only production-quality, genuine work shown
- **Project metrics** — measurable outcomes on every project card
- **GitHub contribution heatmap** — live activity graph
- **Firebase Analytics** — real-time visit tracking, project click logs, chat message logs
- **Private admin dashboard** — password-protected analytics viewer
- **Secure deployment** — API keys injected via GitHub Actions secrets, never in source

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5 · CSS3 · Vanilla JavaScript |
| AI Agent | LLaMA 3.3 70B · Groq API · ReAct · Tool Calling · Session Memory |
| AI Assistant | LLaMA 3.3 70B · Groq API · FastAPI (Render) |
| Analytics | Firebase Firestore |
| Deployment | GitHub Pages + GitHub Actions |
| Security | GitHub Secrets — zero API keys in source code |

---

## Projects (10)

| # | Project | Area | Key Tech | Metric |
|---|---|---|---|---|
| 1 | [AQI Predictor — Time-Series Forecasting](https://github.com/krishbakriwala8/AQI-Predictor) | ML · Data Science | XGBoost · LightGBM · MLflow · Streamlit | R² 0.458 vs 0.16 baseline |
| 2 | [Predictive Customer Retention Pipeline](https://github.com/krishbakriwala8/customer-retention-pipeline) | Data Science · Analytics | XGBoost · Scikit-learn · SQL · Power BI | 5-fold CV · SMOTE |
| 3 | [GenAI Evaluation & System Monitoring](https://github.com/krishbakriwala8/genai-evaluation-framework) | AI Evaluation · MLOps | Ragas · Langfuse · PostgreSQL | 100+ edge-case prompts |
| 4 | [Real-time Sentiment Analysis Microservice](https://github.com/krishbakriwala8/Real-time-Sentiment-Analysis-Microservice) | NLP · Backend | BERT · FastAPI · Docker | 90% accuracy · <200ms |
| 5 | [Industrial Defect Detection (CLIP + VLM)](https://github.com/krishbakriwala8/Industrial-Defect-Detection) | Computer Vision | CLIP · Grad-CAM · PyTorch | Zero-shot, no labels |
| 6 | [Battery Test Failure Assistant](https://github.com/krishbakriwala8/battery-test-assistant) | RAG · LLM | LangChain · ChromaDB · Groq | 60% effort reduction |
| 7 | [Web Scraping Data Pipeline](https://github.com/krishbakriwala8/web-scraping-data-pipeline) | Data Engineering | BeautifulSoup · Scrapy · PostgreSQL | 10+ automated sources |
| 8 | [Document Workflow Automation](https://github.com/krishbakriwala8/document-workflow-automation) | Automation | Power Automate · N8N · SharePoint | 55% time reduction |
| 9 | [Distributed Capacity Optimization](https://github.com/krishbakriwala8/distributed-production-planner) | ML · Operations Research | Mesa · SimPy · OR-Tools | M.Sc. research project |
| 10 | [Multi-Tool AI Research Agent](https://github.com/krishbakriwala8/multi-tool-ai-agent) ⭐ | AI Engineering | Groq · ReAct · Tool Calling · FastAPI | Live demo available |

⭐ = Has a live interactive demo

---

## Live AI Research Agent

Available at [`/agent.html`](https://krishbakriwala8.github.io/portfolio/agent.html) — a production-grade multi-tool agent.

**Architecture:** ReAct (Reason → Act → Observe → Synthesize) loop, up to 6 iterations per task

**Tools:**
- `web_search` — DuckDuckGo real-time search
- `calculate` — safe mathematical expression evaluator
- `summarize_text` — LLM-powered condensation
- `analyze_text` — sentiment, themes, entity extraction

**Features:** Session memory · full reasoning transparency · structured prompt harness · FastAPI backend on Render

---

## Secure Deployment

Zero API keys in source. GitHub Actions injects secrets at build time:

```
Repo (PASTE_YOUR_API_KEY)  →  GitHub Actions  →  Live site (real key)
```

**Secrets required:**

| Secret | Purpose |
|---|---|
| `FB_API_KEY` | Firebase API key |
| `FB_PROJECT_ID` | Firebase project ID |
| `FB_SENDER_ID` | Firebase messaging sender ID |
| `FB_APP_ID` | Firebase app ID |
| `ADMIN_PASSWORD` | Analytics dashboard password |

---

## Analytics

Firebase Firestore tracks three collections:

| Collection | Data captured |
|---|---|
| `visits` | Timestamp · country · city · device type · referrer |
| `project_clicks` | Which GitHub links are clicked and when |
| `chat_messages` | Questions asked to the AI assistant |

Admin dashboard at `/admin.html` — password protected, includes Test Write diagnostics.

---

## Deployment

```bash
# Push to GitHub — Actions runs automatically
git add .
git commit -m "update"
git push origin main
# deploy.yml injects secrets → deploys to gh-pages branch

# Backend (Render) — two endpoints
# POST /chat       → portfolio AI assistant
# POST /agent/run  → multi-tool research agent
```

---

## Contact

**Krish Akshay Bakriwala**
M.Sc. Artificial Intelligence · BTU Cottbus-Senftenberg · Germany
Open to internships, Werkstudent roles, and full-time positions in ML, Data Science, and AI Engineering across Europe.

📧 krishbakriwala8@gmail.com · 📱 +49 15566067876
🔗 [LinkedIn](https://www.linkedin.com/in/krish-akshay-bakriwala-3885a61b8) · 🌐 [Portfolio](https://krishbakriwala8.github.io/portfolio)

---

<div align="center">
  <sub>Built with Python, patience, and honest evaluation metrics · Available August 2026</sub>
</div>
