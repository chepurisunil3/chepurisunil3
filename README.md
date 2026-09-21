<div align="center">

# Hi, I'm Sunil 👋

### Senior Full Stack Engineer — 8+ years building systems that hold up under real load

I own products end to end: architecture, development, testing, production delivery, and the performance work that happens after launch.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chepuri-sunil)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chepurisunil3@gmail.com)
[![Location](https://img.shields.io/badge/Hyderabad,_India-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

### About me

Senior Full Stack Engineer with 8+ years of experience building complex, production-grade web, mobile, and backend applications — from frontend architecture through distributed backend systems, API integrations, and cloud infrastructure.

- 🔭 Currently architecting distributed reporting/query systems and campaign-automation tooling at **Optmyzr**
- 💻 Specialize in **React.js**, **Node.js**, **TypeScript**, and **C#/.NET**, with production mobile experience in **React Native** and **Ionic**
- ☁️ Comfortable across the stack: **AWS**, caching layers, SQL/NoSQL data stores, and third-party API integrations at scale
- 🚀 Into system design, performance optimization, and distributed systems
- 📚 Currently exploring AI-assisted engineering workflows (Claude, Copilot) in production codebases

### Impact, in numbers

A few figures from the Central Query System (CQS) — a distributed reporting platform I architected and shipped at Optmyzr:

<div align="center">

| 76,000 | 40 | &lt;500ms | 99.95% |
|:---:|:---:|:---:|:---:|
| accounts processed / day | concurrent users served | cached response time | user coverage on rollout day, zero downtime |

</div>

---

### 💼 Experience

**Senior Software Developer · [Optmyzr](https://optmyzr.com)** — *May 2020 – Present*
SaaS platform for PPC campaign management and automation

- Architected and led **CQS**, a distributed reporting/query platform, from design through production rollout — 99.95% user coverage within a single day, zero customer-facing downtime
- Scaled CQS ingestion to 76,000 advertising accounts/day across a rolling 14-day window, incrementally patched into a DuckDB store instead of full rebuilds
- Built an intermediate caching layer that cut repeat queries from sub-2s to under 500ms for 40 concurrent users
- Built rule-based campaign optimization engines on the Google, Microsoft (Bing), Meta, and Amazon Ads APIs — handling rate limits, pagination, and schema differences across all four
- Rebuilt the Alerts Management UI in React/Redux and shipped Slack, email, and webhook notification workflows

**Full Stack Developer / Lead Architect · Prahem Technologies** — *2 years*
On-demand logistics and delivery products

- Designed and built **Pickkup**, an on-demand delivery app for Android and iOS (Ionic + Angular) — solo, from architecture to launch on both app stores
- Implemented live delivery tracking with background geolocation and real-time status updates
- Designed backend services for order management, geolocation tracking, and automated delivery-agent assignment
- Grew and led a team of 4 developers through the platform's scale-up phase

---

### 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[Consumers-Retailers-E-Commerce](https://github.com/chepurisunil3/Consumers-Retailers-E-Commerce)** | Multi-tenant marketplace (retailer console + consumer storefront + shared API) modeled on Indian e-commerce — GST/PAN onboarding, split-shipment order lifecycle, role-scoped staff accounts. Atomic stock reservation proven safe under concurrency with a dedicated race-condition test. Dockerized, with a Jest/Supertest backend test suite. | React 18 · Node/Express · MongoDB · JWT · Docker |
| **[TransactionsProject](https://github.com/chepurisunil3/TransactionsProject)** | A wallet/ledger API that goes past CRUD: a per-wallet FIFO queue serializes concurrent balance updates to prevent read-modify-write races, with compensating rollback if a balance write fails after the transaction record is created. | React · Express · MongoDB · Mongoose |
| **[Video-Conference](https://github.com/chepurisunil3/Video-Conference)** | Browser-based video conferencing app — real WebRTC mesh (`RTCPeerConnection`) for peer-to-peer audio/video, Socket.IO signaling, host controls (mute/remove/timer), hand-raise. Hardened with helmet, rate limiting, and env-based config for production deployment. | Node.js · Express · Socket.IO · WebRTC |
| **[stocks-model](https://github.com/chepurisunil3/stocks-model)** | AI-assisted paper-trading bot: technical-indicator strategies (RSI, MACD, Bollinger, ADX) and options strategies from Zerodha Varsity, a Random Forest signal model, and a risk-managed order loop. Deployable as a serverless API on Vercel with a scheduled trading-hours cron. | Python · scikit-learn · yfinance · Vercel |
| **[Image-Processing-Using-Google-Vision-API](https://github.com/chepurisunil3/Image-Processing-Using-Google-Vision-API)** | Full-stack OCR tool — upload an image, extract text via the Google Vision API, and browse per-user OCR history, with a health-check endpoint for verifying Vision credentials before use. | React (Vite) · Node/Express · MongoDB · Google Vision API |

*More on my [pinned repositories](https://github.com/chepurisunil3?tab=repositories) — this list is the highlights, not the whole picture.*

---

### 🛠️ Tech stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Mobile**

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

**Cloud & Tooling**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

Also integrate regularly with the **Google, Microsoft (Bing), Meta, and Amazon Ads APIs**, plus Slack and webhook-based automation.

---

### 📊 GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=chepurisunil3&show_icons=true&theme=default&hide_border=true&count_private=true" alt="Sunil's GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chepurisunil3&layout=compact&hide_border=true&langs_count=8" alt="Top languages" height="165" />

</div>

---

### 🎓 Education

B.Tech, Computer Science Engineering — Vidya Jyothi Institute of Technology, Hyderabad (2014 – 2018)

### 🤝 Let's connect

I'm always open to discussing engineering challenges, system design, or interesting opportunities.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chepuri-sunil)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chepurisunil3@gmail.com)

<sub>⭐ Thanks for stopping by!</sub>
