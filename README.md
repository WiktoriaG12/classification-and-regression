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

At the beggining, I prepared a few descriptive statistic and checked for null. Nearly half of all respondents are going to shop in the supermarket. Women rated their satisfaction with the service and assortment in the supermarket higher.



Data was splitted into training data and testing data. I used 20% of data for testing and 80% for training. 


