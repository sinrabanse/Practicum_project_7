# Practicum_project_7
 My seventh project from Practicum course. "Making Business Decisions Based on Data"

 What was used in the project: Python, Jupyter notebook. Libraries: pandas, numpy, plotly, matplotlib, seaborn, scipy, statsmodels.

# Project Description

I am an analyst at a big online store. Together with the marketing department, I've compiled a list of hypotheses that may help boost revenue. 
I need to prioritize these hypotheses, launch an A/B test, and analyze the results.

# Steps
1) Prioritizing Hypotheses.<br/>
   The file hypotheses_us.csv contains nine hypotheses on boosting an online store's revenue with Reach, Impact, Confidence, and Effort specified for each.
   - Apply the ICE framework to prioritize hypotheses. Sort them in descending order of priority.
   - Apply the RICE framework to prioritize hypotheses. Sort them in descending order of priority.
   - Show how the prioritization of hypotheses changes when you use RICE instead of ICE. Provide an explanation for the changes.
2) A/B Test Analysis.<br/>
   I carried out an A/B test and got the results described in the files orders_us.csv and visits_us.csv.
   - Graph cumulative revenue by group. Make conclusions and conjectures.
   - Graph cumulative average order size by group. Make conclusions and conjectures.
   - Graph the relative difference in cumulative average order size for group B compared with group A. Make conclusions and conjectures.
   - Calculate each group's conversion rate as the ratio of orders to the number of visits for each day. Plot the daily conversion rates of the two groups and describe the difference. Draw conclusions and make conjectures.
   - Plot a scatter chart of the number of orders per user. Make conclusions and conjectures.
   - Calculate the 95th and 99th percentiles for the number of orders per user. Define the point at which a data point becomes an anomaly.
   - Plot a scatter chart of order prices. Make conclusions and conjectures.
   - Calculate the 95th and 99th percentiles of order prices. Define the point at which a data point becomes an anomaly.
   - Find the statistical significance of the difference in conversion between the groups using the raw data. Make conclusions and conjectures.
   - Find the statistical significance of the difference in average order size between the groups using the raw data. Make conclusions and conjectures.
   - Find the statistical significance of the difference in conversion between the groups using the filtered data. Make conclusions and conjectures.
   - Find the statistical significance of the difference in average order size between the groups using the filtered data. Make conclusions and conjectures.
   - Make a decision based on the test results. The possible decisions are: 1. Stop the test, consider one of the groups the leader. 2. Stop the test, conclude that there is no difference between the groups. 3. Continue the test.

# Description of the data

#### The hypotheses_us.csv table:

'Hypotheses' — brief descriptions of the hypotheses<br/>
'Reach' — user reach, on a scale of one to ten<br/>
'Impact' — impact on users, on a scale of one to ten<br/>
'Confidence' — confidence in the hypothesis, on a scale of one to ten<br/>
'Effort' — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

#### The orders_us.csv table:

'transactionId' — order identifier<br/>
'visitorId' — identifier of the user who placed the order<br/>
'date' — of the order<br/>
'revenue' — from the order<br/>
'group' — the A/B test group that the user belongs to

#### The visits_us.csv table:

'date' — date<br/>
'group' — A/B test group<br/>
'visits' — the number of visits on the date specified in the A/B test group specified<br/>
