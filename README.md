# Exploratory Data Analysis on SMRT Tweets

This demo will provide a brief introduction in performing a rudimentary analysis on train service disruptions in Singapore. Data scrapped are from the SMRT's twitter account and wikipedia containing the relevant train stations information such as name and code 

- scraping of data from website (twitter) using Selenium 
- scraping of tabular data from website (wikipedia) using Xpath
- exploratory data analysis (EDA) on the scrapped data
- data cleaning, data prepration and processing 
- geospatial analysis on frequency of service disruptions 

There are two primary methods of extracting data from the SMRT tweets (twitter website). The first method was to use the provided twitter API for getting SMRT tweets, while the second method was to scrap information out from the HTML codes on the official SMRT twitter website (https://twitter.com/smrt_singapore). Due to a limitation on the number of tweets the twitter's API could be pulled and an expected substantial number of SMRT tweets involved (approximately 4000 tweets), the latter method was employed to overcome twitter API's rate limitation 
