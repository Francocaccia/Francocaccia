<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1D3A,50:123A6B,100:0B1D3A&height=200&section=header&text=FRANCO%20CACCIA&fontSize=52&fontColor=FFB000&fontAlignY=40&desc=Quant%20%C2%B7%20Aerospace%20%C2%B7%20Aviation%20software&descAlignY=62&descSize=17&descColor=C9D6EA" width="100%" alt="Franco Caccia"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1200&color=FFB000&center=true&vCenter=true&width=720&lines=CS+grad+%E2%86%92+M.S.+Aerospace+%26+Space+Systems+%40+Lehigh;Commercial+pilot+%C2%B7+IFR+%C2%B7+Flight+dispatcher;Quant+analyst+%C2%B7+Go+%C2%B7+Python+%C2%B7+LLM+trading+bots;Where+finance+meets+flight)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Franco_Caccia-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/TU-USUARIO)
[![GitHub](https://img.shields.io/badge/Francocaccia-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Francocaccia)

</div>

---

## ✈ Flight plan

```
SABE  ──✈──▶  KLYH  ──✈──▶  KABE
Buenos Aires   Lynchburg, VA   Lehigh Valley, PA
home           CS degree       M.S. Aerospace & Space Systems
```

I'm a computer science graduate (University of Lynchburg, minor in mathematics) and M.S. student in Aerospace & Space Systems Engineering at Lehigh. I hold a commercial pilot license with instrument rating and a flight dispatcher license, and I build quantitative finance software where numbers have to be right and mistakes are expensive.

## 🌤 Weather at home and at school

**SABE** (Aeroparque, Buenos Aires)
<!--METAR_SABE_START-->
```
Waiting for the first automatic update.
```
<!--METAR_SABE_END-->

**KABE** (Lehigh Valley, nearest field to campus)
<!--METAR_KABE_START-->
```
Waiting for the first automatic update.
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

<details>
<summary><b>Coming up</b></summary>

<br>

An IFR navigation trainer, a METAR/TAF decoder, a market-risk checker, and a portfolio site. They will show up here once they are public.

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

## 🎖 Ratings & certificates

```
▸ Commercial Pilot, Instrument Rating     FAA · ANAC Argentina
▸ Flight Dispatcher
▸ Restricted Radiotelephone Operator      FCC
▸ Bloomberg Market Concepts
```

## 🗣 Crew languages

`ES` native · `EN` bilingual · `PT` fluent · `中文` basic

## 🛠 Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

---

<div align="center">
<sub>Paper trading only. Nothing here is investment advice.</sub>
</div>