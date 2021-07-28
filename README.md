# World_Weather_Analysis Purpose

The Beta testers suggested changes to the PlanMyTrip app. The specific recommendation:
* add the weather description to the weather data

To add the weather data, the code includes these processes:
* input statements to filter data for weather preferences
* use map markers to identify potentinal travel destinations and hotels - four cities for testing purposes
* create a travel itinerary
* create a travel route between the four cities using Google Maps Directions API.

## Results
A csv file was created with city latitude and longitude, maximum and minimum temperature and weather description data.
![alt text](https://github.com/sarifrey/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database_City_Data.png)

Using input statements requesting minimum and maximum temperatures, a new csv file was generated from the data in the weather database csv. The weather vacation csv file contains the cities that met the input statement criteria. A map was generated showing the city markers meeting the criteria.
![alt text](https://github.com/sarifrey/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

The travel itinerary was generated from the weather vacation csv file. Four cities randomly chosen from the Goolge map had a round trip map generated using the Google Maps Directions API. 
![alt text](https://github.com/sarifrey/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

Then a new map was generated showing the chosen cities' data: hotel name, city, country, weather and maximum temperature.
![alt text](https://github.com/sarifrey/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
