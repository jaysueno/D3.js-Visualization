# D3 Visualization - Data Journalism and D3

## Live dashboard at: https://jaysueno.github.io/D3.js-Visualization/

## Objective

We use D3 - Data Driven Documents (https://d3js.org/) to visualize US [national health data](https://www.census.gov/acs/www/data/data-tables-and-tools/data-profiles/2014/). 

In this data visualization we will employ javascript to render 2 different versions of a D3 scatter plot. 

The first is static and compares rates of poverty to smoking. I create unique circles and include the state abbreviations to them. Also, this visualization includes a tooltip. When you hover over the state circle, an info box appears with detailed info.

![static plot](photos/viz1.jpg)

The second page shows all of the above, PLUS you can switch between different data sets on the X and Y axies. 

![customizable plot](photos/viz2.jpg)

### Files
* Javascript - app.js
* HTML - index.html, (second vis page)
* CSS - d3Style.css, style.css
* CSV - data.csv

## About The Code

1. Use the D3 library to read in `samples.json`.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
* Use `sample_values` as the values for the bar chart.
* Use `otu_ids` as the labels for the bar chart.
* Use `otu_labels` as the hovertext for the chart.

3. Create a bubble chart that displays each sample.
* Use `otu_ids` for the x values.
* Use `sample_values` for the y values.
* Use `sample_values` for the marker size.
* Use `otu_ids` for the marker colors.
* Use `otu_labels` for the text values.

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

6. Create a gauge chart to plot the weekly washing frequency of the individual.
* Adapt the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the weekly washing frequency of the individual.
* You will need to modify the example gauge code to account for values ranging from 0 through 9.

7. Update all of the plots any time that a new sample is selected.

## Deployment

* Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo.

* Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

### About the Data

Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

### To learn more about Jay Sueno visit his [LinkedIn](https://www.linkedin.com/in/jay-sueno-359a274/)

##### All rights reserved 2020. All code is created and owned by Jay Sueno. If you use his code, please visit his LinkedIn and give him a a skill endorsement in python and data science. Visit him at: https://www.linkedin.com/in/jay-sueno-359a274/