---
title: "TSLA 2024 — Heikin-Ashi + Ichimoku + VWAP"
excerpt: "Heikin-Ashi candles, Ichimoku Cloud, anchored VWAP, Stochastique & OBV (style ggplot2).<br/><img src='https://aw0007.github.io/images/technical%20anlysis/TSLA%202024.png'>"
collection: portfolio
authors:
  - Abdoul Wahid Massaoudou Namata
---

🔍 One of the major goals of market analysis is to understand **how prices move and how trends/cycles emerge over time**.

But explaining these dynamics is tricky—even for practitioners. As any trader will tell you: sometimes, explaining **risk management** to a newcomer is harder than placing the trades themselves! 😅

👉 **[Launch the Interactive App ▶](https://abdoulwahid.shinyapps.io/tsla-ita/)**

---

### 📉 The Reality Behind Price Action

Markets don’t move in straight lines. They **trend**, **consolidate**, and **revert**—these are the rhythms of **price cycles**.

Understanding these movements helps to:
- anticipate momentum shifts,
- design robust trading/hedging rules, and
- make more informed portfolio decisions.

I illustrated this by analyzing **Tesla (TSLA)** in **2024** with a **different toolkit**:
- **Heikin-Ashi** (smoothed candles)
- **Ichimoku** (Tenkan/Kijun + **Kumo Cloud**)
- **Anchored VWAP** (volume-weighted mean price)
- **Stochastic %K/%D** (momentum oscillator)
- **OBV & Volume (M)** (flow/participation)

---

### 📊 Visualization

<img src="https://aw0007.github.io/images/technical%20anlysis/TSLA%202024.png" style="width:90%;" alt="TSLA Heikin-Ashi + Ichimoku 2024" />

**Legend**:
- **Heikin-Ashi**: Smoothed price candles  
- **Tenkan (9) / Kijun (26)**: Ichimoku baselines  
- **Kumo Cloud**: Span A/B volatility cloud  
- **VWAP**: Anchored volume-weighted average price  
- **%K/%D**: Stochastic oscillator  
- **OBV / Volume (M)**: On-Balance Volume & traded volume

---

### 🧰 Methodology & Data

- **Period**: 2024-01-01 → 2024-12-31  
- **Data source**: Yahoo Finance via `yfinance`  
- **Indicators**: Heikin-Ashi, Ichimoku, VWAP, Stoch %K/%D, OBV, Volume  
- **Tools used**: Python (`pandas`, `plotly`)

---

### 🧠 Why It Matters

Whether in **cooking**, **medicine**, or **markets**—precision matters.

- In cooking: a wrong dose can ruin the dish.  
- In medicine: a milligram too much can have serious consequences.  
- In trading: misreading a signal or reacting late can deepen drawdowns or miss opportunities.

---

### 📚 Suggested Readings

- **Hosoda, G.** — *Ichimoku Kinko Hyo*  
- **Murphy, J. (1999)** — *Technical Analysis of the Financial Markets*

---

### 🏷️ Tags

`#TSLA`, `#Ichimoku`, `#HeikinAshi`, `#VWAP`, `#Stochastic`, `#OBV`, `#TechnicalAnalysis`, `#Plotly`, `#Python`, `#yfinance`
