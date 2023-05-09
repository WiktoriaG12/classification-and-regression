# Projects


## Project 1: Prediction of purchases in the supermarket
The aim of the project is to compare which of the methods best predicts whether a person with certain characteristics will  make a purchase in the supermarket. I used such classifiers as **Decission Trees**, **Random Forest** and **k-Nearest Neighbors**. 
Confusion matrix, accuracy, precision, recall an ROC curve were used to evaluate the quality of classifiers. 

Variables:
* assortment - satisfaction with the assortment in the supermarket (0-100)
* service - satisfaction with the service in the supermarket (0-100)
* day - the number of days in a week when the customer makes purchases
* income - average income (monthly)
* internet - shopping online (0 - no, 1 - yes)
* other - number of other supermarkets in which the person does shopping
* credit_card - having a credit card (0 - no, 1 - yes)
* age - age in years
* sex - (0 - men, 1 - woman)
* loan - taking a loan (0 - no, 1 - yes)
* distance - distance of residence
* purchase - Are you going to shop at the supermarket? (0 - no, 1 - yes)

At the beggining, I prepared a few descriptive statistic and checked for null. There are no null values. Nearly half of all respondents are going to shop in the supermarket. Women rated their satisfaction with the service and assortment in the supermarket higher.

Data set was splitted into training data and testing data. I used 20% of data for testing and 80% for training. 
## Results: 
* Decission Trees Classifier:
- Accuracy = 0,85 (85% of the values were classified correctly)
- AUC = 0,89
- The most important variable was number of other supermarkets in which the person does shopping.
* Random Forest Classifier:
- Accuracy = 0,85 (85% of the values were classified correctly)
- AUC = 0,91
- The most important variables were number of other supermarkets in which the person does shopping and satisfaction of 
.... service.
* k-Nearest Neighbors Classifier:
- Accuracy = 0,83 (83% of the values were classified correctly)
- AUC = 0,90

To sum up, the best results were obtained to Random Fores Classisier (the highest accuracy and AUC). 


## Project 2: Prediction of satisfaction with supermarket service
The aim of the project is to compare which of the regression methods best predicts whether a person with certain characteristics is satisfied with supermarket service. I used such regressors as **Decission Trees**, **Random Forest** and **k-Nearest Neighbors**. 
Root mean square error were used to evaluate the quality of regressors (the lower the RMSE, the better a given model is able to fit a dataset).

Variables:
* assortment - satisfaction with the assortment in the supermarket (0-100)
* service - satisfaction with the service in the supermarket (0-100)
* day - the number of days in a week when the customer makes purchases
* income - average income (monthly)
* internet - shopping online (0 - no, 1 - yes)
* other - number of other supermarkets in which the person does shopping
* credit_card - having a credit card (0 - no, 1 - yes)
* age - age in years
* sex - (0 - men, 1 - woman)
* loan - taking a loan (0 - no, 1 - yes)
* distance - distance of residence

Data set was splitted into training data and testing data. I used 20% of data for testing and 80% for training. 

## Results: 
* Decission Tree Regressor:
- MSE = 12,97
- RMSE = 3,60
- The percentage of error in the prediction is 6,68%.
- The most important variable was income and assortment.
* Random Forest Regressor:
- MSE = 26,79
- RMSE = 5,17
- The percentage of error in the prediction is 9,60%.
- The most important variable was aincome and assortment.
* k-Nearest Neighbors Regressor:
- MSE = 65,99
- RMSE = 8,12
- The percentage of error in the prediction is 15,07%.

The best results were obtained to Decission Tree Regressor (the lowest RMSE).


![alt text](https://github.com/WiktoriaG12/projects/images/blob/main/purchase\)sex.png?raw=true)
