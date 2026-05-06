# Weather Dashboard

A lightweight weather dashboard built with plain HTML, CSS, and JavaScript.
It shows current weather, hourly charts, a rain radar, pollen forecasts, a 5-day forecast, and a Windy radar preview.

## Features

- Current weather summary for the selected location
- Hourly charts for temperature, precipitation, and wind
- Animated rain radar with playback controls
- Three-day pollen forecast and current pollen levels
- Five-day weather forecast
- Windy radar embed at the bottom of the page
- Search by city or use browser geolocation

## Data Sources

- **Open-Meteo** for current conditions, hourly forecast, and daily forecast data
- **RainViewer** for the animated rain radar tiles
- **Pollenrapporten** for pollen forecast data
- **Windy** for the embedded radar preview
- **Chart.js** for the charts
- **Leaflet** for the map and radar layer display

## Running the App

1. Open `index.html` in a browser, or serve the folder with a static file server.
2. The app defaults to Malmö at latitude `55.6050` and longitude `13.0038`.
3. Use the search box or the location button to change the weather location.

## Project Files

- `index.html` - page structure and embedded assets
- `style.css` - responsive layout and styling
- `script.js` - data fetching, rendering, maps, charts, and radar logic

## Notes

- The app is built without a framework.
- External services are loaded through public CDNs and APIs.
- Some services may have rate limits or availability quirks; the UI includes fallback handling where possible.
