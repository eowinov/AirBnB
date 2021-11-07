# AirBnB Seattle Project

## Project Overview
This project uses data from AirBnB in Seattle from the years 2016 - 2017 and conducts data analysis regarding properties of the accommodations, the hosts, and the reviews of the customers.

## Installation
The project is based on Python 3.0 (Anaconda distribution. The following libraries are used:
1. numpy
2. pandas
3. matplotlib
4. sklearn
5. seaborn
6. datetime

## Data 
The data used in this project is available at Kaggle and can be found here: https://www.kaggle.com/airbnb/seattle 
The dataset in particular consists of 3 csv.-files:
- listings.csv
- reviews.csv
- calendar.csv

Though, the main data analysis was made on the listings.csv data, because it also includes metrics related to reviews and availability that can be found in the other two files.

## Business questions
Following business questions are answered throughout the project:

1. What are the property types and amenities of superhost vs. non-superhosts?
2. Does the response time of the host affect the review score rating?
3. What are the aspects that correlate to the price of the accommodation? How well can we predict the price?

## Summary of analysis
The data analysis shows that there are several property types and amenities that tend to appear more often in the group of superhosts. Moreover it gets clear, that the time a host needs to respond to a customer is correlated with more and better ratings and more booking behaviour. Thus, AirBnB hosts should pay attention to their response time to be successful with their accommodation rent. Finally the price of the accommodation is also an important indicator when it comes to booking an accommodation. The prediction model for the price is showing moderate results, as the variation in prices can not be fully explained by the given variables. Nevertheless, we see that accommodation features like the number of accommodants, number of bedrooms and bathrooms show a correlation with the price and can be used as an orientation for hosts while picking the price for their own accommodation.

