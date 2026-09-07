# Weather Application

A simple browser-based weather application built with HTML, CSS, and vanilla JavaScript. It uses the OpenWeatherMap API to show current weather information for the user's location or a searched city.

## Features

- Get weather for the current location using browser geolocation
- Search for weather by city name
- Display temperature in Celsius
- Show weather description and icon
- Display wind speed, humidity, and cloudiness
- Remember the user's coordinates with `sessionStorage`
- Responsive weather interface with separate location and search views

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- OpenWeatherMap Current Weather API
- Browser Geolocation API
- Web Storage API

## Project Structure

```text
.
├── Weather App/
│   ├── index.html              # Main application page
│   ├── index.js                # Weather application logic
│   ├── styles.css              # Application styles
│   ├── script.js               # API practice/demo script
│   ├── 01-printDataUsingAPI.js # API learning example
│   ├── Homework.txt            # Practice notes
│   └── images/                 # Weather and interface images
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mallharshit2003-droid/Weather-Application.git
cd Weather-Application
```

### 2. Configure the API key

Open `Weather App/index.js` and set `API_KEY` to your OpenWeatherMap API key:

```javascript
const API_KEY = "your_openweathermap_api_key";
```

Do not publish a private API key in a public repository. For a production application, keep the key on a backend server or use an environment-based build setup.

### 3. Run the application

Open `Weather App/index.html` in a browser, or serve the project with a local development server such as VS Code Live Server.

> Browser geolocation generally requires `localhost` or HTTPS. Allow location access when prompted to load weather for your current position.

## How to Use

1. Open the application.
2. Select **Grant Access** and allow location permission to view local weather.
3. Select **Search Weather** to search for another city.
4. Enter a city name and submit the search form.

## API

This project uses the OpenWeatherMap Current Weather endpoint:

```text
https://api.openweathermap.org/data/2.5/weather
```

Create an API key at [OpenWeatherMap](https://openweathermap.org/api) before running the application.

## License

This project is for learning and demonstration purposes.
