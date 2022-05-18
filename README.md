# Analysis of Kickstarter Campaigns
## Performing analysis on Kickstarter data to uncover trends (Module 1 Assignment)
### Goal of analysis is to provide customer with insights that will assist in planning a successful Kickstarter campaign for their play.

## Analysis and Challenges
### Analysis of Outcomes Based on Lauch Date
 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/104801614/169138603-78837847-af34-4eda-9310-d119f5ed83dc.png)

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/104801614/169138534-33a0963f-a368-417d-9ef4-73d903f134f0.png)

### Challenges and Difficulties Encountered

## Results
When the data was analyzed to compare Kickstarters by month for theater-related campaigns, a few observations could be made.  Firstly, the most successful month for for campaigns of this category was May.  In general, campaigns were most successful during the summer months, with a semi-consistent decline in the total number of successful campaigns observed from May until September (see "Theater Outcomes vs Launch Date" Figure).  The second observation is that December was the least successful month to launch a Kickstarter for a play.  In December, nearly as many campaigns failed as they succeeded.  This was the only month of the year where the number of successful campaigns was not 20%+ higher than the number of failed campaigns.  In general, campaigns that were started in Winter (December to March) were less successful than other parts of the year (see "Theater Outcomes vs Launch Date" Figure). 

Analyzing the data to compare the outcomes of campaigns agaisnt their initial goals of fundraising shows several interesting trends.  In general, smaller play campaigns show a higher rate of success than larger campaigns ("small" and "large" being relative to the amount of money they are trying to raise).  However, this trend does not hold for campaigns between $35,000-$45,0000.  In those months, two-thirds of campaigns were successful.  It should also be noted that the number of those campaigns was limited to only 9 (i.e. the population of that dataset was much smaller).  therefore, the recommendation based on the data would be to pursue a campaign that is less that $20,000 because the failure rate generally exceeds the success rate past that inflection point (see "Outcomes vs. Goals" Figure).

Data was parsed to look at outcomes for plays depending on when the Kickstarter campaign was launched and how high the stated funding goal was.  The dataset itself was challenging because it included Kickstarter projects that may not be relevant to this particular effort (i.e. not all the data was restricted to theatrical plays).  An effort was made to exclude categories of data that are not relevant to this particular Kickstarter.  The dataset itself appeared to be pretty "clean", and did not contain any noticeable misspellings or typos.  However, one of the identified discrepancies/challenges of this dataset is that the different Kickstarter campaigns were not all normalized to the same monetary unit.  This could create miscategorization of some campaigns when they were separated into categories based on the pledged goal (i.e. campaigns in Great Britain and the US mare compared against one another because they fell into the same monetary category, when that may be inappropriate depending on what the exchange rate was at the time of the Kickstarter).

There is more analysis that could be done to help the customer arrive at a strategy for their Kickstarter campaign.  One interesting division of the data could be to look at whether plays have been less or more succesful over time.  In other words, a line graph showing the data based on year (instead of month) could show whether or not the success rate for plays has been increasing or decreasing (i.e. has the public's interest for plays gone up or down recently?).  Another useful item would be a table showing the success and failure rates based on time but further categorized by country.  This may show whether or not individual countries follow the same overall trends of success and failure depending on their launch dates and/or campaign-funding goal.
