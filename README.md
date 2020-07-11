# world_weather_analysis

## resources

data sources: cities.csv, weather_database.csv, weatherPy_vacation.csv
resources: jupyter notebook, python, visual studio code
API's: openweathermap.org, google.com

## Overview

This project uses API's from google and openweathermap.com. A list of over 500 cities is generated randomly. The python library citipy is used to find cities close to these randomly generated latitude and longitute pairs. Once that is done various metrics were graphed ranging from temperature vs. latitude to wind speed vs latitude. Some work with regression analyis was done on these graphs as well. All of this is viewable through  weatherPy.ipynb. An openweathermap api key is required. 

## Vacation info

weather_database.ipynb, vacation_search.ipynb, and vacation_itinerary.ipynb all work together. weather_database.ipynb creates a list of over 500 randomly generated cities as described above. vacation_search.ipynb prompts the user for some weather preferences. vacation_itinerary.ipynb is an example travel map of 4 cities relatively close together. It uses google maps to generate a travel route and place markers at hotels in the selected cities. This will be updated eventually to sort the dataframe generated in vacation_search by latitude and longitude. vacation_itinerary will then use this sorted dataframe to create a travel map with hotels and weather data for each city. 
