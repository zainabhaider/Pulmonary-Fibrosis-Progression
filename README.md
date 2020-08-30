# Pulmonary-Fibrosis-Progression
My goal for this project was to predict longitudinal changes in lung capacity for patients with pulmonary fibrosis, using the OSIC Pulmonary Fibrosis Progression dataset on Kaggle. 

Lung capacity is measured through Forced Vital Capacity (FVC), which is a measure of the maximal exhalation of air from the lungs, in milliliters.
In this project, I utilized Multiple Linear Regression to predict FVC, given features such as age, sex, smoking status, and time since baseline assessments. 

**Summary**:
First, I conducted exploratory data analysis to familiarize myself with the data, identify important trends, and note any potential sources of biases in the data. After studying the data, I went on to conduct data cleaning. I removed outliers and encoded categorical data into numerical data in prepartion of building a model. Then, I trained the regression model to predict FVC values in the training dataset and evaluated the accuracy of my model using Root Mean Squared Error (RMSE). Finally, I used the regression model to predict FVC values in the submission dataset.

The dataset for this project is from the OSIC Pulmonary Fibrosis Progression project on Kaggle: https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression, 
which looks at lung capacity over time for patients with pulmonary fibrosis.


