# World Weather Analysis
## Overview of Project
The project focused on learning how to use APIs to visualize weather data, as well as build a hypothetical app called "PlanMyTrip". The weather data was pulled utilizing OpenWeatherAPI to analyze how weather patterns correlate to latitudinal coordinates.  The weather variable used to show trends was "Max Temp".  In addition to pulling weather data, we also utilized Google Maps library of APIs to build a travel itinerary for the user.  Shown below is a sample of a potential user experience.

### Variables Used:
- City
- Latitude
- Longitude
- Max Temp
- % Humidity
- % Cloudiness
- Current Weather Description

## Simulation of User Experience (Traveling to 4 Cities)

### User Enters Preferred Weather (Based On Min/Max Temperature)
 - The app prompts the user to enter their preferred Minimum and Maximum temperature they would like for their trip
 - Once the information is entered, the app filters city results based on current weather data from over 700 cities
 ![WeatherPy_vacation_map](https://user-images.githubusercontent.com/89044350/134932380-98408ce5-7df6-4c0a-9d62-0ece4f305695.PNG)

The above image displays results for cities around the world with a current temperature between 80 - 90 degrees F. 

### User Chooses 4 Cities
![WeatherPy_travel_map](https://user-images.githubusercontent.com/89044350/134932955-bb9182fe-3b32-4217-aee5-20563078f46f.PNG)

In this simulation, the user has decided to travel to 4 different cities in Africa.  The above image shows the travel itinerary generated using Google Maps Directions API.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/89044350/134933195-7eb4dbb5-99ae-4dd6-8a91-b5bf2b714035.PNG)

The above image displays an "Info Box" attached to each city pin listing details for that city including:
 - Hotel Name
 - City Name
 - Country
 - Current Weather Description
 - Max Temp 
