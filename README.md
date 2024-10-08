Weather Now

Weather Now is a simple weather application that allows users to check the current weather and forecast for any city worldwide. The app provides real-time data such as temperature, humidity, wind speed, and more.

Features

Search by City: Users can search for weather information by typing the city name.

Real-time Weather Data: Displays current temperature, weather conditions, humidity, and wind speed.

Weather Forecast: Shows a 4-day weather forecast for the selected city.

Auto-suggestions for Cities: As users type, city suggestions are displayed for easy selection.

Error Handling: Displays error messages if a city is not found or if there is an issue fetching data.


Technologies Used

HTML: Structuring the application layout.

CSS: Styling the user interface for a clean and modern look.

JavaScript: Handling user inputs, fetching data from the API, and updating the UI dynamically.

OpenWeather API: Fetching weather data and city information.


Getting Started

Follow these steps to run the project locally.

Prerequisites

Before you begin, make sure you have the following installed:

Node.js

A text editor or IDE (e.g., VSCode)


Installation

1. Clone the repository to your local machine:

git clone https://github.com/yourusername/weather-now.git


2. Navigate to the project directory:

cd weather-now


3. Install the necessary dependencies (if any):

npm install


4. Create an account on OpenWeather and get your API key.


5. In your project, create a .env file and add your API key:

API_KEY=your_openweather_api_key



Running the Project

To start the project, open the index.html file in your browser or use a live server extension in your IDE. Alternatively, you can run it using a simple HTTP server:

npx http-server

Usage

1. Enter the name of a city in the search bar.


2. View the current weather, including temperature, humidity, wind speed, and a 4-day forecast.


3. Select suggestions from the dropdown if available.



Screenshots

1. Home Page with Weather Information



2. City Search with Auto-suggestions



Future Improvements

Add functionality for selecting temperature units (Celsius/Fahrenheit).

Provide more detailed weather information (sunrise/sunset times, pressure, etc.).

Implement a mobile-friendly design for better user experience on smartphones.


Contributing

Feel free to fork this project and submit pull requests. If you encounter any issues, please report them in the issue tracker.

License

This project is licensed under the MIT License. See the LICENSE file for more details.
