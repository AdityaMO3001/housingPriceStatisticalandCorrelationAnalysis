# 🏠 Housing Price Statistical Correlation Analysis

## Project Overview
This data science project explores statistical relationships in housing price data through advanced correlation analysis techniques. The analysis pipeline includes data exploration, visualization, statistical testing, and validation through machine learning models.

### 🔍 Key Features

Multi-method Correlation Analysis: Comparison between Pearson, Spearman, and Kendall correlation coefficients
Statistical Visualization: Heatmaps, scatter plots, and pair plots for comprehensive visualization
Feature Pair Analysis: Identification of strongly correlated feature pairs (r > 0.7)
Predictive Modeling: Implementation of Linear Regression and Random Forest models to validate correlation findings
Feature Importance Analysis: Extraction of key price determinants through model-based feature importance

### 📊 Key Insights
The analysis discovered several significant correlations with housing prices:

Overall quality (OverallQual) showed the strongest correlation with sale price (r=0.79)
Ground living area (GrLivArea) was the second most influential feature (r=0.71)
Several feature pairs displayed strong multicollinearity, which provides important insights for feature engineering
Random Forest model achieved an R² of 0.82 using only the top 5 correlated features
Feature importance analysis confirmed correlation findings, with OverallQual ranking as the most important predictor

### 🛠️ Technologies Used

Python: Main programming language
Pandas & NumPy: Data manipulation and numerical operations
Matplotlib & Seaborn: Data visualization
SciPy: Statistical testing
scikit-learn: Machine learning for predictive modeling

### 📈 Results
The project successfully identified the most influential factors affecting housing prices:

Quality-related features have the strongest impact on price
Size metrics (especially living area) are secondary price determinants
Location factors show significant but more nuanced relationships with price
The predictive models demonstrate that using just the top 5 correlated features can explain approximately 82% of price variance

### 🔗 Dataset
This project uses the Housing Prices dataset from Kaggle: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset


**_This project was created as part of my data science portfolio to demonstrate statistical analysis and correlation techniques in Python._**
