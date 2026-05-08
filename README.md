# 🛒 Superstore Data Analysis Project

## 🎯 Project Overview

This project is part of a strategic initiative called **"Operation Increase Sales and Profit" (OISP)**. As the in-house data analyst team, our goal is to analyze four years of daily retail sales records to uncover actionable insights. The results aim to assist management in making data-driven decisions to maximize profit and optimize sales across various global regions.

## 📊 Project Objectives

The analysis addresses several key business questions:

* Identify the **top 5 regions** by sales and profit.
* Analyze **Category and Sub-Category** performance (Units Sold, Sales, Profit) within these top regions.
* Examine the **relationship** between Sales, Profit, Quantity, and Discounts.
* Evaluate **Customer Segments** and **Shipping Modes** to identify the most lucrative channels.
* Determine if regional performance differences are **statistically significant** using ANOVA.

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** * `Pandas` & `NumPy` for data manipulation.
* `Matplotlib` & `Seaborn` for data visualization.
* `Scipy.stats` for statistical inference (ANOVA).



## 📂 Dataset Description

The dataset consists of a `superstore.csv` file containing 4 years of transactional data.
Key features include:

* **Order/Ship Dates:** Temporal data for trend analysis.
* **Geographical Data:** Market, Region, Country, City.
* **Product Data:** Category, Sub-Category, Product Name.
* **Metrics:** Sales, Quantity, Discount, Profit.
* **Customer Segment:** Consumer, Corporate, Home Office.

## 📈 Key Insights

* **Product Performance:** **Office Supplies** lead in volume (units sold), but **Technology** is the primary driver of revenue and profit due to higher average selling prices.
* **Segments:** The **Consumer segment** is the business powerhouse, significantly outperforming Corporate and Home Office segments in all metrics.
* **Logistics:** **Standard Class** is the most utilized and profitable shipping mode, indicating a customer preference for economy over speed.
* **Regional Trends:** There are statistically significant differences in sales and profit performance across regions (e.g., Central Asia is a "Zero-Loss" region, while Southeast Asia shows extreme volatility).
* **Growth:** The business showed rapid growth in sales and steady growth in profit over the four-year period.

## 🧪 Statistical Inference

We performed an **ANOVA (Analysis of Variance)** test to compare the top-performing regions:

* **Sales & Profit:** Both showed highly significant p-values, confirming that performance differences between regions are not due to chance and warrant localized strategies.
* **Quantity:** Showed a borderline p-value (~0.06), suggesting volume is relatively consistent across the top regions.

## 💡 Recommendations

1. **Scale Technology:** Focus marketing spend on high-margin Technology items to maximize bottom-line impact.
2. **Optimize Furniture:** High sales but low profit margins in Furniture suggest a need to reduce logistics costs or adjust the product mix.
3. **Customer Retention:** Implement loyalty programs for the **Consumer segment**, as even small retention gains here yield massive total profit increases.
4. **Logistics Efficiency:** Further optimize **Standard Shipping** routes and carrier negotiations, as this is the primary engine of profit.
5. **Address Regional Gaps:** Investigate the loss-making sub-categories (like Tables) in volatile regions like Southeast Asia to mitigate risk.
