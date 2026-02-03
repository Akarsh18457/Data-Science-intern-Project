# Executive Summary — Trader Performance vs Market Sentiment

## Objective  
This analysis examines how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on Hyperliquid. By aligning daily trader metrics with sentiment regimes, we identify behavioral shifts, performance differences, and actionable strategy insights.

---

## Methodology  
- Merged daily Bitcoin Fear/Greed sentiment data with Hyperliquid trade-level data.
- Aggregated metrics at the trader-day level, including:
  - Daily PnL and win rate  
  - Trade frequency  
  - Average leverage and position size  
  - Long/short ratio  
  - PnL volatility as a drawdown proxy
- Conducted trader segmentation using behavioral and performance features.
- Supported findings with visual evidence (boxplots, bar charts, and summary tables).

---

## Key Findings

### 1. Performance Differs Significantly by Sentiment
- **Greed days** are associated with higher and more stable daily PnL and win rates.
- **Fear days** show significantly higher PnL volatility, indicating larger drawdowns.
- Overall trader performance deteriorates during Fear regimes due to increased risk and inconsistency.

**Evidence:** Daily PnL boxplots and PnL volatility comparisons across sentiment regimes.

---

### 2. Trader Behavior Changes with Market Sentiment
- **Trade Frequency:** Higher during Greed days; reduced participation during Fear.
- **Leverage:** Average leverage increases during Fear days, particularly among aggressive traders.
- **Positioning:** Greed regimes exhibit stronger long bias and larger average position sizes.

These patterns indicate elevated risk-taking during Fear despite weaker performance outcomes.

**Evidence:** Trade frequency bar charts, leverage distribution plots, and long/short ratio summaries.

---

### 3. Distinct Trader Segments Show Different Sensitivities

**Segment 1 — High-Leverage Traders**  
- High volatility and largest drawdowns, especially during Fear regimes.

**Segment 2 — Frequent Traders**  
- Perform well during Greed regimes but lose edge during Fear due to overtrading.

**Segment 3 — Consistent Winners**  
- Lower leverage, stable win rates, and best risk-adjusted performance across all regimes.

**Evidence:** Segment-level performance and volatility summary tables.

---

## Strategy Ideas

1. **Risk Control During Fear**  
   Elevated leverage during Fear increases drawdowns without improving returns.  
   **Rule:** Cap leverage or reduce exposure for high-risk trader segments during Fear regimes.

2. **Selective Aggression During Greed**  
   Increased trade frequency improves performance only for historically consistent traders.  
   **Rule:** Allow higher activity during Greed regimes selectively for disciplined traders.

---

## Final Takeaway  
Market sentiment materially impacts both trader behavior and performance. Adaptive strategies that adjust leverage and trading activity based on sentiment and trader archetype can meaningfully improve returns while reducing downside risk.
