# Weather App
A simple weather app that allows users to check the current weather in a specific city. The app provides information on temperature, weather conditions, and features a dynamic background that changes based on the current weather.

## Features
1. Search: Enter the name of a city in the search box and press Enter to retrieve the current weather information.
2. Weather Information: Display of city name, current temperature, weather condition, and a high-low temperature range.
3. Background Image: The background image of the app changes dynamically based on the current weather condition.
4. 
## Getting Started
1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/weather-app.git
```
2. Open the index.html file in your web browser.

3. Enter the name of a city in the search box and press Enter to see the weather information.

## API Key
This app uses the OpenWeatherMap API to fetch weather data. You will need to sign up for a free API key at OpenWeatherMap and replace the placeholder API key in the script.js file:

```bash
const api = {
  key: "YOUR_API_KEY",
  base: "https://api.openweathermap.org/data/2.5/"
};
```
## Images
Place your background images in the same directory as the HTML file and update the image file names in the weatherBackgrounds object in the script.js file:
```bash
const weatherBackgrounds = {
  'Clear': 'clear-sky.jpg',
  'Clouds': 'cloud.jpg',
  'Rain': 'rainy.jpg',
  'Snow': 'snowy.jpg',
};
```
## Author
**Joshoua Simon**
![image](https://github.com/Joshoua1/Simple-Weather/assets/94278805/abbd77f9-569f-4279-8225-910095a7a764)


