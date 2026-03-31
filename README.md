<div align="center">

<svg width="800" height="150" viewBox="0 0 800 150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="g" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#a78bfa"/>
      <stop offset="100%" stop-color="#38bdf8"/>
    </linearGradient>
  </defs>

  <rect width="800" height="150" fill="#0d1117"/>

  <!-- Name fades in -->
  <text x="400" y="78" text-anchor="middle"
        font-family="'Segoe UI', Arial, sans-serif"
        font-size="50" font-weight="700" fill="#e6edf3" opacity="0">
    Astik Kumar
    <animate attributeName="opacity" from="0" to="1" dur="1s" begin="0.2s" fill="freeze"/>
  </text>

  <!-- Subtitle fades in -->
  <text x="400" y="108" text-anchor="middle"
        font-family="'Segoe UI', Arial, sans-serif"
        font-size="13" fill="#8b949e" letter-spacing="4" opacity="0">
    FULL-STACK DEV  ·  ML ENTHUSIAST  ·  OPEN SOURCE
    <animate attributeName="opacity" from="0" to="0.85" dur="1s" begin="0.9s" fill="freeze"/>
  </text>

  <!-- Underline draws outward from center -->
  <line x1="400" y1="120" x2="400" y2="120" stroke="url(#g)" stroke-width="1.5" stroke-linecap="round">
    <animate attributeName="x1" from="400" to="295" dur="0.7s" begin="1.6s" fill="freeze"/>
    <animate attributeName="x2" from="400" to="505" dur="0.7s" begin="1.6s" fill="freeze"/>
  </line>
</svg>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/astik-kumar-a94aa628a/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Astik1/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aastikrajput1@gmail.com)

</div>

---

## 👨🏻‍💻 About Me

Hey there! I'm a Computer Science student from India who enjoys tackling complex problems through Data Structures & Algorithms and building projects in backend development and data analytics.

Currently deepening my expertise in **system design**, **scalable backend architectures**, and **data-driven applications** — the kind of work where performance decisions actually matter at scale.

I've shipped projects across the full stack — from LLM proxy middleware and ML diagnosis dashboards to real-time fintech UIs — always with a bias toward clean APIs, measurable outcomes, and code that doesn't break in prod.

When I'm not coding, I'm exploring new technologies, grinding competitive programming, or connecting with the developer community. I believe the best engineers are the ones who never stop being curious.

---

## 🚀 Flagship Project

<table>
<tr>
<td width="100%">

### [⚡ ContextForge](https://github.com/Astik01/contextforge)
**OpenAI-compatible LLM proxy middleware — cut API costs by up to 60% with zero code changes.**

Point your app at `localhost:8000` instead of `api.openai.com`. Same SDK, same API, same code. Behind the scenes:

```
Your App → ContextForge Gateway
              ├─ Context Compression   (summarize long conversations → fewer tokens)
              ├─ Semantic Cache         (FAISS + Redis, ≥92% cosine similarity → <30ms hits)
              ├─ Smart Model Router     (simple → gpt-3.5 | complex → gpt-4o)
              ├─ Telemetry              (SQLite, p95 latency, cache hit rate, cost tracking)
              └─ Response ← upstream API
```

84+ tests passing · fully containerized · real-time analytics dashboard · MIT licensed

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

</td>
</tr>
</table>

---

## 📂 More Projects

| Project | What it does | Stack |
|:--------|:-------------|:------|
| **[📈 munafa.io](https://github.com/Astik01)** | NSE stock market analytics dashboard with live index feeds, sparkline charts, and a Groww-inspired glassmorphism UI. | `React` `Vite` `Recharts` |
| **[🧠 MediScan AI](https://github.com/Astik01)** | Cancer diagnosis classification — XGBoost + SHAP explainability served over FastAPI with a React dashboard. | `Python` `FastAPI` `TensorFlow` |
| **[Neuracare](https://github.com/Astik01)** | AI-powered telemedicine frontend with symptom checker chatbot, booking flow, and health library. | `HTML` `CSS` `Vanilla JS` |
| **[Portfolio](https://github.com/Astik01)** | Single-file self-contained portfolio. Bold typography, animated skill bars, orange accent. | `HTML` `CSS` `Syne` |

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

**Infra & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)

</div>

---

## 📊 GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=Astik01&hide_border=true&background=00000000&ring=a78bfa&fire=a78bfa&currStreakLabel=a78bfa&sideLabels=c9d1d9&dates=8b949e&currStreakNum=f0f0f0&sideNums=f0f0f0" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=Astik01&hide_border=true&background=00000000&ring=7c3aed&fire=7c3aed&currStreakLabel=7c3aed&sideLabels=1f2328&dates=57606a&currStreakNum=1f2328&sideNums=1f2328" />
  <img src="https://streak-stats.demolab.com/?user=Astik01&hide_border=true" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Astik01&theme=react-dark&hide_border=true&area=true&bg_color=00000000&color=a78bfa&line=a78bfa&point=f0f0f0" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Astik01&theme=minimal&hide_border=true&area=true&bg_color=00000000&color=7c3aed&line=7c3aed&point=1f2328" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Astik01&hide_border=true&area=true" width="95%" />
</picture>

</div>

---

## 🏆 Competitive Programming

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Astik1/)
[![GeeksforGeeks](https://img.shields.io/badge/GFG-2f8d46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/aastikrqqu2)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/Astik01)

</div>

---

## 🤝 Let's Connect

<div align="center">

I'm always open to interesting conversations, collaboration opportunities, or just a good tech discussion. Feel free to reach out!

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/astik-kumar-a94aa628a/)
[![Email](https://img.shields.io/badge/Gmail-Drop%20a%20Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aastikrajput1@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-Let's%20Grind-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Astik1/)

<br/>

*"First, solve the problem. Then, write the code."*

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Astik01&color=a78bfa&style=flat-square&label=Profile+Views)

</div>
