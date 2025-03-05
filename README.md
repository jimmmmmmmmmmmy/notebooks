# Financial Analysis Notebooks

This repository contains some of my Python notebooks for financial market analysis.
Dependencies: `pandas`, `numpy`, and `matplotlib`.

---

## Notebooks

### 1. S&P 500 Returns Analysis
- Analyzes historical S&P 500 annual returns.
- Features:
  - Histograms of returns for periods: 1871-2024, 1976-2024, 1954-2024.
  - 1871: Start of Cowles' Commission data on SPX
  - 1954: Start of Standard's and Poor's 500 Index
  - 1976: Start of when the SPX was actually buyable in the form of Vanguard's First Index Investment Trust
  - Box plots of returns over four years post-decline.
  - Table of decline events with recovery stats.
- Data from [S&P 500 Historical Data](https://finance.yahoo.com/quote/%5EGSPC/history/)

### 2. Relative Strength Index & 1-Day Returns on the S&P
- Examines next-day returns after extreme RSI readings (<20 oversold, >80 overbought).
- At some point in the 1980's the index became mean reverting
- Data from 'CSV/SPX_RSI_2.csv'

### 3. Headline Event Straddles / Analysis
- Analyzes price reactions and straddles pricing for economic events (e.g., ISM Manufacturing PMI).
- Data from 'NQ_QQQ_ATR.csv', 'QQQ_options_data.csv'

---

*Updated: March 04, 2025*
