# Redflare Charts
A vizulization framework based on D3.js

*Create nice charts without writing any code*

Why would you use Redflare?

* You want an easy way to add a chart to your web page
* You like D3.js graphs but find coding them time consuming
* You want a professional looking chart

Who would use Redflare?
* You are a web professional, you know all about HTML and CSS
* You know how to create directory folders
* You know what a csv file is, and how to format basic data

What do you need to see results?

* Edit your html page and add a div ID and class
* Edit the redflare.css file to:
  * Add your div ID
  * Point to your csv data file
  * Edit colors and text options
 
That is it!
Of course you can dig into the code and create any functionality you want!

# Redflare Concepts: D3js

Updated 01-08-18

D3.js is a JavaScript based library used for creating dynamic data displays.  Redflare is designed to add basic bar charts, pie charts to existing content.  Just the core code to get a decent looking chart into your HTML page


## Prototype ##
The first task is to develop the core framework:

Requirements:
* A html page with div markups
* A css style sheet with coresponding sytles for each div
* Javascript using d3.  This script can be referenced mutiple times for similar charts.  For exampe if you need 2 bar charts call the same script and pass div parameters to it.


## First Use Case ##
Build easy to use code that will place more than one d3 graph (Bar and line) onto a HTML page with other content.

Stage 1:
Basic HTML page, 1 CSS file (style.css), 1 JS file (jscript.js)
Spending information, no formatting.
Spending101

Stage 1:
Basic HTML page, 2 CSS file, 2 JS file
Spending information, formatting (redflare.css), graphs (redflare-graphs.js)
Spending102
roboto text

Requirements:
* Data is easy to add.  First version will read only JSON.
* Handle issues associated with adding too much data to a graph.

Bar Chart Elements:
* The div size = canvas
  * Pixels Wide, Pixels High
* Margin
  * chartWidth = divWidth - margin, chartHeight = divHeight - margin
* Y Scale location
  * Pixel Start, Pixels Long 
* X Scale location
* Bar spacing
* 

Math for chart sizing

* Chart width	500
* Border width	10
* Bar padding	5
* Number of bars	14
* Calc - Total Border	20
* Calc - Max Image width	480
* Calc - Max bar width	34.29
* Calc - Bar width	29.29
* Calc - Resulting image width	475
* Calc - Resulting border	25
* Calc - Start chart location	12.50





