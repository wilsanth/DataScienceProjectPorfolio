# Naive Bayes - First Event in Hockey Game
## Table of Contents
* [General Information](#general-information)
* [Technologies](#technologies)
* [Python Libraries](#Python-Libraries)
* [Files](#files)
* [Sources](#sources)
## General Information
The purpose of this model is to pull data from the undocumented NHL website to try and see if a team is the first 
to each type of event, does it increase their odds of winning a game? We first pull the data from the 
API, and then we clean it and run it through a few models to test the results. 
## Technologies
* Python 3.7
## Python Libraries
* pandas
* regex
* numpy
* urllib3
* requests
* sqlite3
* IPython.display
* json
* datetime
* seaborn
* matplotlib
* sklearn
## Files
* DataPull.ipynb: Coding file that pulls the data from the API
* EDA.ipynb: Coding file for EDA and model results
* Who controls the rink.pdf: Report on final findings. 
## Sources
NHL. (2020). Https://statsapi.web.nhl.com/api/v1. Retrieved June 21, 2020, from
https://statsapi.web.nhl.com/api/v1/schedule