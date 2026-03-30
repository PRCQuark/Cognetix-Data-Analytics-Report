# Loan Approval Decision Analysis

## Objective
To identify the key financial and personal factors that influence loan approval decisions using historical application data.

## Functional Requirements
- Data Preprocessing: Cleaned string categorical values and handled feature stripping.
- Ratio Analysis: Calculated the baseline approval vs rejection percentage.
- Impact Study: Evaluated the weight of education, self-employment, and credit scores.
- Visualizations: Created bar charts for categorical analysis and box plots for income distribution.
- Correlation: Developed a heatmap to visualize the mathematical relationship between credit scores and approval status.

## Tech Stack
- Python Pandas, Seaborn, Matplotlib)
- Jupyter Notebook

## Key Findings
- Credit Score is King: The correlation analysis shows CIBIL score is the strongest predictor of approval.
- Approval Trend: 62.2% of applicants were successful.
- Income Paradox: Annual income influences the loan amount allowed, but the credit score determines the final decision.