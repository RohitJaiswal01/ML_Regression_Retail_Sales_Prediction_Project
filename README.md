# **ML_Regression_Retail_Sales_Prediction_Project**


![image](https://github.com/user-attachments/assets/4a3366de-7232-47b7-ac69-038f0df44632)


📊 Rossmann operates over 3,000 drug stores in 7 European countries. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. 

# **Dataset Link**
https://drive.google.com/drive/folders/1-pr4tUFBuCMsBjJSX6SbI2RAPsUvNsn0?usp=sharing


# **Problem Statement:**

Rossmann operates over 3,000 drug stores in 7 European Countries. Currently, Rossmann store managers are tasked with predicting their daily sales up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the 'Sales' column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment

# **Project Summary:**

The Rossman Sales Prediction project involved extensive data analysis, feature engineering, and model selection to accurately forecast sales. Here is a brief overview of the project steps and key findings:

**1. Data collection and Cleaning**

Collected historical sales data for Rossmann stores, including competitor details, holiday details, customer details, and daily sales detail
Cleaned and prepared the dataset for analysis ensuring data integrity
Handled missing values and outliers to improve the quality of the data.


**2. Exploratory Data Analysis (EDA)**

Conducted in-depth EDA in order to extract valuable insights from the data set by exploring univariate, bivariate, and multivariate relationships.
Generated insightful visualizations to uncover patterns and trends in the data.
Extracted meaningful insights to inform future decision-making in the machine learning pipeline.


**3. Feature Engineering and Preprocessing**

Engineered new features, including PromoDuration and Competition Distance, to capture essential information.
Addressed multicollinearity among independent variables using variance inflation factor (VIF) analysis.
Detected and managed outliers using the Interquartile Range (IQR) technique.
Applied One-Hot Encoding to categorical variables for compatibility with machine learning algorithms.
Employed various transformation techniques to achieve a normal distribution of data.


**4. Model Selection and Training**

Split the preprocessed data into training and testing sets to evaluate model performance.
Implement multiple machine learning algorithms, including linear regression, decision trees, and random forest with regression techniques
Evaluated model performance using metrics such as R-squared score, means square error, and root mean square error
Employed regularization techniques, including Lasso, Ridge, to enhance model performance.

**6. Conclusion**

After thorough experimentation with various machine learning The XGBoost model emerged as the top-performing model for sales prediction.
It achieved an impressive R2 score of around 97.5%** on the training data and maintained 96% on the test dataset.
The model displayed lower Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) values compared to other models, indicating superior predictive accuracy.
Consistent performance across multiple evaluation metrics, including R2 score, MSE, and RMSE, suggests robust generalization.
Residuals analysis revealed well-behaved residuals with mean and median values close to zero, affirming the model's ability to capture underlying data patterns effectively
This project showcases the effective utilization of data analysis, feature engineering, and machine learning techniques to solve a real-world forecasting problem. The insights gained from the analysis provide valuable information for decision-making within the retail industry.
