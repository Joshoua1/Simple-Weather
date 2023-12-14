Weather App
A simple weather app that allows users to check the current weather in a specific city. The app provides information on temperature, weather conditions, and features a dynamic background that changes based on the current weather.

Features
Search: Enter the name of a city in the search box and press Enter to retrieve the current weather information.
Weather Information: Display of city name, current temperature, weather condition, and a high-low temperature range.
Background Image: The background image of the app changes dynamically based on the current weather condition.
Getting Started
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/weather-app.git
Open the index.html file in your web browser.

Enter the name of a city in the search box and press Enter to see the weather information.

API Key
This app uses the OpenWeatherMap API to fetch weather data. You will need to sign up for a free API key at OpenWeatherMap and replace the placeholder API key in the script.js file:

javascript
Copy code
const api = {
  key: "YOUR_API_KEY",
  base: "https://api.openweathermap.org/data/2.5/"
};
Images
Place your background images in the same directory as the HTML file and update the image file names in the weatherBackgrounds object in the script.js file:

javascript
Copy code
const weatherBackgrounds = {
  'Clear': 'clear-sky.jpg',
  'Clouds': 'cloud.jpg',
  'Rain': 'rainy.jpg',
  'Snow': 'snowy.jpg',
};
Author
[Your Name]
License
This project is licensed under the MIT License - see the LICENSE file for details.
