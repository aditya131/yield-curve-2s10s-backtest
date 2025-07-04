# Yield Curve 2s10s Steepener Strategy

## 📌 Overview
This strategy backtests 2s10s curve trades using interpolated yield data for 2-year and 10-year Treasury points. The strategy uses z-score signals for entry/exit and scales exposure by DV01.

## 📈 Methodology
- Construct the 2s10s curve using yield data for 2-year and 10-year Treasury points 
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

pip install pandas numpy matplotlib scipy

## 👤 Author

**Aditya Agarwal**  
Quantitative trader exploring fixed income and equity strategies
[LinkedIn](https://www.linkedin.com/in/aditya3005) | [Email](adityaagarwal3000@gmail.com)
