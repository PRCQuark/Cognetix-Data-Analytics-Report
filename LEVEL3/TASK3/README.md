# Hotel Booking Demand Analysis

## Project Overview
This project analyzes hotel booking patterns to identify drivers of cancellations and optimize room demand forecasting. Using a dataset of over 119,000 bookings, we evaluate how lead time, deposit types, and seasonality impact hotel revenue.

##  Key Features
- Data Engineering: Combined split date fields (Year/Month/Day) into a unified time-series object.
- KPI Calculation: Analyzed Cancellation Rates (37%) and No-Show Rates (1%).
- Lead Time Study: Visualized the correlation between advance booking time and the likelihood of cancellation.
- Geographic Analysis: Identified top 10 contributing countries for global demand.
- Policy Impact: Studied how different deposit types (Refundable vs. Non-Refundable) influence customer behavior.

##  Tech Stack
- Pandas: Time-series manipulation and data cleaning.
- Matplotlib & Seaborn: Complex trend analysis and density plots.

## Strategic Recommendations
- Dynamic Deposit Pricing: Implement tiered non-refundable deposits for bookings made more than 100 days in advance.
- Overbooking Strategy: Use the 37% cancellation baseline to safely overbook during peak summer months to maximize final occupancy.