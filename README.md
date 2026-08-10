<div align="center">

# Faizan Khan

**Backend & Full-Stack Engineer**

Building production systems end-to-end — FastAPI services on the backend, Flutter clients on the front.<br>
Computer Science @ IIIT Bhagalpur · Class of 2027 · Open to SWE internships

<a href="https://portfolio-website-chi-two-80.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-1A1A1A?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/faizanxp/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://leetcode.com/u/Fkwarrior/"><img src="https://img.shields.io/badge/LeetCode-1A1A1A?style=flat-square&logo=leetcode&logoColor=FFA116" alt="LeetCode"/></a>
<a href="https://x.com/fkwarrior21"><img src="https://img.shields.io/badge/X-1A1A1A?style=flat-square&logo=x&logoColor=white" alt="X"/></a>
<a href="https://play.google.com/store/apps/details?id=com.prodloo.app"><img src="https://img.shields.io/badge/Prodloo%20on%20Play%20Store-1A1A1A?style=flat-square&logo=googleplay&logoColor=3DDC84" alt="Prodloo"/></a>
<a href="https://drive.google.com/file/d/1IA8N__ysI4MXRFfdtfRQdVrVvU_FWo_v/view?usp=sharing"><img src="https://img.shields.io/badge/Résumé-1A1A1A?style=flat-square&logo=readdotcv&logoColor=white" alt="Resume"/></a>
<a href="mailto:fkhan4d04@gmail.com"><img src="https://img.shields.io/badge/Email-1A1A1A?style=flat-square&logo=gmail&logoColor=EA4335" alt="Email"/></a>

</div>

---

## About

I care about the parts of software that only show up under load: race conditions, cache invalidation, memory that never gets released, and LLM output that has to be parseable every single time.

Most of what I've built is live and used by real people — a Pomodoro app on the Play Store with a background service that survives process death, and an AI resume analyzer that answers cached requests in under 100 ms.

- **Currently** — deepening backend systems work (Postgres internals, caching strategies, API design)
- **Recently** — shipped ResumeIQ end-to-end: FastAPI + PostgreSQL + Redis + Gemini, deployed on Render and Vercel
- **Ask me about** — FastAPI service design, Flutter/BLoC architecture, structured LLM output with Pydantic, C++ DSA

---

## Tech Stack

**Languages**<br>
![C++](https://img.shields.io/badge/C++-1A1A1A?style=flat-square&logo=cplusplus&logoColor=00599C)
![Python](https://img.shields.io/badge/Python-1A1A1A?style=flat-square&logo=python&logoColor=3776AB)
![JavaScript](https://img.shields.io/badge/JavaScript-1A1A1A?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Dart](https://img.shields.io/badge/Dart-1A1A1A?style=flat-square&logo=dart&logoColor=0175C2)
![SQL](https://img.shields.io/badge/SQL-1A1A1A?style=flat-square&logo=postgresql&logoColor=4169E1)

**Backend**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-1A1A1A?style=flat-square&logo=fastapi&logoColor=009688)
![Node.js](https://img.shields.io/badge/Node.js-1A1A1A?style=flat-square&logo=nodedotjs&logoColor=339933)
![Express](https://img.shields.io/badge/Express-1A1A1A?style=flat-square&logo=express&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1A1A1A?style=flat-square&logo=sqlalchemy&logoColor=D71F00)
![Pydantic](https://img.shields.io/badge/Pydantic-1A1A1A?style=flat-square&logo=pydantic&logoColor=E92063)

**Data & Infra**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1A1A1A?style=flat-square&logo=postgresql&logoColor=4169E1)
![Redis](https://img.shields.io/badge/Redis-1A1A1A?style=flat-square&logo=redis&logoColor=DC382D)
![MongoDB](https://img.shields.io/badge/MongoDB-1A1A1A?style=flat-square&logo=mongodb&logoColor=47A248)
![Firebase](https://img.shields.io/badge/Firebase-1A1A1A?style=flat-square&logo=firebase&logoColor=FFCA28)
![Docker](https://img.shields.io/badge/Docker-1A1A1A?style=flat-square&logo=docker&logoColor=2496ED)
![Render](https://img.shields.io/badge/Render-1A1A1A?style=flat-square&logo=render&logoColor=46E3B7)
![Vercel](https://img.shields.io/badge/Vercel-1A1A1A?style=flat-square&logo=vercel&logoColor=white)

**Client & Tooling**<br>
![Flutter](https://img.shields.io/badge/Flutter-1A1A1A?style=flat-square&logo=flutter&logoColor=02569B)
![Git](https://img.shields.io/badge/Git-1A1A1A?style=flat-square&logo=git&logoColor=F05032)
![Postman](https://img.shields.io/badge/Postman-1A1A1A?style=flat-square&logo=postman&logoColor=FF6C37)
![Gemini API](https://img.shields.io/badge/Gemini%20API-1A1A1A?style=flat-square&logo=googlegemini&logoColor=8E75B2)

---

## Selected Work

### ResumeIQ — AI Resume Analyzer
`Python` `FastAPI` `PostgreSQL` `Redis` `Gemini API`

Full-stack resume evaluation service, live on Render + Vercel.

- Constrained Gemini output with Pydantic-enforced JSON schemas, making parsing deterministic instead of best-effort
- Added an MD5-keyed Redis cache in front of the LLM call, taking repeat-request latency from ~4 s to under 100 ms
- Modelled evaluation history in PostgreSQL via SQLAlchemy so users can track score changes across resume versions

<a href="https://ats-resume-checker-gamma.vercel.app/"><img src="https://img.shields.io/badge/Live%20Demo-1A1A1A?style=flat-square&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/Faizan-Khan0007/ats-resume-checker"><img src="https://img.shields.io/badge/Source-1A1A1A?style=flat-square&logo=github&logoColor=white"/></a>

### Prodloo — Productivity App (v2.0, Google Play)
`Flutter` `Firebase` `Provider`

Pomodoro and habit-tracking app shipped to production users.

- Built a background timer engine on `flutter_background_service` with Firestore transactions and offline caching, so sessions survive app kills and network loss
- Debounced UI events at 500 ms, cutting redundant Firestore writes by up to 80% and removing a class of race conditions
- Tracked down orphaned `StreamSubscription`s and `Timer`s causing OOM crashes on 120+ minute sessions

<a href="https://play.google.com/store/apps/details?id=com.prodloo.app"><img src="https://img.shields.io/badge/Google%20Play-1A1A1A?style=flat-square&logo=googleplay&logoColor=3DDC84"/></a>

<details>
<summary><b>More projects</b></summary>

<br>

**Amazin — E-commerce Backend** · `Node.js` `Express` `MongoDB` `Flutter`<br>
JWT-secured REST API across 25+ endpoints, with MongoDB schema and index tuning for concurrent traffic.

**Smart Todo Manager** · `Flutter` `Supabase`<br>
Cross-platform task app built on Clean Architecture with real-time sync and row-level-secure auth.

**Tourist Safety System** · `Blockchain` `Flutter`<br>
Smart India Hackathon 2025 shortlist — tamper-evident incident logging for tourist safety reporting.

</details>

---

## Experience

**Software Developer Intern** · Thyright Innovations · *Aug 2025 – Nov 2025*

- Led the migration of a production healthcare app from MVVM to BLoC-based Clean Architecture, decoupling business logic from UI so three engineers could work in parallel without constant merge conflicts
- Designed a normalized schema of 14+ tables with UUID primary keys covering patient and clinical operations
- Shipped 10+ features and architectural changes in an Agile cycle, from design through testing and release

---

## Beyond Shipping Code

- 2★ on CodeChef · 500+ DSA problems solved (300+ on LeetCode)
- Top 5 at Hacktopia · Smart India Hackathon 2025 shortlist · Top 16 at SIH 2024

---

<div align="center">

**Open to SWE internship roles.** The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/faizanxp/) or [email](mailto:fkhan4d04@gmail.com).

</div>
