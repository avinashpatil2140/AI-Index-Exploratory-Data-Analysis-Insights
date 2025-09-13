# AI-Index-Exploratory-Data-Analysis-Insights
This project explores global AI Index data through data cleaning, visualization, and linear regression modeling. It highlights how research efforts drive overall AI scores, providing insights into regional strengths and trends for future AI development strategies
Perfect — here’s a clean, ready-to-use **README content** for your GitHub repository describing your dataset and EDA project.

---

# 📑 AI Index — Exploratory Data Analysis & Insights

### 📌 Description

This project explores global AI Index data through data cleaning, visualization, and linear regression modeling. It highlights how research efforts drive overall AI scores, providing insights into regional strengths and trends for future AI development strategies.

---

## 📊 Dataset Overview

**File:** `AI_index_db.csv`
**Rows:** 62  **Columns:** 13

**Main Columns:**

* `Country` — Name of the country
* `Region` — Geographic region (Europe, Asia, Americas, etc.)
* `Talent` — Availability of AI talent
* `Infrastructure` — Technology & infrastructure readiness
* `Operating Environment` — Policy, legal & economic environment
* `Research` — Research publications & activities
* `Development` — Development of AI systems and tools
* `Government Strategy` — National-level AI policies
* `Commercial` — AI-related commercial adoption
* `Total score` — Combined index score
* `Cluster`, `Income group`, `Political regime`

---

## 🧩 Steps Performed

### 🧹 Data Cleaning

* Standardized region names (e.g. "Asia-Pacific" → "Asia")
* Removed/handled missing values for consistent analysis
* Exported cleaned dataset as `AI_index_db.csv`

### 📈 Exploratory Data Analysis

* Summary statistics of all numeric features
* Regional and feature-based comparisons using visualizations
* Correlation analysis to find strong predictors of Total score

### 🤖 Modeling

* Built a **Linear Regression model** using `Research` as the predictor for `Total score`
* Found a **strong positive relationship**:

  * Slope ≈ **0.94**, Intercept ≈ **8.85**
* Concluded that countries investing more in **Research** generally have higher overall AI scores

---

## 📌 Key Insights

* Research intensity is a strong driver of overall AI Index rankings.
* Europe and North America dominate top rankings, while Asia is showing rapid growth.
* Clean, structured data enables accurate comparisons and modeling.

---





---

If you want, I can also **add a “How to Run” section** (setup + usage steps) for your GitHub README.
Would you like me to add that?
