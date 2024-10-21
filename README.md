# Description
This Weather App allows users to retrieve real-time weather information for any city across the globe. It leverages the OpenWeather API to provide accurate and up-to-date weather data such as temperature, weather conditions, humidity levels, and wind speed. The app offers a clean, responsive user interface where users can quickly input a city name and get instant weather details displayed with relevant icons.

This project is a beginner-friendly implementation built using HTML, CSS, and JavaScript, showcasing how to integrate a third-party API (OpenWeather) to fetch and display weather data.

# Features:
1. City Search: Users can enter the name of any city to get up-to-date weather data.
2. Real-Time Weather Data: The app fetches current weather data including temperature, weather conditions, humidity, and wind speed.
3. Responsive Design: The app is built to be responsive, ensuring a smooth experience across different device sizes.
4. Weather Icons: The app dynamically displays appropriate weather icons based on the weather conditions.
5. Error Handling: If the city name is incorrect or the data cannot be found, the app displays a "not found" message.

# Technologies Used:
1. HTML5: For structuring the app layout.
2. CSS3: For styling the app and making it responsive.
3. JavaScript (ES6): For fetching data from the API, updating the UI dynamically, and handling user input.
4. OpenWeather API: For retrieving real-time weather data.

# How It Works
1. City Input: The user enters a city name in the input field.
2. Weather Data Fetching: Upon clicking the "Search" button or pressing "Enter", a request is sent to the OpenWeather API to retrieve the weather information for the specified city.
3. Data Display: The app dynamically updates the page to display the weather details such as temperature, weather condition, humidity, wind speed, and the corresponding weather icon.
4. Error Handling: If the city is not found, a "City Not Found" message is displayed.

# API Reference
OpenWeather API: This app uses the Current Weather Data endpoint to retrieve the weather data. More information can be found at the official OpenWeather API documentation.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
