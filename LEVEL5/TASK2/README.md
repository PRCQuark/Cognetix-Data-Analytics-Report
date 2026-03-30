Project Overview
This project analyzes the spending behavior of approximately 9,000 active credit card holders to identify distinct customer segments. By applying unsupervised machine learning (K-Means Clustering), we group users based on their transaction patterns, credit usage, and payment history to provide actionable insights for targeted marketing and risk management.


 Business Objectives
Identify High-Value Users: Distinguish customers who drive the highest transaction volume.

Segment Behavioral Patterns: Group users into categories like "Cash Advance Reliant" or "Installment Buyers."

Optimize Engagement: Recommend specific financial products based on segment-specific needs.

Visualize Spending Trends: Create a comprehensive dashboard to communicate findings to stakeholders.


Technical Workflow
Data Cleaning: Handled missing values in MINIMUM_PAYMENTS and CREDIT_LIMIT using median imputation.

Feature Engineering: Created monthly average metrics to normalize data across different account tenures.

Dimensionality Reduction: Used PCA (Principal Component Analysis) to reduce 17 features into 2 components for 2D visualization.

Clustering: Implemented K-Means Clustering with 4 optimal clusters.


Dashboard Preview
The analysis generates a 4-part visual dashboard including:

Balance vs. Purchases: Mapping the relationship between debt and spending.

Segment Distribution: A census of the customer base.

Purchase Volume: Comparing the profitability of different clusters.

PCA Cluster Map: A mathematical representation of how distinct each group is.