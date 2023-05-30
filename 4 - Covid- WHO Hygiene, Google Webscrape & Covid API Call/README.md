## Covid- WHO Hygiene Coverage, Google Webscrape & Covid API Call
* [General Information](#general-information)
* [Technologies](#technologies)
* [Python Libraries](#Python-Libraries)
* [Files](#files)
* [Sources](#sources)
## General Information
This project aims to create a database from multiple sources and run some analysis. The focus of the study was on COVID. The first dataset is from the World Health Organization, which identifies the status of hygiene coverage among countries worldwide. The second dataset comes from the covid API, where we pulled back the number of cases, deaths, and those still with the virus.
We used the countries that pulled back from the covid API call for the last dataset and did a Google News search for each. We pulled the top ten results from our investigation and did a web scrape on the article to find keywords in each. We did a word count for each. All of the results are stored in a SQL lite database. 
<br><br>
Below are a list of all the keywords used in the search.

```
keywords = 
	[
			# any word related to the coronavirus
			['virus','coronavirus','covid-19','severe acute respiratory syndrome coronavirus 2 ','novel coronavirus','epidemic','pandemic','coronavirus symptoms','what is coronavirus','influenza'],
			# words related to a cure 
			['cure', 'vaccine', 'treatment', 'remedy', 'treat', 'immunization',' medicine', 'antidote', 'medication', 'medicament',' thearapy',' healing',' put an end to', 'remove', 'counteract'],
			# words realated to death or people dying
			['death', 'dead', 'deceased', 'die', 'terminated', 'demise',' dying', 'end',' passing', 'expiry', 'expiration'],
			# words related to counts whether increasing or decreasing
			['cases', 'count', 'total', 'instance', 'occurrence', 'occasion', 'manifestation', 'demonstration'],
			# words related to money, income,etc...
			['money',' stimulus', 'supplement', 'income', 'salary', 'pay', 'wages', 'stipend', 'revenue',' receipts',' takings', 'profits', 'loss', 'gains', 'proceeds',' turnover',' employment', 'unemployment', 'yield', 'dividend',' interest', 'rates',' means', 'expenditure',' outgoings', 'wealth', 'poverty'],
			# words related to distancing and isolation
			# this pandemic has flipped the world upside down with being quarantined 
			['social distancing', 'congregate settings', 'isolation', 'quarantine',' community spread',' flattening the curve', 'withdraw', 'detach', 'separate', 'isolate', 'detachment', 'confinement', 'seperation', 'seclusion', 'remote', 'segregation', 'distance', 'distancing'],
			# looking for demographic words
			['demographic', 'race', 'rural', 'population',' densely populated', 'citizens', 'public', 'community',' society', 'race', 'residents',' people',' society', 'natives', 'country', 'countryside'],
			# medical supplies seems to be an issue as well
			['supplies', 'supply',' medical supplies', 'incubation', 'stock', 'store', 'reserve', 'reservoir', 'stockpile',' heap', 'mass', 'equipment', 'apparatus', 'incubation', 'incubatore', 'respiroator', 'mask', 'beds',' hospital',' health care',' clinic', 'infirmary', 'sanitation', 'swab',' test', 'scrubs']
		]
```
## Technologies
## Python Libraries
* os
* pandas
* numpy
* matplotlib
* sqlite3
* regex
* BeautifulSoup
* multiprocessing
* urllib3
* requests
* IPython.display
* string
* Levenshtein
* import glob
* scipy
* seaborn
* geopandas
* geonamescache

## Files
* 1 - Create WashDash SQLlite Database.ipynb: Coding file to load and analyze the WHO hygiene data
* 2 - Google scrape.ipynb: Coding file to scrape Google and news feeds
* 3 - Covid API Call data.ipynb: Coding file for the covid API data pull and load
* 4 - Analysis.ipynb: Coding file to bring the data together in one location
* #covid_cases.png: example of the covid map

## Sources
WHO/UNICEF. (n.d.). Home: JMP. Retrieved April 6, 2020, from https://washdata.org/

https://covid-api.com/api/