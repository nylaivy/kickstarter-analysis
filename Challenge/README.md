# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to figure out how different Kickstarter campaigns fared in relation to their launch dates and their funding goals. This was completed by analyzing Kickstarter data on 1393 theater campaigns and 1066 play campaigns plays and visualizing campaign outcomes based on their launch dates and fundraising goals via pivot tables and graphing in excel.
## Analysis and Challenges
To analyze the relationship between theater campaign outcomes and launch dates I created a pivot table with rows based on months and columns based on the number of failed and successful outcomes respectively. Campaigns that have reached their goal amount are considered successful while those that have not are considered failed. This pivot table was filtered by parent category to only include theater campaigns. A line graph (shown below) was then created from this pivot table to visualize the relationship between campaign outcomes and launch month.

![Theater_Outcomes_vs_Launch](/Challenge/Challenge_Resources/Theater_Outcomes_vs_Launch.png)

To analyze the relationship between play campaigns and funding goals I created a line graph of the percentage of successful, failed, and canceled plays based on the funding goal amount. The COUNTIFS excel function was used to collect the outcome and goal data for the plays subcategory for the line graph. The number and total of successful, failed, and canceled outcomes was used to find the percentage of each outcome for campaign goals in increments of approximately 5000 dollars. The resulting line graph can be viewed below.

![Outcomes_vs_Goals](/Challenge/Challenge_Resources/Outcomes_vs_Goals.png)

The biggest challenge was using the COUNTIFS function on excel since I had never used it before. My formula when using this function was relatively long and needed to be used in 36 cells of my spreadsheet to help gather the percentages for the line graph showing the relationship between play campaign outcomes and funding goals. While this was a very intricate and time consuming part of my analysis, I overcame this challenge by getting used to using the function each time it was used. I slowly became comfortable with using this function and as I became comfortable it became quicker to use.

## Results

### Analysis of Outcomes Based on Launch Date
One conclusion that can be made regarding theater outcomes by launch date is that successful theater campaigns are at its highest in May. The second conclusion that can be made is that there are about the equal amounts of successful and failed theater campaigns in December.

### Analysis of Outcomes Based on Goals
What can be seen from the analysis of play outcomes based on campaign goals is that the highest percentage of successful play campaigns (and therefore the lowest percentage of failed play campaigns) is for plays with campaign goals that are less than $1000. The opposite is true for campaign goals with goal amounts between $4500 and $5000. There is generally a negative linear trend in successful play campaigns as the goal amount increases with the exception of a positive spike between the goal amounts of $25000 and $45000. The opposite appears to be happening with negative outcomes for play campaigns. There is generally a positive linear trend for negative play campaigns as the goal amount increases with the exception of a negative spike between the goal amounts of $25000 and $45000.

### Challenges and Difficulties Encountered
Some limitations of this data set include the fact that only data from a single crowdfunding website was used to make conclusions about crowdfunding fundraising campaigns. This is a limitation because trends in the data could be attributed to Kickstarter specifically as opposed to the impacts trying to be measured. Another limitation regarding the dataset was the lack of more specific data on the types of plays campaigned for. This is a limitation because making conclusions about play campaigns without knowing the ways different genres of plays impact campaign success seems like a large opportunity missed. These limitations would have to be the most challenging parts of the analysis along with the difficulty in explaining spikes in data trends for the analysis of outcomes based on fundraising goals.

Other possible tables and graphs that could have been created include a bar graph of each play outcome for each launch date month. A similar bar graph of each play outcome per goal interval amount could have also been made. Lastly graphs that show the distribution of theater and play data could have been made (such as histograms) to see if the data collected was skewed in any way and could therefore maybe help explain the spikes found in the analysis of outcomes based on fundraising goals.


