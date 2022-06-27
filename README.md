# Kickstarting with Excel

## Overview of Project
*Louise’s play Fever came close to its fundraising goal in a short amount of time.

### Purpose
* The purpose of this project is to determined how different campaigns fared in relation to their launch dates from Jan to Dec and their funding goals. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
* First I created a Pivot table with Month as row, and outcomes on successful, failed, and canceled as my columns. So we can see outcome for in each month. Because it's a plays which is under theater category, we wanted to filter the data by selecting theater only. Then I generated a theater outcomes based on launch date graph for easy visualization. In this graph we can see that successful numbers are higher in May and it will start lowering down after May, and failed number are around 30 to 50 for all months, and canceled number are lower on all months.

### Analysis of Outcomes Based on Goals
* The first step is create a Pivot Table, and I have a breakdown each goal range to determine what is the number of successful, failed, and canceled for each goal range. Because we are only counting plays, I filter the subcategory column to plays only. Then I create a column to sum up all the number, so I can use it to determine the percentage for each. Lastly, I created a graph for visualize the percentage based on each goal range. 

### Challenges and Difficulties Encountered
* I haven't faced any challenged for this project. However, there are some challenge I wanted to point out. 
* First, creating a pivot table with the correct result might be difficult, and you would have to play around with Pivot table to find the date that you wanted to display. 
* For Outcomes based on Launch Date pivot table, when we drag date created conversion to the rows, it will also include quarters and years2 in the row and we want to remove that because we only wanted to see month. 
* For outcomes Based on Goals table, the challenge is on using the formula COUNTFS, and you want to make sure you are using COUNTIFS and not COUNTIF because you are going to have multiple criteria in the formula. Another challenge would be determine how to set criteria for the goal rate in the COUNTIFS formula, it might be a little bit tricky in the beginning. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
*Under Outcomes based on Launch Date, we can concluded that theater will do better in May, and the successful number will go down after June. 

- What can you conclude about the Outcomes based on Goals?
*Under Outcomes based on goals, we can conclude that goals that are under 10000 will have a high successful rate, and as it go over to 45000 the rate to meet out goal is very low. 

- What are some limitations of this dataset?
* I would say the percentage on Outcomes Based on Goals' graph is incorrect because as the goal range goes higher, the total project is lower so the percentage of successful rate have a significant affect. It could be mistakenly think there is a high a percentage in some goal ranges. 

- What are some other possible tables and/or graphs that we could create?
*I think column chart will also work for this project. 
