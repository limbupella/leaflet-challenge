Visualized an earthquake dataset. Acgieved with following steps:

- With USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:
When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:Import and visualize the data by doing the following:

- Utilized Leaflet to create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

- Markers should reflects the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

# Hint: The depth of the earth can be found as the third coordinate for each earthquake.

- Marker include popups that provide additional information about the earthquake when its associated marker is clicked.

- Created a legend that will provide context for your map data.
