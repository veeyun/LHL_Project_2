# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
* Access data using APIs
* Perform EDA using statistics and visualizations
* Identify trends and patterns in data
* Interpret results of statistical models

## Process
1. Accessed data using Citybikes, Foursquare and Yelp APIs

2. Selected Point of Interest data (restaurants, coffee shops, bars) within 1000m from each of the bike stations in Vancouver

3. Loaded data into database and created dataframe using Python 

4. Performed EDA using statistics (looked at shape of dataframe, looked for nulls, duplicates and outliers) and visualizations (boxplots, correlation between variables using heatmap and pairplots

5.  Merged the dataframes between citybike with yelp, and the dataframes between citybike and foursquare

6. Looked at correlations and generated regression models using the amount of bikes available at a bike station and POI characteristics such as "Rating", "Pricing", "Total Reviews"

## Results

The quality of the API coverage varied between Yelp and Foursquare. 

While Foursquare had finer details and more attributes, Yelp had a higher count of data for the POIs. 

While looking for correlations between bike stations and POI characteristics, there were no strong correlations found between bike stations and POI characteristics.

However, other correlations were found between attributes such as Yelp's "Total Reviews", "Popularity", "Rating" and "Pricing".

In the linear regression model for Foursquare POIs, there was no correlation between the number of total bikes and the number of photos taken at the POI location, as well as there was also no correlation between the total number of bikes and the popularity of the POI location.  Although there is some (almost neglible 0.002) correlation between the total number of bikes and the total ratings, it is still considered an extremely weak correlation (or even none). The linear regression model for Yelp also resulted in 0 correlations observed between the number of free bikes and the price scale at the POI, as well as the number of free bikes and the ratings at the POI location.


## Challenges 

There were various technical challenges faced during this project.

One of the biggest challenges was trying to find a trend and correlation between the bike stations and characteristics of the POI as it seemed as though a lot of them had almost no correlation.

Dropping duplicates and outliers would take some more time for some more analysis but there was some time constraint for this project. 

Another challenge was interfacing the Yelp and Foursquare APIs, extracting the meaningful attributes within the response.

## Future Goals

I'd like to clean my data again and also have the chance to view other POIs and analyze if they have a significant relationship with the number of bikes available or the total number of bikes in a particular station. I'd also like to try different cities and getting other data attributes to see if stronger correlations can be found.
