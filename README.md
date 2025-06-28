# PROJECT TITLE: HealthLens – Understanding Patient Data & Health Trends

## Overview:
This repository contain analysis of patient health records and extract insights into heart disease patterns, risk factors, and population-level trends. It is the result of Exploratory Data Analysis (EDA) on patient data and health trends. The findings are intended to support evidence-based decision-making and may serve as a foundation for predictive modeling, targeted screening, and preventive healthcare initiatives within cardiology.

## Key Features:
- Data Cleaning: Demostrate how to load data and perform cleaning on dataset
- Exploratory Data Analysis: Includes various graph and examine distribution of target variable.
- Insight Generaton: Includes correlation, patterns and Sql scripts.

## Technology Used:
- ⁠Python (Pandas, Matplotlib, Seaborn, Regex).
- Jupyter Notebook/Google colab.
- SQL (MySQL or SQLite).

## Correlation and Insight Generation:
- To understand how various factors relate to the presence of heart disease, a correlation matrix was generated using only numeric features. The results are visualized using a heatmap. This analysis helps identify relationships that might not be immediately visible. 
- There is positive correlation which indicates that individuals with a higher maximum heart rate during exercise tend to have a lower risk of heart disease. This is expected because a healthy heart can sustain a higher rate during physical activity.
- The max-heart rate achieved for person who has disease of lower age is lesser than the person who has no disease.
- A negative correlation shows that the person who experience angina during exercise are more likely to have heart disease.

## Conclusion:
After closely analyzing the dataset of heart disease, we can ssay that:
- There are many features clearly relate to heart disease. Example-chest pain during exercise, fewer colored blood vessels, or high ST depression.
- There are some common health indicators which are not strong predictors like, cholesterol levels, etc.
- These tools to visualize like heatmap, bar plot, etc made it easier for relationships and compare differences between people with and without heart disease.
- In future, on the basis of these insights and by adding more information or clear insights we can make build models that could help predict heart disease more accurately.
