# 📊 Market Pulse: EDA of Nifty 50 Stocks

Explore the Indian stock market through data! This project performs Exploratory Data Analysis (EDA) on historical data of Nifty 50 stocks to uncover trends, correlations, and the impact of COVID-19.

---

## 🚀 Features
- 📈 Normalized price trends (2018–present)
- 📉 Pre-vs-Post COVID performance comparison
- 🔥 Correlation heatmap across 20 major companies
- 🧭 Exported CSV summaries for external use

---

## 🛠 Tools & Tech
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- yfinance (for fetching stock data)

---

## 📁 Project Structure
```bash
EDA-NIFTY50/
├── data/
│ ├── nifty50_prices.csv
│ ├── summary_statistics.csv
│ └── post_covid_changes.csv
├── visuals/
│ ├── normalized_prices.png
│ ├── correlation_heatmap.png
│ └── post_covid_performance.png
├── notebook/
│ └── EDA-NIFTY50.ipynb
├── requirements.txt
└── README.md
```

---

## 🧠 Key Insights
- Not all Nifty stocks rebounded equally post-COVID.
- Tech & FMCG sectors showed strong recovery.
- Several banks were highly correlated in their price movements.

---

## ▶️ Run the Project

1. Clone the repo
```bash
git clone https://github.com/Ex-cute02/EDA-NIFTY50.git
cd EDA-NIFTY50
```
2. Install dependencies
```python
pip install -r requirements.txt
```
3. Run the notebook
```bash
jupyter notebook notebook/EDA-NIFTY50.ipynb
```
## Support

For any issues or inquiries, please [open an issue](https://github.com/Ex-cute02/EDA-NIFTY50/issues) in the GitHub repository.
