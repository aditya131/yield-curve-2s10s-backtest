Yield Curve 2s10s Steepener Backtest

📌 Overview
A simple statistical backtest of a 2s10s yield curve steepener strategy using U.S. Treasury futures. The strategy relies on z-score thresholds, DV01 scaling, and curve slope dynamics.

🛠️ Methodology
- Constructed 2s10s curve using front SOFR futures
- Calculated z-scores of slope
- Entered steepener/flatteners based on thresholds
- Scaled position based on DV01
- PnL backtested over historical futures prices

📈 Output
- Performance metrics (cumulative PnL, Sharpe)
- Z-score plots and trade entry/exit visuals

📂 Files
- `2s10s.ipynb`: Main notebook with full strategy
- `2s10s_data/`: Sample or placeholder data

✅ Requirements
```bash
pandas
numpy
matplotlib
scipy
