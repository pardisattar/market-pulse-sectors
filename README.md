# Market Pulse — Sector Risk/Return & Correlation (2005–present)

Beginner-friendly data science project comparing stock market **sectors**:
- Fetch daily prices via **yfinance** (Yahoo Finance).
- Compute **log returns**, **rolling volatility**, **Sharpe**, **drawdown**.
- Visualize **cumulative returns** and **correlation heatmap**.

## Why this project?
- Real data from financial markets.
- Clear skills: Python, pandas/numpy, matplotlib, API data, scientific computing, plotting.
- Matches my course rubric (GitHub usage, project organization, input/output, data manipulation, scientific computing, visualization).

## Data source
SPDR sector ETFs via yfinance: `XLF, XLK, XLE, XLY, XLI, XLU, XLV, XLB, XLRE, XLC` and `SPY` (benchmark).  
Date range: 2005-01-01 → today.

## How this repo will be organized
market-pulse-sectors/
│ README.md
│ requirements.txt
│ run.py
│ .gitignore
├─ data/
│ ├─ raw/ # (gitignored)
│ └─ processed/ # (gitignored)
├─ notebooks/
│ 01_eda.ipynb
│ 02_features.ipynb
│ 03_analysis.ipynb
└─ src/
├─ config.py
├─ io_utils.py
├─ finance.py
├─ features.py
└─ viz.py
*(Folders will appear as we add files.)*

## Next steps (for me)
1) Set up folders and empty files.
2) Open **Codespaces** (runs in the browser) to execute Python.
3) Fetch data, compute metrics, make plots, write results.
