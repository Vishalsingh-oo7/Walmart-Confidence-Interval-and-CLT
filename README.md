# Walmart Case Study – Customer Purchase Analysis

## 🛒 Project Overview

This project analyzes customer purchase behavior at Walmart, focusing on **purchase amounts** across different customer demographics. Using **Confidence Intervals (CI)** and **Central Limit Theorem (CLT)**, the goal is to provide insights into spending patterns based on **gender, age, marital status, city category, and other factors**, to help Walmart make data-driven business decisions.

---

## 📌 Business Problem

Walmart wants to understand if **spending habits differ between male and female customers**, particularly on high-sales days like Black Friday. Key questions addressed include:

* Do men or women spend more?
* Does age, marital status, or city category affect purchase behavior?
* Which product categories are preferred?
* How can Walmart target specific segments to maximize revenue?

---

## 📊 Dataset

* **Source:** Walmart CSV dataset (approx. 550,068 entries, 10 columns)
* **Columns include:**

  * `User_ID`, `Product_ID`, `Gender`, `Age`, `Occupation`, `City_Category`
  * `Stay_In_Current_City_Years`, `Marital_Status`, `Product_Category`, `Purchase`
* **Data Type Changes:** Converted categorical columns (`User_ID`, `Product_ID`, `Gender`, `Age`, `City_Category`, `Marital_Status`) to `category` type for analysis.

---

## 🛠️ Technologies & Libraries Used

* **Python** (v3.10+)
* **Libraries:**

  * `pandas` – Data manipulation
  * `numpy` – Numerical operations
  * `matplotlib` & `seaborn` – Data visualization
  * `scipy.stats` – Statistical calculations (CLT, CI)
  * `warnings` – Suppress warnings for cleaner outputs
* **Techniques:** Exploratory Data Analysis (EDA), Univariate & Bivariate Analysis, Bootstrapping, Confidence Interval Analysis

---

## 🔍 Key Insights

* **Gender:** 75% male, 25% female; males spend more on average than females.
* **Age:** Majority of purchases (60%) from age 26-45; little effect of age on median spending.
* **Marital Status:** 59% single, 41% married; marital status has minimal effect on spending.
* **City Category:** Most customers from Category B, but Category C customers spend more on average.
* **Purchase Ranges:** Most purchases are between ₹5,000–20,000; product categories 1, 5, 8, and 11 are most frequently bought.
* **Outliers:** High-spending customers exist across all demographics.

---

## 📈 Statistical Analysis

* **Bootstrapping** used to estimate confidence intervals for average purchase values.
* **Central Limit Theorem (CLT)** applied to understand sampling behavior across different sample sizes.
* **Findings:**

  * Male vs Female: Males consistently spend more; CI separates clearly with larger samples.
  * Married vs Unmarried: Purchase behavior largely overlaps, no significant difference.
  * Age Groups: Overlapping CI indicates age has limited impact on spending habits.

---

## 💡 Business Recommendations

* Focus on **male customers** for retention and acquisition.
* Promote **popular product categories** (1, 5, 8, 11) and improve sales for less frequent categories.
* Target **unmarried customers** and age **18-45** for marketing campaigns.
* Offer **special promotions for women** to increase Black Friday spending.
* Introduce **games or offers for kids** to attract younger shoppers.
* Increase sales focus in **City Category C**, where spending is higher.

---

## 📂 Project Structure

Walmart_Case_Study_Scaler.ipynb  # Jupyter Notebook with EDA, CI & CLT analysis
Walmart.csv                       # Dataset (Google Drive link used in notebook)
README.md                         # Project documentation


---

