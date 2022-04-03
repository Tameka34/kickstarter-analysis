# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was to use data from _Kickstarter_, a crowd-funding platform, to analyze the success of campaigns that meet certain criteria. Specifically, I looked at crowd-funding efforts for plays, and whether those failed, met, or exceeded the goals set for said campaigns. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To determine outcomes of campaigns for plays based on their launch date, I first filtered the dataset to only include campaigns under the subcategory of "play" using a pivot table in Excel. Then, using the launch date, I separated the campaigns by month and aggregated total campaigns based on whether they were successful, failed, or canceled. The results are visualized in the chart below. 



### Analysis of Outcomes Based on Goals
In analyzing the outcomes of campaigns for plays based on goals, I first used an established scale of goal amounts, which was goals starting or below $1,000.00 and up to and over $50,000.00, broken into increments of $5,000.00. I then counted the number of successful, failed, and canceled campaigns for plays with goal amounts that fell within each range. From there, I determined what percentage each group of successful, failed, and canceled campaigns were of the total campaigns in that goal range. The results of this analysis are charted below.

### Challenges and Difficulties Encountered
The data needed to be cleaned before it could be used. This required changing some of the datatypes, filtering, and adding some calculated fields. Once the data was cleaned, I did

## Results

- As you can see, based on the analysis of outcomes by launch date, campaigns for plays are generally successful. There also appears to be an uptick of successful campaigns that are launched in May.

- Based on the analysis of outcomes based on goals, play campaigns with goals under $1,000.00 have a rather high success rate, at about 76%. As the goal amount increases, the percentage of successful campaigns begins to decline, ultimately decreasing to 20% as goals reach between $25,000.00 and $29,000.00. Then the success rate begins to increase again, ultimately plateauing at 67% as goals climb to $35,000.00 up to $49,999.00, before declining again as goals reach beyond the $50,000.00 mark.

- One particular limitation of this dataset is that is only contains information for campaigns up to 2017, so there is no data within the last 5 years to make comparisons to. There is also no conversion standard for the monetary amounts and all amounts are listed in that country's currency, which would make it difficult if one wanted to compare campaigns from different countries. 

- If I were to do further analysis on the data, I think it would be interesting to see how play campaigns compare to other campaigns, for example plays against musicals. I could create a table comparing the percentage of successful play campaigns to musical campaigns over the years represented in the dataset, then vizualize the reults in a line graph. I would also like to investigate why there is a spike in successful plays in May, and based on percentage if it was really as significant as the numbers make it seem. I could recreate the Outcomes By Launch Date table using percentages, and if the number is still high, look at jsut plays in May and go from there. 
