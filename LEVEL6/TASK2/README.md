This README.md is designed to meet the professional standards required for a Level 6 Capstone Project. It covers all functional requirements: data cleaning, churn analysis, segmentation, and strategic recommendations.

Capstone Project: Customer Retention Analysis (Level 6 - Task 2)
Project Overview
This project focuses on identifying behavioral triggers that lead to customer churn in a retail environment. By analyzing a dataset of over 30,000 customers, we built a retention profile to help the business transition from reactive to proactive customer management.

 Core Functional Requirements Met
Data Cleaning & Integration: Managed multi-format data (XLSX/CSV) and resolved encoding issues. Standardized date formats and handled missing engagement metrics.

Retention Metrics: Calculated a baseline Retention Rate of 79.45% and a Churn Rate of 20.55%.

Behavioral Analysis: Identified that churned customers receive 86% fewer email touchpoints than retained customers.

Customer Segmentation: Created an Engagement Scoring Model to categorize customers into Low, Medium, and High-risk segments.

Key Retention Insights
The Communication Gap: Retained customers receive an average of 34 emails, whereas churned customers only receive 4. Low frequency is a primary predictor of churn.

Service Stickiness: Customers subscribed to Automatic Refills are 3.1x more likely to stay with the brand.

Digital Integration: 69% of retained customers use paperless billing, suggesting that digital-first customers are more "anchored" to the service.

Early Warning Signs: A drop in eopenrate (Email Open Rate) serves as a 30-day leading indicator of potential churn.

Retention Dashboard
The analysis includes a 4-chart strategic dashboard:

Retention vs. Churn Pie: A high-level view of the current customer health.

Engagement Boxplots: Visualizing the difference in order frequency across segments.

Churn Likelihood Bar: Showing that the "Low Engagement" segment has a 26.8% churn probability.

KDE Distribution: Comparing email open rates between active and inactive users.

Technology Stack
Python 3.x

Pandas: For data manipulation and encoding management.

Matplotlib & Seaborn: For professional-grade behavioral visualizations.

NumPy: For calculating engagement scores and normalized metrics.

 Data-Driven Recommendations
Automated Win-Back: Launch a re-engagement campaign for any customer who reaches the "4-email threshold" without a second purchase.

Subscription Push: Incentivize the "Refill" and "Doorstep" services during the second order to increase customer lifetime value (LTV).

Segment-Specific Targeting: Prioritize the Low Engagement segment for personalized discount offers to lower their 26% churn risk.