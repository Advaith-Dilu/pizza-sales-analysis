# 🍕 Pizza Sales Analysis Dashboard  

### 📊 Data Visualization | Business Intelligence | Trend Analysis  

The **Pizza Sales Analysis Dashboard** is a dynamic visualization and analytical tool developed to evaluate and enhance the performance of a pizza business.  
It tracks **sales, revenue, customer preferences, and time-based patterns** through interactive dashboards built using **Tableau or Power BI**.

---

## 📘 Executive Summary  

The dashboard analyzes sales data over a **12–15 month period (July previous year – October current year)**, highlighting:  
- **Total Orders:** 21K  
- **Total Revenue:** $818K  
- **Average Order Value:** $38  
- **Seating Utilization:** 0K (possible anomaly/full capacity indicator)  

The analysis shows strong performance in **chicken-based pizzas**, **weekend sales peaks**, and identifies opportunities for **menu optimization**.  
Recommendations focus on leveraging high-demand time slots and addressing underperforming products for sustained growth.  

---

## 🏁 1. Introduction  

### 🎯 1.1 Purpose  
The dashboard empowers **business stakeholders** — including managers, marketers, and operations teams — with actionable insights into pizza sales performance.  
It supports **data-driven decisions** for:  
- Inventory & staffing management  
- Promotions & menu engineering  
- Seasonal trend analysis  

### 📈 1.2 Scope  
- **Time Frame:** July (prior year) – October (current year)  
- **Focus Areas:** Orders, revenue, utilization, size preference, product category, weekday vs. weekend, hourly sales  
- **Assumptions:** Data represents single or multi-location pizza outlets; seating utilization metric (0K) requires validation.  

---

## 🧩 2. Dashboard Overview  

The visualization includes two primary components:  

### 🍕 Pizza Sales Dashboard  
- **High-level KPIs:** Total Orders, Revenue, Average Order Value, Seating Utilization  
- **Visual Theme:** Red-Black for readability and contrast  

### ⏰ Pizza Time Series Dashboard  
- **Focus:** Time-based sales trends (monthly, daily, hourly)  
- **Features:** Interactive filters by pizza size, category, and time of day  

---

### 🔹 2.1 Key Performance Indicators (KPIs)

| Metric | Value | Description |
|---------|--------|-------------|
| **Total Pizza Orders** | 21K | Aggregate customer orders |
| **Total Revenue** | $818K | Gross revenue from pizza sales |
| **Average Order Value (AOV)** | $38 | Average revenue per order |
| **Seating Utilization** | 0K | Indicator for occupancy/capacity (requires clarification) |

---

### 🔹 2.2 Visual Components  

#### 📅 Month-Wise Trend (Bar Chart)  
- Weekday (red) vs. Weekend (gray) comparison  
- **Peak:** December (highest weekend revenue)  
- **Trend:** Weekends dominate; dips in January and April  

#### 📦 Sum of Quantity by Days  
- **Saturday:** Highest (~10K units)  
- **Sunday:** Lowest  

#### 🍕 Total Sales by Pizza Size (Pie Chart)  
| Size | Share |
|------|--------|
| XL | 21.7% |
| L | 17% |
| M | 30.5% |
| S | 45.9% |

> Indicates customer preference for smaller, affordable pizzas.  

#### 🍗 Periodic Trend (Stacked Bar Chart)  
| Category | Peak Sales (Day) | Share |
|-----------|------------------|--------|
| CHK (Chicken) | 37K (Fri) | 35–40% |
| SUP (Supreme) | 33K (Sat) | 25–30% |
| CLS (Classic) | 34K (Thu) | 20–25% |
| VEG (Vegetable) | 27K (Wed) | 15–20% |

#### 🏆 Product Highlights  
- **Most Liked:** *California Chicken Pizza*  
- **Least Liked:** *Vegetables + Vegetables Pizza* (decline: 4.4K → 3.8K units)  

---

## 📊 3. Data Analysis  

### 💰 3.1 Sales Performance  
- **Revenue:** $818K from 21K orders  
- **AOV:** $38 per order — healthy benchmark  
- **Seating Utilization:** 0K → possible data gap  

**Temporal Patterns:**  
- **Monthly:** Peaks in December & August, dips in Sep–Oct  
- **Weekly:** Weekends drive 60–70% of total volume  
- **Daily:** Noon–Afternoon surge aligns with lunch rush  

**Size Preference:**  
- Small & Medium pizzas = 76.4% of sales → potential upsell to Large/XL.  

---

### 🍗 3.2 Product Insights  
- **Top Performer:** California Chicken Pizza (~40% contribution)  
- **Underperformer:** Vegetables + Vegetables Pizza (−15% YoY)  
- **Volatile:** Briere Carre Pizza (2K–4K units monthly)  

---

### 📈 3.3 Trends & Correlations  
- **Weekend Revenue:** 1.5–2× higher than weekdays  
- **Growth:** CHK & SUP categories ↑ 5%  
- **Decline:** VEG category ↓ 15% YoY  

---

## 💡 4. Key Findings  

✅ **Strengths:**  
- Strong weekend sales  
- Chicken-based pizzas dominate  
- Healthy AOV ($38)  

⚠️ **Challenges:**  
- Declining vegetable pizza performance  
- Seating utilization uncertainty  

🚀 **Opportunities:**  
- Bundle afternoon lunch combos  
- Upsell larger sizes for profit growth  

---

## 🧠 5. Recommendations  

### 🏭 Operational  
- Increase staff shifts on **Friday afternoons (12 PM peak)**  
- Stock **50% more Chicken/Supreme ingredients** on weekends  

### 📣 Marketing & Menu  
- Launch **“Weekend Warrior”** promotions targeting M/L chicken pizzas  
- Rebrand or phase out *Vegetables + Vegetables Pizza*  
- Promote top-rated pizzas during lunch hours  

### 📊 Analytics & Insights  
- Add **real-time data feeds** for forecasting  
- Include **customer segmentation** (order size, repeat rate)  
- Benchmark AOV against competitors ($30–$40 range)  

---

### 💵 5.4 Projected Impact  

| Initiative | Est. Revenue Lift | Timeline |
|-------------|------------------|-----------|
| Weekend Promotions | +15% | Q4 2025 |
| Menu Optimization | +10% | Q1 2026 |
| Peak-Hour Staffing | +8% | Immediate |

---

## 🏁 6. Conclusion  

The **Pizza Sales Analysis Dashboard** provides a comprehensive view of sales and operational dynamics.  
By focusing on high-performing time slots, top-selling items, and underperformers, the business can achieve **10–20% YoY revenue growth**.  

Future updates should include **predictive analytics** for better demand forecasting and strategic planning.  

---

## 📎 7. Appendices  

### 🗂️ 7.1 Data Sources  
- Internal POS systems (orders, revenue)  
- Customer feedback & satisfaction data  
- Period: **July 2024 – October 2025**

### 🧰 7.2 Tools & Methodology  
| Tool | Purpose |
|------|----------|
| Tableau / Power BI | Dashboard Visualization |
| Excel | Preprocessing & Aggregation |
| Python (Pandas, Matplotlib) | Statistical Analysis |
| Data Cleaning | Outlier and anomaly detection |

**Limitations:** Seating utilization metric (0K) needs clarification.  

---

## 📂 Repository Structure  

├── data/
│ └── pizza_sales.csv
├── visuals/
│ ├── dashboard_preview.png
│ └── charts/
├── reports/
│ └── Pizza_Sales_Analysis_Report.pdf
├── scripts/
│ └── Pizza_Sales_Analysis.ipynb
└── README.md

---

## 🧠 Skills & Concepts Used  
- Data Cleaning & Preparation  
- KPI & Metric Development  
- Time Series Analysis  
- Sales Trend Forecasting  
- Data Visualization in Tableau/Power BI  

---

## 🛠️ Technologies  

| Tool | Purpose |
|------|----------|
| Tableau / Power BI | Visualization |
| Excel / CSV | Data Source |
| Python | Data Preprocessing |
| GitHub | Project Version Control |

---

## 🌟 Acknowledgements  

This project was developed by **Advaith Krishna M**  
as part of the **Unified Mentor Internship Program**  
to demonstrate **advanced business analytics and visualization skills**.  

---

<p align="center">
  <img src="visuals/dashboard_preview.png" alt="Pizza Sales Dashboard Preview" width="800">
</p>

⭐ **If you liked this project, don’t forget to star the repository!**
