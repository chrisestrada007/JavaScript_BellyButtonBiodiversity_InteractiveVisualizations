# Belly Button Biodiversity

![Bacteria by filterforge.com](Images/bacteria_by_filterforgedotcom.jpg)

In this assignment, I built an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

## Step 1 - Plotly.js

I used Plotly.js to build interactive charts for the dashboard.

* Created a PIE chart that uses data from samples route (`/samples/<sample>`) to display the top 10 samples.

* Created a Bubble Chart that uses data from samples route (`/samples/<sample>`) to display each sample.

* Displayed the sample metadata from the route `/metadata/<sample>`

* Displayed each key/value pair from the metadata JSON object

* Updates all of the plots any time that a new sample is selected

## Step 2 - Heroku

Deploy Flask app to Heroku