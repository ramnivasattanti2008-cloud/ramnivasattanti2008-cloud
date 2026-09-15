<!--
  ramnivasattanti2008-cloud profile README
  MERGED: your existing profile, with the animated banner added and the stats
  cards moved off the public instance onto your own.

  Changed vs. what is live on your profile right now:
    1. banner block added at the top. Needs FOUR files in the repo root:
       dark.svg, light.svg, dark-mobile.svg, light-mobile.svg. The wide pair is the
       1180x610 terminal; the mobile pair is a taller cut that stays readable on a
       phone, picked up by the max-width:600px sources. First matching source wins,
       so the order below matters.
    2. stats + top-langs still use the shared public instance, so this file works
       immediately on push. Self-hosting is an upgrade, not a prerequisite - swap the
       2 domains once your own instance is deployed.
    3. hide_rank=true and include_all_commits=true added to the stats card
    4. cards re-themed from `radical` (indigo/amber) to the banner palette
       #A78BFA / #22D3EE / #10B981 on #0A101F, so the page reads as one thing
    5. contribution snake block added, hidden behind SNAKE:BEGIN/END markers until the
       Action runs green
    6. the Let's Connect badges re-themed to the palette too, and LinkedIn moved from
       0077B5 to 0A66C2 - shields.io only renders the LinkedIn glyph on that exact
       brand blue, so on 0077B5 your badge was showing as text with no logo. The
       self-referencing GitHub badge is dropped (it is circular on your own profile);
       Live Demo and AI Portfolio carry the outbound links instead.
  Everything else is your original content, untouched.
-->

<div align="center">
<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramnivasattanti2008-cloud/ramnivasattanti2008-cloud/main/dark-mobile.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/ramnivasattanti2008-cloud/ramnivasattanti2008-cloud/main/light-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramnivasattanti2008-cloud/ramnivasattanti2008-cloud/main/dark.svg">
  <img alt="Attanti Ramnivas — AI/ML Developer" src="https://raw.githubusercontent.com/ramnivasattanti2008-cloud/ramnivasattanti2008-cloud/main/light.svg">
</picture>
</div>

# 👋 Hey, I'm Attanti Ramnivas

<!-- Dynamic status -->
<p align="left">
  <img src="https://img.shields.io/badge/Role-AI%2FML%20Developer-6366F1?style=for-the-badge&logo=robot&logoColor=white" />
  <img src="https://img.shields.io/badge/Student-B.Tech%20CSBS-10B981?style=for-the-badge&logo=graduation-cap&logoColor=white" />
  <img src="https://img.shields.io/badge/GPA-9.3%2F10-F59E0B?style=for-the-badge&logo=star&logoColor=white" />
  <img src="https://img.shields.io/badge/University-Jain%20University-3B82F6?style=for-the-badge&logo=school&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-Bengaluru-EF4444?style=for-the-badge&logo=location&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-22C55E?style=for-the-badge&logo=hand&logoColor=white" />
</p>

---

## 🎯 About Me

```text
╔══════════════════════════════════════════════════════════════════════╗
║  🤖  AI-FIRST DEVELOPER — Building systems that matter              ║
║                                                                      ║
║  🧠  Specialization: LLMs, RAG, Generative AI, NLP                 ║
║  💻  Languages: Python, TypeScript, SQL                             ║
║  🌐  Full-Stack: Next.js, Express.js, Streamlit                    ║
║  🛰️  Domain: Satellite Imagery, Geospatial AI, Risk Systems         ║
║  🏆  Achievement: Smart India Hackathon 2026 Finalist               ║
║  🌐  Live: vojas-frontend.vercel.app (60K+ projects tracked)        ║
╚══════════════════════════════════════════════════════════════════════╝
```

---

## 🏆 Featured Work

### 🛰️ [VOJAS — AI Accountability Platform (SIH 2026)](https://github.com/ramnivasattanti2008-cloud/VOJAS)

> AI-powered accountability platform for India's MPLAD government scheme

| Layer | Technology |
|-------|------------|
| AI Analysis | Satellite imagery (CDSE Sentinel-2), 7-signal risk engine |
| Geospatial | MapLibre GL JS, PostGIS, change detection |
| Backend | Express.js, Prisma ORM, PostgreSQL |
| Frontend | Next.js 15, React, Role-based dashboards |
| Infrastructure | Vercel (FE) + Render (BE) |
| Scale | 60,000+ government projects geocoded |

- 🏆 **Smart India Hackathon 2026 Finalist**
- 🌐 **Live:** [vojas-frontend.vercel.app](https://vojas-frontend.vercel.app)
- 📊 **60K+** projects | 🔗 **101+** commits | 📦 **Full monorepo**

```python
# Core AI: Satellite Change Detection
satellite_data → band_comparison → change_score → confidence_factors
reported_progress → comparison → anomaly_detection → risk_engine → escalation
```

---

### 🧠 [smriti-ai — RAG Memory Assistant](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/01-ai-rag-chatbot)

> Retrieval-Augmented Generation chatbot powered by Google Gemini LLM

```python
# RAG Architecture
documents → chunk → embed(Gemini) → ChromaDB
query → embed → similarity_search → top_k_chunks → LLM → grounded_answer + citations
```

**Tech:** Python, LangChain, ChromaDB, Gemini API, Streamlit

---

## 📦 All AI Projects (12 Production Apps)

| # | Project | Category | Tech | Live |
|----|---------|---------|------|------|
| 🧠 1 | [smriti-ai](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/01-ai-rag-chatbot) | RAG / LLM | Gemini, ChromaDB, LangChain | ✅ |
| 💬 2 | [Sentiment Analyzer](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/02-sentiment-analyzer) | NLP | TextBlob, NLTK, Plotly | ✅ |
| 📺 3 | [YouTube Analyzer](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/03-youtube-comment-analyzer) | API + AI | YouTube API, TextBlob | ✅ |
| 📧 4 | [AI Email Drafter](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/04-ai-email-drafter) | LLM / Productivity | Gemini, Streamlit | ✅ |
| 📝 5 | [Text Summarizer](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/05-text-summarizer) | LLM / NLP | Gemini, NLTK | ✅ |
| 🌤️ 6 | [Weather Insights](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/06-weather-insights-bot) | API + AI | OpenWeather, Gemini | ✅ |
| 🤖 7 | [Code Reviewer](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/07-ai-code-reviewer) | AI / DevTools | Gemini, Streamlit | ✅ |
| 📅 8 | [Post Scheduler](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/08-linkedin-post-scheduler) | AI / Content | Gemini, Streamlit | ✅ |
| 📚 9 | [Study Assistant](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/09-ai-study-assistant) | AI / Education | Gemini, Streamlit | ✅ |
| 💼 10 | [Job Analyzer](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/10-ai-job-analyzer) | AI / Career | Gemini, Streamlit | ✅ |
| 🍅 11 | [Todo + Pomodoro](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/11-todo-pomodoro) | Productivity | Streamlit | ✅ |
| 🖼️ 12 | [Thumbnail Generator](https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects/tree/main/12-youtube-thumbnail) | AI / Content | Gemini, Streamlit | ✅ |

---

## 🛠️ Tech Stack

### 🤖 AI / ML
<p align="left">
  <img src="https://img.shields.io/badge/LLMs-Gemini%202.0%20Flash-4285F4?style=flat&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Gen-9333EA?style=flat" />
  <img src="https://img.shields.io/badge/Generative%20AI-LangChain-00CED1?style=flat" />
  <img src="https://img.shields.io/badge/NLP-TextBlob%20|%20NLTK-F97316?style=flat" />
  <img src="https://img.shields.io/badge/Embeddings-Gemini%20Embedding-10B981?style=flat" />
  <img src="https://img.shields.io/badge/Vector%20DB-ChromaDB-5B21B6?style=flat" />
  <img src="https://img.shields.io/badge/Satellite-CDSE%20Sentinel--2-064F4C?style=flat&logo=satellite&logoColor=white" />
  <img src="https://img.shields.io/badge/Change%20Detection-Geospatial%20AI-1D4ED8?style=flat" />
</p>

### 💻 Languages
<p align="left">
  <img src="https://img.shields.io/badge/Python-3.10-306998?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-Shell-4EAA25?style=flat&logo=gnu-bash&logoColor=white" />
</p>

### 🌐 Frameworks & Libraries
<p align="left">
  <img src="https://img.shields.io/badge/Next.js-15-000000?style=flat&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-4-DC143C?style=flat&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-1.35-FF4B4B?style=flat&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-ORM-2D3748?style=flat&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/TailwindCSS-3.x-06B6D4?style=flat&logo=tailwindcss&logoColor=white" />
</p>

### 🗄️ Databases & Data
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-16-336791?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostGIS-Geospatial-0078D4?style=flat" />
  <img src="https://img.shields.io/badge/ChromaDB-Vector-5B21B6?style=flat" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-Visualization-3F4F75?style=flat&logo=plotly&logoColor=white" />
</p>

### 🚀 Infrastructure & DevOps
<p align="left">
  <img src="https://img.shields.io/badge/Git-GitHub-181717?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-Container-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-Frontend-000000?style=flat&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Render-Backend-46E3B7?style=flat&logo=render&logoColor=white" />
  <img src="https://img.shields.io/badge/npm-Package%20Manager-CB3837?style=flat&logo=npm&logoColor=white" />
  <img src="https://img.shields.io/badge/pnpm-Workspace-FFD700?style=flat&logo=pnpm&logoColor=white" />
</p>

---

## 📊 GitHub Stats

<!-- These two point at the SHARED PUBLIC instance, same as your profile does today, so this
     README works the moment you push it. Once you self-host (SETUP-CHECKLIST.md step 1),
     swap both 'github-readme-stats.vercel.app' for your own domain to stop the
     intermittent "API rate limit exceeded". Everything else about them is already correct. -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ramnivasattanti2008-cloud&show_icons=true&count_private=true&include_all_commits=true&hide_rank=true&hide_border=true&title_color=22D3EE&icon_color=A78BFA&text_color=94A3B8&bg_color=0A101F" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramnivasattanti2008-cloud&layout=compact&langs_count=8&hide_border=true&card_width=320&title_color=22D3EE&text_color=94A3B8&bg_color=0A101F" width="48%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ramnivasattanti2008-cloud&hide_border=true&background=0A101F&stroke=22D3EE&ring=A78BFA&fire=10B981&currStreakLabel=22D3EE&sideLabels=94A3B8&currStreakNum=F8FAFC&sideNums=F8FAFC&dates=64748B&titleColor=22D3EE" width="48%" />
  <img src="https://github-profile-trophy.vercel.app/?username=ramnivasattanti2008-cloud&theme=onedark&no-frame=true&column=3&margin-w=15&margin-h=15&title=Commits,PRs,Issues,Stars,Repositories,Followers" width="48%" />
</p>

<!-- Activity Graph -->
![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=ramnivasattanti2008-cloud&bg_color=0A101F&color=22D3EE&line=A78BFA&point=10B981&area=true&hide_border=true)

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramnivasattanti2008-cloud/ramnivasattanti2008-cloud/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ramnivasattanti2008-cloud/ramnivasattanti2008-cloud/output/github-snake.svg" />
  <img alt="Snake eating my contributions" src="https://raw.githubusercontent.com/ramnivasattanti2008-cloud/ramnivasattanti2008-cloud/output/github-snake.svg" />
</picture>
</div>

---

## 🎓 Education

```
╔══════════════════════════════════════════════════════════╗
║  🎓 Jain (Deemed-to-be University), Bengaluru           ║
║  ├── B.Tech — Computer Science & Business Systems (CSBS) ║
║  ├── Semester: 3rd | Graduation: 2029                   ║
║  ├── CGPA: 9.3 / 10 ⭐                                 ║
║  ├── 12th: 96.5% | 10th: 96%                         ║
║  └── School: Narayana E-Techno School & College         ║
╚══════════════════════════════════════════════════════════╝
```

---

## 🏆 Achievements

| Achievement | Details |
|------------|---------|
| 🏆 SIH 2026 Finalist | Smart India Hackathon with VOJAS platform |
| 📊 60K+ Projects | Government accountability at scale |
| 🌐 Production Deployment | vojas-frontend.vercel.app with real users |
| 📦 12 AI Projects | All production-ready, documented, deployed |
| 💻 101+ Commits | Across VOJAS monorepo |
| 🎯 9.3 CGPA | Maintained academic excellence |

---

## 📫 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/attanti-ramnivas">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:ramnivasattanti2008@gmail.com">
    <img src="https://img.shields.io/badge/Email-0A101F?style=for-the-badge&logo=gmail&logoColor=10B981&labelColor=0A101F" alt="Email" />
  </a>
  &nbsp;&nbsp;
  <a href="https://vojas-frontend.vercel.app">
    <img src="https://img.shields.io/badge/Live%20Demo-0A101F?style=for-the-badge&logo=vercel&logoColor=22D3EE&labelColor=0A101F" alt="Live Demo" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/ramnivasattanti2008-cloud/ai-portfolio-projects">
    <img src="https://img.shields.io/badge/AI%20Portfolio-0A101F?style=for-the-badge&logo=github&logoColor=A78BFA&labelColor=0A101F" alt="AI Portfolio" />
  </a>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ramnivasattanti2008-cloud&style=flat-square&color=6366F1" />
  <img src="https://img.shields.io/github/followers/ramnivasattanti2008-cloud?style=flat-square&color=6366F1" />
</p>

---

<p align="center">
  <i>Building AI systems that solve real problems. 🚀</i>
</p>
