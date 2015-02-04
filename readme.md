#INFO 247 HW: Highcharts

##Instructions

###Setup
1. Open "index.html" & "_data/SF_rainfall_seasons.csv" in your text editor.

###Goals
You are building a horizontal stacked bar chart using the data provided (San Francisco rainfall by season and year). The disaggregated month data is also included in case you are curious. Take a look at result-01.png & result-02.png to see what the final result should look like (they're the same chart, but the second screenshot shows a hover state).

###Practice with Highcharts
1. Create a horizontal stacked bar chart by completing the given code. Take a look at http://www.highcharts.com/demo/bar-stacked & solution-line-chart-ajax.html in lab 2 (https://github.com/raymonst/info247-lab-02-javascript_jquery_highcharts) to get started.
2. You only need to edit the script--no need to edit the HTML or CSS.
3. As with the lab assignment, you need to read the data from a csv file. Set up a local server or upload the files to your i-school server space to read the data successfully via ajax.
4. Take a look at the csv structure, then follow the instructions outlined in index.html to populate the data properly.   
5. Most of the settings in "options" have been set up, but "options.tooltip" & "options.yAxis" are incomplete. Use the hints provided, consult the Highcharts API documentation (http://api.highcharts.com/highcharts), & fill out the missing options.