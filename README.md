# 1015 Mini Project - CSGO Round Predictions

An analysis of pre-round factors and how they affect which team wins a round in Counter Strike: Global Offensive.

We have retreived the dataset for this project from [here](https://www.kaggle.com/datasets/mateusdmachado/csgo-professional-matches).

Specifically, we are using the economy dataset which includes the Teams, Map played, Spending and Outcome of each round.


## Problem Definition

#### 1. Can we predict who will win a round before the round starts? 
#### 2. What is the most accurate model to do so?


## Libraries

* Pandas for general data frame handling
* Scikit-Learn for machine learning
* Seaborn for data visualisation
* NumPy for data wrangling

## Models used

* Decision Tree Classifier
* Gradient Boosting Classifier
* Random Forest Classifier

## Conclusions

* It is possible to predict a round's outcome with reasonable accuracy(67%) with only the starting difference in economy.
* Pistol rounds are indeed the most fair rounds as they are the hardest to predict.
* Some maps really do have inherent bias towards T/CT.

## What have we learnt?
1. Restructuring datasets to fit the requirements for machine learning
2. Ensemble trees and how they work
3. Optimization of algorithms to handle huge datasets
4. Difference between Accuracy, Precision, Recall and f1
5. Complicated algorithms may not always mean the best accuracy


## Contributions
Jiang Yunjun @CopsEatingDonuts - Exploratory Data Analysis & Machine Learning

Tan Pat Guan @beanorockz - Data Cleaning & Machine Learning

Benjamin Yick @benjaminyjr - Slides, Presentation & Documentation

## References

https://scikit-learn.org/stable/modules/classes.html#module-sklearn.ensemble

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingClassifier.html#sklearn.ensemble.HistGradientBoostingClassifier

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier
