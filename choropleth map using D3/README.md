# INF 554 Assignment 9

In this assignment I create a chloropleth map and proportional symbol map to represent the % rural population of 10 countries in the world.  The data is from [World Bank](https://data.worldbank.org/indicator/SP.RUR.TOTL.ZS).


## Development Setup
* The D3.js was accessed by accessing the library files from the repository at [D3 repo](http://d3js.org/d3.v4.min.js). 
* The world map was using data from NaturalEarth-Countries data. TopoJSON file available from [link](https://unpkg.com/topojson-client@3) was directly used instaed of converting shape file from NaturalEarth to GeoJSON or TopoJSON format using GDAL function ogr2ogr. 
* I have also used a local script d3-tip.js to attach a tooltip to hover action. This file is added in the git and aludra.
* Node.js was used along with browsersync library to create a local host environment and also facilitate auto-reload of the browser on every change in the html or css file. The command - browser-sync start --server --files ".html, css/.css" helps to track changes in the html/css files and auto-relod the browser.

## Publishing Instructions
The published page is available at http://www-scf.usc.edu/~patted/a9.html
The html page is published on aludra. The data file and supporting .js files were uploaded using Filezilla application.

## Github details
There are 3 files in github pertaining to this assignment.
1. index.html - This has the html and js code that implements the visualization
2. D3-tip.js- .js script to enable tooltip on hovering
3. Data.csv - This is the data file in csv format

