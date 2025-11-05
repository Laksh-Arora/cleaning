📈 NVIDIA Stock Analysis & Price Forecasting
🔍 Project Overview

This project analyzes the historical performance of NVIDIA Corporation (NVDA) to understand its risk–return profile, market behavior, and potential future price trajectory.
The analysis combines financial concepts with data-driven techniques to evaluate NVDA’s stock performance over the selected period.

🧠 Objectives

Evaluate NVIDIA’s historical stock performance and volatility

Compare returns vs. the market benchmark (e.g., S&P 500 / NASDAQ)

Calculate key risk metrics and understand NVIDIA’s risk profile

Analyze drawdowns to assess downside risk

Forecast future price scenarios using a simulation-based approach

🧰 Tools & Technologies Used
Category	Tools
Data Source	yfinance API
Analysis	Python, Pandas, NumPy
Visualization	Matplotlib, Seaborn
Environment	Jupyter Notebook
📊 Key Analysis Performed

✅ Historical Price Trends & Returns

Downloaded and cleaned NVDA stock data

Computed daily, monthly, and annual returns

✅ Risk & Performance Metrics

Annualized Return

Annual Volatility

Sharpe Ratio (risk-adjusted return)

Beta vs. Market Index

Maximum Drawdown

✅ Rolling Metrics

90-day rolling returns

90-day rolling volatility

(Optional) 90-day rolling Sharpe

✅ Future Price Projection (Forecasting)

Used a Monte Carlo or GBM-style simulation to model possible 1-year price outcomes

Generated P10, P50 (Median), and P90 scenarios

Visualized projected range using confidence bands

📂 Project Structure
📁 NVIDIA-Stock-Analysis
│
├── NVIDIA_Stock_Analysis.ipynb   # Main analysis notebook
├── data/                          # Cleaned datasets (optional)
│   ├── nvda_prices.csv
│   └── nvda_metrics.csv
├── images/                        # Charts & visualizations (optional)
├── README.md                      # Project documentation

🧾 How to Use This Notebook

Clone the repository or download the notebook

Install the required libraries:

pip install yfinance pandas numpy matplotlib seaborn


Open the .ipynb file in Jupyter Notebook or VS Code

Run the cells in sequence to reproduce results

📈 Sample Insights to Highlight (replace with your actual findings)

NVIDIA delivered a CAGR of ~X% over the past 5 years, significantly outperforming the benchmark index.
While volatility remains higher due to growth-stock behavior, Sharpe ratio indicates strong risk-adjusted performance.
Forward projections indicate the stock could trade within the $Y – $Z range under most simulated paths (P10–P90 band).

⚠️ Disclaimer

This project is for academic and learning purposes only.
It is not financial or investment advice.
