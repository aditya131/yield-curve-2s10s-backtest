# Yield Curve 2s10s Steepener Strategy

## 📌 Overview
This project backtests a yield curve steepener/flattener strategy using the 2s10s slope constructed from front SOFR futures. The strategy uses z-score signals for entry/exit and scales exposure by DV01.

## 📈 Methodology
- Construct the 2s10s curve using front SOFR futures  
- Compute z-scores of the slope to trigger trades  
- Enter long (steepener) or short (flattener) positions based on threshold crossings  
- Scale trade exposure dynamically using DV01  
- Generate cumulative PnL and Sharpe ratio  
- Plot strategy signals, slope evolution, and performance

## 🗂 Files
- `2s10s.ipynb`: Main backtest notebook  
- `2s10s_with_macro.ipynb`: Extended version with macro overlay  
- `2s10s_data.csv`: Historical 2s10s slope data  
- `README.md`: This file

## 🛠 Requirements & Setup
First, install the required packages:

```bash
pip install pandas numpy matplotlib scipy
