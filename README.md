# belly-button-challenge

Overview:
This project involves the 	building an interactive dashboard to explore the Belly Button Biodiversity dataset which catalogues the microbes that colonies human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare. The dashboard includes a Guage chart, bubble chart, horizontal chart and a summary of the metadata for the human that the sample came from. 
Scope: 
In this report we have used D3 library from javaScript to read in sample.json from the url and based on the data – three different visualization are displayed based on the user input. 
Methodology:
1.	Plotly and D3 library from JavaScript to generates plot
2.	HTML – page framework
3.	Data restored in sample.json format
Tasks Performed:
1.	Displaying the top 10 OTUs found in an individual with horizontal bar chart 
i.	Sample values – Values of the bar chart
ii.	Out_ids – labels for the bar chart
iii.	Out_labels – hovertext for the chart

2.	Displaying each sample with bubble char 

i.	Out_ids – x values 
ii.	Sample_values – y values and marker size
iii.	Out_ids – marker colors
iv.	Out_labels – text values

3.	Displaying an individual demographic information 
4.	Displaying weekly washing frequency of the individual with the Guage Chart 
