# ABC-Bank-Customer-churn-data-analysis
**🎯 1. Problem Statement**

The objective of this project was to analyze customer data and identify key factors driving churn in order to improve customer retention for the bank.

**🧩 2. Approach**

I performed end-to-end analysis using Python (Pandas, NumPy) in Google Colab for data cleaning, feature engineering, and exploratory analysis, followed by dashboard creation in Microsoft Power BI.

**🧹 3. Data Preparation**
- Cleaned dataset (handled nulls, duplicates)
- Standardized column names
- Created new features:
- Balance-to-Salary ratio
- Tenure-to-Age ratio

👉 This helped in deeper behavioral analysis

**📊 4. Key Insights**

**🔹 Insight 1:** Customer Activity Drives Retention

Inactive customers showed a significantly higher churn rate (~27%) compared to active customers (~14%).

👉 Meaning:

Engagement is a critical factor in retention

**🔹 Insight 2:** Product Holding Impacts Churn

Customers with only 1 product had a higher churn rate (~27%), while those with 2 products had the lowest churn (~7.6%).

👉 Meaning:

Customers using more services are less likely to leave

⚠️ Note:

High churn in 3–4 products segment was observed but not considered reliable due to low sample size

**🔹 Insight 3:** Customer Segmentation Matters

Different customer segments (based on activity and product usage) show clear variation in churn behavior.

👉 Meaning:

One strategy cannot fit all customers

**💡 5. Business Recommendations**

Based on analysis:

✅ 1. Increase Customer Engagement
Target inactive customers with personalized campaigns
Encourage usage of banking services
✅ 2. Promote Cross-Selling
Encourage customers to adopt at least 2 products
Bundle offerings (e.g., savings + credit card)
✅ 3. Segment-Based Strategy
Design retention strategies based on:
- Activity level
- Product usage
  
**📈 6. Dashboard (Power BI)**

In Microsoft Power BI, I built an interactive dashboard including:

- KPI cards (Total Customers, Churn Rate)
- Churn by Activity Status
- Churn by Number of Products
- Customer segmentation visuals
- Filters for dynamic analysis

**🧠 7. Conclusion**

This analysis highlights that customer engagement and product adoption are key drivers of retention, and targeted strategies can significantly reduce churn.
