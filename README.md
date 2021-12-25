
# Predicting Titanic Survivors
Titanic survival prediction is a classification problem where our objective is to predict whether the passenger of titanic will survive or not. 


## Source of Dataset
I downloaded the dataset from Kaggle.
## Describing Dataset
* Each row represents the data of one passenger.
* Columns represent the features. There are 10 independent features in this dataset excluding Id column. In training csv file, we have one more dependent feature. Features are :-
1. Survival:- This variable shows whether the person survived or not. This is our target variable & we have to predict its value. It’s a binary variable. 0 means not survived and 1 means survived.
2. pclass:- The ticket class of passengers. 1st  (upper class), 2nd (middle), or 3rd (lower).
3. Sex:- Gender of passenger.
4. Age:- Age(in years) of passenger.
5. SibSp:- The no. of siblings/spouses of a particular passenger who were there on the ship.
6. Parch:- The no. of parents/children of a particular passenger who were there on the ship.
7. Ticket:- Ticket number.
8. Fare:- Passenger fare.
9. Cabin:- Cabin number.
10. Embarked:- Port of Embarkation; From where that passenger took the ship. ( C = Cherbourg, Q = Queenstown, S = Southampton)


#### After Exploratory Data Analysis and Data Preprocessing, I tried 4 different machine learning models-
Logistic regression

KNN

SVM

Random Forest


#### Random Forest gives me high accuracy.

