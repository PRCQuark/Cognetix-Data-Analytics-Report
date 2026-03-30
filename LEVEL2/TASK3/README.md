# YouTube Channel Performance Analytics

## Project Objective
The goal of this project is to evaluate YouTube channel engagement and content performance. By analyzing real-world performance metrics, we identify top-performing content categories and calculate key engagement rates to drive data-driven content strategies.

## Functional Requirements Addressed
- Data Cleaning: Handled missing values and removed invalid engagement metrics.
- Engagement Analysis: Calculated the total impact of Views, Likes, and Comment counts.
- Derived Metrics: Created an 'Engagement Rate' formula: `(Likes + Comments) / Views`.
- Category Comparison: Analyzed performance trends based on the 'Day of Week' to identify optimal publishing schedules.
- Visualizations: Developed Bar Charts for categorical comparison and Scatter Plots for correlation analysis.

## Tech Stack
- Language: Python
- Libraries: Pandas (Data Wrangling), Matplotlib & Seaborn (Visualization)
- Tools: VS Code, Jupyter Notebook

## Key Findings
1. Top Engagement: Videos posted on **Tuesdays** actually have the highest engagement rate, despite not having the highest total views.
2. Viral Potential: Identified specific outliers in the scatter plot that achieved 10x the average engagement, providing a template for future content.
3. Primary Metric: Total Views peaked at over **670,000** for the top-performing video in this dataset.

## Repository Structure
- `youtube_analysis.ipynb`: The main execution script.
- `youtube_channel_real_performance_analytics.csv`: The raw dataset used for analysis.
- `youtube_analysis.png`: Exported visualization charts.