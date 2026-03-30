Project Overview
This project involves a comprehensive statistical analysis of the King County Housing Dataset. The objective is to identify the core physical and geographical factors that drive real estate pricing and to prepare the data for high-accuracy predictive modeling.

Key Functional Requirements Met
Data Engineering: Cleaned 21,613 records, handled date-time transformations, and removed non-predictive identifiers.

Correlation Analysis: Quantified the relationship between 19 different property features and final sale prices.

Outlier Detection: Utilized the Interquartile Range (IQR) method to identify and isolate 1,146 luxury market anomalies.

Feature Importance: Identified 'sqft_living', 'grade', and 'sqft_above' as the primary price drivers.

Statistical Insights
The Space Factor: sqft_living has a 0.70 correlation with price, confirming it as the most reliable linear predictor.

Quality vs. Quantity: Analysis showed that a house's Grade (construction quality) often influences price more significantly than the total lot size (sqft_lot).

The Luxury Ceiling: Statistical anomalies begin appearing above the $1.13M mark, indicating a shift from functional pricing to "prestige" pricing (views, waterfront).

 Data Science Toolkit
Python 3.x

Pandas & NumPy: For statistical computation and data cleaning.

Matplotlib & Seaborn: For distribution plotting and heatmap generation.

Scikit-Learn: (Prepared) Dataset is formatted with numeric encoding for regression pipelines.