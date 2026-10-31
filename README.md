# Spending Stress Detection Using Category Shifts

An advanced financial data analytics and machine learning pipeline designed to detect, analyze, and monitor financial stress and budgeting anxiety by identifying abrupt behavioral shifts in consumer spending categories over time.

---

## 📖 Overview
Financial stress often manifests subtly through changes in spending habits long before individuals face severe economic distress or missed payments. Traditional credit risk models look primarily at debt-to-income ratios or late payments, which are reactive metrics. 

The **Spending Stress Detection Using Category Shifts** project shifts this paradigm by analyzing granular transaction logs to track sudden shifts in category allocations (e.g., a sharp increase in essential utility spending paired with a sudden drop in discretionary leisure, or heavy reliance on cash advances and high-interest credit). By flagging these behavioral indicators early, this framework empowers financial institutions, personal finance applications, and advisory services to provide proactive support and intervention.

---

## 🔑 Key Features & Objectives
* **Category Shift Analysis:** Monitors longitudinal changes in spending ratios across essential, discretionary, and emergency categories.
* **Behavioral Stress Scoring:** Computes risk and stress indices based on spending volatility, liquidity drops, and irregular transaction cadences.
* **Early Warning Anomalies:** Identifies sudden deviations from personal baseline budgets that signal financial distress.
* **Actionable Insights:** Generates summary reports and diagnostic visualizations to assist financial advisors and automated wellness platforms.

---

## 🛠️ Core Architecture & Pipeline

1. **Data Ingestion & Preprocessing:** 
   * Aggregates historical transaction logs, merchant category codes (MCC), timestamps, and account balances while maintaining strict data privacy and compliance.
2. **Feature Engineering:** 
   * Extracts rolling category totals, month-over-month percentage changes, ratio shifts between discretionary and non-discretionary spending, and transaction frequency volatility.
3. **Machine Learning / Anomaly Detection Engine:** 
   * Trains supervised classifiers and unsupervised anomaly detection models (such as Isolation Forests, Random Forests, or Clustering algorithms) to flag stress-induced behavioral profiles.
4. **Reporting & Dashboarding:** 
   * Outputs structured risk profiles and visualization plots to track spending stress trajectories.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Data Processing & Analysis:** Pandas, NumPy, SciPy
* **Machine Learning:** Scikit-Learn
* **Visualization:** Matplotlib, Seaborn

---

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Delightech25/29-spending-stress-detection-using-category-shifts-1-.git](https://github.com/Delightech25/29-spending-stress-detection-using-category-shifts-1-.git)
   cd 29-spending-stress-detection-using-category-shifts-1-
