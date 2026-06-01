# Krish Bakriwala — AI Engineer Portfolio

<div align="center">

![Portfolio Preview](https://img.shields.io/badge/Status-Live-32b8c6?style=for-the-badge&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-181717?style=for-the-badge&logo=github)
![Firebase](https://img.shields.io/badge/Analytics-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**M.Sc. Artificial Intelligence · Brandenburg University of Technology · Germany**

[🌐 Live Portfolio](https://krishbakriwala8.github.io/portfolio) · [💼 LinkedIn](https://www.linkedin.com/in/krish-akshay-bakriwala-3885a61b8) · [🐙 GitHub](https://github.com/krishbakriwala8) · [📧 Email](mailto:krishbakriwala8@gmail.com)

</div>

---

## ✨ Features

- **Neural network canvas animation** — interactive, mouse-reactive hero background
- **Bento grid project layout** — 14 AI/ML projects with 3D card tilt effects
- **AI Portfolio Assistant** — powered by LLaMA 3.3 70B via Groq, with conversation history
- **Firebase Analytics** — tracks page visits (with geolocation), project link clicks, and chat messages
- **Private admin dashboard** — real-time analytics viewer with password protection
- **Scroll reveal animations** — smooth entrance effects on all sections
- **Sidebar navigation dots** — section-aware scroll timeline
- **Fully responsive** — mobile, tablet, and desktop
- **Secure deployment** — API keys injected via GitHub Actions secrets, never exposed in source

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Assistant | LLaMA 3.3 70B · Groq API · FastAPI · Python |
| Backend | Render (FastAPI) |
| Analytics | Firebase Firestore |
| Deployment | GitHub Pages + GitHub Actions |
| Security | GitHub Secrets (zero keys in source code) |

---

## 📁 Projects (14)

| # | Project | Category | Tech |
|---|---|---|---|
| 1 | [Multi-Agent Travel Intelligence System](https://github.com/krishbakriwala8/travel-intelligence) | Agentic AI | Google ADK · LLaMA 3.3 70B · Groq |
| 2 | [Industrial Defect Detection (VLM)](https://github.com/krishbakriwala8/Industrial-Defect-Detection) | Computer Vision | CLIP · Grad-CAM · PyTorch |
| 3 | [Battery Test Failure Assistant](https://github.com/krishbakriwala8/battery-test-assistant) | RAG · LLM | LangChain · ChromaDB · Groq |
| 4 | [Real-time Sentiment Analysis Microservice](https://github.com/krishbakriwala8/Real-time-Sentiment-Analysis-Microservice) | NLP · MLOps | BERT · FastAPI · Docker |
| 5 | [Smart Document Q&A with RAG](https://github.com/krishbakriwala8/Smart-Document-Q-A-with-RAG) | RAG | LangChain · FAISS |
| 6 | [Schema-Based ETL Pipeline](https://github.com/krishbakriwala8/schema-based-etl-pipeline) | Data Engineering | Python · CSV · JSON |
| 7 | [Scenario Generation & Anomaly Detection](https://github.com/krishbakriwala8/Scenario-Generation-Anomaly-Detection) | Machine Learning | Python · Scikit-learn |
| 8 | [Fine-Tuned Niche Content Generator](https://github.com/krishbakriwala8/Fine-Tuned-Niche-Content-Generator) | Generative AI | Transformers · Hugging Face |
| 9 | [Email Summarizer Tool](https://github.com/krishbakriwala8/Email-Summarizer-Tool) | Generative AI | GPT-4 · Gmail API |
| 10 | [Air Quality Index Predictor](https://github.com/krishbakriwala8/Air-Quality-Index-Predictor-) | Machine Learning | Scikit-learn · Pandas |
| 11 | [Movie Recommendation System](https://github.com/krishbakriwala8/Movie-Recommeded-System-project) | ML · NLP | Cosine Similarity · Python |
| 12 | [Car Price Predictor](https://github.com/krishbakriwala8/Car-Price-Predictor-Project) | Machine Learning | Scikit-learn · Regression |
| 13 | [Fitness Mobile Application](https://github.com/krishbakriwala8/fitness-mobile-app) | Mobile Dev | Android · Java |
| 14 | [Online Car Rental System](https://github.com/krishbakriwala8/Online-Car-Rental-system-project) | Web Dev | HTML · CSS · JavaScript |

---

## 🔒 Secure Deployment

This repo contains **zero API keys**. All secrets are stored in GitHub repository secrets and injected at build time via GitHub Actions:

```
Source code (placeholders)  →  GitHub Actions  →  Live site (real keys)
     PASTE_YOUR_API_KEY      →   injects secret  →   AIzaSy...
```

Secrets used:
- `FB_API_KEY` — Firebase API key
- `FB_PROJECT_ID` — Firebase project ID
- `FB_SENDER_ID` — Firebase messaging sender ID
- `FB_APP_ID` — Firebase app ID
- `ADMIN_PASSWORD` — Analytics dashboard password

---

## 📊 Analytics

Firebase Firestore tracks three events automatically:

- **Page visits** — timestamp, country, city, device, referrer
- **Project clicks** — which GitHub project links are clicked
- **Chat messages** — questions asked to the AI assistant

View stats at `/admin.html` (password protected).

---

## 🚀 Local Development

```bash
# Clone the repo
git clone https://github.com/krishbakriwala8/portfolio.git
cd portfolio

# Create a local config file (gitignored)
cp config.example.js config.js
# Fill in your Firebase config in config.js

# Open in browser
open index.html
```

---

## 📬 Contact

**Krish Akshay Bakriwala**
Open to AI/ML internships and full-time roles across Europe.

📧 krishbakriwala8@gmail.com
🔗 [linkedin.com/in/krish-akshay-bakriwala-3885a61b8](https://www.linkedin.com/in/krish-akshay-bakriwala-3885a61b8)

---

<div align="center">
  <sub>Built with ❤️ and a lot of Python · Deployed on GitHub Pages</sub>
</div>
