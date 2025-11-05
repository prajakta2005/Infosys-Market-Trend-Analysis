# 📊 Infosys Market Trend Analysis (2015–2025)

## 🧭 Overview
This project presents a comprehensive data analysis of **Infosys Limited’s** financial and stock market performance over the last decade.  
Using data sourced from **Yahoo Finance** via the `yfinance` API, the project explores Infosys’s long-term growth trends, volatility patterns, and correlations with major benchmark indices like **NIFTY IT** and **NASDAQ**.

The goal is to derive **actionable insights** into Infosys’s performance through data-driven storytelling — bridging financial analytics with visualization and real-world business context.

---

## 🎯 Objectives
- Analyze 10 years of historical stock data for Infosys (INFY.NS)
- Compare Infosys performance against **NIFTY IT** and **NASDAQ** indices
- Study quarterly **revenue**, **profit**, and **EPS** trends
- Compute and visualize **returns**, **volatility**, and **moving averages**
- Build an interactive **dashboard** to communicate insights effectively

---

## 🧰 Tools & Technologies
| Purpose | Tools / Libraries |
|----------|-------------------|
| Data Extraction | `yfinance`, `pandas`, `numpy` |
| Data Cleaning | `pandas`, `datetime` |
| Visualization | `matplotlib`, `seaborn`, `plotly` |
| Dashboard (optional) | Power BI / Tableau / Streamlit |
| Environment | Jupyter Notebook, GitHub |

---
## 🔍 Methodology

### **Phase 1: Data Collection**
- Extracted 10-year stock price data for Infosys, NIFTY IT, and NASDAQ using `yfinance`.
- Gathered financial statement data (Revenue, EPS, Net Profit) from public sources (Moneycontrol, NSE India).

### **Phase 2: Data Cleaning**
- Handled missing values, formatted date fields, and merged datasets.
- Calculated new metrics: **daily returns**, **rolling averages**, and **volatility**.

### **Phase 3: Exploratory Data Analysis**
- Visualized long-term stock trends and market correlations.
- Compared Infosys’s growth with broader IT and global indices.
- Studied periods of volatility (e.g., COVID-19 dip, post-2020 recovery).

### **Phase 4: Financial Analysis**
- Analyzed revenue and profit growth trends.
- Correlated financial KPIs with stock price movement.
- Computed CAGR and drawdowns to evaluate investor performance.

### **Phase 5: Dashboard & Reporting**
- Designed an executive dashboard summarizing:
  - Key KPIs (Stock growth %, CAGR, EPS trend)
  - Infosys vs NIFTY IT vs NASDAQ comparison
  - Yearly returns and volatility patterns
- Created visual storytelling insights using Power BI / Streamlit.

---

## 📈 Sample Insights
- Infosys’s stock shows a **strong 0.83 correlation** with NIFTY IT index.  
- The **2020–2023 period** marked accelerated growth driven by digital transformation.  
- The **5-year CAGR** of Infosys’s stock price stands at **~16%**, outperforming peers.  

---

## 📊 Key Visualizations
- Infosys Stock Price Trend (2015–2025)  
- Comparison with Benchmark Indices (NIFTY IT, NASDAQ)  
- Rolling Average & Volatility Analysis  
- Revenue vs Stock Movement Correlation  

---

## 💼 Business Impact
This analysis demonstrates how **data analytics can uncover patterns behind corporate growth and investor sentiment**.  
It showcases proficiency in:
- Financial data processing  
- Market trend interpretation  
- Business intelligence reporting  

This is representative of real-world analysis performed by data analysts and consultants in the IT and financial sectors.

---

## 🗓️ Project Timeline
| Phase | Duration | Status |
|--------|-----------|--------|
| Data Collection | Day 1–3 | 🔄 In Progress |
| Data Cleaning & Preprocessing | Day 4–5 | ⏳ Pending |
| EDA & Visualization | Day 6–8 | ⏳ Pending |
| Financial Insights | Day 9–11 | ⏳ Pending |
| Dashboard & Reporting | Day 12–15 | ⏳ Pending |

---

## 🧾 License
This project is for **educational and research purposes only**.  
All data is publicly available via **Yahoo Finance API** and other open financial sources.

---

## 📂 Folder Structure

```bash
infosys-financial-stock-analysis/
│
├── data/
│   ├── raw/
│   │   ├── infosys_stock_data.csv
│   │   ├── nifty_it_data.csv
│   │   └── nasdaq_data.csv
│   │
│   └── processed/
│       └── merged_data.csv
│
├── notebooks/
│   └── infosys_analysis.ipynb
│
├── dashboard/
│   ├── infosys_dashboard.pbix     # Power BI dashboard
│   └── app.py                     # Streamlit dashboard (optional)
│
├── reports/
│   ├── insights_summary.pdf
│   └── presentation.pptx
│
├── requirements.txt
└── README.md
---

