## ecommerce-sales-analysis
E-Commerce sales data analysis and Sales prediction using python and machine learning
## Project overview
This project analyzes e-commerce sales data to identify factors affecting profit and develop a machine learning model to predict Sales based on different features. The goal is to help businesses optimize inventory management by identifying periods of high demand, reducing stockouts and improve supply chain planning. This project combines Exploratory data analysis, feature engineering and machine learning to uncover sales patterns and predict future sales.
# Business Problem
Businesses often experience difficulties in determining when to restock products due to fluctuations in customer demand. Without an accurate sales forecasting system, businesses risk:

Stock shortages during peak demand
Overstocking during low-demand periods
Increased inventory costs
Lost sales opportunities

This project addresses these challenges by building a predictive model that forecasts future sales based on historical business data.
This project includes:
Data cleaning
Data visualization
Correlation analysis
Linear Regression modelling
Model Evaluation
Residual Analysis

## Objective
Perform data quality validation and preprocessing.
Conduct exploratory data analysis to identify sales trends and patterns.
Analyze how different factors influence sales.
Build and evaluate machine learning models for sales prediction.
Compare Linear Regression and Random Forest Regression models.
Recommend the most suitable model for forecasting future sales.

## Tools and Techniques
Python
Pandas
Matplotlib
Numpy
Seaborn
Sci-kit Learn
Vs Code
## Data Preprocessing

The following preprocessing steps were performed:

Checked for missing values
Checked for duplicate records
Converted Order Date to datetime format
Created Year, Month, and Day features
Detected outliers using the IQR method
Encoded categorical variables
Split the dataset into training and testing sets

## Exploratory Data Analysis

The analysis included:

Correlation analysis
Multivariate analysis
Sales trends over time
Regional sales analysis
Category and subcategory performance
Pair plots
Sales distribution
Skewness and kurtosis analysis

Key insights identified seasonal demand patterns across different regions and product categories.

## Findings
Some Categories Make the highest profits yet they are not the best selling.
Sales have a strong positive correlation with profit

## Machine Learning Model
Two regression models were developed and compared:

Linear Regression
Random Forest Regression

The models were evaluated using:

R² Score
RMSE (Root Mean Squared Error)
Cross-validation
Residual analysis
Actual vs Predicted plots

Model Selection

Although both models performed well, Random Forest Regression was selected as the final model because it:

Produced more accurate predictions.
Achieved better overall evaluation metrics.
Generated residuals randomly distributed around zero.
Captured complex, non-linear relationships in the data more effectively than Linear Regression.

## Evaluation metrics
R2 Score: 0.9994
Root Mean Squared error evaluated
Residual plot
## Key Insights
Residual analysis was performed to evaluate the quality of the Random Forest model. The residual plot, which displays residuals against predicted sales values, showed that the residuals were randomly scattered around zero with no visible pattern. This indicates that the model successfully captured the underlying relationships in the data and that there were no systematic prediction errors.

 ## Author
 Mwamize Khalfan
 Computer Science Student
 Data Scientist


