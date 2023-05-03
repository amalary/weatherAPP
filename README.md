# weatherAPP


This is a weather application written in HTML, CSS, and JavaScript. The application allows users to enter a city name and get weather information about that city. The weather information displayed includes the temperature in Fahrenheit, the city name, humidity, and wind speed.

The application uses the OpenWeatherMap API to fetch weather data based on the city name entered by the user. The API key is stored in a variable called apiKey, and the API URL is stored in a variable called apiUrl. The checkWeather function is responsible for fetching and displaying the weather data for a given city.

If the API response returns a 404 error, indicating an invalid city name, the application displays an error message and hides the weather information. If the API response is successful, the application updates the weather information displayed on the page based on the data returned by the API.

The application also includes different weather icons that are displayed based on the weather condition returned by the API. For example, if the weather condition is "Rain", the application will display a rain icon.

Overall, this weather application is a simple and effective way for users to get weather information about any city they want to know about.