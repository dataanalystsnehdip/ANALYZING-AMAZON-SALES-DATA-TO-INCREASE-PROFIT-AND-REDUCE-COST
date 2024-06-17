# ANALYZING-AMAZON-SALES-DATA-TO-INCREASE-PROFIT-AND-REDUCE-COST
"Let us take a dive into the world of e-commerce analytics where I analyze sales data from Amazon.com to understand ways of enhancing profits and cutting down costs. The decision is straightforward: concentrate on items that bring best returns while consuming less resources, while staying away from those that run high costs but only yield low revenues. In our journey, we will go through huge amount of sales materials from one of the biggest online traders globally in order to understand emerging patterns, customer conduct and practical tips for business development

Steps followed
Step 1 : Load data into Power BI Desktop, data was not in proper formate converted it in a csv file and date was also not in date formate.

Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

Step 4 : It was observed that in none of the columns errors & empty values were present 

Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column.
also 'order date' And Ship 'Date Colounm' where not in proper formate. it take time to fix it.

Step 6 : In the report view, under the view tab, theme was selected.

Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view.

Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".

Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes. Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
