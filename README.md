# IDEA PROPOSALS:


## Title 1: User Retention Prediction for Application Developers

Problem Statement: 

For application developers, a potential challenge for them would be the user retention. They need a realiable and reuseable method to simluate the retention rates of their users so that they can figure out which group of users are likely to be retained/churned. In this way, they can later on keep different users interested in their product by performing corresponidng retention task.

Abstract:

Create a cloud hosted BigQuery machine learning model to determine the likelihood rates of users continue to use the app based on the user behaverior logs and user demographic information.

Approach:
1. Pre-process the training data using user's demographic and behavioural logs.
2. Train and evaluate machine learing models using BigQuery ML in GCP.
3. Make predictions using the terminative ML model.
4. Create project dashboard and perform visualization of the prediction results.

Technology Stack:

Python, Bigquery(SQL), GCP

Persona:

Undecided



## Title 2:  Generating a Safety Score for Areas Given Crime Data 

Problem Statement:
There aren't any applications that help people determine if traveling between locations in San Francisco is necessarily safe. The question of safety is typically decided based on how individuals feel given the time of year and the time of the day. 


Abstract: We would try to build a model that generates a "safety score" which gives users a more quantitative tool to determine how safe their plans are.   

Dataset: https://www.kaggle.com/c/sf-crime

Approach:

1. Go through the data to attain an understanding of it
2. Preprocess the data
3. Decide the best types of models that would help us determine a safety score
4. Choose which metrics to emphasize 
5. Maximize those metrics
6. Create a front/backend for users to utilize


Technology Stack = Python

Personas:

Undecided

## Title 3:  Medical Insurance Cost Prediction for Citizens 

Problem Statement:

The objective of this article is to accurately predict insurance costs based on people’s data, including age, Body Mass Index, smoking or not, etc. Additionally, we will also determine what the most important variable influencing insurance costs is. These estimates could be used to create actuarial tables that set the price of yearly premiums higher or lower according to the expected treatment costs. This is a regression problem.

Dataset: https://bit.ly/3H8Oeff

Abstract 

Create a Tensorflow machine learning model to determine the insurance cost for medicine based on patient's personal information.

Approach :

1. Data Cleaning
2· Exploratory Data Analysis
3· Metrics and Validation Strategy
4· Modeling
5. Linear Regression
6. Polynomial Regression
7. Model Evaluation

Technology Stack = Python/R 
