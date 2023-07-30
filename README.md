# belly-button-challenge1
Module 14: JavaScript Visualizations

# Belly Button Biodiversity Dashboard 

In this challenge, an interactive dashboard was created to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/) which catalogs the microbes that colonize human navels.
The dashboard created, allows one to explore the dataset of each individual included in the study via the usage of a drop down menu that selects a desired test subject ID, then displays unique charts for that individual.

# Instructions

Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
  	- Use sample_values as the values for the bar chart.
	- Use otu_ids as the labels for the bar chart.
	- Use otu_labels as the hovertext for the chart.

3. Create a bubble chart that displays each sample.
	- Use otu_ids for the x values.
	- Use sample_values for the y values.
	- Use sample_values for the marker size.
	- Use otu_ids for the marker colors.
	- Use otu_labels for the text values.

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.
6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard.
7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file
   
# Resources
1. Modules 14: In Class Activities
2. Collaborated with fellow classmates
3. Class Instructor: Arooj A Qureshi
4. TA Instructor: Abdelrahman "Abdo" Elewah
5. Ask BCS Learning Assistants
