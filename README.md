# kickstarter-analysis
## Project Overview
    The goal of this project is to analyze kickstarter campaign data to determine the impact of the following two variables on campaign success:
    - Launch Date
    - Funding goal (in local currency)
---
## Analysis and Challenges
### Launch Date
    First we segment the data by launch date, using the date the campaign was created. 
    ![Success_by_Launch_Date](/resources/Theater_Outcomes_vs_Launch.png)
    Though we have data points from 2009 to 2017, 2017 is incomplete, data prior to 2014 is very thin, and several years lack results results for each month. We only have 2 years with campaigns in every month (2015, 2016). A second view, based on launch month and year was also created, to provide a more granular picture of success by month. ![Success_seasonality](/resources/Success_by_Month_Year.png)
    


### Funding Goal
    Segmenting data by funding goal was done by breaking goals down into $5K increments, with a minimum of $1K. Note all analysis is done in local currency, so we've blended amounts in different currencies.

