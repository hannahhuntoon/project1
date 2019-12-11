# project1
project one repo

Project Proposal: Our project is to uncover patterns in voter trends across the United States. We'll examine relationships between marital status, educational attainment, income, health care and state of residence, and their potential correlation with voting.

Questions for our project will be:
1. Is marital status correlated with voter patterns?
2. Is education attainment correlated with voter patterns?
3. Is household income correlated with voter patterns?
4. Is health care coverage correlated with voter patterns?
4. How does this relate to actual election results?

Our original focus for this project was on voter registration and using data from the Census Bureau, but our scope shifted to look at candidates voted for in the 2016 General Election. We decided to change our focus because census data had already been analyzed and raw data was difficult to come across.

Our data came from an online survey conducted by The Democracy Fund Voter Study Group and YouGov. The survey asked 116 questions from a sample size of 8,637. Questions ranged from basic demographic information to political preferences.

Participants were recruited from the 2012 Cooperative Campaign Analysis Project (CCAP) and used a sample matching procedure managed by YouGov. Participants differed in age, marital status, political views, educational attainment, etc. Our original sample size included 8,000 participants, 7,038 remaining after cleaning the data.
District of Columbia was included as a “state” – resulting in 51 total "states". Our data included all possible candidates and we narrowed our analysis to focus on the two major candidates: Hillary Clinton and Donald Trump. Please note that this further reduced our data set for some of our questions. 

In order to answer our questions, we looked through the documentation for the survey results and pulled out relevant columns. We used python, pandas, and jupyter notebook to clean our data. Additionally, we used matplotlib to graph our data.

For our exploration and clean up process we: 
-Removed blanks
-Created data frames with relevant columns
-Re-named column headers
-Looked for unique values
-Grouped by variables of interest based on “candidate voted for”

After analyzing our data, we found the following: 
Martial status did not have a significant correlation on voter trends as both breakdowns looked very similar. However, Trump did have 14.2% more married voters and Clinton had 10.2% single voters. Married voters made up majority of both parties. (project1/Percentage of Votes for Hillary Clinton by Martial Status.png + project1/Percentage of Votes for Donald Trump by Martial Status!.png)

For educational attainment,  the largest difference was between HS graduate (Trump) and post-grads (Clinton). (project1/Votes by Educational Attainment.png)

In terms of household income, Clinton had more votes on opposite ends of the spectrum (less than $10,000 - $29,999 AND $100,000 - $150,000+). Trump had more votes in the mid-range for household income ($50,000 - $99,999).  At $40,000 - $49,999 there was an exact tie. (project1/Votes by Income Bargraph.png)

For health care coverage, there were no major differences between the two candidates. The majority of voters were covered by private insurance or HMO. (project1/Votes by Health Care Coverage.png)

Finally, we compared our survey data to actual election results. In the actual election 8% more states went Republican than in our survey data. (project1/Percentage of States Won by Candidate.png)


In summary, the differences between Trump and Clinton were not as significant as we were expecting them to be. Additionally, our sample size may be skewed due to the sampling method. We did not compare the demographics of our participants to that of the general public. So, it is difficult to know if our sample was representative of 2016 voters. If given more time, we would do more comparative analysis on this. 
