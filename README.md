#  Interactive Weather Page

An interactive, map-based weather application that lets users search for any city to view **current weather**, **forecast**, and live **OpenWeatherMap overlays** (e.g., clouds, precipitation, wind, and pressure). This app also supports **dark mode** and map tile switching.

![Weather Page Screenshot](Weather.png)

##  Features

- Leaflet-powered map view
- Live weather overlays via OpenWeatherMap
- City search with geolocation using OpenStreetMap Nominatim
- Toggle between Current Weather and 5-Day Forecast
- Dark mode toggle with visual updates to map and UI
- Custom UI with smooth transitions and scrollable forecast cards

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/LeeMarshall1113/Weather-page.git
   cd Weather-page

    Add your OpenWeatherMap API key in the HTML file:

    Open index.html and replace:

    const OPENWEATHERMAP_KEY = 'Insert_key_here';

    with your actual key.

    Open index.html in a browser. No server needed — it’s fully static!

    Technologies Used

    HTML5, CSS3, Vanilla JS

    Leaflet.js for interactive maps

    OpenWeatherMap API for live weather and forecast

    OpenStreetMap Nominatim for geocoding

    CartoDB dark/light map tile styles

  Folder Structure

Weather-page/
├── index.html
├── assets/
│   └── Weather.png

 Screenshot

Add a screenshot of the project and place it inside the assets/ folder to visually represent your app.

     Built with care to showcase API integration, map UX, and interactive front-end development.
