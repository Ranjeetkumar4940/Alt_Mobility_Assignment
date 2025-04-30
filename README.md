# Alt Mobility Data Analyst Intern Assignment: Summary of Findings

# Name = Ranjeet Kumar
# Email = kumarranjeet4940@gmail.com
# Mobile = 7011512372

# Introduction
This analysis examines Alt Mobility’s order and payment data to uncover insights into operational efficiency, customer behavior, and financial performance in their EV leasing and fleet management business. Using MySQL queries, Power BI visualizations, and cohort analysis, we identify key trends, assess customer retention, and provide actionable recommendations to improve business outcomes.

# Key Insights from SQL Queries

# 1. Order and Sales Trends
* Order Fulfillment Rate:   Only 33.71% of orders (5057 out of 15000) are delivered, with 66.29% pending or shipped. This indicates inefficiencies in the delivery process, potentially impacting customer satisfaction.

* Seasonality:   Order counts fluctuate significantly throughout the year, with a peak of 1469 orders in January (Month 1) and a low of 1149 orders in September and December (Months 9 and 12).

* YoY growth:    Order and revenue growth peaked at 2.09% and 3.24% in 2023 but declined sharply by 2025 (-66.55% orders, -66.04% revenue), signaling urgent retention and operational challenges.

# 2. Customer Behavior
* Repeat Ordering:    Customer retention drops significantly over time, with 2932 customers in month 1 declining to 1 by month 8, while the average order value rises from Rs 0.00 to a peak of Rs 4.04 in month 7, indicating fewer but higher-value purchases by remaining customers.

* Order Frequency:    Among 7666 repeat customers, the average time between orders is 480 days, ranging from 0 to 1905 days, indicating highly variable purchasing patterns that may challenge consistent fleet utilization for Alt Mobility.

# 3. Payment Performance
* Payment Success Rate:   Payment statuses are evenly distributed (33% each for completed, failed, and pending) with similar total amounts (Rs 1,257,085.15, Rs 1,273,618.69, and Rs 1,273,403.02) and average values (Rs 251.87, Rs 254.57, Rs 254.38), suggesting no significant payment method or value differences but highlighting a critical 66% failure/pending rate impacting Alt Mobility's revenue.

* Payment Delays:   Payment methods show balanced usage (bank transfer, credit card, PayPal) with similar average amounts (Rs 249.95–Rs 258.78), but bank transfer has the highest failure rate (1758 failed) and credit card the highest pending average (Rs 258.78), indicating method-specific reliability issues impacting Alt Mobility's payment success..

* Payments Counts:    Payment counts and amounts showed minor fluctuations from 2021 to 2024 (-1.69% to 2.62% growth, 0.02% to 2.62% amount growth) with a stable success rate (32.64% to 33.93%), but a drastic decline in 2025 (-67.76% count, -68.59% amount) with a slight success rate increase (0.57%) suggests a significant operational or market disruption for Alt Mobility.

# Recommendations
1. Investigate 2025 decline (-66.55% orders, -67.76% payments) with mid-year reviews.
2. Boost Q1 demand with marketing and premium leases.
3. Counter mid-year slumps with promotions and maintenance.
4. Increase 32% fulfillment rate to 50% in 6 months.
5. Fix 66% failure/pending payments and long delays.
6. Raise 4% retention with loyalty programs and shorter leases.
7. Optimize pricing during low-demand months.
8. Monitor 33–34% success rate to sustain gains.


