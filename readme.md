# CA-Projects-template-submission-repo
## TEAM PARIS LP2 - TIME SERIES REGRESSION ANALYSIS PROJECT

## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| LP2 | Time series Linear Regression |  https://www.linkedin.com/posts/mugisha-eric-411547135_time-series-forecasting-and-analysis-of-store-activity-7059111657473474561-HJBH?utm_source=share&utm_medium=member_desktop |  https://github.com/E-hub-mugisha/LP2-REGRESSION-ANALYSIS-TIME-SERIES.-TEAM-PARIS--main|

## Project Description
Our project is a time series regression analysis project, Where we build regression project and build various models . Afterwards we will select and deploy our best model after tuning. 

## Setup
The set up of the training set was divided into 4 parts 

Part 1 : Understanding the business Objective and defining the success 
     
Part 2 : Understanding our data 
    Here we had a series of formulated questions and hypothesis to better understand our data 


Part 3 : Prepare our data for training 
    (a) Encode the categorical column
    (b) Scale the data, to prevent over/under fitting 
    (c) Split the data into train set and test set 

Part 4 : Training our various ML models and evaluate their metrics 
    (a) Model 1 - Linear Regression 
    (b) Random Forest 
    (c) Support Vector 
    (d) X Boost 1
    (e) X Boost 2 
    (f) Arima Model

| Model | r_2score | mean squared error | mean average error |
|-------|----------|--------------------|--------------------|
| Linear Regression | 0.233980 | 9.520182e+05 | 421.559150 |
| Random Forest | 0.937429 | 7.776341e+04 | 54.922638 |
| Support Vector | 0.350954 | 8.066418e+05 | 386.584585 |
| X Boost 1 (n=10) | 0.772901 | 2.822418e+05 | 194.316372 |
| X Boost 1 (n=50) | 0.772901 | 2.822418e+05 | 194.316372 |
| AR | 0.699139 | 1.211640e+06 | 510.246890 |


Part 5 : Fine tune our model
The goal is to: 
-(a) minimize RMSLE
-(b) increase r2 score  




## App Execution
...

**Authors**

- Elly Okumu

- Awudu Jamal

- Jonas Afutu

- Vincent Kipkorir 

- Eric Mugisha

- David Mantey

