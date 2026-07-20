# Analyzing Toronto, Montreal, and Ottawa Airbnb Datasets
# Introduction
Conducted an exploratory data analysis (EDA) of Airbnb listings and reviews data from Toronto (November 2025), Montreal (September 2025), and Ottawa (September 2025), combining datasets to analyze pricing patterns across major Canadian urban markets.

Performed comprehensive data preparation, including data cleaning, missing value treatment, feature engineering, feature selection, multicollinearity assessment, and sentiment analysis. Review text was analyzed using the VADER (Valence Aware Dictionary and sEntiment Reasoner) natural language processing model to generate sentiment-based features that were incorporated into predictive models.

Developed and evaluated multiple predictive machine learning models, including Linear Regression, Random Forest, and XGBoost, to identify the most significant factors influencing Airbnb listing prices. Model performance was assessed using R², RMSE, MAPE, and K-Fold Cross Validation.

The primary objective of the analysis was to identify listing characteristics, host behaviors, location factors, and guest sentiment indicators that contribute to higher Airbnb pricing and revenue potential. A secondary objective was to help guests identify features associated with higher value-for-money accommodations.

Key analytical techniques include:
Exploratory Data Analysis (EDA)
Correlation Analysis and Feature Selection
Missing Value Imputation
Log Transformation of Price
Sentiment Analysis using VADER
Linear Regression Baseline Modeling
Random Forest and XGBoost Machine Learning Models
Feature Importance Analysis
K-Fold Cross Validation
Model Evaluation using R², RMSE, and MAPE



# Table of Contents
1. Initalization
2. Usage
3. Licenses

## 1. Initialization
The code was developed and tested using Python 3.12.13 (64-bit) via [Google Collab](http://colab.research.google.com/), but should be compatible with most Python 3.x versions.

All required libraries are listed and installed at the beginning of each notebook.

The recommended way to install dependencies locally is via **PyPI** using `pip`

**Notes**:

Some notebooks generate HTML reports (via ydata-profiling and sweetviz).

Google Colab features such as file download are utilized.

## 2. Usage
i. Open the notebooks in Google Colab or Jupyter Notebook

ii. Run the cells sequentially

iii. Dependencies will install automatically (Colab users)

## 3. Licensing

This project uses the following open-source Python libraries:

- `pandas` – data manipulation and analysis  
- `matplotlib` – data visualization  
- `seaborn` – statistical data visualization  
- `ydata-profiling` – automated dataset profiling  
- `sweetviz` – exploratory data analysis reports  
- `IPython` – enhanced notebook display tools
- `scikit-learn` – machine learning framework for data preprocessing, train-test splitting, model development, and performance evaluation
- `RandomForestRegressor` – machine learning algorithm used for Airbnb price prediction and feature importance analysis
- `xgboost` – gradient boosting machine learning framework used to implement Extreme Gradient Boosting (XGBoost) models for predictive performance comparison
- `time` – runtime measurement and computational performance benchmarking
- `vaderSentiment` – lexicon and rule based sentiment analysis of Airbnb reviews using the VADER (Valence Aware Dictionary and sEntiment Reasoner) framework

These libraries are distributed under permissive licenses such as **MIT** and **BSD**, allowing free use and modification.

VaderSentiment is used under the MIT License (MIT), Copyright (c) 2016 C.J. Hutto, which states:

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:
  
  The above copyright notice and this permission notice shall be included in all
  copies or substantial portions of the Software.

## 4. Data Processing
The libraries run locally in your Python environment and do not transmit your data externally. 

The data is processed in the runtime environment’s memory, either provided by your local machine or cloud-based platforms like Google Colab.
