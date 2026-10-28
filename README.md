Waypoint Grid — Trail Marker App

A single-page web app for viewing and managing trail markers. Load a CSV of marker GPS coordinates and see them on a simple grid, a custom image map, or OpenStreetMap tiles.

Features
Load marker data from a CSV file (id, lat, lon, action)
Four map modes: Grid, My Map (uploaded image), OSM Tiles, Google Maps
Distances between markers, in metric or imperial units
Gap analysis: highlights long stretches between markers where new markers may be needed
Management View: shows each marker's action (Install New, Replace, Paint) by shape
Download the marker list as CSV
Use it

Open the live app: https://YOUR-USERNAME.github.io/trail-app/

Or download index.html and open it in a browser. Note that OpenStreetMap tiles only load when the app is served over https:// (not when opened as a local file).

CSV format
id,lat,lon,action
1,26.7304,-80.2506,Paint
2,26.7303,-80.2507,Replace

Optional columns: group, sequence, highlightTo for ordering markers along a trail and highlighting specific gaps.

Credits

Map data © OpenStreetMap contributors. Satellite imagery © Esri.
