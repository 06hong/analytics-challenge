# analytics-challenge

An open data set and challenge to test exploratory data analysis skills of an analyst.  In this repo, you'll find the data and instructions for an assignment.

## Challenge 1:  Marketing Mix Assessment

This challenge will test your skill in understanding the relationships between marketing investment and an outcome variable.  For this challenge, please use the file called mmm.csv in the data folder.  

### About the data:

mmm.csv contains sales and marketing expenditure data for 2 years in an unknown industry for an unknown product. Each row represents a week. This is the only file the client has provided us. This data is assumed to be continuous, weekly data for 2 years - 104 weeks total.

These are the only facts shared about the columns of data:

- NewVolSales - Sales of the item being marketed.
- Base_Price - Price of the item being marketed during that period.
- Radio - Investment in radio advertising during that period.
- InStore - Investment in in-store promotions during that period.
- Newspaper - An indicator of newspaper inserts for that period.  Null values represent no insert used. [more info here](https://en.wikipedia.org/wiki/Insert_(print_advertising)
- Discount - The percentage discount offered during that period.
- TV - Investment in TV advertising during that period.
- Stout - unknown anomaly in the data?
- Website_Campaign - An indicator of a website campaign during that period.  Null values represent no website campaign used.


### Assignment

1. What follow up questions do you have for this client?
2. Sometimes we have incomplete information and still must perform some initial analysis.  Perform a quick exploratory data analysis on this data set given what you know. Attempt to find relationships between advertising and product sales. The client is interested in understanding the effectiveness of the advertising investments they've made over the past 2 years.

<strong>Please present your questions and initial findings as a series of data visualizations representing your take on an initial exploration of the data.  Please submit this as a PDF.</strong>

## Challenge 2:  Technical Challenge

Sometimes we must interact with strange data formats, and at times they may not be in the format needed to immediately support analytics. In this challenge, you'll attempt to analyze a document related to Chicago crime.  The data, which you'll find in the link below is in JSON format. It represents all crimes reported in Chicago since 2020.

### Assignment

Using the tool of your choice, please access the data in the link below, transform it into a dataframe or table, and answer the following question:

1. What "primary_type" of crime is reported most in ZIP code 60613 since 2020?

Chicago Crime Data in JSON can be found here:  http://abcf662db43574fd99b224e0ab41b018-1792580361.us-east-2.elb.amazonaws.com:8080/ 

<strong>Please submit your code and answer for that question.</strong>