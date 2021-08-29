
# Kickstarter-Challenge

## Overview of Project

    The aim of the project is to perform two technical analysis using excel. The client wants to know how 
different campaigns fared in realtion to their launch dates and their funding goals.

### Purpose
The objective of the project to is to provide the client with a clear view of the fundraising reaching its goal in a short amount of time by considering outcomes based on launch date and outcomes based on goals.

## Analysis and Challenges
    The analysis was done in two parts. Firstly by theatre outcomes based on launch date and the next one was by Outcomes based on goals. For the first problem I had a column called launch date which was in epoch time which had to be converted to excel date format 00/00/0000. The new column holding this data is called the Date creaated conversion. The purpose of this column helped us get the year column as well as the month in the pivot table. Then with help of the data in the kickstarter worksheeet created a pivot table in a new worksheeet which included Months of year, Sum of outcomes and also includes two filters called the parent category & year. Then with the help of the pivot table I then plotted a line graph for theatre outcomes Vs Months. When we look at the graph for outcomes vs Launch Date the success rate percentage is 66.9%  in the month of may when compared to the remaining months in the year. So I would recommend the client to have the plays launch in the month of may to have successful outcomes. The challenges faced was converting the launch date which was in epoch time to excel date format. Here is a screenshot showing the conversion of the epoch time to excel date format 00/00/0000 resources/BargraphGoalsVsTotalProjects.png 

    Similar in the next of the problem consists of analysisng the data given for Outcomes based on Goals. Here I had to plot a graph for Outcomes Vs Goal. From the given dataset I had to create a new table containing the goals, number successful , number failed, number canceled, total projects, precentage successful, percentage failed and percentage canceled columns. After calculating all the values for the above columns I plotted a line graph for outcomes Vs goals. After looking at the graph I found out that the success rate percentage is better for the range of goal being below 5000.

### Analysis of Outcomes Based on Launch Date
    When we look at the graph for outcome vs Launch Date that the success rate percentage is higher in the month of may when compared to the remaining months in the year. And the highest failure rate is in the month of october.


### Analysis of Outcomes Based on Goals
    Looking at the graph plotted against the Outcomes vs Goals it shows that it is more likely to have a better success rate for the goal below 5000. And the creteria for success above 45000 is 13%. However the success rate is inconsistent for the goal range 35000 to 39999. Thus we do not recommend a this goal range. 

### Challenges and Difficulties Encountered
The challenge that I faced was with dataset not being in an analysis friendly format.
The challenges faced was converting the launch date which was in epoch time to excel date format. Here is a screenshot showing the conversion of the epoch time to excel date format 00/00/0000 /Users/sbk/Desktop/Screen Shot 2021-08-29 at 12.45.31 PM (3).png 
    

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
     The graph made it very clear in providing the success rate percentage for launching a play in the month may is 66.9% higher.
    The second inference fro the graph was that failure rate percentage is higher in the month of october.


- What can you conclude about the Outcomes based on Goals?
The line graph for the Outcomes based on Goals shows us that having a we have a better success rate for the goal below 5000. 

- What are some limitations of this dataset?
When we look at the bar graph for the outcomes based on goals we can infer that there is less data for doing data analysis for the range of goal starting from 15000. Here is a screenshot for the bar graph resources/BargraphGoalsVsTotalProjects.png

- What are some other possible tables and/or graphs that we could create?
Outcome based on goals - Bar graph for Goals vs Total prjects
One Table year, outcomes - Graph for the year VS Outcomes
