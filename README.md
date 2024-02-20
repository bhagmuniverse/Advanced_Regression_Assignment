# Housing Case Study
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
> The company wants to know:
	1. Which variables are significant in predicting the price of a house, and
	2. How well those variables describe the price of a house.
> Also, determine the optimal value of lambda for ridge and lasso regression.

## Table of Contents
* [Libraries used](#libraries-used)
* [Observations](#Observations)
* [Acknowledgements](#acknowledgements)
* [Conclusion](#Conclusion)

## Libraries used
- Python 3
- Pandas
- Numpy
- Seaborn
- matplotlib.Pyplot
- sklearn

## Observations
1. R2 score of Ridge model for the train data is 91 and for the test data is 88
2. R2 score of Lasso model for the train data is 89 and for the test data is 87

## Top 5 features selected by lasso

 1. ('GarageFinish_RFn', 0.079),
 2. ('GarageFinish_Unf', 0.084),
 3. ('SaleCondition_Normal', 0.098),
 4. ('SaleCondition_Others', 0.12),
 5. ('SaleCondition_Partial', 0.198)]

 ## Top 5 features selected by Ridge

1. ('GarageFinish_RFn', 0.092),
2. ('GarageFinish_Unf', 0.094),
3. ('SaleCondition_Normal', 0.099),
4. ('SaleCondition_Others', 0.105),
5. ('SaleCondition_Partial', 0.143)]

## Conclusion
- This project was inspired by upGrad


## Contact
Created by @bhagmuniverse - feel free to contact me!