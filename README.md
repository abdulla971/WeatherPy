# WeatherPy

## Overview

The main purpose of this challenge is to collect, analyze and visualize weather data across cities worldwide and to give travelers a tool that allows them to chose their next travel destination based on weather conditions.

### Resources Utilized to Complete Analysis
* **CSV Files:** 
![Weather_Database.csv](Weather_Database/WeatherPy_Database.csv), 
![WeatherPy_vacation.csv](Vacation_Search/WeatherPy_vacation.csv)
* **Jupyter Notebook Files:**:
![Weather_Database.ipynb](Weather_Database/Weather_Database.ipynb), 
![Vacation_Search.ipynb](Vacation_Search/Vacation_Search.ipynb),
![Vacation_Itinerary.ipynb](Vacation_Itinerary/Vacation_Itinerary.ipynb)

* **Python**: Python v3.8.8, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON Traversals

## Project Plan

1. Task: Collect and analyze weather data across cities worldwide.
2. Purpose: Use the data to recommend ideal hotels based on clients’ weather preferences.
3. Method: Create a Pandas DataFrame with 500 or more of the world’s unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

## Main Stages

1. Collect the Data

- Use the *NumPy module* to generate more than 1,500 random latitudes and longitudes.

- Use the *citipy module* to list the nearest city to the latitudes and longitudes.

- Use the *OpenWeatherMap API* to request the current weather data from each unique city.

- Parse the *JSON* data from the API request.


2. Exploratory Analysis with Visualization

- Create scatter plots and linear regression of the weather data and determine the correlations.

- Create a series of heatmaps using the Google Maps and Places API.


3. Visualize Travel Data

Create a heatmap with pop-up markers that can display information on specific cities based on a customer’s travel preferences. 

## Background

Add the amount of rainfall or snowfall within the last three hours so that customers can filter the DataFrame based on the temperature range and whether or not it is raining or snowing. Create a directions layer Google map that shows the directions between multiple cities for travel.
