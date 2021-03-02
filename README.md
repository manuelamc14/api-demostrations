# WeatherAPI-and-googleAPI-Demostration

## Dependencies

* Matplotlib.pyplot 
* Pandas 
* Numpy 
* Requests
* Gmaps
* Json

## APIS

* https://openweathermap.org/api
* https://developers.google.com/maps/documentation/places/web-service/overview

## Description

The aim of this project is to demonstrate how to use API to acquire information. The project is split in two sections: WeatherPy and Vacation Pay.

WeatherPy section is focusing on creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.The cities were chosen through a random generation of latitude and longitude values and selecting  the closest cities to those values.

![ScreenShot](https://github.com/manuelamc14/api-demostrations/blob/main/Images/cities_information.png)

The cities's information was extracted from Weather API (https://openweathermap.org/api) through a request and stored as a csv file. This allows to import the file in pandas as a data frame for the analysis.

![ScreenShot](https://github.com/manuelamc14/api-demostrations/blob/main/Images/cities_data_frame.png)

The project includes four weather variables:  Temperature, humidity, cloudiness and wind speed, which were plotted against the Latitude to showcase the relationships between them. Also, a linear regression was run for each variable.
 
Since the relationship changes based on the hemispheres, the data was splitted in two groups Northern Hemisphere and Southern Hemisphere

This project aims to demonstrate how to use API to acquire information. There are two sections to this project: WeatherPy and Vacation Pay.

WeatherPy section focuses on creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. The cities were chosen through a random generation of latitude and longitude values and selecting the closest cities to those values.

The cities' information was extracted from Weather API (https://openweathermap.org/api) through a request and stored as a CSV file. It allows importing the file in pandas as a data frame for the analysis.

The project includes four weather variables: Temperature, humidity, cloudiness, and wind speed, plotted against the Latitude to showcase the relationships between them. Also, a linear regression was run for each variable.
 
Since the relationship changes based on the hemispheres, the data was split into the Northern Hemisphere and Southern Hemisphere.

Part II - VacationPy

On the other hand, VacationPy aims to demonstrate some of the jupyter-gmaps and the Google Places API features. 

First, a heat map was created that displays every city's humidity from the CSV file obtained in WeatherPy. 

![ScreenShot](https://github.com/manuelamc14/api-demostrations/blob/main/Images/heatmap.png)

Then, the information was narrow to specify weather conditions. With the aid of Google Places API, a hotel was found for each city located within 5000 meters of the coordinates. The hotel's locations were plotted on top of the humidity map. Each pin contains the Hotel Name, City, and Country.

![ScreenShot](https://github.com/manuelamc14/api-demostrations/blob/main/Images/hotels_location.png)

**Note: Please replace your API key before running the files.
