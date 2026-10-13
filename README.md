<h1 align="center">Hi 👋, I'm Ruben Kagbanon</h1>
<h3 align="center">Data Science student · Backend & AI engineer in the making · Based in Abidjan, Côte d'Ivoire 🇨🇮</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/ruben-kagbanon"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:rubenkagbanon@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=rubenkagbanon&style=for-the-badge&color=0e75b6" alt="Profile views"/>
</p>

---

## 🧑‍💻 About me

- 🎓 4th-year **Data Science** student at **African School of Economics** (Abidjan)
- 🌍 Developer of **[EconGlobe](https://www.econglobe.com)**, a bilingual platform that gives visibility to research and ideas
- 🤖 Currently building **Lia**, a voice AI callbot for a mobile-money company (LiveKit · RAG · LLMs · Asterisk)
- 📦 Deploying and securing a **Sonatype Nexus Repository** artifact manager (Docker · Nginx · LDAP · HTTPS)
- 🐍 Love working on **Python backends**, **AI agents** and **data-driven apps**
- 🌍 Languages: French (native) · English (intermediate)
- 💬 Ask me about: Django, voice AI, RAG, Docker, data analysis

---

## 🚀 Featured projects

### 🗓️ Planex — School Timetable Generator

<p align="center">
  <a href="https://planexci.netlify.app/"><img src="assets/planex-logo.png" alt="Planex" width="320"/></a>
</p>

<p align="center">
  <a href="https://planexci.netlify.app/"><img src="https://img.shields.io/badge/Live%20demo-planexci.netlify.app-1F3A2E?style=for-the-badge&logo=netlify&logoColor=white" alt="Live demo"/></a>
</p>

What takes school administrators weeks by hand, Planex does in seconds: it builds the timetable of an entire middle or high school with **zero conflicts**, following the official Ivorian ministry (MENA) curriculum hours and the school's own teaching rules — and explains every choice in a report.

- ⚙️ **Generate:** official MENA hour grid built in, configurable teaching rules (no back-to-back sciences, one session per subject per day, PE early morning or late afternoon…), shared lectures, LV2 groups, specialised rooms
- ✅ **Control:** guaranteed zero teacher/class/room conflicts, generation report, overview of all classes, teacher workloads
- ✏️ **Adjust:** checked drag-and-drop, locked sessions, teacher unavailability, versions & restore
- 📤 **Share:** printing in the official format, Excel export, team access via invite code, learns a school's habits from its existing PDF timetables

**Tested on real data** — a middle/high school in Bingerville (37 classes, 55 teachers):

| | Hand-made timetable | Planex |
|---|:---:|:---:|
| Hours placed | — | **929 / 929** |
| Teacher / class / room conflicts | 75 | **0** |
| Back-to-back languages or sciences | 77 | **0** |
| Time to generate the whole school | weeks | **~5 s** |

- `Constraint solving` `Optimization` `Tailwind CSS` `Netlify`

### 🌍 EconGlobe — Bilingual Research & Ideas Platform

<p align="center">
  <a href="https://www.econglobe.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/econglobe-logo-dark.png"/>
      <img src="assets/econglobe-logo-light.png" alt="EconGlobe" width="160"/>
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://www.econglobe.com"><img src="https://img.shields.io/badge/Live-econglobe.com-8B0000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live site"/></a>
</p>

*Research, Ideas and Global Perspectives.* Each year, thousands of dissertations, studies and reports by students, researchers and institutions go unread. EconGlobe is an editorial platform that gives them visibility, with articles in 12 categories (economics, finance, politics, law, health, ecology, AI, data science…).

I'm the **developer** of the platform (founded by Sosthene Jichi). I built it end to end:

- 📖 **Readers:** free articles, search by article or author, category filters, public author profiles, sharing, FR / EN, automatic light / dark mode, fully responsive
- ✍️ **Authors:** sign-up by email or Google, propose a topic to the editors, unlock the editor with an access code sent by email, rich **block editor** (headings, quotes, info boxes, images, sources, credits), drafts, preview, word count and reading time
- 📊 **Author dashboard:** articles, reads, words written, reads per article (a read only counts after a real read, not a click)
- 🛡️ **Editorial back office:** review and publish or reject pending articles, approve proposals and send access codes automatically, manage users
- 🎨 **Design:** premium editorial look with an animated particle-globe built on HTML Canvas

- `JavaScript` `HTML Canvas` `Authentication` `Transactional emails` `i18n`

### 🎙️ Lia — AI Voice Callbot
Real-time phone assistant answering customer calls for a mobile-money service.
- **Telephony:** FreePBX / Asterisk ↔ LiveKit SIP
- **Voice pipeline:** Deepgram (speech-to-text) → DeepSeek (LLM) → ElevenLabs (text-to-speech)
- **Knowledge:** RAG over a customer FAQ with ChromaDB
- **Next step:** agentic "computer use" — caller identity verification and browser automation of back-office tools
- `Python` `livekit-agents` `Redis` `Docker` `ChromaDB`

### 📦 Nexus Repository — Enterprise Artifact Manager
Design and deployment of a central artifact repository for development teams.
- Docker Compose deployment with persistent volumes
- Repositories for npm, Maven, Gradle, PyPI, NuGet and Docker images
- Nginx reverse proxy shared with GitLab, HTTPS/TLS, LDAP / Active Directory auth
- Backup & restore strategy, high-availability study, full technical documentation
- `Docker` `Nginx` `Linux` `LDAP` `DevOps`

### 🧾 OHADA Accounting Module
Backend for an accounting module following the OHADA standard (West/Central African accounting framework), built during my internship at African School of Economics.
- `Django` `Python` `REST API` `PostgreSQL`

### 📊 HR Analytics App
Project lead & research assistant (African School of Economics / Yodan Consulting) on an HR analytics application turning workforce data into dashboards and insights.
- `Python` `Data analysis` `Data visualization`

---

## 🛠️ Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend & AI**
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-1F1F1F?style=flat-square&logo=webrtc&logoColor=white)
![LangChain / RAG](https://img.shields.io/badge/RAG-ChromaDB-FF6F00?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**DevOps & Infra**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Asterisk](https://img.shields.io/badge/Asterisk-F68F1E?style=flat-square&logo=asterisk&logoColor=white)

---

## 📈 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=rubenkagbanon&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rubenkagbanon&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rubenkagbanon&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

---

<p align="center"><i>"Turning data into decisions and ideas into working systems."</i></p>
