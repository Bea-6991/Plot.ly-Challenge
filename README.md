# Plotly-Challenge

 Interactive Dashboard to explore the Belly Button Biodiversity Dataset. 
 Deployed to belly-button-biodiversity app to Heroku: https://biodiversity-ib.herokuapp.com
 Technologies=> JavaScript, Plotly.js, Flask, SQLite, Heroku

# Biodiversity_InteractveDashboard
Interactive Dashboard to explore the Belly Button Biodiversity Dataset

# Belly Button Biodiversity

![Bacteria by filterforge.com](Images/bacteria_by_filterforgedotcom.jpg)

This analysis will build an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

## Step 1 - Plotly.js

Use Plotly.js to build interactive charts for your dashboard.

* Create a PIE chart that uses data from your samples route (`/samples/<sample>`) to display the top 10 samples.

  * Use `sample_values` as the values for the PIE chart

  * Use `otu_ids` as the labels for the pie chart

  * Use `otu_labels` as the hovertext for the chart

  ![PIE Chart](Images/pie_chart.png)

* Create a Bubble Chart that uses data from your samples route (`/samples/<sample>`) to display each sample.

  * Use `otu_ids` for the x values

  * Use `sample_values` for the y values

  * Use `sample_values` for the marker size

  * Use `otu_ids` for the marker colors

  * Use `otu_labels` for the text values

  ![Bubble Chart](Images/bubble_chart.png)

* Display the sample metadata from the route `/metadata/<sample>`

  * Display each key/value pair from the metadata JSON object somewhere on the page

* Update all of the plots any time that a new sample is selected.


## Step 2 - Heroku

Deploy your Flask app to Heroku.

* Use the provided sqlite file for the database.

- - -

## Flask API

Use Flask API starter code to serve the data needed for your plots.

* Test routes by visiting each one in the browser.

- - -
