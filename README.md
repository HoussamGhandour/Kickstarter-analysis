# Kickstarting with Excel
This readme file is structured into 4 main sections listed below.  

Section 1 - **Overview of Project**  
Section 2 - **Analysis Methodology and Challenges**  
Section 3 - **Results**  
Section 4 - **Limitations**  
Section 5 - **Recommendations for Additional Analysis** 
  
## 1. Overview of Project
This project performs an analysis on Kickstarter crowdfunding data to uncover trends based on launch date (months) and aimed goal (dollars).
### 1.1 Purpose
The purpose of the project is to provide Louise with a data-driven analysis that may help her with her decision making for when to launch her campaign and in her selection of an appropriate goal.


## 2. Analysis Methodology and Challenges
The analysis was performed using Excel (version 16.0.13127.20266). The analysis was completed using kickstarter data that was provided in the "kickstarter" tab in the excel sheet. Some of the used tools/functions included: filtering data, `countifs()` function, creation of pivot table, creation of pivot chart, formatting and editing charts and tables for readability.

### 2.1 Challenges
There were no significant challenges performing this analysis. Below is a list of some of the challenges and how they were overcome.

1) Removing the filter buttons from the Pivot Charts - Resolved by a quick Google Search
2) Adding Images to this readme file in GitHub - Resolved by a quick Google Search 
3) Providing data-driven recommendations based on the limited analysis that was performed - Provided Recommendation for additional analysis in the Recommendations Section


## 3. Results
This section presents the results based on launch date and goals.

### 3.1 Analysis of Outcomes Based on Launch Date
The line chart below shows that theater projects have the largest number of successful projects (111 projects) when the launch date was May. It should also be noted that the largest number of failed projects (52 projects) was when the launch date was May. More importantly, the gap which is the difference between the successful and failed projects, is largest when the launch date was in May (111-52=59). It is recommended to use percentage of successful and failed projects instead of raw numbers to have a clearer indication of the chance of success.  

![Outcomes based on Launch Date](https://github.com/HoussamGhandour/Kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png)

**Conclusions**  
1. There is an almost upward trend of successful projects from December until it peaks in May. There is a downward trend from May until the rest of the year. This suggests that summer months especially May have higher number of successful projects.
2. The number of failed projects follow a similar trend but less volatile. It is recommended to accompany this analysis with a ratio of success-to-fail instead of representing the raw numbers only.

### 3.2 Analysis of Outcomes Based on Goals
The line chart below shows an alternating pattern between successful and failed play projects based on the goal ranges. It should be noted that success rate is significantly higher than failed rate for projects with a goal of 5000$ or less. Also, the goal range between 35,000 and 40,000 showed relatively high chance of success compared to the rest of ranges. The alternating pattern makes it hard to identify possible explanation. It is recommended to perform additional analysis to calculate and visualize the pledged percentage of the goal for these ranges as it might highlight better trends.

![Outcomes based on Goals](https://github.com/HoussamGhandour/Kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png)

**Conclusions**  
1. The pattern seems to be alternating and it is difficult to draw conclusions from it. It is possible that some of the failed projects barely missed the goal, therefore, it is recommended to perform an additional analysis to show the percentage of pledged to the goal. 
2. Limiting to this performed analysis, the recommendation to Louise would be to choose a goal in the range that is closest to the ranges with higher successful percentages. I.e. if Louise's initial goal was $7,000, the recommendation is to reduce it a little bit to around $5,000 to have higher rate of success. Whereas, if Louise's goal was $30,000, the data indicates that there is higher chance for her to meet the goal if she raises the goal to around $35,000. Again, it is preferred to add additional scope to this project to perform additional analysis to draw more reliable data-driven recommendations and conclusions.

## 4. Limitations
Below is a list of limitations for the analysis and dataset.

1. The scope of analysis was limited to study trends based on launch date and goals only

2. One of the analysis limitations is the use of "successful" vs "failed" outcomes as base of comparison. "Successful" is defined as project which succeeds to meet or exceed the goal while the "failed" outcomes are when the project fails to meet the goal. This categorization made this analysis kind of discrete by disregarding the actual pledged money for each project.

3. Another limitation of the dataset is that it is missing the amounts collected in each month. This can be more helpful that determining the launch date based on successful number of projects.

## 5. Recommendations for Additional Analysis
Some of the recommendations for additional analysis were discussed in the aforementioned sections to provide Louise with more reliable data-driven conclusions. The recommendations are also summarized below for quick reference.

1. Analyze percentage of successful projects based on launch date
2. Consider analyzing the pledged money based on launch date instead of successful and failed outcomes
2. Study effect of pledged percentage of goal based on goal ranges to have a better representation of outcomes
3. Consider statistical analysis to study sensitivity of setting launch month and goal on the pledged amounts

