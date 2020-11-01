# World Weather Analysis
## Overview of the project
The purpose of the project is to provide the user with travel destinations and hotel recommendations based on their desired city and weather criteria. Python script is used to visualize the weather of 500+ cities across the world of varying distance from the equator, using Python library, Openweather, Google API keys and create a representative model of weather across world cities. 

## Steps Performed 
1.	Performed an API call with the OpenWeatherMap to retrieve the following weather details:

- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed 
- Weather description.

2.	Added the data generated to a new Data Frame and exported the Data Frame as a CSV file, and saved it as ```WeatherPy_Database.csv``` in the ```Weather_Database``` folder.

3.	Inputted desired temperature ranges in the ```Vacation_Search.ipynb``` from the ```Vacation_Search``` folder and based on the input temperature ranges it will filter out the destinations. The output will be a google map with markers and a csv dataset that can be used for building an itinerary.

4.	Lastly in the ``` Vacation_Itinerary.ipynb ``` file using the Google Maps Directions API and a marker layer map created a travel route between the four selected cities of choice from the google maps displayed. This will give you the best route between the cities depending upon your mode of travel i.e. 'Driving', 'Walking' or 'Bicycling'.
