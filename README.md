# World_Weather_Analysis

Analysis of weather and travel using APIs

## Overview

This project started out as a simple exploratory analysis on some simple weather data, but ended up being an application that gives travel and hotel suggestions based upon user weather preferences.

### Data Collection

The data was collected from free and open source sources.  The weather data was collected from the openweathermap.org API, the city locations from CitiPy and the hotel and map information was created using the Google API

## Weather Analysis

The analysis shows weather data including temperature, humidity, cloudiness, wind speed, etc, and performs regression analysis divided by southern and northern hemispheres as well as heat mapping the data onto a map.  The analysis can be found in the WeatherPy.ipynb file.

### Figures

A collection of figures made from the data are displayed below.  The data and figures can be found in the weather_data folder.

#### Weather Figures by Latitude

Latitude vs Temperature
![Latitude vs Temperature](/weather_data/fig1.png)

Latitude vs Humidity
![Latitude vs Humidity](/weather_data/fig2.png)

Latitude vs Cloudiness
![Latitude vs Cloudiness](/weather_data/fig3.png)

Latitude vs Wind Speed
![Latitude vs Wind Speed](/weather_data/fig4.png)

#### Linear Regression Analysis By Hemisphere

Latitude vs Temperature Northern Hemisphere
![Latitude vs Temperature](/weather_data/fig5.png)

Latitude vs Temperature Southern Hemisphere
![Latitude vs Temperature](/weather_data/fig6.png)

Latitude vs Humidity Northern Hemisphere
![Latitude vs Humidity](/weather_data/fig7.png)

Latitude vs Humidity Southern Hemisphere
![Latitude vs Humidity](/weather_data/fig8.png)

Latitude vs Cloudiness Northern Hemisphere
![Latitude vs Cloudiness](/weather_data/fig9.png)

Latitude vs Cloudiness Southern Hemisphere
![Latitude vs Cloudiness](/weather_data/fig10.png)

Latitude vs Wind Speed Northern Hemisphere
![Latitude vs Wind Speed](/weather_data/fig11.png)

Latitude vs Wind Speed Southern Hemisphere
![Latitude vs Wind Speed](/weather_data/fig12.png)

#### Heat Maps

Temperature
![Temperature](/weather_data/fig13.png)

Humidity
![Humidity](/weather_data/fig14.png)

Cloudiness
![Cloudiness](/weather_data/fig15.png)

Wind Speed
![Wind Speed](/weather_data/fig16.png)

## Travel Recommendation Software

The next part of the project was to create a piece of software that makes travel recommendations based upon the weather.  In the first program, the user enters the weather that they enjoy and the software shows a list of cities that have the desired weather.

The second program made for people who would like to travel to multiple nearby destinations within the same country.  The software recommends four nearby cities within the same country with the desired weather as well as accommodation.

### Data

A larger data set was collected from the openweathermap API.  The collection file and data can be found in the weater_database folder.

### Vacation Search

The first program uses all of the data collected from openweathermap API to create a map of cities that shows the most popular accommodation, the city and country, and the current weather and temperature. The files, data and image can be found in the vacation_search folder.  Sample output is shown below. 

Vacation Search Sample Output
![Vacation Search Sample Output](/vacation_search/WeatherPy_vacation_map.png)

### Vacation Itinerary

In the second program, the user inputs the weather that they would like for their next vacation.  The program outputs a sample itinerary consisting of four cities that are all nearby and within the same country.  The output of the cities is randomized and will vary if the program is run several times.

The program outputs the navigation map necessary to drive between the cities, and always ends in the same city that trip started in for ease of plane trips, car rentals, etc.  The program also outputs information on accommodations and weather for each of the cities in the recommended itinerary.

This program along with sample images can be found in the vacation_itinerary folder.  Sample output is shown below.

Vacation Itinerary Navigation Map
![Vacation Itinerary Navigation Map](/vacation_itinerary/WeatherPy_travel_map.png)

Vacation Itinerary Accommodation and Weather Map
![Vacation Itinerary Accommodation and Weather Map](/vacation_itinerary/WeatherPy_travel_map_markers.png)
