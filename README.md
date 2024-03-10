This is a small project, creating a weather widget which can be implemented on a website using the "openweathermap.org" API in order to fetch local weather data (temperature, humidity, wind speed) based on the users input.
Besides using the "openweathermap.org" API, the geocoding API from OpenCageData.org (https://opencagedata.com/) is used, in order to determine the users location via reverse geocoding on page load, displaying the weather at the users location.
Scope of the WeatherAppWidget:
+local weather information on page load (requires user to allow location access)
+current temperature (celsius), humidity (%) and wind speed (km/h) of location
+search every city in the world and get instant, live weather information
+changing background images according to location search (for visual appeal)
Current limitations (future implementations):
-no option to display local time (yet)
-no option to show time of sunrise/sunset
-no option to show wind direction
Languages used:
-HTML5 ,
-CSS ,
-JavaScript

APIs used:
-OpenWeather Current Weather Data API (https://openweathermap.org/current)
-OpenCage Geocoding API (https://opencagedata.com/)

To make the widget work it is necessary for you to enter your personal API Keys in the respective fields ( ... 'YOUR API KEY' ... in script.js file) for openweathermap.org and opencagedata.com.
