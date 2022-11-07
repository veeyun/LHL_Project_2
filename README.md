# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
* Access data using APIs
* Perform EDA using statistics and visualizations
* Identify trends and patterns in data
* Interpret results of statistical models

## Process
1. Accessed data using Citybikes, Foursquare and Yelp APIs

2. Selected Point of Interest data (restaurants, coffee shops, bars) within 1000m from each of the bike stations

3. Loaded data into database and created dataframe using Python 

4. Performed EDA using statistics (looked at shape of dataframe, looked for nulls, duplicates and outliers) and visualizations (boxplots, correlation between variables using heatmap and pairplots

5.  Merged the dataframes between citybike with yelp, and the dataframes between citybike and foursquare

6. Looked at correlations and generated regression models using the amount of bikes available at a bike station and POI characteristics such as "Rating", "Pricing", "Total Reviews"

## Results
(fill in what you found about the comparative quality of API coverage in your chosen area and the results of your model.)

The quality of the API coverage varied between Yelp and Foursquare. 

While Foursquare had finer details and more attributes, Yelp had a higher count of data for the POIs. 

While looking for correlations between bike stations and POI characteristics, there were no strong correlations found between bike stations and POI characteristics.

However, other correlations were found between attributes such as Yelp's "Total Reviews", "Popularity", "Rating" and "Pricing" 

## Challenges 

There were various technical challenges faced during this project.

One of the biggest challenges was trying to find a trend and correlation between the bike stations and characteristics of the POI.

Another challenge was interfacing the Yelp and Foursquare APIs, extracting the meaningful attributes within the response.

## Future Goals

To try different cities and getting other data attributes to see if stronger correlations can be found.
