## Boom BikesCase Study
> The aim of the project is to build a multiple linear regression model for the prediction of demand for shared bikes for a US based company named BoomBikes. The goal is to find the below:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Steps Performed](#steps-performed)
* [Conclusions](#conclusions)



## General Information
- The project aims to achieve the identification of driving variables and their significance in predicting the demand of bike rental.
- The project is a part of the curriculum of upGrad's IIIT Bangalore EPGP in Machine Learning and Artificial Intelligence.
- The business objective is to predict the demand for shared bikes.
- For analysis bike sharing dataset from Boom Bikes has been taken for the years of 2018 and 2019.



## Steps Performed
- Importing the necessary libraries
- Importing the dataset
- Data Preparation
- Exploratory Data Analysis
- Model creation using:
    1. Model 1 using sklearn library
    2. Model 2 using statsmodels.api library
    3. Model 3 using RFE and statsmodels.api



## Conclusions
- From residual analysis for all the three models the conclusion is that multiple linear regression model is suitable for the dataset as the residuals do follow the assumptions od homoscedasticity and the residuals also follow a normal distribution. Also a linear relationship exists between the dependent variable and the predictor/independent variables.
- Out of the three models prepared: Model-1, Model-2 and Model-3, Model-3 was selected as the final model because it had fewer number of predictor variables and the R2 scores for both test and train data were in a comparable range for all the three models. Hence the model with lower number of predictors was chosen.
- Three top features were:
    1. temp
    2. light snow weather situation
    3. yr 
- Final model:
    𝑐𝑛𝑡 = 0.2340×𝑦𝑟 − 0.1062×ℎ𝑜𝑙𝑖𝑑𝑎𝑦 + 0.4502×𝑡𝑒𝑚𝑝 − 0.1396×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑 − 0.1102×𝑠𝑝𝑟𝑖𝑛𝑔 + 0.0494×𝑤𝑖𝑛𝑡𝑒𝑟 − 0.2916×𝑙𝑖𝑔ℎ𝑡𝑠𝑛𝑜𝑤 − 0.0831×𝑚𝑖𝑠𝑡 − 0.0704×𝐽𝑢𝑙 + 0.0564×𝑆𝑒𝑝 − 0.0479×𝑆𝑢𝑛𝑑𝑎𝑦 + 0.2597



## Technologies Used
- numpy - version 1.24.3
- pandas - version 1.5.3
- matplotlib - version 3.7.1
- seaborn - version 0.12.2
- statsmodels.ap1 - version 0.14.0
- sklearn - version 1.3.0



## Contact
Created by [@alokabhayajith] - feel free to contact me!