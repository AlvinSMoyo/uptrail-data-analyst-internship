## 📊 Week 04 — Executive Dashboard, BI Tools & AI in Analytics

**Project: TechHub Executive Performance Overview**

### 🔎 Project Overview

This project delivers an **executive-level analytics solution** for *TechHub Retail*, combining an **interactive Tableau dashboard** with **Python-based data validation and forecasting**.

The objective is to:

* Validate the integrity of an 18-month transactional dataset
* Surface key performance drivers across revenue, profit, and customers
* Provide **forward-looking insight for 2025 planning**, overcoming BI tool limitations

---

### 🧰 Tools & Technologies

* **Tableau Public** — Executive dashboard & KPI visualisation
* **Python** — Data validation, EDA, and forecasting

  * Pandas, NumPy
  * Matplotlib, Seaborn
  * Scikit-Learn (Linear Regression)
* **Jupyter Notebook**

---

### 📈 Tableau Executive Dashboard

The Tableau dashboard provides a **single executive view** with:

* Revenue, Profit, and Margin KPIs
* Customer acquisition and tenure metrics
* Interactive **Acquisition Channel** filtering
* Monthly customer acquisition trends

🔗 **Live Dashboard (Tableau Public):**
👉 [https://public.tableau.com/views/TechHub_Executive_Performance_Overview_FINAL/ExecutiveOverview](https://public.tableau.com/views/TechHub_Executive_Performance_Overview_FINAL/ExecutiveOverview)

---

### 🤖 Advanced Analytics (Python)

Due to the dataset spanning **only 18 months**, Tableau’s native forecasting could not reliably detect seasonality.
To address this, a **Python Linear Regression model** was built with seasonal feature engineering.

Key outcomes:

* Confirmed **extreme negative margin outliers** (as low as −1,200%)
* Validated **100% referential integrity** across Sales, Customers, and Products
* Projected a **repeatable Q4 revenue surge in 2025**, supporting inventory planning

---

### 📌 Key Business Questions Answered

1. **Overall performance:** Strong headline KPIs but top-heavy profitability
2. **Hidden risks:** Loss-making transactions distort averages
3. **Customer acquisition trends:** Highly seasonal and campaign-driven
4. **Channel performance:** Volume ≠ Value (CLV varies by channel)
5. **Customer value:** High retention, opportunity to increase frequency
6. **Forward planning:** Python model enables confident 2025 forecasting

---

### 🧠 Strategic Recommendations

* **Protect margins proactively** by monitoring extreme negative transactions
* **Shift focus from volume to value**, prioritising channels with higher CLV
* **Plan early for Q4 demand**, ramping inventory in Q3 2025
* **Strengthen retention strategies** to unlock value from long-tenure customers

---

### 📂 Repository Structure

```
week-04/
│
├── data/
│   ├── TechHub_Sales_Data.csv
│   ├── TechHub_Customers.csv
│   └── TechHub_Products.csv
│
├── brief/
│   └── Week 4 – Project Brief (PDF)
│
├── Week_4_TechHub_Executive_Dashboard.ipynb
├── TechHub_Executive_Performance_Overview_FINAL.twbx
├── Week_4_Project_Coversheet_TechHub_Executive_Dashboard.pdf
└── README.md
```

---


