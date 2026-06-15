# Customer Shopping Behaviour Analysis

An end-to-end corporate-grade analytics workflow demonstrating the ability to collect, validate, analyse, and visualise customer data to produce strategic business intelligence.

---

## 📌 Business Problem

A retail business needed to understand **who its most valuable customers are**, **what drives repeat purchases**, and **which product categories and demographics generate the most revenue** — in order to optimise marketing spend and inventory planning.

---

## 🗃️ Dataset

- **Source:** Simulated retail customer transaction dataset
- **Records:** 3,900 customer transactions
- **Key fields:** Customer ID, Age, Gender, Purchase Amount, Product Category, Season, Subscription Status, Payment Method, Review Rating, Frequency of Purchase

---

## 🔧 Workflow & Tools

| Stage | Tool | Purpose |
|---|---|---|
| Data preparation & EDA | Python (Pandas, Seaborn, Matplotlib) | Clean, transform, and explore raw data |
| Business queries | SQL | Extract segment-level insights and KPIs |
| Dashboard & reporting | Power BI | Interactive KPI dashboard for stakeholders |
| Documentation | PDF | Business problem definition and findings report |

---

## 📊 Key Findings

### 1. Customer Segmentation
- **Female customers aged 25–34** accounted for the highest share of total purchase value, contributing approximately **38% of revenue** despite representing 29% of the customer base.
- Customers with active **subscription status** spent on average **22% more** per transaction than non-subscribers.

### 2. Purchase Drivers & Loyalty
- **Clothing and accessories** were the top-performing categories by volume, while **outerwear** generated the highest average transaction value.
- Customers who rated their experience **4 stars and above** showed a **3× higher repeat purchase frequency** compared to lower-rated cohorts — indicating that service quality is a strong loyalty predictor.

### 3. Seasonal Trends
- **Fall and Winter** seasons drove the highest purchase volumes, with transaction counts peaking in November–December.
- Spring showed the lowest activity — a signal for targeted promotional campaigns during that period.

### 4. Payment & Behaviour Patterns
- **Credit card** was the most used payment method (35%), followed by PayPal (28%).
- Free shipping preference correlated with larger basket sizes — customers selecting free shipping spent an average of **$12 more** per transaction.

---

## 📈 Power BI Dashboard

The interactive dashboard tracks the following KPIs:
- Total revenue by category and season
- Customer segment breakdown by age, gender, and subscription status
- Repeat purchase rate and review rating distribution
- Payment method trends

> 📂 File: `customer_behavior_dashboard.pbix` — download and open in Power BI Desktop to interact with the full dashboard.

---

## 💡 Business Recommendations

1. **Target subscription upsell campaigns** at female customers aged 25–34 — highest ROI segment.
2. **Launch Spring promotions** to address the seasonal dip in Q1 purchase volumes.
3. **Prioritise service quality monitoring** — review ratings above 4 stars are the strongest predictor of customer retention.
4. **Bundle free shipping offers** with minimum spend thresholds to increase average basket size.

---

## 📁 Repository Structure

```
customer_analysis/
├── customer_shopping_behavior.csv          # Raw dataset
├── shopping_behavior_of_customer_analysis.ipynb  # Python EDA notebook
├── customer_behavior_sql_queries.sql       # SQL business queries
├── customer_behavior_dashboard.pbix        # Power BI dashboard
├── Business Problem Document.pdf           # Problem definition
└── Customer Shopping Behavior Analysis.pdf # Full findings report
```

---

## 🛠️ How to Run

1. Open `shopping_behavior_of_customer_analysis.ipynb` in Jupyter Notebook
2. Run all cells to reproduce the EDA and visualisations
3. Open `customer_behavior_sql_queries.sql` in any SQL client with the CSV loaded as a table
4. Download `customer_behavior_dashboard.pbix` and open in **Power BI Desktop** for the interactive dashboard

---

*Project by [Alex Maseko](https://github.com/alex166-cmd) — BSc Applied Statistics, The Catholic University of Malawi*

