title: "MACD + SMA Backtesting (2015–2024)"
excerpt: "Systematic backtesting of a MACD crossover strategy with SMA overlays across multiple assets (TSLA, NVDA, AAPL, MSFT, AMZN).<br/><img src='https://aw0007.github.io/images/BACKTESTING/BACKTESTING.png'>"
collection: portfolio
authors:
  - Abdoul Wahid Massaoudou Namata
---

🔍 **What is this project about?**  

This project is a **systematic backtesting experiment**. The idea was to test a simple but widely studied trading rule: the **MACD crossover strategy**, often combined with short-term moving averages for context.  

Backtesting here means:  
- taking **historical OHLCV data** (open, high, low, close, volume),  
- applying a **trading rule** (when to buy, when to sell),  
- simulating a portfolio evolution,  
- and measuring performance (returns, drawdowns, win rate, etc.).  

It’s a bridge between **quantitative finance research** and **practical Python coding**.

---

### 📉 The Strategy Tested  

The **MACD crossover rule** is a canonical example of a momentum/trend-following strategy.  

- **MACD line** = EMA(12) – EMA(26)  
- **Signal line** = EMA(9) of MACD  
- **Trading logic**:  
  - **Buy (long entry)** when MACD crosses above the Signal line.  
  - **Sell (short entry)** when MACD crosses below the Signal line.  

In addition, I plotted:  
- **SMA(10)** and **SMA(20)** to contextualize short-term trends.  

Two modes were tested:  
1. **Long-only** → stay in cash when a sell signal appears.  
2. **Long & short** → reverse position on each crossover.  

---

### 🧰 Methodology  

- **Universe tested**:  
  - Tesla (TSLA), Nvidia (NVDA), Apple (AAPL), Microsoft (MSFT), Amazon (AMZN)  
- **Period**: 2015-01-01 → 2024-12-31  
- **Data source**: Yahoo Finance via `yfinance`  
- **Indicators**: MACD, Signal line, SMA(10), SMA(20)  
- **Tools used**:  
  - `backtesting.py` (portfolio simulation)  
  - `pandas`, `numpy` (data manipulation)  
  - `TA-Lib` (when available; otherwise NumPy EMA fallback)  
  - `bokeh` (interactive charts)  

To reduce Yahoo Finance rate limits, I implemented:  
- **batch downloads** (fetching multiple tickers at once),  
- **local CSV caching**,  
- **retry logic with exponential backoff**.  

For each asset, the code generates:  
- **HTML interactive report** with equity curve, OHLC chart, trades, and indicators,  
- **CSV trade log** with detailed entries/exits (timestamp, size, PnL, returns).  

---

### 📊 Example Visualization  

<img src="https://aw0007.github.io/images/BACKTESTING/BACKTESTING.png" style="width:95%;" alt="MACD Backtesting Chart" />

**Legend**:  
- Green/red bars = OHLC candles (price evolution)  
- Orange/blue lines = SMA(20) and SMA(10)  
- Dashed markers = trades (entries/exits)  
- Bottom panels = MACD and Signal line dynamics  

---

### 📈 Key Metrics  

Each backtest outputs a **performance summary** including:  
- **CAGR** (compound annual growth rate)  
- **Annualized volatility**  
- **Sharpe, Sortino, Calmar ratios**  
- **Maximum drawdown**  
- **Win rate & expectancy per trade**  
- **Profit factor (gross profit / gross loss)**  

Example (TSLA 2015–2024):  
- CAGR ≈ XX%  
- Sharpe ratio ≈ YY  
- Max drawdown ≈ ZZ%  
- Win rate ≈ ~50%  
- Profit factor ≈ ~2.0  

*(values depend on exact runs, commission settings, and long-only vs. long+short mode)*  

---

### 📚 Relation to the Literature  

This experiment replicates one of the **most studied technical rules in finance**.  

- **Brock, Lakonishok & LeBaron (1992)** showed that moving average and trading range break rules capture non-random structure in stock returns.  
- **Park & Irwin (2007)** surveyed 92 academic studies and found that rules like MACD are sometimes profitable, particularly in futures and FX markets.  

Thus, this project is not “reinventing the wheel”—it is a **practical reimplementation** of well-known research strategies, extended to modern data and tools.  

---

### 🧠 Why It Matters  

This kind of exercise is important for three reasons:  

1. **Educational**: it teaches how to structure systematic strategies and avoid common pitfalls (look-ahead bias, overfitting, ignoring costs).  
2. **Practical**: even if simple rules are not “alpha generators” today, they provide a baseline for testing more complex methods.  
3. **Research-oriented**: it directly connects academic finance literature with hands-on coding and visualization.  

---

### 🏷️ Tags  

`#Backtesting` `#QuantFinance` `#Python` `#MACD` `#SMA` `#TechnicalAnalysis` `#TradingStrategy` `#DataScience`  

---
