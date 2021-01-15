# World_Weather_Analysis

## Overview
Beta testers for the fictional app "PlanMyTrip" gave positive reviews, but recommended a few changes to enhance the app.  Suggestions included adding the weather description to the weather data and use input statements to filter data for weather preferences.  This will be used to identify potential travel destinations and nearby hotels.  This new feature will also allow users to choose cities to create their travel itinerary.

## Resources
- Jupyter Notebook
- Python v3.7.x
    - Dependencies:
        - pandas
        - requests
        - gmaps
        - numpy
  - APIs:
      - OpenWeatherMap
      - Google Places
      - Google Maps JavaScript
      - Google Directions
      
 ## Overview
 # Weather Database
This folder contains information from 740 countries that was retrieved with the OpenWeatherMap API.  The weather information consists of maximum temperatire, humidity, cloudiness, wind speed, country, date, and weather description.  The amount of information provided will allow app users to make an informed decision regarding their travel plans.  

Weather data retrieved can be found here:
- [WeatherPy_Database.csv](https://github.com/acfthomson/World_Weather_Analysis/tree/main/Weather_Database)


# Vacation Search
This folder contains data that was obtained via the weather database that was previoulsy created and uses the Google Maps API to plot potential travel locations based on the user's input for minimum and maximum temperature.  This graphic shows travel destinations between 75 and 90 degrees fahrenheit:
[Weather-Py-vacation-map.png](https://postimg.cc/t13P12fn)


# Vacation Itinerary
The Google Directions API was used to create a travel itinerary that shows the route between four cities from the user's selected travel destinations.
[Weather-Py-travel-map.png](https://postimg.cc/ZCzSHHD5)

A map displaying pop-up markers was created that showed hotel name, city, country, weather description, and maximim temperature for the selected travel destinations along the user's route.
[Weather-Py-travel-map-markers.png](https://postimg.cc/wRhnnKbT)
