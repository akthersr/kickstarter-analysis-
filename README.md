# An Analysis of Kickstarter Campaigns
performing analysis on Kickstarter data  
# An Analysis of Kickstarter Campaigns

performing analysis on Kickstarter data  
## Overview

The main objective is to use Kickstarter Campaign data to uncover trends and to focus how different factors influence campaign outcomes.Here,Louise is looking to create a campaign fund for her upcoming play "Fever".These findings from the analyzed data help her to understand what factors should she focus to plan a successful campaign.

### Purpose

The purpose of this project is to provide Louise a visual feedback using pivot tables,charts and graphs to make her upcoming play Fever successful.This additional visualization would benefit her, to identify trends and provide recommendations on how a new campaign should be approached based on outcomes. 

## Analysis and Challenges

In order to complete the analysis,the kickstarter data set needed to be organized by breaking down the columns into new columns.At frist,we break down the category and subcategory column into two new columns named parent category and subcategory. By creating new columns for theater and plays,more detailed analysis can be done.The majority of the analysis conducted in this exercise by pivot tables and creating pivot charts to plot the results.

![Theater Outcomes by Launch Date]()

 The pivot table is filtered by the Parent Category “theater".Since we found there is a correlation between successful campaigns and months of the year they were launched, we created a pivot table to help Louise pick the most successful date to start her fundraiser.

![Parent Category Outcomes]()

This figure shows us that of all categories in the US,"theater" category had the most success.

## Analysis of Outcomes Based on Launch Date

Based on the data we had on theatre fundraisers we have created a pivot table to filter by successful, failed and cancelled fundraisers based on the month.The below graph shows the number of theater campaigns
catgorized by the outcomes charted by the months when they were launched.

![Theater Outcomes Based on Launch Date]()

This figure shows us that campaign launched in the spring were more successful than those launched in the winter.This means that the best time to start the campaign would be May or June. On the other hand campaign launched between December to January are the least successful.

## Analysis of Outcomes Based on Goals

For the analysis of outcomes based on goals,we create a sheet "outcomes based on goals".To analyze the outcome data and its relationship to fundraising goal we created a table in the outcomes based on goals sheet.

To create this table, I use countifs()formula to find the columns “Number Success”, “Number Failed” and“Number Canceled”.I used a variation of the following formula
=COUNTIFS(Kickstarter_Challenge.xlsx!$D:$D,"<1000",Kickstarter_Challenge.xlsx!$F:$F,"successful",Kickstarter_Challenge.xlsx!$R:$R,"plays")

![Outcomes Based on Goals]()

The figure above shows us that campaigns with lower range goals had a higher chance of succeeding than of failing.According to the chart,plays who had a goal less than $1000 and below $5000 had a good success rate in the 70 percentile.The most unsuccessful campaign are the ones with goals over $45000.

## Challenges

 The biggest challenge I had encountered during the analysis of outcomes based on goals sheet,when I entered the formula for countifs,I get errors for several times.And the whole process was very time time consuming.Resolving this errors requires attention to detail to ensure each comma,bracets and apostrophe was appropriately placed.

 ## Results

 We can infer the following conclusions from analysis of outcomes based on launch date:

 1.Based on the data collected for theater outcomes by lauch date, we observe that kickstarter campaigns launched in May or June tend to be the most successful for a play.So,we can interpret that summer months are better times to run a campaign.

 2. September to March are the least successful months to launch a campaign.The analysis also shows that the least amount of successful theater campaign launched in December.

 We can deduce the following conclusions from analysis of Outcomes based on Goals:

 In analyzing the data, it can be concluded that the rate of success is higher for campaigns with a funding goal that is less than $5000.Theater Kickstarter campaigns with a lower fundraising goal which is less than $1000 up to $4999 has the most  success rate ranging from 76%-73%.

 ##  Limitations

 There are some limitations in the data set.The Kickstarter data being analyzed is from 2014-2016.To provide Louise with a better analysis and understanding more up to date data could be used.

 ## Recomendation
 We could create  additional tables and graphs for further analysis of Kickstarter campaign data.We could use the other subcategory data under the parent category of theater to determine the overall success of plays comparison to other categories.

