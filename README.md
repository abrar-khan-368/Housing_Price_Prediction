# Housing Price Prediction
> The objective of this project is to help Surprise Housing, a US-based housing company, enter the Australian market by building a regression model using regularization to predict the actual value of prospective properties. The model will assist the company in deciding whether to invest in these properties or not.

# Data Source:
> The data for this project is provided in a CSV file containing information about the sale of houses in Australia. The file contains various variables that might influence the price of a house. The dataset will be used to train and evaluate the regression model.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
  - Which variables are significant in predicting the price of a house.
  - How well those variables describe the price of a house.

## Conclusions
- Ridge and Lasso model both have given the almost the same accuracy, and it concludes that overfitting is not present.
- R2 Score of both the model on test dataset is 0.8713 and 0.8747 respectively.
- In Lasso regression the model has selected 105 features excluding 121 features
- Also from above we can see the top 25 features of Lasso regression.


## Technologies Used
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodel


## Contact
Created by [@abrar-khan-368] - feel free to contact me!
