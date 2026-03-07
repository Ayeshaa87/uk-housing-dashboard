# uk-housing-dashboard
Interactive Power BI dashboard analyzing UK housing prices, YoY growth, and transaction volume (2022–2025).
# 🏠 UK Housing Market Dashboard (2022–2025)

> **Analysing price trends, market corrections, and transaction behaviour across the UK housing market using Power BI and DAX.**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![CSV](https://img.shields.io/badge/Data-CSV-green?style=for-the-badge)

---

## 📌 Project Summary

The UK housing market went through dramatic shifts between 2022 and 2025 — a post-pandemic boom, rising interest rates, and a notable price correction in 2025. This project builds an end-to-end interactive Power BI dashboard to visualise and quantify those changes, uncovering key patterns in price movement, year-over-year growth, and transaction volume.

Built as part of my Data Analyst portfolio while studying Computer Science at university.

---

## 🔍 Key Findings

- 📈 **Housing prices peaked in 2024** following sustained post-pandemic demand
- 📉 **YoY growth turned negative in 2025** — the first market correction in the dataset
- 🔄 **Transaction volume declined alongside prices** — indicating reduced buyer confidence, not just seller-side pressure
- 🔮 **Forecast model suggests stabilisation** in late 2025, consistent with Bank of England rate hold signals

---

## 📊 Dashboard Features

| Feature | Description |
|---|---|
| **Executive KPI Cards** | Latest average price, YoY % change, total transactions at a glance |
| **Price Trend Chart** | Monthly average prices 2022–2025 with built-in forecast |
| **YoY Growth Analysis** | Month-by-month growth rate to pinpoint market turning points |
| **Transaction Volume Trends** | Buyer activity over time — leading indicator of market direction |
| **Interactive Year Slicer** | Filter all visuals dynamically by year |

---

## 🛠 Tools & Technologies

- **Power BI Desktop** — dashboard design, interactivity, and publishing
- **DAX (Data Analysis Expressions)** — custom KPI measures, YoY calculations, rolling averages
- **Time Series Forecasting** — built-in Power BI forecast with confidence intervals
- **Data Cleaning & Transformation** — Power Query for handling nulls, date formatting, aggregation

---

## 📂 Repository Structure

```
uk-housing-dashboard/
│
├── UK_Housing_Dashboard.pbix   # Main Power BI dashboard file
├── monthly_avg.csv             # Processed monthly average house price data
├── monthly_volume.csv          # Processed monthly transaction volume data
└── README.md                   # You are here
```

---

## 🚀 How to Run

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `UK_Housing_Dashboard.pbix` in Power BI Desktop
4. All data is embedded — no additional setup needed

---

## 💡 What I Learned

- Writing DAX measures for time-intelligence calculations (YoY, MTD, rolling averages)
- Designing dashboards for non-technical audiences — clarity over complexity
- How transaction volume often *leads* price changes by 1–2 months (a key market signal)
- Translating raw CSV data into a narrative a business stakeholder can act on

---

## 👤 Author
**Ayesha Irfan**  
Computer Science Student | Placement Year Candidate | Aspiring Data Analyst  

[LinkedIn](https://www.linkedin.com/in/ayesha-irfan-1093b428a/)  
[GitHub](https://github.com/Ayesha87)
