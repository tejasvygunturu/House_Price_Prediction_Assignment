# House_Price_Prediction_Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

* <a href="https://github.com/tejasvygunturu/House_Price_Prediction_Assignment/blob/main/train.csv">Dataset</a>

> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


## Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. Ridge and Lasso Regeression



## Technologies Used
- Scikit-Learn
- Matplotlib
- Numpy
- Seaborn
- Pandas

## Conclusions
* The optimal lambda value in case of Ridge and Lasso is as below:

> Ridge - 9.0
  Lasso - 0.0005
* The Mean Squared error in case of Ridge and Lasso are:

> Ridge - 0.01358
  Lasso - 0.013329
* The Mean Squared Error of Lasso is slightly lower than that of Ridge

* Based on Lasso, the factors that generally affect the price are Zoning classification, Living area square feet, Overall quality and condition of the house, Foundation type of the house, Number of cars that can be accomodated in the garage, Total basement area in square feet and the Basement finished square feet area

Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price of a house

## Contact
Created by [@tejasvygunturu](https://github.com/tejasvygunturu)
