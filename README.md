# Redflare Concepts: D3js#

*** Updated 01-08-18 ***

D3.js is a JavaScript based library used for creating dynamic data displays.  Redflare is designed to add basic bar charts, pie charts to existing content.  Just the core code to get a decent looking chart into your HTML page


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





