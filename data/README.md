# Trader Performance vs Market Sentiment

## Objective
This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid platform. The goal is to uncover actionable insights that can inform sentiment-aware trading strategies.

---

## Datasets
1. Bitcoin Market Sentiment (Fear & Greed Index)
   - Columns: Date, Classification (Fear / Greed)

2. Hyperliquid Historical Trader Data
   - Trade-level data including account, side, size, leverage, execution price, and closedPnL

---

## Methodology
1. Loaded and cleaned both datasets
2. Converted timestamps and aligned data at daily granularity
3. Engineered key metrics:
   - Daily PnL per trader
   - Win rate
   - Trade frequency
   - Average leverage and trade size
   - Long/Short ratio
4. Compared trader behavior and performance across Fear vs Greed days
5. Segmented traders by leverage, frequency, and consistency
6. Derived actionable strategy recommendations

---

## Key Insights
- Traders increase leverage and trade frequency during Greed days, leading to higher volatility.
- Fear days show more controlled behavior but reduced profitability.
- Consistently profitable traders reduce leverage during Fear periods, indicating superior risk management.

---

## Strategy Recommendations
- During Fear days, reduce leverage and focus on fewer high-confidence trades.
- During Greed days, increased trading activity should be limited to experienced and consistently profitable traders.

---

## How to Run
1. Clone the repository
2. Install dependencies:

