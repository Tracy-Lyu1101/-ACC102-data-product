# Project Title
**Notebook Link**
https://github.com/Tracy-Lyu1101/-ACC102-data-product/blob/main/2473591_Yuxi.Lv_ACC102_track2.ipynb
## 1. Problem & User
- This project systematically compares the stock return performance and risk characteristics between Apple Inc. and Microsoft Corporation from 2019 to 2026. It targets business students and individual retail investors who want data-driven insights on US tech stock investment.
## 2. Data (source + access date + key fields)
- Data Source：Kaggle Open Dataset 
- Access Date: April 21, 2026
- Key Fields: Date, Open, High, Low, Close, Volume
## 3. Methods (main Python steps)
- Load raw CSV stock data and auto-detect valid price columns
- Clean data: convert date format, filter 2019–2026 period, remove missing values
- Calculate core financial indicators: daily return, cumulative return, annualized volatility, max drawdown
- Generate comparative visualizations for return and risk analysis
- Export cleaned data and plots
## 4. Key Findings (3–5 bullets)
- Apple achieves a higher cumulative total return (~520%) than Microsoft (~340%) over the full 2019–2026 cycle
- Both companies have similar annualized volatility, with maximum drawdown around 35%-40% during market crashes
- Microsoft shows more stable short-term daily return distribution, while Apple has stronger long-term growth elasticity
- Two stocks perform synchronously during COVID pandemic shock and post-pandemic recovery periods
## 5. How to run (optional but valuable)
- Install dependencies: `pip install pandas numpy matplotlib seaborn`
- Open and run all cells in `Stock_Analysis.ipynb`
- All data results and plots will be generated automatically
## 6. Product link / Demo
- Product link:
- github： https://github.com/Tracy-Lyu1101/-ACC102-data-product/tree/main
- notebook：https://github.com/Tracy-Lyu1101/-ACC102-data-product/blob/main/2473591_Yuxi.Lv_ACC102_track2.ipynb
## 7. Limitations & next steps
- Limitations: Analysis only uses historical price data, no company fundamental financial data or macroeconomic indicator analysis
- Next steps: Add company fundamental data analysis and macro indicator correlation research in future updates
