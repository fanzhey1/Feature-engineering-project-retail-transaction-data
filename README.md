# Retail Transaction Data Analysis

** This project is adapted from projects of CHE1147/CHE1148 at University of Toronto, under the supervision of Dr. Nikolaos Anesiadis. **

This purpose of this project is to analyze a retail transaction dataset in Kaggle and try to predict the client's response to a promotion campaign (https://www.kaggle.com/datasets/regivm/retailtransactiondata?select=Retail_Data_Response.csv). Major topics included: Feature engineering; Machine learning algorithms (Logistic regression, Decision tree algorithm, Random forest algorithm); Model assessing and agnostic methods. The project is coded in both Python and PySpark.

In the first part, I built a wide range of features, which fall into two categories: monthly and annual.

In the second part, I predicted the response for each client based on supervised machine learning algorithms and access model accuracies.

In the third part, I assessed my machine learning models in various ways. I first explored the relationship between dataseize and model performance and estimated the appropiate sample size required for achieving a high model performance. I also gave some visualizations to assess data quality and some feature performances, including completeness-feature importance graph, Partial dependency plots, and Local interpretable model-agnostic explanations dashboard (LIME).
