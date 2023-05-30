# Random Forest Hotel Cancelation
## Table of Contents
* [General Information](#general-information)
* [Technologies](#technologies)
* [Python Libraries](#Python-Libraries)
* [Files](#files)
* [Sources](#sources)
## General Information
In this data model, we are looking to predict hotel reservation cancellations. Categorical variables were all set with numerical values and transposed and converted to binary values. We used featurewiz for our feature selection. We then used the package random forest classifier to fit and train the model. The training data sets from Kaggle, "Reservation Cancellation Prediction," was used to train the model, and the "Binary Classification with Tabular Reservation Cancellation Dataset" training data set was used to test the model. Three different models were created, two with Random Forest Classifiers. One used all the features, and the other only used feature selection. The third model used Random Forest Classifiers with Hyperparameter tuning. We tested the accuracy and balanced accuracy of each model.
## Technologies
* python 3.7
## Python Libraries
* pandas
* numpy
* featurewiz
* scipy
* sklearn
* seaborn
* matplotlib
## Files
* Hotel Reservation Cancelation Model.ipynb: Coding file where model is created
* Random Forest Hotel Cancelation.pdf: final report
## Sources
Chow, A., & Reade, W. (2023). Binary classification with a tabular reservation cancellation dataset. Kaggle. https://www.kaggle.com/competitions/playground-series-s3e7/overview   

Dutta, G. (2023, January 6). Reservation cancellation prediction. Kaggle. https://www.kaggle.com/datasets/gauravduttakiit/reservation-cancellation-prediction 
