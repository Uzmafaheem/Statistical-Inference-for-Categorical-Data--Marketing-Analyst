
# Customer Loyalty Program Analysis
## 📊 Project Overview

This project analyzes customer engagement with a retail chain’s promotional campaigns to optimize marketing strategies. The marketing team aims to understand:

Customer engagement patterns by time of day (morning, afternoon, evening).

Relationship between promotion type (email, SMS, app notification) and purchase behavior within 7 days of promotion.

Using statistical analysis and visualization, the project provides actionable insights to improve campaign effectiveness and maximize ROI.

## 🎯 Business Objectives

Identify peak engagement times for promotions to improve targeting and timing.

Determine whether certain promotion types drive more purchases to prioritize effective channels.

Provide data-driven recommendations to optimize promotional strategy and marketing spend.

## 🔬 Research Questions & Hypotheses

Time-of-Day Engagement

Null Hypothesis (H₀): Customers engage equally across all times of day.

Alternative Hypothesis (H₁): Customers show preferences for certain times of day.

Promotion Type vs Purchase Behavior

Null Hypothesis (H₀): Promotion type and purchase behavior are independent.

Alternative Hypothesis (H₁): Promotion type and purchase behavior are related.

## 📈 Exploratory Data Analysis (EDA)

Visualizations include:

Customer engagement by time of day (bar chart).

Purchase behavior by promotion type (stacked bar chart).

Heatmaps of promotion type vs purchase behavior for easy interpretation.

Key observations from EDA:

Trends in customer engagement throughout the day.

Initial differences in conversion rates across promotion types.

## 🧮 Statistical Analysis
1. Time-of-Day Engagement

Method: Chi-square goodness of fit test

Purpose: Test if customer engagement is uniform across time categories.

Expected Frequencies: Assuming no time preference, each time category expected to have equal engagement.

Interpretation:

p-value < 0.05 → Reject H₀ → Customers show a time-of-day preference.

2. Promotion Type vs Purchase Behavior

Method: Chi-square test of independence

Purpose: Evaluate if promotion type influences purchase behavior.

Contingency Table: Cross-tabulation of Promotion_Type vs Purchased_7days.

Interpretation:

p-value < 0.05 → Reject H₀ → Promotion type significantly impacts purchase behavior.

## 📝 Business Recommendations

Optimize Promotion Timing: Target campaigns during peak engagement times (e.g., morning or evening).

Prioritize Effective Channels: Focus marketing spend on promotion types with higher conversion rates (e.g., SMS or app notifications).

Combine Insights: Schedule the most effective promotion type during peak times for maximum ROI.

Continuous Monitoring: Track future campaigns to validate findings and adjust strategy dynamically.

## 🛠 Technologies & Libraries

Python – Data analysis and visualization

Pandas – Data cleaning and manipulation

Seaborn & Matplotlib – Visualization

SciPy – Statistical tests (Chi-square)
