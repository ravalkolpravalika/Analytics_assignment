# Trader Performance vs Market Sentiment - Hyperliquid × Fear/Greed Index

Analyzing how Bitcoin market sentiment (Fear/Greed) affects trader behavior and performance on Hyperliquid.

## Datasets
- `historical_data.csv` — 211,224 trades across 32 accounts (May 2023 – May 2025) from Hyperliquid
- `fear_greed_index.csv` — Daily Bitcoin Fear/Greed index values

## What I looked at
- Does PnL and win rate differ on Fear vs Greed days?
- Do traders change their long/short bias based on sentiment?
- Which trader segments perform consistently?

## Key Findings
- Win rate is highest on Fear days (84.4%) vs Greed days (82.5%)
- Traders open 1.77x more longs on Fear days — and it works
- On Greed days, fewer trades win but position sizes are larger (riskier pattern)
