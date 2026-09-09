# DataX_intern_task5
Exploratory Data Analysis using Python
# Task 5: Exploratory Data Analysis (EDA) — E-Commerce Dataset

## 📌 Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on an e-commerce transactions dataset to extract actionable patterns, evaluate feature distributions, identify outliers, and diagnose fulfillment trends.

* **Objective:** Extract insights using statistical auditing and visual exploration.
* **Tools Used:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`) in a Kaggle Notebook.
* **Dataset:** E-Commerce Transaction Records (`nabihazahid/ecommerce-dataset-for-sql-analysis`).
* **Deliverables:** Executed Jupyter Notebook (`.ipynb`), visual outputs, and an exported PDF report.

---

## 🔬 Analysis Breakdown & Methodology
1. **Statistical & Structural Audit:** Profiled 10,000 transactions across 24 features using `.info()`, `.describe()`, and `.value_counts()`, validating 100% complete data integrity with zero null values.
2. **Univariate Numerical Analysis:** Plotted histograms and KDE distributions for basket quantities (uniform 1–5 units), unit pricing (multimodal, right-skewed), and line-item revenue (heavy right tail).
3. **Outlier Detection:** Utilized boxplots to examine IQR boundaries, identifying high-ticket fliers ($899–$999) and premium basket totals extending up to $4,995.
4. **Categorical & Sentiment Profiling:** Analyzed transaction volume across product categories (`Electronics` and `Apparel` leading at ~47% combined), customer ratings (balanced ~3.0 average), and fulfillment pipelines.

---

## 🔍 Key Business Findings
* **Catalog Concentration:** `Electronics` (2,616 orders) and `Apparel` (2,047 orders) dominate platform demand, while the remaining four categories exhibit flat, stable volume (~1,300 orders each).
* **Fulfillment Leakage:** Orders are evenly divided across stages, but ~39.3% represent friction points (`Cancelled` at 19.70% and `Returned` at 19.62%).
* **Demographic Uniformity:** Transactions are distributed across age tiers (`Teenagers`, `Adults`, `Senior`) and 10 countries, supported by balanced payment methods (`Cash on Delivery` leading at 34.09%).

---

## 📁 Repository Deliverables
* `task5_exploratory_data_analysis.ipynb` — Full executable EDA notebook with code and visual observations.
* `Task5_EDA_Report.pdf` — Exported visual report of findings.
* `README.md` — Project documentation and summary.
