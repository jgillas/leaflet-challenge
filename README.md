# leaflet-challenge

In this challenge I was asked to create a map showing earthquakes around the world. I chose to show all earthquakes in the past 7 days. In order to find this information I used the USGS website and navigated to the GeoJSON Summary Format page where I found the JSON link/format for all the earthquakes in the past 7 days. The link for USGS is: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php and the link for the JSON format is: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson

I then used Leaflet to create a map that plots all the earthquakes from my dataset based on the earthquakes' longitude and latitude. The data markers that mark the earthquakes reflect the magnitude of the earthquake by the size and depth of the earthquake by color. Earthquakes with larger markers have a higher magnitude and earthquakes with smaller markers have a lower magnitude. Earthquakes with greater depth will have a darker color marker and earthquakes with lower depth will have a lighter color.

In the legend you can see how I broke up the different depths for the earthquakes and which color represents each depth range. Depths of -10 to 10 are lightgreen, depths of 10 to 30 are yellow, depths of 30 to 50 greenyellow, depths of 50 to 70 are orange, depths of 70-90 are orangered, and depths of 90+ are red.

A picture of the map showing the different markers is below: 

  <img width="1633" alt="Screenshot 2023-06-21 at 3 08 30 AM" src="https://github.com/jgillas/leaflet-challenge/assets/125215083/bfe03954-e81a-466a-91fe-f593840c0583">

I was also asked to include popups that provide additional information about each earthquake when you click on the marker. A picture of the map with one of the popups for the earthquake is below: 

  <img width="1632" alt="Screenshot 2023-06-21 at 3 09 15 AM" src="https://github.com/jgillas/leaflet-challenge/assets/125215083/a5b96ea6-0d8c-4bcb-89c9-a8eead905d48">


This concludes my challenge 15 assigment. 
