# kickstarter-analysis

## Overview of Project
Performing analysis on Kickstarter data to uncover trends


### Purpose
Creating graphical representations of campaign outcomes based on the launch date. In order to do this, used the YEAR() function to obtain the year from each data point and then created a PivotTable to count all of the different outcomes (for Theaters only). From there, created a line chart with header. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Used the the YEAR() function to obtain the year from each data point and then created a PivotTable to count all of the different outcomes (for Theaters only). From there, we just created a line chart with header.

### Analysis of Outcomes Based on Goals
Used the COUNTIFS() function which essentially filters through a data set by the columns you enter in the function. Using this function, I created a table based on the different outcomes (successful, failed, canceled) and by different ranges (for the goal amount). 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

From looking at the chart, we can tell that from all the theater launches, there have been a lot more successful outcomes than failed or canceled outcomes in each month. We can also tell that successful outcomes tend to fall towards the end of the year while canceled and failed outcomes stay relatively stable throughout the year compared to the successful outcomes. 

- What can you conclude about the Outcomes based on Goals?

From looking at the graph, we can tell that the percentage of canceled outcomes is 0% in the given goal ranges. Moreover, we can tell that the combination of Percentage Successful and Percentage Canceled adds up to 100%. This is seen on the chart as the Percentage Successful and Percentage Failed graphs are mirror opposites of each other. 

- What are some limitations of this dataset?

There is a lot of data in the dataset and it needs to be filtered if an individual wants to see something specific about it. 

- What are some other possible tables and/or graphs that we could create?

We could create a table/graph for Outcomes Based on Country to see how each country does compared to the other. We could also create a table/graph for Average Donation Based on Country to see how the donations differ based on each country. 

