# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends
---
---
# Kickstarting with Excel

## Overview of Project
### Purpose
This project analyzes campaign outcomes of various projects, with the ultimate goal of outlining recommendations on how to best execute a campaign for a play in the US. Given a dataset that is inclusive of each campaign's goal, pledges, outcomes, etc. we should be provide guidance on campaign timing and funding expectations.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To determine the recommended campaign launch date, we compared the outcomes (success, failed, or canceled) of all theater campaigns against the time of year the campaign launched. By separating campaign outcomes types, we can easily identify which months had the most failed, successful, or canceled campaigns. This indicates which month(s) we should advise for and against a campaign launch. 

![Theater Outcomes vs Launch](https://raw.githubusercontent.com/emilymcdaniel/kickstarter-analysis/master/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
To determine the recommended campaign goal, campaign goals of plays were grouped as under $1000, over $50,000, and by $5000 ranges inbetween. The occurences of each outcome type within each range was counted. This grouping identifies which goal ranges had the most failed, successful, and canceled campaigns. 

![Outcomes vs Goals](https://raw.githubusercontent.com/emilymcdaniel/kickstarter-analysis/master/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The challenges in making a recommendation with only this information is that any month and any goal could have the greatest number of successful and failed campaigns, so it is possible that several months will have unclear outcome prediction from this analysis.
Secondly, the results may be skewed because neither analysis accounts for the year of the production, the theater's history of campaign success, or length of the campaign to name a few examples that would also impact success.
A third issue with the campaign launch date analysis specifically is the type of theater production (musical, plays, spaces) was not specified.

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?

- December is the only month where a theater campaign is more likely to fail or be canceled than to succeed. 
- May and June are the best months to launch a campaign because the ratio of success to failed+canceled is the highest.

### What can you conclude about the Outcomes based on Goals?

- Most plays in our dataset do not have a goal over $15,000. Acknoweldging there are fewer datapoints to provide a reliable analysis, goals of $15,000 or greater are likely to fail. In fact, the results show the smaller the goal, the more likely the campaign will succeed. 
- It is also notable that a campaign goal under $5000 is over 70% likely to succeed. 

### What are some limitations of this dataset?

- As mentioned above, there are many factors that were not considered in campaign success, including length of the campaign, the year of the campaign, etc. 
- Additionally, analysis is best done when there is overwhelming data in every category; it is possible that success could occur within a range we could not recommend solely because the limited data was insufficient for a recommendation.
- Another issue is grouping, by month or goal, could have been done differently. Perhaps a review by calendar quarters or further breaking down campaign success for productions under $1000 would be informative.

## What are some other possible tables and/or graphs that we could create?

Additional tables that could be useful are:

(1) Comparing outcomes to countries of interest to outcomes.

(2) Comparing the length of the campaigns to outcomes.

(3) Comparing the type of production to the number of backers (this could be useful in identifying topical interest).

(4) Finding intersections in all of the areas examimed - particularly if there is a specific plan for the desired campaign.
