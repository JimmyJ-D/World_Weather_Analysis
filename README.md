# World Weather Analysis Module 6
##Using Python, API, and gmaps

## Overview and Parameters

We have been has to look at weather patterns around the world and design a simulation of a weather app that takes uses input and provide recommended destination and travel itinerary map. Using Python, gmaps and OpenWeatherMap we will analyze weather databases, perform a vacation search and recommend a driving itinerary. 

### Deliverable 1 : Retrieve Weather Data
Using the "citipy module we generated 2000 random latitudes and longitudes points and map them to over 750 cities. Using the OpenWeatherMap API we were able create a dataframe with the following:

1. Latitude and Longitude
2. Maximum Temperature
3. Percent Humidity
4. Percent Cloudiness
5. Wind Speed
6. Weather Description
![weather_database_folder](https://github.com/JimmyJ-D/World_Weather_Analysis/blob/main/Weather_Database/dataframe.png) 

### Deliverable 2: Creating a Travel Map 

Using the weather data from the dataframe we developed a user search interface for vacationers maximum and minimal ideal temperature at their potential vacation destination. Using Google Maps API we able to show those destination on a marker layer map. 
![vacation_serarch_folder](https://github.com/JimmyJ-D/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

### Deliverable 3: Create an itinerary 

Take the users preference on weather of maximum 90 degrees and minimal of 75 degree for vacation destination we were able to map them a 4 city driving tour in Brazil using Google Maps API.

![vacation_itinerary_folder](https://github.com/JimmyJ-D/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
