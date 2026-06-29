# 🌤️ NIMBUS - Weather Anywhere

NIMBUS is a premium, luxury-themed single-page weather application designed with a sleek Black/White/Blue color scheme. It features automatic geolocation, search suggestions, real-time weather analytics, and smooth CSS animations (particles, clouds, rain, snow) that adapt dynamically to current weather conditions.

![NIMBUS UI Preview]   (https://amit15032003kumar-cell.github.io/nimbus-weather/ )                                                                   (https://images.unsplash.com/photo-1592210405989-78a2ae1ff68c?q=80&w=1200&auto=format&fit=crop)

## ✨ Features

- **📍 Intelligent Geolocation**: Automatically detects the user's city name and current weather conditions upon loading.
- **🔍 World-wide City Search**: Real-time autocomplete suggestions as you type, pulling data from coordinates worldwide.
- **📊 Detailed Meteorological Metrics**:
  - UV Index (with automated warnings)
  - Relative Humidity levels
  - Real-feel Apparent Temperature
  - Wind speed & direction
  - Visibility range
  - Atmospheric Pressure (MSL)
  - Interactive Sun Path (visualizing Sunrise/Sunset progress)
- **❄️ Dynamic Ambient Effects**: Smooth GPU-accelerated micro-animations (drifting clouds, falling raindrops, wind particles, rotating snowflakes, lightning flashes) changing based on the current weather code.
- **🔄 Local Settings Cache**: Persistent storage for unit settings (Metric °C / Imperial °F) and search history.
- **📱 Fully Responsive Design**: Seamless premium mobile, tablet, and desktop experience.

## 🛠️ Built With

- **Structure**: Semantic HTML5
- **Style**: Custom Glassmorphism Vanilla CSS
- **Interactions**: Vanilla Modern JavaScript (ES6+)
- **APIs**: 
  - [Open-Meteo Weather Forecast API](https://open-meteo.com)
  - [Open-Meteo Geocoding Search API](https://open-meteo.com)
  - [BigDataCloud Reverse Geocoding Client](https://www.bigdatacloud.com)
- **Typography & Icons**: Google Fonts (Space Grotesk & Inter), Font Awesome Icons

## 🚀 Live Demo / Getting Started

The app is built entirely client-side. To run locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/amit15032003kumar-cell/nimbus-weather-web.git
   ```
2. Open `index.html` in your default web browser, or serve it using a local HTTP server:
   ```bash
   npx http-server
   ```
3. Enjoy precise weather forecasts, anywhere on Earth!
