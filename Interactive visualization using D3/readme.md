This folder creates a bar chart for electricity consumption by 10 countries in 2014. The visualization is interactive and allows the user to perform various actions. D3 datajoin cencept and transition are used implement the interactive functionality. Data from UN Data website is used. [UN Data](http://data.un.org/Data.aspx?d=EDATA&f=cmID%3aEL%3btrID%3a1231).
**Note: The output of top 5 and bottom 5 may look similar but the digits in y axis max are different.

## Screenshot
The below screenshot shows the bar plot with interaction option for sorting and data selection. Sorting of data can be ascending / descending / alphabetically.
Data selection can be choosing top 5, bottom 5 or all data.
![img1](https://github.com/TejalPatted/Information-Visualization/blob/master/Interactive%20visualization%20using%20D3/Interactive%20plot.JPG)

## Development Setup
The D3.js was accessed by accessing the library files from the repository at [D3 repo](http://d3js.org/d3.v4.min.js). 
Node.js was used along with browsersync library to create a local host environment and also facilitate auto-reload of the browser on every change in the html or css file. The command - browser-sync start --server --files ".html, css/.css" helps to track changes in the html/css files and auto-relod the browser.

## Github details
There are 3 files in github pertaining to this assignment.
1. index.html - This has the html and js code that implements the visualization
2. style1.css - This has the css details applied to the elements in the html file
3. UNData.json - This is the data file in json format
