# Kickstarter-analysis
## Overview of Project
	In this project we are analyzing crowdfunding data in order to help Louise who is a new play writer. She is looking into start a crowdfunding campaign to raise over $10 thousand dollars that she needs to fund her play "Fever".    

### Purpose
	The purpose of this project is to analyze the data collected of over four thousand  crowdfunding campaigns and focus in how the launch date and the proposed goal affect the outcomes of these crowdfunding campaigns. With this data we will create tables and charts that will help us understand these factors so we can recommend Louise the best dates and goal expectations that will improve her chances of having a successful campaign.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
  In order to start the analysis of these factors; we started analyzing how outcome and launch date are related. First, we created a new column in our data sheet so we could extract the year of the launch date for each campaign by using the function YEAR(). Then we created a pivot table with date created column data as our rows, outcomes as our columns, years and parent category as our filters and count of outcomes as our values. Then with the pivot table obtained we filtered the column labels so it just showed succesful, failed and canceled campaigns data. Furthermore, we grouped the row labels data to show the months of the year and we filtered the parent category to show only the data for theater. Then we sorted the campaign outcomes so we would have these outcomes in descending order. Finally, we created a line chart from the pivot table that would show us the relationship between outcomes and launch month.
### Analysis of Outcomes Based on Goals
  Moreover, we created a new sheet where with the help of the function COUNTIF() we created a table that showed us the number, percentages and totals of successful, failed and canceled campaigns; grouping them by goal amount ranges. Then with this table we created a line chart that showed us the relationship between goal amounts and percentage of succesfulness, failure and cancelation.
### Challenges and Difficulties Encountered
  The challenges that we encountered were mostly on how to properly write the functions requirements. Also, i had to spend some time deciding the columns, rows and values of the pivot table. It was difficult to setup the pivot table since my computer automatically grouped and formated the date column; so my table did not look exactly as the one provided as an example in the module. Another challege was to wirite the analysis on the readme file since there was not much instructions on how to do it and how to add links and images to it.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  * We can conclude that the best month to start a crowfunding campaign is May. So Louise should start her campaign in this month.
  * We also found that the worst time to start a crowfunding campaign is at the end of the year, were the succesful rate is low. 
- What can you conclude about the Outcomes based on Goals?
  * We can conclude that campaigns with goals from $0 to a little bit under $10,000 dollars have a more successful rate. This is a descending rate so the closer the goal is to the $10,000 the lower the rate of successfulnes. Moreover, campaigns with a goal between $10,000 and $29,999 have a hicgher rate of failure. So we recommend that Louise lower her goal to a little bit under $10,000 in order for it to have more probabilities of being successful.  
- What are some limitations of this dataset?
  This dataset do not reflect the possible relationship between the genre of the plays or a description of the crowd in the crowdfundings that could have an impact on the successfulnes of the crowdfunding.
- What are some other possible tables and/or graphs that we could create?
  We could create a graph that compares the average donation with the outcome to see how a crowd that pledge more individually, affects the outcome. Also, we could create a graph that compares the country were the crowfunding was done in order to decide were it would make more sense to have the crowfunding
