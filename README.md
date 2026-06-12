<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:1a0033,35:4c1d95,70:6d28d9,100:a78bfa&text=Austin%20Liu&fontColor=ffffff&fontSize=58&fontAlignY=35&desc=Software%20Engineer%20%7C%20AI%2FML%20%7C%20Quantitative%20Research&descSize=18&descAlignY=55&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=24&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=700&lines=Building+intelligent+systems+at+scale;AI+%2B+Quantitative+Research+%2B+Full+Stack;Turning+market+data+into+production+software;Engineering+with+a+product+mindset" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/Vanderbilt%20University-Economics%20%26%20Political%20Science-6d28d9?style=flat-square&logo=googlescholar&logoColor=white" />
<img src="https://img.shields.io/badge/Class%20of-2028-7c3aed?style=flat-square&logo=academia&logoColor=white" />
<img src="https://img.shields.io/badge/GPA-3.86%2F4.0-8b5cf6?style=flat-square&logo=bookstack&logoColor=white" />
<img src="https://img.shields.io/badge/📍-Los%20Angeles%20%7C%20Nashville-a78bfa?style=flat-square" />

<br/><br/>

<a href="https://medium.com/@austinpliu"><img src="https://img.shields.io/badge/Portfolio-1a0033?style=for-the-badge&logo=medium&logoColor=a78bfa" /></a>
<a href="https://www.linkedin.com/in/austinpliu"><img src="https://img.shields.io/badge/LinkedIn-4c1d95?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:austin.liu@vanderbilt.edu"><img src="https://img.shields.io/badge/Email-6d28d9?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/austinpliu"><img src="https://img.shields.io/badge/GitHub-7c3aed?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=austinpliu&style=flat-square&color=6d28d9&label=Profile+Views" />
<img src="https://img.shields.io/github/followers/austinpliu?style=flat-square&color=7c3aed&labelColor=1a0033&logo=github&label=Followers" />
<img src="https://img.shields.io/github/stars/austinpliu?style=flat-square&color=8b5cf6&labelColor=1a0033&logo=github&label=Stars" />

</div>

---

## 💼 About Me

```text
Software engineer and quantitative researcher operating at the intersection
of AI, market microstructure, and full stack product development.
```

- 🧠 **Software Engineering First.** I build production-grade systems, from real-time data pipelines and alerting infrastructure to research dashboards. Clean architecture, tested code, and reproducible environments are non-negotiable.
- 🤖 **AI / ML Expertise.** Hands-on with regime-detection models (Hidden Markov Models), rolling information-coefficient analysis, walk-forward backtesting, and LLM-powered agent workflows using the Claude API and multi-model CLI tooling.
- 🌐 **Full Stack Development.** Comfortable across the stack: Python and Node services on the backend, React and Streamlit on the frontend, Postgres and Redis underneath, Docker and GitHub Actions around everything.
- 📦 **Product Engineering Mindset.** Every system I ship answers a real user question. My Polymarket smart-money tracker exists because traders need signal, not noise. My research engine exists because alpha decays and someone has to measure it.
- ✍️ **Research Communicator.** Published analyst covering market structure, stablecoins, DeFi mechanics, and digital asset regulation, with work syndicated through Coinmonks.

> **Open To:** Software Engineering Internships · Quantitative Research Roles · AI/ML Engineering · Crypto Venture & Trading Firms · Open Source Collaboration

---

## 🛠️ Tech Stack

### Languages
<div align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,javascript,solidity,bash&theme=dark" />
</div>

### Frontend
<div align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&theme=dark" />
</div>

### Backend & Databases
<div align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,fastapi,flask,postgres,mongodb,redis&theme=dark" />
</div>

### Cloud, DevOps & Tooling
<div align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,git,github,githubactions,vercel,linux,vscode&theme=dark" />
</div>

---

## 🤖 AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:-------|:-----------:|:--------|
| **Regime Detection & Time Series** | ▰▰▰▰▱ | Hidden Markov Models for market regime classification, regime-conditional signal evaluation |
| **Signal Research & Alpha Decay** | ▰▰▰▰▱ | Rolling IC analysis, signals-by-regime cross-tabulation, walk-forward backtesting |
| **LLM Engineering & Agents** | ▰▰▰▰▱ | Claude API integration, Claude Code automation, multi-LLM CLI orchestration, overnight agent pipelines |
| **Data Engineering** | ▰▰▰▰▱ | API ingestion pipelines, wallet-level on-chain data processing, real-time alert systems |
| **ML for Prediction Markets** | ▰▰▰▱▱ | Smart-money wallet scoring, coordination detection, probability calibration |

</div>

---

## 🚀 Featured Projects

<details>
<summary><b>📡 Polymarket Smart-Money Tracker</b></summary>
<br/>

Real-time intelligence system that monitors historically profitable Polymarket wallets and fires Telegram alerts when smart money coordinates into the same market.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Python, Polymarket API, Telegram Bot API, PostgreSQL, Docker |
| **Scale** | Continuous monitoring across thousands of wallets and active markets |
| **Performance** | Sub-minute alert latency from on-chain position change to Telegram delivery |
| **Security** | Global secrets-protection layer, environment-isolated credentials, read-only API scopes |
| **Impact** | Surfaces coordinated positioning by proven-profitable wallets before market consensus shifts |
| **Repository** | [github.com/austinpliu/polymarket-smart-money](https://github.com/austinpliu/polymarket-smart-money) |

The system maintains a rolling profitability ledger per wallet, scores historical performance, and triggers only on multi-wallet coordination events to keep the signal-to-noise ratio high. Built for unattended overnight operation with automated recovery and structured logging.

</details>

<details>
<summary><b>📉 Regime-Conditional Alpha Decay Engine</b></summary>
<br/>

Quantitative research platform that measures how trading signal predictive power decays across market regimes, built on the Mangrove API across five structured phases.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Python, Mangrove API, hmmlearn, pandas, NumPy, Streamlit |
| **Scale** | Full signal library evaluation across multi-year historical datasets |
| **Performance** | Vectorized rolling IC computation with walk-forward validation windows |
| **Security** | API keys managed through permission-scoped configuration, no credentials in source |
| **Impact** | Identifies which signals retain alpha in which regimes, directly informing strategy allocation |
| **Repository** | [github.com/austinpliu/alpha-decay-engine](https://github.com/austinpliu/alpha-decay-engine) |

Architecture spans data ingestion, HMM regime detection, rolling information-coefficient analysis, signals-by-regime cross-tabulation, and a walk-forward backtest surfaced through an interactive Streamlit dashboard. Designed as a portfolio-grade research artifact for institutional trading contexts.

</details>

<details>
<summary><b>🏦 Institutional Basis Trade Framework</b></summary>
<br/>

Bilateral decision framework comparing direct prime brokerage execution against ETF-plus-futures replication for a macro hedge fund basis trade, developed for the Coinbase Institutional Client Strategy Challenge.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Python, pandas, financial modeling, CME and ETF market data |
| **Scale** | Institutional-size notional modeling with funding, custody, and margin variables |
| **Performance** | Side-by-side cost-of-carry decomposition across execution venues |
| **Security** | Counterparty and custody risk analysis embedded in the framework itself |
| **Impact** | Demonstrated when Coinbase Prime outperforms IBIT + CME replication and when it does not |
| **Repository** | [github.com/austinpliu/basis-trade-framework](https://github.com/austinpliu/basis-trade-framework) |

The framework treats venue selection as a function of fund mandate, leverage constraints, and operational overhead rather than headline fees, producing a defensible recommendation under each client profile.

</details>

<details>
<summary><b>🗂️ Unified Research & Coding Workflow</b></summary>
<br/>

Two-world development architecture integrating Claude Code, VS Code, and Obsidian into a single reproducible environment for research and engineering work.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Claude Code, VS Code, Obsidian, shell scripting, Git |
| **Scale** | Governs all research notes and every active coding project under one permission model |
| **Performance** | Eliminates context-switching overhead between writing, research, and engineering |
| **Security** | Global secrets-protection layer enforced through Claude permission settings |
| **Impact** | Single source of truth for research vault and codebases, with agentic automation hooks |
| **Repository** | [github.com/austinpliu/dev-workflow](https://github.com/austinpliu/dev-workflow) |

The architecture separates a research vault from coding projects while letting agents operate safely across both, enabling overnight automation without exposing credentials.

</details>

---

## 💻 Experience

### 🔬 Research Writer · **Mangrove Technologies**
**2025 – Present**

Research and engineering contributor at an AI platform for building and deploying crypto trading strategies.

- Designed a five-phase quantitative research project on regime-conditional alpha decay using the platform's signal library and backtesting infrastructure
- Authored brand-safe technical content covering platform capabilities, signal methodology, and market structure
- Conducted structural due diligence on the company's seed raise, including SAFE mechanics

`Python` `Quantitative Research` `Backtesting` `Technical Writing` `API Integration`

### 📊 Research Analyst & Voting Member · **Anchor DAO**
**2024 – Present**

Analyst and governance participant at a student-run crypto fund.

- Produced investment research informing fund allocation decisions
- Exercised voting rights on portfolio and governance proposals
- Evaluated DeFi protocols across risk, mechanism design, and sustainability dimensions

`DeFi` `Investment Research` `Governance` `Risk Analysis`

### 📰 Writer & Newsletter Lead · **Vanderbilt Blockchain Club**
**2024 – Present**

Lead writer for a newsletter reaching 450+ subscribers with exchange partnerships across Coinbase, Gemini, and Jupiter.

- Own end-to-end newsletter production from research through publication
- Cover market structure, regulation, stablecoins, and protocol developments
- Coordinate content alignment with exchange partners

`Content Strategy` `Market Analysis` `Editorial Leadership`

### 🏛️ Campus Representative · **Stand With Crypto**
**2024 – Present**

Policy advocacy coordinator operating across a 48+ school network.

- Coordinate crypto policy advocacy campaigns across university chapters
- Translate legislative developments, including the CLARITY Act, into actionable campus programming

`Policy Analysis` `Advocacy` `Cross-Team Coordination`

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|:------------|:--------|
| 🥇 **Coinbase Institutional Client Strategy Challenge** | Developed a bilateral Prime vs. IBIT + CME basis trade framework for a macro hedge fund client profile |
| ✍️ **Published Research Analyst** | Syndicated through Coinmonks covering Chainlink, Monero, prediction market regulation, RWA tokenization, and crypto policy |
| 📬 **Newsletter Growth** | Scaled Vanderbilt Blockchain newsletter to 450+ subscribers with three exchange partnerships |
| 🎓 **Academic Standing** | 3.86 GPA, Economics & Political Science with Business Minor, Vanderbilt University |
| 🤝 **Hedge Fund Collaboration** | Co-authored DeFi diversification research with Cipher Chain Capital, a market-neutral DeFi fund |

</div>

---

## 📜 Certifications

### ☁️ AWS
<img src="https://img.shields.io/badge/AWS-Cloud%20Practitioner-6d28d9?style=for-the-badge&logo=amazonwebservices&logoColor=white" />

### 🗄️ Oracle
<img src="https://img.shields.io/badge/Oracle-OCI%20Foundations%20Associate-7c3aed?style=for-the-badge&logo=oracle&logoColor=white" />

### 🎓 NPTEL
<img src="https://img.shields.io/badge/NPTEL-Data%20Analytics%20with%20Python-8b5cf6?style=for-the-badge&logo=python&logoColor=white" />

### 🌐 Cisco
<img src="https://img.shields.io/badge/Cisco-Introduction%20to%20Cybersecurity-a78bfa?style=for-the-badge&logo=cisco&logoColor=white" />

---

## ⚔️ Coding Profiles

<div align="center">

<a href="https://leetcode.com/austinpliu"><img src="https://img.shields.io/badge/LeetCode-1a0033?style=for-the-badge&logo=leetcode&logoColor=FFA116&label=&labelColor=1a0033" height="40"/></a>&nbsp;
<a href="https://www.geeksforgeeks.org/user/austinpliu"><img src="https://img.shields.io/badge/GeeksforGeeks-1a0033?style=for-the-badge&logo=geeksforgeeks&logoColor=2F8D46" height="40"/></a>&nbsp;
<a href="https://www.hackerrank.com/austinpliu"><img src="https://img.shields.io/badge/HackerRank-1a0033?style=for-the-badge&logo=hackerrank&logoColor=00EA64" height="40"/></a>&nbsp;
<a href="https://www.codechef.com/users/austinpliu"><img src="https://img.shields.io/badge/CodeChef-1a0033?style=for-the-badge&logo=codechef&logoColor=ffffff" height="40"/></a>

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=austinpliu&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=8b5cf6&text_color=c9d1d9&count_private=true" height="170" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=austinpliu&theme=midnight-purple&hide_border=true&background=0d1117&ring=8b5cf6&fire=a78bfa&currStreakLabel=a78bfa" height="170" />

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=austinpliu&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=8" height="160" />

</div>

---

## 🏅 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=austinpliu&theme=radical&no-frame=true&no-bg=true&row=1&column=7&margin-w=8&title_color=a78bfa" width="100%" />

</div>

---

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=austinpliu&theme=react-dark&bg_color=0d1117&color=a78bfa&line=8b5cf6&point=ffffff&hide_border=true&area=true" width="100%" />

</div>

---

## 🎯 Current Focus

```yaml
learning:
  - Advanced regime-detection architectures beyond HMMs
  - Production LLM agent orchestration patterns
  - Market microstructure of perpetual futures venues

building:
  - Polymarket smart-money tracker v2 with wallet clustering
  - Regime-conditional alpha decay engine with Streamlit deployment
  - Overnight multi-agent research automation pipeline

exploring:
  - Hyperliquid ecosystem and on-chain orderbook design
  - CLARITY Act implications for digital asset market structure
  - Stablecoin settlement infrastructure

open_to:
  - Software engineering internships
  - Quantitative research roles
  - Crypto venture and trading firm opportunities
  - Open source collaboration
```

---

## 🤝 Connect

<div align="center">

<a href="mailto:austin.liu@vanderbilt.edu"><img src="https://img.shields.io/badge/Gmail-6d28d9?style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;
<a href="https://www.linkedin.com/in/austinpliu"><img src="https://img.shields.io/badge/LinkedIn-4c1d95?style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;
<a href="https://github.com/austinpliu"><img src="https://img.shields.io/badge/GitHub-1a0033?style=for-the-badge&logo=github&logoColor=white" /></a>&nbsp;
<a href="https://medium.com/@austinpliu"><img src="https://img.shields.io/badge/Portfolio-7c3aed?style=for-the-badge&logo=medium&logoColor=white" /></a>

</div>

---

<div align="center">

*"Engineering is the discipline of turning uncertainty into systems that work."*

<img src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:a78bfa,50:6d28d9,100:1a0033&section=footer" width="100%"/>

</div>
