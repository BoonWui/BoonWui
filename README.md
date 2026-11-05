# Hi, I'm BoonWui 👋

I build Python tools for commodity markets: pipelines that pull market data and news from LSEG/Refinitiv, bots that deliver palm oil updates, trading analytics for FCPO, and finance calculators. Based in Malaysia.

🌐 **Portfolio:** [boonwui.github.io](https://boonwui.github.io) · ✍️ **Notes:** [boonwui.github.io/blog](https://boonwui.github.io/blog/)

## ⭐ Featured

### 🌴 [Palm Oil Market Monitor](https://boonwui.github.io/palm-oil-monitor/)
A self-updating monthly palm oil report built only from public data. A Python ETL pipeline pulls World Bank prices, NOAA's El Niño index and MPOB balances. GitHub Actions rebuilds the report twice a month, with tests in CI.
- Written market read-out and a **six-factor bullish/bearish scorecard**
- **Stock-to-usage valuation model** (fair value vs market premium)
- **El Niño output projection**: Malaysian production up to 9 months ahead
- Price, spread and correlation tables, plus the full Malaysian supply and demand balance

[Open the report](https://boonwui.github.io/palm-oil-monitor/) · [How it's built](https://github.com/BoonWui/BoonWui.github.io/tree/main/palm-oil-monitor)

**[Palm Oil Fundamentals](https://boonwui.github.io/palm-oil-fundamentals/)**: a palm oil outlook dashboard covering Malaysian supply and stocks, export trends, El Niño, India and China demand, Indonesian biodiesel and an FCPO price model, with a [forecast to June 2027](https://boonwui.github.io/palm-oil-fundamentals/#forecast).

**[Compounding Calculator](https://boonwui.github.io/compounding-calculator/)**: see what savings grow into with compound interest, then how long the money lasts once withdrawals start. Includes a financial-independence goal, inflation and 10 currencies. [Live demo](https://boonwui.github.io/compounding-calculator/) · [Code](https://github.com/BoonWui/compounding-calculator)

## 🛠 Projects

**Market data pipelines**
- [Palm oil market news pipeline](https://github.com/BoonWui/palm-oil-news-pipeline): LSEG/Refinitiv news extraction, cleaning and storage in Parquet
- [LSEG ETL](https://github.com/BoonWui/LSEG-ETL): minute-level market data from the LSEG API
- [Minute-to-hourly ETL](https://github.com/BoonWui/minute-to-hourly-etl): turns minute bars into hourly data
- [Web scrape → ETL → report](https://github.com/BoonWui/WebScrap-to-ETL-to-Report): scrape, clean and report

**Automation**
- [Palm oil price news bot](https://github.com/BoonWui/lseg-news-automation-bot-telegram-Refinitiv): daily filtered palm oil price news by email
- [LSEG news email](https://github.com/BoonWui/LSEG-news): extra LSEG news digest
- [Freelance automation](https://github.com/BoonWui/Freelance)

**Trading & quant**
- [FCPO calendar spread report](https://github.com/BoonWui/OU-Calendar-Spread-Trading-Report): mean-reversion trading report for FCPO spreads
- [Monte Carlo price simulation](https://github.com/BoonWui/Monte-Carlo-Simulation): stock and crypto price paths from Yahoo Finance data
- [Machine learning](https://github.com/BoonWui/Machine-Learning)

**Live web tools**
- [Bursa Malaysia Market Monitor](https://boonwui.github.io/bursa-monitor/): FBM KLCI and 48 stocks across 10 sectors with sector rotation, breadth, a stock screener, momentum and risk analysis, updated every trading day
- [Palm Oil Market Monitor](https://boonwui.github.io/palm-oil-monitor/): self-updating monthly report with a factor scorecard, valuation model and El Niño output outlook from public data (GitHub Actions) [![Tests](https://github.com/BoonWui/BoonWui.github.io/actions/workflows/tests.yml/badge.svg)](https://github.com/BoonWui/BoonWui.github.io/actions/workflows/tests.yml)
- [Palm Oil Price Tools](https://boonwui.github.io/palm-oil-tools/): RM/USD price converter and Indonesia export levy and duty estimator
- [Option Strategy Builder](https://boonwui.github.io/option-strategy/): multi-leg futures and options strategies with payoff, break-evens and combined Greeks
- [Calendar Spread Analyser](https://boonwui.github.io/spread-analyser/): OU mean-reversion fit, z-score signals and backtest in the browser
- [Monte Carlo Simulator](https://boonwui.github.io/monte-carlo/): GBM and Heston price paths with fan chart and value at risk
- [Market Simulator (Streamlit)](https://github.com/BoonWui/market-simulator-streamlit): Monte Carlo calibrated to live Yahoo Finance data

**Tools & algorithms**
- [FCPO Trade Calculator](https://boonwui.github.io/fcpo-calculator/): P&L, fees, margin, break-even, risk/reward and position sizing for palm oil futures (live)
- [Option Pricing Calculator](https://boonwui.github.io/option-calculator/): Black-Scholes and Black-76 pricing with Greeks, implied volatility and payoff chart (live)
- [Retirement & option calculators](https://github.com/BoonWui/Application): [retirement v1.0](https://github.com/BoonWui/Application/releases/tag/v1.0) · [option v1.1](https://github.com/BoonWui/Application/releases/tag/v1.1)
- [LPMP coin minimisation library](https://github.com/BoonWui/LPMP-library): fast, memory-efficient coin minimisation using recursive modular pruning

> **Disclaimer:** Data in these projects may be delayed, incomplete or inaccurate. Everything here is for education and research only. Use at your own risk. **Not financial advice.**

## 🧰 Toolkit

`Python` `pandas` `ETL` `Parquet` `LSEG / Refinitiv API` `Yahoo Finance` `Web scraping` `Monte Carlo` `Machine learning` `Email automation` `HTML / JavaScript`
