# 🍫 Chocolate Sales Analysis (Power BI + Python)

### 📌 Project Overview

This project focuses on analyzing chocolate sales data using a combination of Power BI and Python to derive meaningful business insights.
The goal was not only to visualize patterns but also to statistically validate them using hypothesis testing.


### 🎯 Objectives

Analyze the relationship between product features and pricing
Evaluate the impact of discounts on revenue
Combine data visualization with statistical testing for better decision-making

### 🛠️ Tools & Technologies
* Power BI → Data cleaning, transformation, dashboards, and reporting
* Python → Data analysis & hypothesis testing
  
Libraries Used:
pandas → Data manipulation
numpy → Numerical operations
scipy → Pearson correlation & p-value
matplotlib, seaborn → Visualization

### 📂 Dataset

The project uses multiple datasets:

* customers.csv
* products.csv
* sales.csv
* stores.csv

These datasets were combined and transformed to create a unified analytical model.

### ⚙️ Methodology

1️⃣ Data Preparation
* Imported datasets using Pandas
* Cleaned missing and inconsistent values
* Merged datasets for analysis

2️⃣ Data Visualization (Power BI)
* Built interactive dashboards showing:
* Revenue trends
* Product performance
* City/store-level insights
* Identified patterns visually before statistical testing

3️⃣ Hypothesis Testing (Python)

Used Pearson Correlation Test

* Significance Level (α): 0.05
* Null Hypothesis (H0): No significant relationship
* Alternative Hypothesis (H1): Significant relationship

### 📊 Hypothesis Testing Results
🔹 1. Cocoa % vs Unit Price
* Correlation: -0.0003
* p-value: 0.755
* Result: Fail to reject H0
* Insight: Cocoa percentage does not influence pricing

🔹 2. Weight vs Unit Price
* Correlation: 0.0016
* p-value: 0.101
* Result: Fail to reject H0
* Insight: Product weight has no significant impact on price

🔹 3. Discount vs Revenue
* Correlation: -0.127
* p-value: < 0.05
* Result: Reject H0
* Insight: Discount significantly impacts revenue
#### Key Insights
* Pricing is not influenced by cocoa percentage
* Product weight does not affect pricing significantly
* Discounts impact revenue, but:
Negative correlation suggests over-discounting
Higher discounts may reduce profitability

### 📈 Power BI Dashboard Highlights
* Revenue breakdown by city and store
* Top-performing products
* Pricing and sales trends
* Interactive filters for dynamic analysis

  
🔗 Project Structure

├── data/

│   ├── customers.csv

│   ├── products.csv

│   ├── sales.csv

│   └── stores.csv
│

├── notebooks/

│   └── hypothesis_testing.ipynb
│

├── powerbi/

│   └── Chocolate Store Analysis.pbix
│



###  Key Takeaway

Data visualization helps identify patterns, but hypothesis testing confirms whether those patterns are statistically valid.
Combining Power BI + Python ensures:Better insights Stronger validation More confident business decisions

#### Author 

Anmol Verma
