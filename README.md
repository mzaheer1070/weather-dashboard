# 🌤️ Weather Dashboard

A beautiful, responsive weather dashboard that fetches real-time weather data from the OpenWeatherMap API. Get current weather conditions, detailed metrics, and a 5-day forecast for any city in the world.

## ✨ Features

- 🔍 **Search by City**: Look up weather for any city worldwide
- 📍 **Geolocation Support**: Get weather for your current location
- 🌡️ **Current Weather**: Temperature, conditions, and "feels like" temperature
- 📊 **Detailed Metrics**: Humidity, wind speed, pressure, visibility, sunrise, and sunset times
- 📅 **5-Day Forecast**: Visual forecast cards with temperatures
- 🎨 **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- ⚡ **Real-time Updates**: Instant weather data retrieval
- 🎭 **Weather Emojis**: Visual weather icons for better understanding

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/mzaheer1070/weather-dashboard.git
cd weather-dashboard
```

2. **Open in browser**
```bash
open index.html
# or
firefox index.html
```

3. **Start using**
   - Type a city name in the search box
   - Click Search or press Enter
   - Or click 📍 to use your location

## 📁 Project Structure

```
weather-dashboard/
├── index.html          # HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript logic and API integration
└── README.md           # Documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, animations, gradients
- **JavaScript (ES6+)**: Fetch API, async/await
- **OpenWeatherMap API**: Real-time weather data

## 📊 Current Weather Display

Shows comprehensive information:
- **Temperature**: Current temperature in Celsius
- **Feels Like**: Adjusted temperature based on humidity and wind
- **Humidity**: Percentage of moisture in the air
- **Wind Speed**: Speed in meters per second
- **Pressure**: Atmospheric pressure in hPa
- **Visibility**: Visible distance in kilometers
- **Sunrise/Sunset**: Times for your location

## 📅 5-Day Forecast

Visual forecast cards displaying:
- Day of the week and date
- Weather emoji representation
- Temperature for that day
- Max and min temperature range

## 🌐 API Endpoints

The dashboard uses three OpenWeatherMap API endpoints:

1. **Geocoding API** - Convert city names to coordinates
```
https://api.openweathermap.org/geo/1.0/direct
```

2. **Current Weather API** - Get current weather data
```
https://api.openweathermap.org/data/2.5/weather
```

3. **Forecast API** - Get 5-day forecast
```
https://api.openweathermap.org/data/2.5/forecast
```

## 📱 Responsive Design

- **Desktop** (1200px+): Full-width layout with multi-column grids
- **Tablet** (768px - 1199px): Optimized for medium screens
- **Mobile** (480px - 767px): Single column layout, touch-friendly buttons
- **Small Mobile** (<480px): Compact layout

## ✅ Features Explained

### Search Functionality
- Type any city name (e.g., London, New York, Tokyo)
- Press Enter or click Search
- Supports international cities

### Geolocation
- Click the 📍 button
- Allow browser permission
- Auto-loads weather for your location

### Error Handling
- City not found: Friendly error message
- API errors: Graceful fallback
- Geolocation denied: Alternative search prompt
- Network errors: Clear messaging

## 🔧 Configuration

The API key is pre-configured with a free tier key. To use your own:

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Open `script.js`
3. Replace the API_KEY value:
```javascript
const API_KEY = 'your_actual_api_key_here';
```

## 📊 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## ⚠️ Known Limitations

- Free API tier has rate limiting (60 calls/minute)
- Forecast data updates every 3 hours
- Some advanced features may require paid API tier

## 🐛 Troubleshooting

### Weather data not loading
- Check internet connection
- Verify API key is valid
- Open browser console (F12) for error details

### Geolocation not working
- Check browser permissions
- Some browsers require HTTPS
- Try searching for a city instead

### API rate limit exceeded
- Wait a few minutes before trying again
- Consider upgrading to paid API plan

## 🚀 Future Enhancements

- [ ] Weather alerts and warnings
- [ ] Save favorite cities
- [ ] Celsius/Fahrenheit toggle
- [ ] Air quality index
- [ ] Weather history graphs
- [ ] Dark mode
- [ ] Multiple languages
- [ ] Hourly forecast

## 📄 License

MIT License - Feel free to use this project for personal or commercial purposes

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Fork the repository
- Create a feature branch
- Submit pull requests
- Report issues

## 📞 Support

For questions or issues:
1. Check the troubleshooting section
2. Review [OpenWeatherMap API documentation](https://openweathermap.org/api)
3. Check browser console for error messages

## 📚 Data Sources

- Weather data: [OpenWeatherMap](https://openweathermap.org/)
- Geographic data: OpenWeatherMap Geocoding API

---

Made with ❤️ by [@mzaheer1070](https://github.com/mzaheer1070)

**Live Demo**: [Open in Browser](https://mzaheer1070.github.io/weather-dashboard/)