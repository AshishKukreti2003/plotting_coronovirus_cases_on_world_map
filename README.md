# Real-time COVID-19 Map Tracker

This project creates a real-time map tracking COVID-19 cases around the world using Mapbox API.

Link:- https://ashishkukreti2003.github.io/plotting_coronovirus_cases_on_world_map/

## Prerequisites

To run this project locally, ensure you have the following:

- [Mapbox API Access Token](https://docs.mapbox.com/help/how-mapbox-works/access-tokens/)
- [Web Browser](https://www.google.com/chrome/)

## Installation

1. Clone the repository to your local machine using `git clone https://github.com/your-username/your-repository.git`.
2. Replace `mapboxgl.accessToken` in `index.html` with your Mapbox API token.
3. Open `index.html` in a web browser.

## Usage

- The map visualizes real-time COVID-19 data fetched from `data.json`.
- The map is initialized with a zoom level of 2 and centered at [0, 20] coordinates.
- Markers on the map represent COVID-19 cases, with marker color indicating the number of cases.

## Features

- Fetches real-time COVID-19 data from `data.json` using JavaScript's `fetch` API.
- Dynamically updates the map markers based on the number of infected cases.

## File Structure

- `index.html`: HTML file for rendering the map.
- `index.js`: JavaScript file handling map updates and data visualization.
- `data.json`: JSON file containing COVID-19 case data with latitude, longitude, and infected count.

## Contribution

Contributions are welcome! Fork the repository and create a pull request for any improvements.
