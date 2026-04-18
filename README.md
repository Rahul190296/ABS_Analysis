# 🌱 Agrostar ABS Business Performance Analysis (FY26 vs FY27)

## 📌 Project Overview

This project analyzes the **Advance Booking Scheme (ABS)** performance across FY26 and FY27 to evaluate its impact on **revenue growth, partner performance, and operational efficiency**.

The analysis combines:

* **Python (EDA & Insights)**
* **Power BI (Interactive Dashboards)**

---

## 🎯 Objective

* Evaluate whether ABS drives higher revenue
* Analyze **efficiency vs returns trade-off**
* Identify **high-risk products, partners, and regions**
* Provide **data-driven recommendations for FY27 strategy**

---

## 📂 Dataset

* Source: Internal ABS tracking dataset
* Records: ~14,500 rows 
* Key Features:

  * Revenue, Net Revenue, Return Amount
  * ABS participation (FY26 & FY27)
  * Product, Territory, State
  * Sales hierarchy (TM, SM)

---

## 🧹 Data Cleaning & Feature Engineering

Performed using Python:

* Removed unnecessary columns
* Handled missing values
* Created key metrics:

  * `return_pct`
  * `net_efficiency`
  * `abs_flag_fy26 / fy27`
  * `Net_Rev_in_lacs`

---

## 📊 Exploratory Data Analysis (Python)

### 🔹 Product Performance

* Wheat & Maize are top contributors
* Revenue is highly concentrated in few products

### 🔹 Territory Analysis

* Identified top-performing territories per state
* Highlighted regional concentration risk

### 🔹 Return Analysis

* Mustard & Castor show highest return %
* Indicates potential quality or demand issues

### 🔹 ABS Impact (FY26 Benchmark)

* ABS partners generated **~3X higher revenue**
* However, **efficiency was lower** (higher returns)

### 🔹 ABS Transition Analysis (FY26 → FY27)

* Consistent ABS users perform best
* New adopters show improvement
* Dropping ABS reduces performance

---

## 📊 Power BI Dashboards

### 📌 Dashboard 1: Business Overview

![Dashboard Overview](images/dashboard_overview.png)

**Key Insights:**

* Total Revenue: **2bn**
* Net Revenue: **1.12bn**
* ABS Adoption: **11%**
* Revenue is dominated by Seeds - FC category

---

### 📌 Dashboard 2: ABS Efficiency & Risk Analysis

![ABS Efficiency](images/abs_efficiency.png)

**Key Insights:**

* ABS improves **revenue significantly**
* But increases **return % (efficiency drop)**
* Efficiency gap exists between ABS vs Non-ABS

---

## 📈 Key Business Insights

### 🟢 1. ABS Drives Revenue Growth

* ABS partners outperform non-ABS significantly
* Strong case for scaling adoption

---

### 🔴 2. Efficiency Trade-Off

* Higher returns observed in ABS partners
* Indicates need for better execution

---

### 🔵 3. Product-Level Risk

* Certain products drive high returns
* Requires targeted intervention

---

### 🟣 4. Partner Concentration

* Few partners contribute majority revenue (Pareto effect)

---

### ⚫ 5. Strategic Insight (Most Important)

> Consistent ABS participation yields the highest performance, while discontinuation leads to decline.

---

## 🧠 Recommendations

* Expand ABS adoption strategically
* Focus on **high-performing partners**
* Reduce returns through:

  * Better product targeting
  * Operational improvements
* Monitor **high-risk products & regions**

---

## 🛠 Tools & Technologies

* **Python** (Pandas, NumPy, Seaborn, Matplotlib)
* **Power BI** (Dashboarding & DAX)
* **Jupyter Notebook**

---

## 📁 Project Structure

```
Agrostar-ABS-Analysis/
│
├── data/
├── notebooks/
│   └── analysis.ipynb
├── dashboard/
│   ├── agrostar.pbix
│   └── dashboard.pdf
├── images/
│   ├── dashboard_overview.png
│   └── abs_efficiency.png
└── README.md
```

---

## 🚀 How to Use

1. Open notebook → run analysis
2. Open `.pbix` file in Power BI
3. Explore dashboards with slicers

---

## 🎯 Final Conclusion

The ABS scheme is a **strong revenue driver**, but its **efficiency impact needs optimization**.
A balanced strategy focusing on **growth + quality** will maximize business outcomes.

---

