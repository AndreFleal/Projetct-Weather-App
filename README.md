# Projetct-Weather-App



<p>This is a small JavaScript code snippet for a weather app that fetches weather data for a specified city using the OpenWeatherMap API. The app allows users to enter a city name in the search box and then displays the current weather details for that city, including temperature, weather description, humidity, and wind speed.

Here's a brief summary of how the app works:

1- The app listens for a click event on the search button.

2- When the search button is clicked, the city name entered by the user is retrieved from the input field.

3- The app makes an API call to OpenWeatherMap to fetch weather data for the specified city, using the city name and an API key.

4- If the city is not found or there is an error with the API call (indicated by the response code '404'), the app displays an error message.

5- If the weather data is successfully fetched, the app updates the DOM to display the weather information, including an appropriate weather image (e.g., sunny, rainy, snowy, etc.), the current temperature in Celsius, a brief weather description, humidity percentage, and wind speed in kilometers per hour.

6- The app also includes some simple animations using CSS classes to fade in the weather details when they are displayed.

7- The weather images displayed are based on the main weather condition returned by the API, and the app supports specific images for clear, rainy, snowy, cloudy, and hazy conditions.

In summary, this weather app is a simple and user-friendly tool for checking the current weather conditions in different cities by entering their names in the search box.</p>
