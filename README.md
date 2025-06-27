# St. Louis Sandbox

This Leaflet map visualizes how much of the city I've explored by various modes. Currently, it contains city parks and bus routes, although I plan to add other data sets in the future. 

**Want to make your own?** Use the "Fork" button in the top right corner to make a copy of this repository. Currently, the status of each park and route is encoded in the geoJSON file. In the future, I plan to tweak the code so that you can update the status via a spreadsheet. If you do that before I do, let me know and I'll pull the changes! In the meantime, the easiest way to navigate the geoJSON is to do a Ctrl+F for "LineName" in rideeveryroute.js or for "TEXT_" in parks.js. Each of these fields contains the recognizable name of the route or park. The status field ("Status" in rideeveryroute.js and "Visited" in parks.js) is nearby.

If you want to add data sets of your own or change the styling, you'll find some bare bones comments in the code indicating where to do that. I'll probably make those more robust in the future, but again, feel free to add things (comments or substantive changes) and push them back to this repo.

This repo carries an MIT license, which means you are free to use the code in whatever way you'd like with attribution.
