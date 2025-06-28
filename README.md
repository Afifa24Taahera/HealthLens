# PROJECT TITLE: HealthLens – Understanding Patient Data & Health Trends

## Overview:
This repository presents an analysis of patient health records, focusing on heart disease patterns, risk factors, and broader health trends across populations. The project is based on Exploratory Data Analysis (EDA) techniques and aims to support evidence-based decision-making in healthcare. Insights derived from this analysis can serve as a strong foundation for future predictive modeling, targeted screenings, and preventive cardiology efforts.

## Key Features:
- Data Cleaning: Demostrates how to load data and perform cleaning on dataset
- Exploratory Data Analysis: Includes various graphs and examine distribution of target variable.
- Insight Generation: Highlights correlations, patterns in the data, and includes SQL queries for structured insights.
  
## Technology Used:
- ⁠Python (Pandas, Matplotlib, Seaborn, Regex) for data manipulation and visualization.
- Jupyter Notebook/Google Colab for interactive code execution and analysis.
- SQL (MySQL or SQLite) for querying.

## Correlation and Insight Generation:
- To understand how various factors relate to the presence of heart disease, a correlation matrix was generated using only numeric features. The results are visualized using a heatmap. This analysis helps identify relationships that might not be immediately visible. 
- There is positive correlation which indicates that individuals with a higher maximum heart rate during exercise tend to have a lower risk of heart disease. This is expected because a healthy heart can sustain a higher rate during physical activity.
- The max-heart rate achieved for a younger person who has disease is lesser than the person who has no disease.
- A negative correlation shows that a person who experiences angina during exercise is more likely to have heart disease.

## Conclusion:
After closely analyzing the dataset of heart disease, we can ssay that:
- There are many features clearly relate to heart disease. Example:chest pain during exercise, fewer colored blood vessels, or high ST depression.
- There are some common health indicators which are not strong predictors like, cholesterol levels, etc.
- Visualization tools such as heatmap, bar plot, etc made it easier for relationships and compare differences between people with and without heart disease.
- In future, on the basis of these insights and by adding more information or clear insights we can build models that could help predict heart disease more accurately.
