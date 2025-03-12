# leaflet-challenge
Leaflet Earthquake Visualization

Project Overview

This project utilizes the Leaflet.js library to visualize real-time earthquake data on an interactive map. The data is sourced from the USGS GeoJSON feed, and various features such as popups, color-coded markers, and legends have been implemented to enhance the user experience.

Files and Structure

📂 Project Directory
├── index.html       # Main HTML file containing the Leaflet map
├── style.css        # CSS file for styling the map and legend
├── logic.js         # JavaScript file for data fetching and visualization logic
└── static/
    ├── css/style.css # Styling for the webpage
    └── js/logic.js   # JavaScript logic for Leaflet map

Technologies Used

Leaflet.js: Interactive mapping library

D3.js: Data-driven visualization

HTML5 & CSS3: Structure and styling

JavaScript (ES6): Fetching and processing earthquake data

Features

Interactive Map: Displays earthquake locations using Leaflet.js

Real-time Data: Retrieves earthquake data from USGS GeoJSON feed

Color-Coded Markers: Represent earthquake magnitude and depth

Popups: Provide details on each earthquake

Legend: Helps users interpret the color-coded depth markers

Installation & Usage

Clone the repository:

git clone https://github.com/your-repository/leaflet-earthquake.git

Navigate to the project folder:

cd leaflet-earthquake

Open index.html in a browser to view the interactive map.

Data Source

The earthquake data is retrieved from the USGS GeoJSON Feed:
https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php

Future Enhancements

Implement tectonic plate overlay for better geological context

Add timeline filtering to visualize earthquakes over time

Improve UI with additional styling and animations

License

This project is open-source and available under the MIT License.

