# World Weather Analysis Module 6
Using Python, API, and gmaps

## Overview and Parameters

We exam weather patterns around the world and design a user input weather app that can provide destination recommendations based on preferred  temperatures. Using Python, OpenWeatherMap, and Google Map API we will analyze weather databases, perform a filtered search and recommend a driving itinerary using the returned destinations from the perferred temperature inputs. 

### Deliverable 1 : Retrieve Weather Data
Using the "citipy module" we generated 2000 random latitudes and longitudes points and mapped them to over 750 cities. Using the OpenWeatherMap API we were able to filter the cities into a dataframe with the following data:

1. City Name
2. Country
3. Latitude and Longitude
4. Maximum Temperature
5. Humidity
6. Cloudiness
7. Wind Speed
8. Weather Description
![weather_database_folder](https://github.com/JimmyJ-D/World_Weather_Analysis/blob/main/Weather_Database/dataframe.png) 

![world_marker_map](https://github.com/JimmyJ-D/World_Weather_Analysis/blob/main/WeatherPy_vacation_map.png)

### Deliverable 2: Creating a Travel Map 

Using the retrieve weather data we developed a user search interface for vacationers maximum and minimal ideal temperatures at their potential vacation destination. Using Google Maps API we able to show those destination on a marker layer map. 
![vacation_serarch_folder](https://github.com/JimmyJ-D/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

### Deliverable 3: Create an itinerary 

Taking the users preference on weather of maximum 90 degrees and minimal of 75 degree for vacation destination we were able to map them a 4 city driving tour in Brazil using Google Maps API. Weather pattern change daily and our data pull from January 2021, so the majority of the warmer climate cities are Southern Hemisphere that will be equal to and or less that zero degrees longitude.  

![vacation_itinerary_folder](https://github.com/JimmyJ-D/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

ALL API KEYS HAVE BEEN REMOVED FROM THE CODE PER INSTRUCTIONS. 
