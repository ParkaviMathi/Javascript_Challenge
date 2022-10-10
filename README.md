# Javascript_Challenge

## Belly Button Biodiversity
In this assignment, an interactive dashboard is built to explore the Belly Button Biodiversity dataset, which catalogues the microbes that colonise human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Instructions
The following stepswere follwed:

### Importing Data
The D3 library is used to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

### Horizontal Bar Chart
A horizontal bar chart has been created with a dropdown menu to display the top 10 OTUs found in that individual.

. sample_values has been used as the values for the bar chart.
. otu_ids has been used as the labels for the bar chart.
. otu_labels has been used as the hover text for the chart.

### Bubble Chart
A bubble chart has been created that displays each sample.

. otu_ids has been used for the x values.
. sample_values has been used for the y values.
. sample_values has been used for the marker size.
. otu_ids has been used for the marker colours.
. otu_labels has been used for the text values.





Display the sample metadata, i.e., an individual's demographic information.


Display each key-value pair from the metadata JSON object somewhere on the page.




Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:



Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file
