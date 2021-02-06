# An Analysis of Kickstarter Campaigns
## Overview of Project
### Purpose
In this project, we examined kickstarter campaigns based on their launch dates and funding goals to help Louise visualize how other campaigns fared in comparison to hers. Project data can be found here: [Kickstarter_Challenge](https://github.com/Dspiper/kickstarter-analysis/blob/main/Kickstarter_Challenge%20copy.xlsx.zip)
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
Analysis was performed by filtering the complete kickstarter data down to specific datasets relevant to Louise’s ask. The first dataset was for successful, failed, and canceled theater outcomes by launch date which was found by creating a pivot table from the data in the Kickstarter worksheet. The pivot table was filtered based on "Years" and "Parent Category." The "Parent Category" filter was later set to only display results for "theater" campaigns. Once the filters were set, a line chart was created to display successful, failed, and canceled theater campaigns by month (line chart can be found below).
![Theater_Outcomes_vs_Launch](https://github.com/Dspiper/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
Second, we examined the percentage of successful, failed, and canceled theater campaigns based on their funding goals. We looked specifically at plays which is a subcategory of theater campaigns. We began by creating a new sheet that contained the following columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, and Percentage Canceled. In the Goal column, dollar-amount ranges were added to group campaigns together. The countifs function was then used to find the number of successful, failed, and canceled plays for each dollar-amount range. The number of total projects was calculated using the sum function for the successful, failed, and canceled plays in each dollar-amount range. Percentages were found by dividing the cell value of successful, failed, and canceled plays with the total numbers of projects for each dollar-amount range in the row. Line chart was created to display results of the analysis, see below.
![Outcomes_vs_Goals](https://github.com/Dspiper/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
When performing the analysis, the first challenge I encountered was using the countsif function to find the number of successful, failed, and canceled plays for each dollar-amount range. I had no previous experience using this function, so it required me to do some research to figure out how to format and input each criteria for the function. I was able to figure it out but was unsure if the order that the criteria was listed in the function influenced the outcome. I used the TA as a resource and was able to find that the order of the criteria does not matter for countifs function. 
## Results
What are two conclusions you can draw about the Theater Outcomes by Launch Date? For theater outcomes by launch date, I can conclude that the most successful theater campaigns were launched in May and trend downward as the year progresses. Also, I can conclude the months of May, June, and October had the most failed theater campaigns. 

What can you conclude about the Outcomes based on Goals? For outcomes based on goals, I can conclude that campaigns with a success rate greater than 70% had a goal of $4,999 or less. Also, that no play campaigns were canceled. 

What are some limitations of this dataset? A couple of limitations of this dataset would be the goal values and the amount of time the campaign was run. Louise reached her fundraising goal relatively quickly, but some campaigns may have taken the entire allotted time to reach their goal. 

What are some other possible tables and/or graphs that we could create? We could create an additional graph to show the number of backers for successful, failed, and canceled theater campaigns. This would give us greater insight to see if the numbers of backers influenced the outcome of the campaign. We could also create a chart to show the number of backers for a specific dollar-amount range. 
### End of Deliverable 3
## Analysis report on kickstarter campaign data to uncover trends to help Louise successfully launch her crowdfunding campaing to fund her play.
---
Findings:
* Theater is the most successful campaign category 
* Plays are the most successful campaign in the theater category
* Succesful plays had a mean goal of $5,049
* Failed plays had a mean goal of $10,554
* Successful plays had a higher average and median pledged amount
* May had the most successfull campaign launchs 
* January, June, July and October had the most failed campaigns
---
Recommendations: 
* Launch campaign in May
* Lower campaign goal to increase probabilty of being fully-funded
---
![Outcomes_Based on_Launch_Date](https://github.com/Dspiper/kickstarter-analysis/blob/main/Outcomes%20Based%20on%20Launch%20Date.png)
![Parent_Category_Outcomes](https://github.com/Dspiper/kickstarter-analysis/blob/main/Parent%20Category%20Outcomes.png)
---
[Kickstarter Data](https://github.com/Dspiper/kickstarter-analysis/blob/main/data-1-1-3-StarterBook%20(1).xlsx)
