# Kickstarting with Excel

## Overview of Project
Louise is looking to launch a crowdfunding campaign to raise money to help produce one of her plays. This is her first time using Kickstarter and she is not quite sure where to start or how to structure her campaign. She knows there have been many successful campaigns in the past (and some not so successful ones!) and she would like to learn from those in order to ensure that her fundraising goal is met. 
<BR>
<BR>
### Purpose
We were hired by Louise to try and determine the characteristics of succesful kickstarter campaigns to provide some insight into how she should structure her own crowdfunding effort. 
<BR>
<BR>

## Analysis and Challenges
To provide Louise with the insights she desires, we pulled a dataset from Kickstarter of roughly 4,000 campaigns that were launched between 2009 and 2017. This data provided us with details including the campaign's goal, pledged amount, date launched, duration, category and total number of backers. With this data we can make some inferences on what makes a successful crowdfunding campaign.

We wanted to focus specifically on the category that Louise is interested in - plays. In the data, plays are a subcategory of the theater parent category. There were 1,394 theater campaigns and within that, 1,067 were for plays specifically.

One challenge we ran into during this analysis was not getting bogged down by the performance of campaigns outside of the *theater/plays* category. How well a *Space Exploration* or *software* crowdfunding campaign performed is unlikely to inform Louise on how to best run her campaign. While interesting to gain an understanding of the entire crowdfunding landscape, this information tends to be more of a distraction and could lead to some less-than-useful conclusions. We will focus specifically on the data within the theater category for this analysis.
<BR>
<BR>


## Analysis of Outcomes Based on Launch Date
Having combed through the data to make some initial assumptions, we pinpointed launch date as a variable worth considering when planning a crowdfunding campaign. While there may be some externalities that can impact this (e.g., a Kickstarter to fund a new snow shovel probably won't do too well in April) we determined that the dataset was large and diverse enough to prove useful.   

To get this data here we created a pivot table and filtered only campaigns within the theater parent category. We then built a line graph chart based on this table to visualize the number of succesful, failed and canceled campaigns by month.
<br>
<br>
## Analysis of Outcomes Based on Goals
How much the campaign hopes to raise is another variable we highligted as an important consideration because how high or low you set your goal will have a direct impact on its success. For example, if the goal is set at one million dollars you can almost certainly expect for your campaign to fail, because youve set the bar too high, so finding a reasonable goal is extremely important. 

To look at this data we grouped the goals into amount ranges for easier analysis and looked at the percentage of campaigns that were either successful or failed.
<br>
<br>
### **Challenges and Difficulties Encountered**
Trying to determine the statistical significance of some of the data was a bit of a challenge. Is 93 successful campaigns launched in May more significant compared to the 60 that were launched in February? This is something worth digging into to provide a more robust analysis of the data by eliminating insignificant differences and outliers.
<br>
<br>

## Results


### **What are two conclusions you can draw about the Outcomes based on Launch Date?**
1. Across all categories, campaigns launched in May were the most successful. This holds true for the theater category as well with the largest majority of campaigns launched in May being succesful. On average 65% of theater campaigns launched in May, June, or July are succssful and 33% fail.

! [Outcomes by Launch Date] ()


2. Campaigns launched between October and December have the highest percentage of failed campaigns - 41%, on average. This may be due to the it being the holiday season and money being spent elsewhere. 
<br>
<br>
### **What can you conclude about the Outcomes based on Goals?**

Campaigns with reasonable goals are more likely to succeed than those with high goals. The most successful campaigns had a goal of less than $5,000 with an average of 74% of them being successful and 26% failing. There is a negative correlation between outcomes and goals - the higher the goal the less likely the campaign is to succeed. While the chart shows this fairly well, there is some outlier data that is skewing the chart a bit. Campaigns with goals between $35,000 and $44,999 are 67% successful and show up as a seem to contradict the idea that higher goals lead to increased likelihood of failure, but it's worth considerig the sample size here, with only nine campaigns in the sample it is likely too small to be representative. 

! [Outcomes by Goal] ()

Overall, if you are looking to have a successful campaign, keeping the goal below $5,000 is advisable.
<br>
<br>

### **What are some limitations of this dataset?**
While the dataset is fairly robust, with ~4000 campaigns to look at, it is mostly representative of the US and Great Britain. If you are looking to do an analysis of kickstarter campaigns outside of these two countries, the data might not be as useful. 
<br>
<br>


### **What are some other possible tables and/or graphs that we could create?**
One other consideration could be an analysis of campaign backers. How does the amount of backers impact success? How many backers do succesful camoaigns have? What is the average pledge for successful campaigns? This information could give Louise an idea of how many backers she might need and how much they would need of them them to pledge to meet her goal. 

