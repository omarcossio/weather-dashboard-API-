# weather-dashboard-API-
This app is a weather dashboard that shows current temperature, date, 5 days forecast, uv index, humidity, windspeed, and weather icons for a city. 
The app allows for the user to search a city through an input. Once the city has been searched, it is saved in localStorage and added to a history search. Each city in the history search is clickable, and will redirect user to current conditions and 5 day forecast. 
The history of searched cities will not allow for duplicate cities.

The app was created using HTML, Bootstrap, CSS, Moment.js, openweather.com API, and jQuery. 


## Acceptance Criteria

The success of the application is based off of the following criteria:

GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history 
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index 
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe 
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity 
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city 
WHEN I open the weather dashboard
THEN I am presented with the last searched city forecast 

A photo of the demo can be seen here: (./06-server-side-apis-homework-demo.png)

* The URL of the deployed application: https://omarcossio.github.io/weather-dashboard-API-/

* The URL of the GitHub repository: https://github.com/omarcossio/weather-dashboard-API-