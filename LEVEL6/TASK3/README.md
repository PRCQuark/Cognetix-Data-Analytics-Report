Project Overview
This project provides an end-to-end analytical review of supply chain operations, focusing on product movement from suppliers to end consumers. The goal was to identify inefficiencies in lead times, evaluate shipping performance, and pinpoint high-risk nodes in the logistics network.

Core Functional Requirements Met
Timeline Analysis: Evaluated order processing, manufacturing, and shipping durations to calculate the total fulfillment cycle.

Risk Identification: Pinpointed high-risk regions and specific suppliers with high defect rates and long lead times.

Cost-Performance Mapping: Analyzed the relationship between shipping costs and delivery speed to identify "over-spend" scenarios.

Operational KPIs: Measured key metrics including Average Lead Time, Shipping Time, and Defect Rates.

Optimization Insights: Provided data-driven strategies for reducing bottlenecks and improving cost efficiency.

Key Operational KPIs
Avg. Manufacturing Lead Time: ~15.96 Days

Avg. Shipping Time: ~5.75 Days

Average Defect Rate: 2.28%

Cost-to-Revenue Ratio: 0.09 (Logistics and manufacturing costs represent 9% of revenue).

Identified Bottlenecks & Patterns
Manufacturing Lag: The primary bottleneck is in the production phase (15+ days), which dwarfs the actual shipping time.

Carrier Performance: Carrier B demonstrated the highest efficiency, maintaining low shipping times without a linear increase in cost.

Regional Risks: Shipments originating from or passing through Mumbai and Chennai showed higher variability in lead times compared to other hubs.

Quality Control: A subset of 27% of suppliers were identified as "High Risk," consistently exceeding the average defect rate of 2.28%.

Technology Stack
Python 3.x

Pandas: Data cleaning, transformation, and SKU-level aggregation.

Matplotlib & Seaborn: For regional performance heatmaps and cost-speed scatter plots.

NumPy: For statistical risk modeling and KPI calculations.

 Executive Recommendations
Inventory Positioning: Transition to a decentralized warehousing model near high-demand regions (like Delhi/Bangalore) to mitigate manufacturing lead-time impacts.

Strategic Partnering: Shift higher volumes to Carrier B and Carrier C, which showed better reliability in the cost-performance analysis.

Supplier Development: Implement a mandatory quality improvement program for "Supplier 1" and "Supplier 3" to address high defect rates.

Route Optimization: Review "Route A" shipments, which frequently correlate with higher costs but average delivery speeds.