# Weather App Clone

A real-time weather application that displays current conditions and 5-day forecasts using the OpenWeatherMap API.

## Features

- Current weather display with temperature, humidity, and wind speed
- 5-day weather forecast
- City search functionality
- Dynamic weather icons
- Responsive design with blur glass effect
- Error handling for city not found

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- OpenWeatherMap API
- Google Material Icons
- Google Fonts (Poppins)

## Installation

1. Clone the repository
2. Replace the API key in `script.js`:
```javascript
const apiKey = 'your_openweathermap_api_key';
```
3. Open `index.html` in a browser

## Project Structure

```
weather-app/
├── index.html
├── style.css
├── script.js
└── assets/
    ├── weather/
    │   ├── clear.svg
    │   ├── clouds.svg
    │   ├── rain.svg
    │   └── ...
    ├── message/
    │   ├── search-city.png
    │   └── not-found.png
    └── bg.jpg
```

## API Usage

The app uses OpenWeatherMap's free API endpoints:
- Current weather: `api.openweathermap.org/data/2.5/weather`
- 5-day forecast: `api.openweathermap.org/data/2.5/forecast`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request
