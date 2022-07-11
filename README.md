# Python-API-challenge: What's the Weather Like?

This repository contains scripts and outputs for two challenges: WeatherPy and VacationPy.

## WeatherPy

The following folder contains analysis of the weather of 500+ cities around the globe, utilising the OpenWeatherMap API. 

The following plots are produced:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Further analysis has been undertaken on both the Northern Hemisphere and Southern Hemisphere. A series of scatter plots and linear regressions have been produced for the following:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

Output files: [Outputs](WeatherPy/Output)

## VacationPy

Utilising the data produced in the script above, the following challenge produces a heatmap displaying the humidity for each city.

In addition, Google Places API has been utilised to find the first hotel located within 5,000 meters for the cities that have the following weather conditions:

* A maximum temperature above 30 (F)
* A wind speed below 4 (mph)
* A humidity level below 50%
* A cloudiness level equal to 0%

Output files: [Outputs](VacationPy/Images)
