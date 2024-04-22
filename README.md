# Leaflet Challenge

![Screenshot 2024-04-22 at 7 39 53 AM](https://github.com/AshleyKAnderson/leaflet_challenge/assets/151413928/d3d93d64-f064-4a42-af2f-adda2ff9cfde)


## Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Deployment 


## Instructions
The instructions for this activity are:

* Create the Earthquake Visualization

![Screenshot 2024-04-22 at 7 23 12 AM](https://github.com/AshleyKAnderson/leaflet_challenge/assets/151413928/b6bb0a09-d8f6-4559-9ac6-eab54a5f10e2)

Your first task is to visualize an earthquake dataset. Complete the following steps:

1. Get your dataset. Follow these steps:

* The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:

![Screenshot 2024-04-22 at 7 24 14 AM](https://github.com/AshleyKAnderson/leaflet_challenge/assets/151413928/b8bc1608-a811-414e-afc0-b308a0ec35e9)

* When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:

![Screenshot 2024-04-22 at 7 29 59 AM](https://github.com/AshleyKAnderson/leaflet_challenge/assets/151413928/3fac30cf-3704-4166-ab5c-4f4f71fc2294)

2. Import and visualize the data by doing the following:

* Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

* Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

* Include popups that provide additional information about the earthquake when its associated marker is clicked.

*Create a legend that will provide context for your map data.

Your visualization should look something like the preceding map.

## References 

Dataset created by the [United States Geological Survey](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php).

