# ML-Assignment 1 - Statistical Measures

https://drive.google.com/file/d/1UlWRYU0UglE2ex3iFse0J6eCLEU8g98P/view?usp=
Given a dataset house_price.csv which contains property prices in the city of Bangalore. Examine price per square feet do the following.: 
Q1. Perform basic EDA. 
Q2. Detect the outliers using following methods and remove it using methods like trimming / capping/ imputation using mean or median .
a) Mean and Standard deviation. 
b)Percentile method(In percentile method, you can consider less than 5% and greater than 95% ).
c) IQR(Inter quartile range method) .
d) Z Score method .
Q3. Create a box plot and use this to determine which method seems to work best to remove outliers for this data? . 
Q4. Draw histplot to check the normality of the column(price per sqft column) and perform transformations if needed. Check the skewness and kurtosis before and after the transformation.  
Q5. Check the correlation between all the numerical columns and plot heatmap.  
Q6. Draw Scatter plot between the variables to check the correlation between them.  

# ML_Assignment_2_EDA_and_Preprocessing

Objective: The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning.

Dataset: https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view?usp=sharing

Key Components to be fulfilled:

1.Data Exploration:  Explore the data, list down the unique values in each feature and find its length. Perform the statistical analysis and renaming of the columns. 
2.Data Cleaning:  Find the missing and inappropriate values, treat them appropriately. Remove all duplicate rows. Find the outliers. Replace the value 0 in age as NaN Treat the null values in all columns using any measures(removing/ replace the values with mean/median/mode) 
3.Data Analysis:  Filter the data with age >40 and salary<5000 Plot the chart with age and salary Count the number of people from each place and represent it visually 
4.Data Encoding:  Convert categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms. 
5.Feature Scaling:  After the process of encoding, perform the scaling of the features using standardscaler and minmaxscaler. 

# ML_Assignment_3_Regression_Assignment

Objective:
 The objective of this assignment is to evaluate your understanding of regression techniques in supervised learning by applying them to a real-world dataset.

Dataset:
Use the California Housing dataset available in the sklearn library. This dataset contains information about various features of houses in California and their respective median prices.

Key Components to be Fulfilled:
 1.Loading and Preprocessing 

Load the California Housing dataset using the fetch_california_housing function from sklearn.
Convert the dataset into a pandas DataFrame for easier handling.
Handle missing values (if any) and perform necessary feature scaling (e.g., standardization).
Explain the preprocessing steps you performed and justify why they are necessary for this dataset.

2.Regression Algorithm Implementation 
 
 Implement the following regression algorithms:
*Linear Regression
*Decision Tree Regressor
*Random Forest Regressor
*Gradient Boosting Regressor
*Support Vector Regressor (SVR)
 For each algorithm:
 Provide a brief explanation of how it works.
 Explain why it might be suitable for this dataset.
 
3.Model Evaluation and Comparison

Evaluate the performance of each algorithm using the following metrics:
*Mean Squared Error (MSE)
*Mean Absolute Error (MAE)
*R-squared Score (R²)
Compare the results of all models and identify:
The best-performing algorithm with justification.
The worst-performing algorithm with reasoning.



