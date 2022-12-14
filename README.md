# Final-Project-Statistical-Modelling-with-Python

## Project/Goals

My main goal in this project is to review and analyze data from different APIs and formats (json, csv, etc.)

## Process
1) Make requests and connect to Citybike, Foursquare, and Yelp API’s
- create credentials for api requests
- set credential environments on terminal 
- apply environments on vscode, python 

2) Once relevant data is gathered from corresponding API’s, extract and transform data to dataframes using python

3) Having subset dataframes for each API, use python to join tables using related datapoints (ie. ‘id’, ‘address’, ‘station name’) 

4) Analytically review joined dataframe to establish outline for statistical modelling 

5) Build regression model using Python’s `statsmodels` module 
- demonstrate a relationship between the number of bikes in a particular location and the characteristics of the venues in that location
## Results

As noted in the eda notebook, the main difference between the foursquare API data and yelp API data was one of quantity over substance. The foursquare data was able to provide a much larger amount of results returned for venues near bike stations (comparative to the yelp API), but did not offer as much detail (review counts, ratings, etc.) about the venues returned as the yelp API did. 

Using the yelp API data, we built a regression model between the amount of reviews that a venue recieved with the amount of bikes that were in use ('empty_slots') at the bike station nearest to that venue. We would expect that as a venue is more popular (measured by review count), the amount of bikes in use around that venue similarly increases. Unfortunately, our model shows that we can not assume that this relationship is not statistically significant.  

## Challenges 
1)  Creating/ accessing varible environment to store api keys locally 

2) Reading json data confidently and purposefully

## Future Goals

I would: 
- spend more time working with requests to fully understand the working relation between API’s and python 
- build more specific/constrained dictionaries and lists to extract data from JSON or CSV files without fillers 
-  fix/ reset variable environments set through terminal to avoid committing API keys to code, GitHub