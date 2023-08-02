# DSAI-SC1015-Project
Welcome to our SC1015 Data Science Mini-Project! This project uses the [Heart Disease](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) dataset from Kaggle. Here is our presentations [slides](https://www.canva.com/design/DAFdotrY1hA/EVLGTds1KHDa02-J5L70yg/edit?utm_content=DAFdotrY1hA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) and [video](https://drive.google.com/file/d/1y1P5ds_2jYjox3cuqYuXXuRj2oG-4_Mp/view?usp=sharing). For a complete walkthrough of the project, refer to the following jupyter notebooks in order form:

1. [Exploratory Data Analysis & Data Preparation](https://github.com/hridayyy/SC1015-Project/blob/144d14462991c36629c18833c81e6d4539487f99/Exploratory%20Data%20Analysis%20&%20Data%20Preparation.ipynb)
2. [Machine Learning](https://github.com/hridayyy/SC1015-Project/blob/af9243a0b76b6bbf4e132099c07528315d8daae7/Machine%20Learning.ipynb) 
3. [Data-Driven Insights & Recommendations](https://github.com/hridayyy/SC1015-Project/blob/23f6379d66bb5eeb64caf2ae8670f11d34280af1/Data%20Driven%20Insights%20&%20Recommendations.ipynb)

## Problem Definition
- Are we able to predict if a patient will suffer from heart disease in patients based on their medical conditions?
- Which condition (variable) will be the most important in predicting whether a patient is likely to develop heart disease?

## Models Used
- K-Nearest Neighbours
- Decision Tree Classifier
- Logistic Regression
- Random Forest Classifier
- Neural Networks

## Summary and Conclusion
- The neural network model was the most accurate model in predicting whether a person has heart disease. 

- "Thal" is the most important variable in predicting heart disease as this variable is deemed the most important by 2 Machine Learning models.

- The Logistic Regression model's most significant feature was "sex" but our exploratory data analysis indicated no relationship between sex and heart disease. Thus, the coefficient feature importance method may not be entirely accurate.

- It is possible to predict if a person will suffer from heart disease & identify the most important factor using Machine Learning. ML models aid in early detection by identifying factors in patient data that can cause heart disease. For example, a patient with "Thal" type 1 and type 3 has a higher likelihood of heart disease, enabling doctors to diagnose and treat the condition earlier.

- To enhance accuracy in predicting the primary factor in determining heart disease, a dataset comprising medical records, lab results, lifestyle factors, and genetic data could have been used. This approach would have enabled the models to capture a wider range of risk factors

## What we learned from this project
- Random Forest Classifier, Logistic Regression, K-Nearest-Neighbours, and Neural Networks
- Finding the optimal value of K for the KNN model
- Finding the optimal depth for the Decision Tree Classifier
- Importance of scaling the data using Standard Scaler prior to Machine Learning
- Using the interactive library of Plotly for data visualization
- Label encoding. The necessity of having our target variable to be encoded with the values of 0 and 1 for the absence and presence of heart disease instead of "No" and "Yes". 
- Permutation feature importance method to deduce the most important feature in the KNN model
- Coefficient feature importance method to deduce the most important feature in the Logistic Regression model
- Using Github as a tool for collaboration

## References
- https://www.analyticsvidhya.com/blog/2021/11/neural-network-for-classification-with-tens
- https://machinelearningmastery.com/neural-network-models-for-combined-classification-and-regression/
- https://towardsdatascience.com/a-look-into-feature-importance-in-logistic-regression-models-a4aa970f9b0f
- https://scikit-learn.org/stable/modules/permutation_importance.html
- https://www.analyticsvidhya.com/blog/2021/11/training-neural-network-with-keras-and-basics-of-deep-learning/
- https://abiyevanar.medium.com/complete-exploratory-data-analysis-guide-with-python-plotly-259174e58885
