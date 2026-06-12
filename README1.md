# 📊 Operational Metrics Dashboard — Google Sheets

![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Data Cleaning](https://img.shields.io/badge/Data%20Cleaning-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot%20Tables-0F9D58?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Interactive%20Dashboard-FBBC04?style=for-the-badge)
![ABC Analysis](https://img.shields.io/badge/ABC%20Analysis-EA4335?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

End-to-end sales analytics project built entirely in **Google Sheets**: from raw data cleaning to an interactive dashboard with strategic business recommendations.

> ⚙️ The focus of this project was a **lightweight cleaning approach** — records with missing values were removed rather than imputed, keeping the dataset strictly verified and analysis-ready.

---

## 🔗 Live Project

👉 [**Open in Google Sheets**](https://docs.google.com/spreadsheets/d/1r4Pq5bu6bV9jP4pnMn5p0Bf2ODsB82l1WOIAdhnp6IE/edit?gid=1279352890#gid=1279352890)

---

## 🎯 Project Goals

- Clean and structure raw transactional sales data
- Calculate key business metrics (KPI)
- Analyze sales by category, geography, channel, and time
- Segment the product portfolio using ABC analysis
- Build an interactive dashboard for decision-making

---

## 🧹 Data Preparation

- Removed duplicates and records with missing values
- Standardized categorical fields (sales channel, country names)
- Enriched orders with reference data (products, countries, regions) via lookup functions
- Derived calculated fields: lead time, margin, revenue, cost, profit

**Tools used:** pivot tables, `QUERY`, `VLOOKUP` / `INDEX+MATCH`, `ARRAYFORMULA`, conditional formatting, data validation.

---

## 📈 Key Metrics (KPI)

| Metric | Value |
|---|---|
| 💰 Total Revenue | **$1,601,423,215** |
| 📈 Net Profit | **$474,107,477** |
| 🧾 Transactions | **1,248** |
| 🌍 Geography | **45 countries, 2 global regions** |
| 🛒 Average Order Value | **$1,283,192** |
| 📦 Product Categories | **12** |

---

## 🔍 Analysis Highlights

### 🛍️ Product Categories
- **Top sellers by volume:** Beverages, Office Supplies, Clothes
- **Revenue leaders:** Office Supplies, Household
- **Most profitable:** Cosmetics, Office Supplies, Meat
- **Highest margin:** Clothes (~67% profitability)
- **Underperformer:** Cereal — lowest results across all metrics

### 🌍 Geography
- **Europe generates ~94% of total profit**; Asia is the secondary region
- Top contributing countries: **Ukraine, Hungary, Czech Republic**
- Leading sub-regions by revenue: **Southern & Eastern Europe**

### 🛒 Sales Channels (Online vs Offline)
- **Offline:** largest orders in Household and Office Supplies
- **Online:** key channel for Cosmetics, Clothes, and Snacks

### 🚚 Lead Time
- Shipment times range from **1 to 50 days** regardless of category or distance
- Bottleneck identified at the **warehouse assembly stage**, not transportation
- No correlation found between profit and lead time

### 📅 Seasonality & Weekly Patterns
- **Peak months:** March, July, December
- **Slump months:** August–October → recommended window for inventory checks and demand-stimulating promos
- **Most active days:** Monday ("accumulated demand"), Saturday & Sunday ("family shopping")

---

## 🧮 ABC Analysis of the Product Portfolio

| Group | Categories | Strategy |
|---|---|---|
| 🥇 **AAA** | Cosmetics, Office Supplies, Meat | Maximum assortment, priority shipping, loyalty programs |
| 🥈 **ABA / AAB** | Household, Snacks | Stock optimization for Household; automated processing for Snacks |
| ⚠️ **CCC / CAC** | Cereal, Fruits, Beverages | Cost & logistics optimization; investigate Cereal's slump |

---

## 💡 Business Recommendations

1. **Optimize "C" categories** — raise prices or cut logistics costs for Fruits and Beverages (high volume, low profit).
2. **Protect the leaders** — maintain Cosmetics as the primary margin source.
3. **Investigate Cereal** — research the reasons behind the category's temporary drop to group "C" despite strong historical efficiency.
4. **Use the seasonal slump** (late summer – early autumn) for inventory audits and promotional campaigns.

---

## 🗂️ Workbook Structure

| Sheet | Purpose |
|---|---|
| `Primary Events` | Raw transactional data |
| `Events Clear` | Cleaned, analysis-ready dataset |
| `Products` / `Countries` | Reference tables |
| `Key Metrics` | KPI calculations |
| `Categories info` | Category-level analysis |
| `Geography` | Country / region / sub-region breakdown |
| `Sales Channel` | Online vs Offline comparison |
| `Lead Time` | Order-to-shipment analysis |
| `Profit by Geo` / `Sales Trend` | Yearly & monthly dynamics |
| `Weekday Trend` | Day-of-week patterns |
| `ABC` | Portfolio segmentation |
| `Dashboard` | Interactive summary dashboard |

---

## 🛠️ Tech Stack

`Google Sheets` · `Pivot Tables` · `QUERY` · `ARRAYFORMULA` · `VLOOKUP / INDEX+MATCH` · `Conditional Formatting` · `Charts & Dashboards`

---

## 👤 Author

**Maxim Pogorelskiy** — Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](http://www.linkedin.com/in/blizzardheart)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/maxim.pogorelskiy/vizzes)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:Pogorelskiymaxim@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)](http://t.me/EventFunMax)
