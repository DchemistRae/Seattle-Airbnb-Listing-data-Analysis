# Seattle-Airbnb-Listing-data-Analysis
A data science project that uses the CRISP - DM Process to analyse Airbnb listing data in Seattle. See the [link](https://medium.com/@rasimhi/seattle-airbnb-data-how-to-get-the-best-accommodation-rate-for-your-seattle-getaway-5df2c11cdfb2) to the accompanying medium post of this project 

## Project
This project will use the open-source Airbnb data which describes the Seattle, WA homestays listing activity. This project will be used as a part of the "Become a data scientist Nanodegree"  program of Udacity. 

## Motivation
In a attempt to reduce the cost of accomodation in a Seattle get-away, Airbnb listing data in Seattle for the year 2016 will be analysed and modellled to answer the following questions:

      What are the busiest times of the year to visit Seattle? By how much do prices spike?
      what factors affect listing prices?
      time of the year with lowest rates?
      Neighbourhoods with lowest rates.

## The data

The dataset used is part of Airbnb Inside data, and the original source can be found [here](http://insideairbnb.com/get-the-data/).

listings.csv :Some of the activity included in the dataset include:
    Listings, including full descriptions and average review score
    Reviews, including unique id for each reviewer and detailed comments
    Calendar, including listing id and the price and availability for that day
    
calendar.csv: contains Airbnb listings and booking activities in Seattle for the year 2016.

 ## Other Files
 
 Other files are airbnb.ipynb: this contains the entire project in a jupyter notebook format.
 
 ## Libraries Used
 
pandas, numpy, matplotlib, seaborn and sklearn 

## Result Summary

The best time to Visit Seattle if Airbnb rates are sole indicators will be in January when prices are lowest. Totally avoid the period around July as it is the most expensive time as ascertained from the data. A way of keeping accomodation cost even lower is by choosing to rent an Airbnb in the cheaper neighbourhood such as Rainier Beach, Olympic Hills, South Delridge. Type of apartment could also influence cost, hence opt instead to stay in a smaller apartment with less bedrooms. 

## Acknowledgement

Opensource community at large as the data was downloaded from Kaggle website and AIrbnb for making this data available for use.
