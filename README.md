
# Web3 Trading Team – Data Science Assignment

## 📌 Overview
This project analyzes the relationship between **trader behavior** and **market sentiment** (Fear & Greed Index) in the context of Web3 trading.  
It uses:
- **Fear & Greed Index** data
- **Historical Trader Data** from Hyperliquid

The goal is to uncover **patterns, correlations, and actionable insights** that could inform smarter trading strategies.

---

## 📂 Project Structure
ds_vishnu_vardhan/
├── notebook_1.ipynb # Main analysis notebook (Google Colab compatible)
├── notebook_2.ipynb # Optional / extended analysis notebook
├── csv_files/
│ ├── merged_fg_trader.csv # Merged dataset (Fear & Greed + Trader Data)
│ ├── merged_fg_trader_processed.csv # Cleaned dataset with derived metrics
├── outputs/
│ ├── score_vs_trades_time.png
│ ├── score_vs_avg_closed_pnl.png
│ ├── score_vs_total_volume.png
│ ├── win_rate_time.png
│ ├── correlation_matrix.png
│ └── (other generated plots)
├── web3-data-science-report.pdf # PDF report with findings and plots
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🛠️ Data Sources
1. **Fear & Greed Index**  
   - Columns: `Date`, `Score`, `Classification` (Extreme Fear → Extreme Greed)

2. **Historical Trader Data (Hyperliquid)**  
   - Columns include: `Account`, `Coin`, `Execution Price`, `Size USD`, `Side`, `Timestamp IST`,  
     `Start Position`, `Direction`, `Closed PnL`, `Fee`, `Trade ID`, etc.

---

## 📊 Key Metrics Analyzed
- **Score** (0–100) – Market sentiment level
- **Trades Count** – Number of trades per day
- **Total Volume (USD)** – Sum of trade sizes per day
- **Average Closed PnL** – Mean profitability per day
- **Win Rate** – Ratio of profitable trades per day
- **Average Trade Size (USD)**

---

## 📈 Visualizations
Generated plots in `/outputs` include:
- **Fear & Greed Score vs Trades Count (Time Series)**
- **Score vs Average Closed PnL**
- **Score vs Total Volume**
- **Win Rate Over Time**
- **Correlation Matrix** of metrics

---

## 📑 Report
The **[PDF Report](./web3-data-science-report.pdf)** summarizes:
- Data cleaning steps
- EDA findings
- Correlation analysis
- Key observations and insights
- Potential implications for trading strategy

---

## ▶️ How to Run
### Option 1: Google Colab
1. Clone the repository:
   ```bash
   git clone https://github.com/VISHNU-VARDHAN-MAMIDISETTI1/Web3-Trading-Team-Data-Science-Assignment.git
Open notebook_1.ipynb in Google Colab.

Run all cells to reproduce preprocessing, analysis, and plots.

Option 2: Local Python Environment
Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn fpdf
Run analysis:

bash
Copy
Edit
jupyter notebook notebook_1.ipynb
📬 Contact
Author: Vishnu Vardhan Mamidisetti
LinkedIn | GitHub
