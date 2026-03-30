Project Overview
This project focuses on identifying and quantifying the medical and demographic factors that drive high-cost insurance claims. By analyzing a dataset of 1,340 patient records, we identify key "Risk Profiles" to assist insurance providers in more accurate premium pricing and proactive health management.

Core Functional Requirements Met
Data Cleansing: Resolved missing values in age and region using statistical imputation (median/mode).

Profile Comparison: Segmented the customer base into "High-Claim" vs. "Low-Claim" groups based on median expenditure to identify contrasting health markers.

Impact Analysis: Measured the influence of BMI, Age, Smoking Status, and Blood Pressure on total payouts.

Statistical Validation: Performed Independent T-Tests and One-Way ANOVA to prove the statistical significance of risk factors.

Key Risk Insights
The "Smoking Premium": Smoking is the single largest driver of cost. Smokers average $32,050 in claims, compared to just $8,421 for non-smokers.

Blood Pressure Correlation: A strong positive correlation (0.53) exists between blood pressure and claim amount, making it a critical vital sign for risk assessment.

Regional Variance: Statistical testing (ANOVA) confirmed that the Northeast region has significantly higher claim costs than the Northwest, indicating regional economic or health-standard differences.

BMI & Obesity: High-claim patients consistently show a higher BMI (Avg: 31.2) compared to the lower-cost group, highlighting obesity as a long-term financial risk.

Visualization Dashboard
The project includes a 4-chart analytical dashboard:

Box Plots: Visualizing the massive cost disparity between smokers and non-smokers.

Bar Charts: Comparing average claim costs across different geographic regions.

Scatter Plots: Illustrating how Age and Smoking interact to multiply claim costs.

Comparative Distribution: Analyzing BMI levels across high and low claim categories.

 Technology Stack
Python 3.x

Pandas: For data manipulation and cleaning.

Seaborn & Matplotlib: For advanced statistical visualization.

SciPy: For conducting T-Tests and ANOVA significance testing.

Risk Mitigation Recommendations
Incentivize Non-Smokers: Offer premium discounts for verified non-smokers to attract low-risk profiles.

Hypertension Monitoring: Integrate wearable tech or regular BP check-ins for high-risk policyholders to prevent emergency-level claims.

Regional Loading: Consider "Regional Loading" (adjusted premiums) for the Northeast territory to offset the statistically higher claim averages in that area.
