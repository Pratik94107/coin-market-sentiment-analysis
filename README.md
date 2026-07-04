# Coin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical trading data.

The objective is to identify whether market sentiment influences trading behavior, profitability, trading volume, and overall trader performance.

---

## Datasets

### 1. Fear & Greed Index
fear_greed_index.csv
  
- Date
- Classification (Fear / Greed)


### 2. Hyperliquid Historical Trading Data
historical_data.csv
  
- Account
- Coin
- Side
- Execution Price
- Size Tokens
- Size USD
- Closed PnL
- Fee
- Timestamp
- Direction
- etc.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

1. Load both datasets
2. Data Cleaning
3. Date preprocessing
4. Merge datasets using Date
5. Exploratory Data Analysis
6. Visualization
7. Trading insights

---

## Analysis Performed

- Data Cleaning
- Missing Value Analysis
- Fear vs Greed Distribution
- Profit Analysis
- Win Rate Analysis
- Trading Volume Analysis
- Coin-wise Profit
- Buy vs Sell Analysis
- Fee Analysis
- Top Traders
- Loss Making Traders
- Daily Profit Trend
- Hour-wise Trading Activity
- Correlation Analysis

---

## Key Findings

- Market sentiment affects trader behavior.
- Trading volume changes across Fear and Greed periods.
- Profitability varies with market sentiment.
- A small number of traders contribute most of the total profit.
- Trading activity is concentrated in a limited number of coins.

---

## Project Structure

```
Bitcoin-Sentiment-Analysis/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── analysis.ipynb
├── README.md
└── requirements.txt
```

---

## How to Run

Clone the repository

```bash
git clone <repository-url>
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
jupyter notebook
```

Open

```
analysis.ipynb
```

---

## Author

Pratik
