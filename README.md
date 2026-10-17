<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1D3A,50:123A6B,100:0B1D3A&height=200&section=header&text=FRANCO%20CACCIA&fontSize=52&fontColor=FFB000&fontAlignY=40&desc=Software%20%C2%B7%20Quant%20%C2%B7%20Aerospace%20%C2%B7%20Aviation%20%C2%B7%20and%20more&descAlignY=62&descSize=17&descColor=C9D6EA" width="100%" alt="Franco Caccia"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1200&color=FFB000&center=true&vCenter=true&width=760&lines=CS+grad+%E2%86%92+M.S.+Aerospace+%26+Space+Systems+%40+Lehigh;Commercial+pilot+(ANAC)+%C2%B7+IFR+%C2%B7+FAA+certs+in+progress;Quant+analyst+%C2%B7+Go+%C2%B7+Python+%C2%B7+LLM+trading+bots;I+like+building+software%2C+all+kinds+of+it)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Franco_Caccia-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/franco-caccia-37b5a1177/)
[![GitHub](https://img.shields.io/badge/Francocaccia-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Francocaccia)

</div>

---

## ✈ Flight plan

```
SABE  ──✈──▶  KLYH  ──✈──▶  KABE
Buenos Aires   Lynchburg, VA   Bethlehem, PA
Home           CS degree       M.S. Aerospace & Space Systems
```

I'm a computer science graduate (University of Lynchburg, minor in mathematics) and M.S. student in Aerospace & Space Systems Engineering at Lehigh. I'm an instrument-rated commercial pilot (ANAC Argentina) with my FAA certificates in progress, and I build software where numbers have to be right and mistakes are expensive. Finance and aviation are where I spend most of my time, but I'm into software in general: backends, data pipelines, systems, and whatever is next.

## 🌤 Weather at home and at school

**SABE** (Aeroparque Internacional Jorge Newbery, Buenos Aires)
<!--METAR_SABE_START-->
```
METAR SABE 171000Z 19007KT 130V240 9999 OVC033 09/01 Q1022 NOSIG
```
<!--METAR_SABE_END-->

**KABE** (Lehigh Valley International Airport, Allentown)
<!--METAR_KABE_START-->
```
METAR KABE 170951Z 35012KT 10SM BKN038 10/03 A3004 RMK AO2 SLP171 T01000033
```
<!--METAR_KABE_END-->

<sub>Pulled from aviationweather.gov by a GitHub Action every few hours.</sub>

## 📊 My trading bot, live

The bot below runs on a paper account and is benchmarked against SPY. These numbers come straight from its public `/stats` endpoint; they will read "N/A" until it has two trading days of data, and early results mean nothing statistically.

<!--
Uncomment once /stats returns real numbers (after ~Oct 15, 2026):

![Bot return](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fautotradingbot-kjr0.onrender.com%2Fstats&query=%24.bot_return_pct&label=bot%20return&suffix=%25&color=123A6B)
![Excess vs SPY](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fautotradingbot-kjr0.onrender.com%2Fstats&query=%24.excess_return_pct&label=vs%20SPY&suffix=%25&color=FFB000)
![Days tracked](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fautotradingbot-kjr0.onrender.com%2Fstats&query=%24.days_tracked&label=days%20tracked&color=555)
-->

Raw data: [`/stats`](https://autotradingbot-kjr0.onrender.com/stats)

## 🧰 Pre-flight checklist (projects)

<details>
<summary><b>AutoTradingBot</b>: autonomous paper-trading bot in Go</summary>

<br>

- **What it does:** every 15 minutes it combines technical indicators, news and an LLM (Gemini) to decide BUY / SELL / HOLD, then places bracket orders on Alpaca.
- **Risk controls:** position sizing by conviction, max open positions, daily loss and drawdown circuit breakers, liquidity filters.
- **Honest scoreboard:** public, privacy-safe `/stats` endpoint benchmarked against SPY.
- **Stack:** Go · Python · Gemini API · Alpaca API · Docker · Render

[Repo](https://github.com/Francocaccia/AutoTradingBot) · [Live stats](https://autotradingbot-kjr0.onrender.com/stats)

</details>

<details>
<summary><b>Stock-Quant-Reports</b>: equity report generator</summary>

<br>

- **What it does:** turns a ticker (or a batch) into a two-page PDF with weekly/monthly indicators, charts, a plain-English narrative and a rule-based signal.
- **Built for:** a university student-managed investment fund, where it replaced hours of manual weekly analysis.
- **Stack:** Go · React · MongoDB · Firebase

[Repo](https://github.com/Francocaccia/Stock-Quant-Reports)

</details>

## 🛫 Next on the runway (planned, not built yet)

<details>
<summary><b>Lending protocol with Chainlink price feeds</b></summary>

<br>

A collateralized lending protocol: deposits, borrows, interest accrual, health factors and liquidations, priced with Chainlink oracles and covered by fuzz and invariant tests. Solidity · Foundry.

</details>

<details>
<summary><b>MEV sandwich-attack detector</b></summary>

<br>

Scans on-chain swap data to flag sandwich attacks and quantify what victims lost to slippage, with a small dashboard of the findings. Python · SQL · public node and indexer data.

</details>

<details>
<summary><b>Mini blockchain from scratch in Go</b></summary>

<br>

A small chain built to understand the fundamentals: peer-to-peer networking, block and transaction validation, a proof-of-stake validator set and account state. Go.

</details>

## 📒 Logbook (experience)

<details>
<summary><b>Finance & Data Research Assistant</b>, Lehigh University · 2026 to present</summary>

<br>

Python pipelines that extract securities-lending data from historical SEC filings and turn unstructured disclosures into research-ready datasets.

</details>

<details>
<summary><b>Quant Analyst & CS intern</b>, Student Managed Investment Fund · 2025 to 2026</summary>

<br>

Market and asset analysis with weekly updates, and an automated quantitative stock-analysis system in Go and Python used in the fund's decision making.

</details>

<details>
<summary><b>Coursework</b></summary>

<br>

Artificial Intelligence · Machine Learning · Data Structures · Databases · Operating Systems · Architecture & Assembly · Applied Regression · Business Statistics · Investment Fundamentals · Finance · Accounting

</details>

## 🎖 Ratings & certificates

```
▸ Commercial Pilot, Instrument Rating     ANAC Argentina
▸ Commercial Pilot (FAA)                  in progress of conversion
▸ Flight Dispatcher                       in progress
▸ Restricted Radiotelephone Operator      FCC
▸ Bloomberg Market Concepts
```

## 🗣 Crew languages

`ES` native · `EN` bilingual · `PT` fluent · `中文` basic

## 🛠 Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

**Web, data and cloud**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<sub>Also: Assembly, Flex & Bison.</sub>

---

<div align="center">
<sub>Paper trading only. Nothing here is investment advice.</sub>
</div>
