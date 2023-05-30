# XGBoost Digital Game-Based Learning
## Table of Contents
* [General Information](#general-information)
* [Technologies](#technologies)
* [Python Libraries](#Python-Libraries)
* [Files](#files)
* [Sources](#sources)
## General Information
This model uses the Kaggle dataset to Predict student performance. First, this explores the data and results 
to help identify patterns. We then aggregate the data because the creators of the competition have removed a significant amount of it. 
We then build the model to predict user answers in question groupings. For example, the first groupings are between levels 1-4, and questions 1-3 are answered in this group. Questions 4 to 13 are answered in levels 5-12, and questions 14-18 are between level groups 13 and 22. We have ten kfold groups using a logloss metric, with a max depth of 5 and 1000 n_estimators. We check the accuracy of the training data 
set with an f1 score. We then submit our results on Kaggle to check the accuracy. 
## Technologies
* Python 3.7
## Python Libraries
* pandas
* csv
* matplotlib
* numpy
* seaborn
* sklearn
* xgboost
* math
* jo_wilder
* gc

## Files
* EDA - Game Progress.ipynb: Coding file to explore data and analyze
* xgboost-jw (kaggle notebook).ipynb: Coding file to create model
* Predicting Users Answers Digital Game Based Learning.pdf: Final Report
## Sources
Predict student performance from game play. Kaggle. (n.d.). Retrieved April 1, 2023, from
https://www.kaggle.com/competitions/predict-student-performance-from-gameplay/
overview
