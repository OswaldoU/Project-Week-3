# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
(fill in your description and goals here)

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
(fill in what you found about the comparative quality of API coverage in your chosen area and the results of your model.)

## Challenges 
(discuss challenges you faced in the project)

1)  Creating/ accessing varible environment to store api keys locally 

2) Reading json data confidently and purposefully

## Future Goals
(what would you do if you had more time?)

I would: 
- spend more time working with requests to fully understand the working relation between API’s and python 
- build more specific/constrained dictionaries and lists to extract data from JSON or CSV files without fillers 
-  fix/ reset variable environments set through terminal to avoid committing API keys to code, GitHub