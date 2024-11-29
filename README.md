# 3MTT-Capstone-Project-Godwin-Okorie

A 3MTT Capstone Project

This project leverages the CORD-19 Research Challenge dataset to perform exploratory data analysis (EDA) and predictive modeling. The goal is to analyze trends in COVID-19-related research, forecast publication frequency, and classify abstracts as COVID-related or not using machine learning.

Table of Contents 
Project Overview 
Dataset Description 
Project Workflow 
Key Features 
Technologies Used 
Results 
How to Run the Project
Contributing 
Project Overview

COVID-19 has generated an unprecedented amount of research globally. This project uses the CORD-19 Research Challenge dataset to:

Perform Exploratory Data Analysis (EDA) to uncover trends and insights in publication data. Predict future publication trends using time-series forecasting (ARIMA model). Classify abstracts as COVID-related or not using a Random Forest classifier.

Dataset Description
The CORD-19 Research Challenge dataset is a collection of scholarly articles about COVID-19, SARS-CoV-2, and related coronaviruses. It contains:

Metadata: Titles, abstracts, authors, and publication dates. However, only raw CSV data is used in the project.

Full Text Articles: Not used in this project but available for deeper analysis.

The dataset is hosted on Kaggle: CORD-19 Research Challenge.

Project Workflow
Data Cleaning:

Handle missing values and format publication dates. Create additional features like abstract length and sentiment polarity.

Exploratory Data Analysis (EDA):

Analyze publication trends over time. Generate a word cloud for abstracts to identify key topics.

Predictive Modeling:

ARIMA Model: Forecast future publication trends.

Random Forest Classifier: Classify abstracts as COVID-related or not using TF-IDF vectorization.

Results and Visualizations:

Key plots: Time-series trends, feature importance, and word cloud.

Save processed data and trained models for reuse.

Key Features
Time-Series Analysis: Forecasts future publication trends using ARIMA.

Text Classification: Identifies COVID-related abstracts using a Random Forest classifier with TF-IDF vectorization.

Visualizations: Word cloud of research abstracts. Bar plots for feature importance and publication trends. Technologies Used

Python Libraries: pandas, numpy for data manipulation. matplotlib, seaborn for visualizations. wordcloud for text analysis. statsmodels for ARIMA modeling. scikit-learn for machine learning. textblob for sentiment analysis.

Dataset: CORD-19 Research Challenge on Kaggle.

Google Colab for development and execution.

How to Run the Project
Requirements Python 3.7 or higher. Kaggle API setup with the kaggle.json file. Libraries installed (wordcloud, statsmodels, textblob).

Results
Exploratory Data Analysis

Publications have increased dramatically since the start of the pandemic, with significant spikes in 2020. Common topics include COVID-19, SARS, and pandemic.

Predictive Modeling

ARIMA Forecasting:

Accurately forecasts publication trends for the next 12 months. Visualizes observed vs. forecasted trends. Random Forest Classification:

Achieves high accuracy in identifying COVID-related abstracts. Key features include words like "COVID", "pandemic", and "SARS".

Contributing Contributions are welcome! If you'd like to contribute:

Contact For any questions or suggestions, please reach out to:

Name: Godwin Okorie Email: godwinokorie@gmail.com GitHub: https://github.com/godwinokorie
