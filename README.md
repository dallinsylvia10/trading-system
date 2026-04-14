# 📈 Trading System — BTCUSD AI Signal

> A complete personal trading system built with TradingView Pine Script v5.
> Includes a custom AI indicator, trading journal, and a step-by-step roadmap from paper trading to a live funded account.

-----

## 🗂 What’s In This Repo

|File                       |Description                                                   |
|---------------------------|--------------------------------------------------------------|
|`AI_Trading_Indicator.pine`|Pine Script v5 indicator — BUY/SELL signals with dynamic SL/TP|
|`indicator_guide.html`     |Visual guide explaining how to read every signal              |
|`trading_roadmap.html`     |Step-by-step roadmap from paper trading to live account       |

-----

## 🤖 The Indicator

**AI Smart Signal [Buy/Sell + SL/TP]** is a multi-confluence indicator that only fires when 4 conditions align simultaneously:

1. **EMA Crossover** — Fast EMA (21) crosses Slow EMA (50)
1. **MACD Cross** — MACD line crosses Signal line in the same direction
1. **RSI Confirmation** — RSI between 40–65 on buys, 35–60 on sells
1. **200 EMA Trend Filter** — Only buys above the 200 EMA, only sells below it

### SL/TP Formula

```
BUY  → Stop Loss  = Entry - (ATR × 1.5)
BUY  → Take Profit = Entry + (ATR × 2.5)

SELL → Stop Loss  = Entry + (ATR × 1.5)
SELL → Take Profit = Entry - (ATR × 2.5)
```

### How to Install

1. Open TradingView → Pine Script Editor
1. Delete existing code and paste contents of `AI_Trading_Indicator.pine`
1. Click **Add to chart**
1. Right-click indicator → **Add Alert** for BUY and SELL notifications

### Recommended Settings

|Timeframe|SL Multiplier|TP Multiplier|
|---------|-------------|-------------|
|1H       |1.5          |2.5          |
|4H       |1.5          |3.0          |
|15M      |1.2          |2.0          |
|Daily    |2.0          |4.0          |

-----

## 🗺 The Roadmap

|Phase               |Goal                                      |Timeline |
|--------------------|------------------------------------------|---------|
|1 — Learn the System|Understand every signal, log 10 trades    |Week 1–2 |
|2 — Build a Record  |30 paper trades, 45%+ win rate            |Week 2–4 |
|3 — Risk Management |Master 1% rule and position sizing        |Week 3–5 |
|4 — Simulate Live   |Grow a $500 paper account by 10%          |Week 5–8 |
|5 — Go Live         |Fund real account, start small, protect it|Month 2–3|

👉 [View Full Interactive Roadmap](https://dallinsylvia10.github.io/trading-system/trading_roadmap.html)

-----

## 📋 Trading Rules — Never Break These

- 🚫 **No signal = no trade.** If there’s no arrow, you wait.
- 🚫 **Never move your stop loss** once it’s set.
- 🚫 **Max 1% risk per trade** — always calculate position size first.
- 🚫 **No revenge trading** — step away after a loss.
- ✅ **Journal every single trade** — wins, losses, and skipped signals.
- ✅ **Trust the system** — give it 50 trades before changing any settings.

-----

## 📊 My Progress

|Metric           |Value         |
|-----------------|--------------|
|Started          |April 14, 2026|
|Current Phase    |Phase 1       |
|Paper Trades     |1             |
|Win Rate         |100% (1/1)    |
|Total P&L (Paper)|+$60.62       |
|Live Account     |Not yet       |


> Update this table as you progress!

-----

## 🔗 Links

- 📖 [Indicator Guide](https://dallinsylvia10.github.io/trading-system/indicator_guide.html)
- 🗺 [Trading Roadmap](https://dallinsylvia10.github.io/trading-system/trading_roadmap.html)
- 📺 [TradingView Profile](https://www.tradingview.com)

-----

*Built with Claude AI · Started April 2026*
