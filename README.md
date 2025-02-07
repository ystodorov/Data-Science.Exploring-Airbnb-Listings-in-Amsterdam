# Exploring Airbnb Listings in Amsterdam
### by Yuri Todorov

In this project we'll analyze data about AirBNB listings in Amsterdam, Netherlands. The data is taken from http://insideairbnb.com/ and is sourced from publicly available information from the Airbnb site. It has been scraped from the website on 05 June, 2023.<br><br>

The project was created as part of an assignment during my education in the AI program of SoftUni. 

## Abstract 

This project aims to predict the prices of Airbnb listings based on a comprehensive analysis of various features and factors that influence pricing. The project utilizes a dataset containing information about Airbnb listings, including property characteristics, location, amenities, host information, and guest reviews. The goal is to develop a regression model that accurately predicts listing prices, which can provide valuable insights to hosts, travelers, and the Airbnb platform itself. This prediction can aid hosts in setting competitive prices for their properties and assist travelers in making informed decisions when choosing accommodations. Additionally, the project contributes to the broader understanding of the factors that influence pricing in the short-term rental market.<br><br>
I've used three datasets:
 - <b>Listings</b>: A csv file containing a list of all properties available for renting in Amsterdam at the time of the scraping. It contains 75 features descibing them.
 - <b>Reviews</b>: A csv file with all comments left from the guests. I'll use it to try to justify and find the reason for low review scores in certain neighbourhoods.
 - <b>Neighbourhoods geo-dataset</b>: geojson file containing geometry data in the form of multipolygons as  which will help me draw the neighbourhoods and make analysis on the map.

## Contents 

* 1. Reading and tidying data. Preparing data for exploration
* 2. Columns Description
* 3. Analyze data quality and make feature selection, feature extraction and feature engineering based on the result
    * 3.1. Listings dataset
    * 3.2. Reviews dataset
    * 3.3. Neighbourhood geometry dataset
* 4. Geospatial analysis
* 5. Analyze guests reviews
    * 5.1. Merge the two datasets 
    * 5.2. Create wordcloud for each neighbourhood
* 6. Heat-map of correlation  
* 7. Prediction

* 8. Key Accomplishments and conclusion
