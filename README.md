# 🌤️ Weather App


A simple and responsive weather application built with HTML, CSS, and JavaScript
The app allows users to search for a city and view its current weather information, including temperature, humidity, wind speed, and weather conditions.

<img width="1363" height="662" alt="image" src="https://github.com/user-attachments/assets/ba9ade02-ec7a-44ee-8413-e9213300bd2e" />


## ✨ Features

- 🔍 Search weather by city name
- 🌡️ Display current temperature in Celsius
- 💧 Display humidity
- 💨 Display wind speed
- ☁️ Display weather conditions with dynamic icons
- ❌ Show an error message for invalid city names
- 📱 Clean and responsive user interface
- ⚡ Fetches real-time weather data from the OpenWeather API

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- OpenWeather API

## 📂 Project Structure

```text
weather_app_/
│
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   └── wind.png
│
├── index.html
├── style.css
├── script.js
└── README.md

🚀 How to Run

1. Clone the repository
git clone https://github.com/Vamsi266/weather_app_.git
2. Open the project

Open the project folder in Cursor, Visual Studio Code, or another code editor.

3. Run the application

You can open index.html directly in your browser, or use the Live Server extension in VS Code/Cursor.

Using Live Server:

Open index.html
Right-click inside the file
Select Open with Live Server

🔑 API Setup

This project uses the OpenWeather API to retrieve weather data.

The JavaScript application sends a request to the OpenWeather current weather endpoint using the searched city name.

Before using the project, create your own API key from OpenWeather and add it to script.js.

Example:

const apiKey = "YOUR_API_KEY";

Then use the API key in the weather request.

⚠️ Do not publish your real API key in a public GitHub repository.

For a production application, the API key should be protected using a backend service or another secure approach.

🌦️ How It Works

Enter a city name in the search box.
Click the search button.
The application sends a request to the OpenWeather API.
Weather information is returned for the selected city.
The application displays:
City name
Temperature
Humidity
Wind speed
Weather condition icon

If the city cannot be found, an Invalid city name message is displayed.

🎨 UI

The application uses a card-based interface with:

Dark background
Gradient weather card
City search input
Weather condition icon
Temperature display
Humidity and wind information

🔮 Future Improvements

Some possible improvements for the project:

Add a 5-day weather forecast
Add current location detection
Add Celsius/Fahrenheit conversion
Add loading animation
Add more weather conditions
Add weather background changes
Add search using the Enter key
Improve error handling
Improve accessibility
Hide the API key using a backend or environment variables
👨‍💻 Author

Vamsi

GitHub:
https://github.com/Vamsi266
