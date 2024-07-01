# Insurance-Pricing-Forecast-Using-XGBoost-Regressor
This data science project aims to build and evaluate linear and xgboost regression models and determine the healthcare charges of each customer


## Insurance Pricing Forecast Using XGBoost Regressor Project Overview 
**Overview**

○ Insurance companies cover expenses the policyholder incurs from damages to health or property policies commonly offered: medical bills, house, motor vehicle, and fire 
   insurance, and financial losses such as a loss of income against a fee or premium paid by the client.n/
○ Traditional approaches to premium calculation require a lot of time-consuming human labor and are getting more complicated daily to capture the increasingly complex 
   interactions in the data. 
○ Insurance firms should normally collect a higher premium than the amount given to the insured individual if that person files a valid claim to generate a profit. Since 
   profitability is the fundamental factor that helps the insurance firm survive, it needs a mechanism for reliably forecasting healthcare expenses. 

Hence, this project aims to build a machine learning model that helps establish the rates by predicting the charges or payouts done by the health insurance firm to maintain profitability. This project will primarily focus on building an XGBoost Regressor to determine healthcare expenses based on features such as age, BMI, smoking, etc. 
We will also learn about categorical correlation, build a linear regression model as a baseline, and compare it with the results of the XGBoost Regressor. 


**Objective**: This data science project aims to build and evaluate linear and xgboost regression models and determine the healthcare charges of each customer. This analysis will help the insurance firm to strategize a premium plan that will help maximize the profits. 

**Data Description**: The insurance price forecast dataset contains historical records for 1338 insured customers. 
The column definitions are below 
● age: Age of the primary beneficiary. 
● sex: Gender of the primary beneficiary. 
● BMI: Body mass index of the primary beneficiary 
● children: Number of children the primary beneficiary has. 
● smoker: Whether the primary beneficiary smokes. 
● region: The primary beneficiary's residential area in the US.
● charges: Individual medical costs billed by health insurance.

**Tech Stack** 
● Language: Python 
● Libraries: pandas, numpy, matplotlib, plotly, statsmodels, sklearn, xgboost, skopt Approach

**Exploratory Data Analysis (EDA)**:  
○ Distributions 
○ Univariate Analysis 
○ Bivariate Analysis 
○ Correlation 
       ■ Pearson Correlation 
       ■ Chi-squared Tests 
       ■ ANOVA 
       
**Build and evaluate a baseline linear model**: 
 ○ Linear regression assumptions 
 ○ Data preprocessing 
 ○ Model training 
 ○ Model evaluation 
        ■ RMSE 
        
**Improve on the baseline linear model**:
○ Introduction to a non-linear model - XGBoost ○ Data preprocessing 
○ Using Sklearn's Pipeline to optimize the model training process 
○ Model evaluation 
        ■ RMSE 
○ Comparison to the baseline model 
● Presenting the results to non-technical stakeholders

**Modular code overview**: 
The requirements.txt file has all the required libraries with respective versions.
Install the file using the command "pip install-r requirements.txt4". 

**Takeaways** 
○ Understanding the insurance pricing problem statement 
○ Exploratory Data Analysis on Categorical and Continuous Data 
○ Univariate Data Analysis 
○ Bivariate Data Analysis 
○ Understand Correlation Analysis 
○ Categorical Correlation with Chi-squared 
○ Correlation between Categorical and Target Variables with ANOVA 
○ Label Encoding for Categorical Variables 
○ Understanding Linear Regression Assumptions 
○ Implementing Linear Regression 
○ Validating Linear Regression Assumptions 
○ Understanding XGBoost Regressor 
○ Implementing XGBoost Regressor 
○ Building pipelines with Sklearn’s Pipeline operator 
○ Implementing BayesSearchCV for XGBoost Hyperparameter Optimization 
○ Evaluating Models with Regression Metrics - RMSE 
○ Presenting Non-Technical Metrics for Stakeholders
 
