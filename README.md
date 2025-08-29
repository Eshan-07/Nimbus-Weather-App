
# Nimbus
A modern, responsive weather forecast web app built with vanilla JavaScript, HTML, and CSS. Get current weather and a 5-day forecast for any city, with support for geolocation, search history, and light/dark themes.

![App Screenshot in dark mode](./assets/Nimbus-dark-mode.png)
![App Screenshot in light mode](./assets/Nimbus-light-mode.png)

## Features

- **Current Weather:** View real-time weather data for any city.
- **5-Day Forecast:** See daily forecasts with icons and temperature.
- **Geolocation:** Get weather for your current location.
- **Search History:** Quickly access recent city searches.
- **Theme Toggle:** Switch between light and dark modes.
- **Responsive Design:** Works great on desktop and mobile.

## Demo

[Live Demo](https://algozenith-weather.netlify.app/)

## Getting Started

### Prerequisites

- A modern web browser
- An [OpenWeatherMap API key](https://openweathermap.org/api)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/aaqib605/az-weather-app.git
   cd az-weather-app
   ```
2. **Add your API key:**

   - Create a new file named `apiKey.js` in the project root and add the following code, replacing the value with your OpenWeatherMap API key:

     ```js
     const OPEN_WEATHER_API_KEY = "YOUR_API_KEY_HERE";

     export default OPEN_WEATHER_API_KEY;
     ```

   - This file is imported by `script.js` to access your API key.

3. **Open the app:**
   - Open `index.html` in your browser.

## Project Structure

```
az-weather-app/
├── index.html        # Main HTML file
├── script.js         # JavaScript logic
├── styles.css        # App styling
└── README.md         # Project documentation
```

## API Reference

- [OpenWeatherMap API Docs](https://openweathermap.org/api)

## License

This project is open source and available under the [MIT License](LICENSE).

---

Created with ❤️ by [Aaqib Javaid](https://github.com/aaqib605)
=======
Nimbus Weather App

A sleek and responsive weather forecasting web application built with HTML, CSS, and JavaScript.
It provides real-time weather updates, dark mode toggle, and persistent search history using localStorage.

🚀 Features

🌍 Search by city – Get live weather data from the OpenWeather API

🌙 Dark/Light mode – Switch themes with one click

📜 Search history – Stores your recent searches in localStorage

📱 Responsive design – Works across desktop and mobile

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

API: OpenWeather API

Storage: LocalStorage for search history & theme persistence

📷 Screenshots

(Add your app screenshots here – e.g., assets/screenshot.png)

⚡ Getting Started
1. Clone the repo
git clone https://github.com/your-username/Nimbus-Weather-App.git
cd Nimbus-Weather-App

2. Open in browser

Simply open index.html in your browser.

🔑 API Key Setup

This app uses the OpenWeather API.

Create a free account at OpenWeather

Generate an API key

Add your API key inside script.js

const OPEN_WEATHER_API_KEY = "YOUR_API_KEY_HERE";

📌 Future Enhancements

🌡️ Hourly & weekly forecasts

🗺️ Weather by current location (Geolocation API)

🔔 Custom alerts for extreme weather

👨‍💻 Author

Your Name – GitHub Profile
>>>>>>> cf397d00965ac483fc3c5dee7df18668fbbe15b7
