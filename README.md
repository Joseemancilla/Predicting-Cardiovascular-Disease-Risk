# Predicting-Cardiovascular-Disease-Risk
Predicting Cardiovascular Disease Risk
HealthPrediction: Cardiovascular Disease Risk Analysis
<!-- Replace with a banner image link if available -->

#Table of Contents
[Overview](#overview)
Data Preprocessing
Exploratory Data Analysis
Feature Engineering
Model Building
Model Evaluation
Conclusion and Key Insights
Installation and Requirements

## Project Overview
This project explores various health and lifestyle factors to predict cardiovascular disease (CVD) risk using machine learning models, specifically logistic regression and random forest. The dataset includes demographic and lifestyle variables, which are analyzed to understand their influence on CVD risk.

Data Preprocessing
This section includes data preparation steps such as loading the data, handling missing values, and transforming categorical variables into factors to enable analysis and modeling.

Exploratory Data Analysis (EDA)
During EDA, we examine variable distributions and the relationships between predictors and CVD risk.

Age vs. Risk_CVD Histogram
This histogram shows the distribution of age, separated by Risk_CVD status, highlighting how age groups differ in their risk profiles.

<!-- Replace with actual link to image -->

BMI vs. Risk_CVD
A scatter plot illustrating BMI values against CVD risk levels, helping visualize potential correlations between BMI and cardiovascular disease risk.

<!-- Replace with actual link to image -->

Feature Engineering
To enhance predictive power, BMI was categorized into four groups: Underweight, Normal, Overweight, and Obese. This categorization aids in better understanding how BMI influences Risk_CVD.

BMI Category Bar Plot
This bar plot shows the distribution of individuals across BMI categories, allowing us to observe which categories may correlate more strongly with increased CVD risk.

<!-- Replace with actual link to image -->

Model Building
This project utilizes two models to predict Risk_CVD:

Logistic Regression: Useful for interpreting the effects of individual predictors on CVD risk.
Random Forest: A tree-based model providing insights into variable importance and predictive accuracy.
Model Evaluation
The models are evaluated using metrics like accuracy and AUC-ROC curves to compare predictive performance and select the best model.

ROC Curve
The ROC curve illustrates model sensitivity and specificity, helping visualize the model's classification performance for Risk_CVD.

<!-- Replace with actual link to ROC image -->

Confusion Matrix
Displays true and false positives and negatives, giving insight into the model’s precision and recall.

<!-- Replace with actual link to confusion matrix image -->

Conclusion and Key Insights
This project highlights several key insights:

Age and BMI play significant roles in predicting CVD risk.
Lifestyle factors, such as smoking status and physical activity, are also important contributors to cardiovascular health.
These insights contribute to understanding how demographic and lifestyle factors relate to cardiovascular disease, and they offer a foundation for future work in risk prediction and preventative health measures.
