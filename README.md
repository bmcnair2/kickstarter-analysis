# Kickstarting with Excel

## Overview of Project

Louise's play _Fever_ nearly reached its fundraising goal. She wanted to know how various campaigns fared in relation to their launch dates and funding goals. The Kickstarter dataset was used to visualize the outcomes. One visual was created for launch dates and the other was created for funding goals.

### Purpose

The purpose of this report is to analyze how various campaigns fared in relation to their launch dates and funding goals. All data is based from the Kickstarter dataset.

## Analysis and Challenges

The analysis of Theater Outcomes based on Launch Date was performed using pivot tables to look at theater data. The analysis of Outcomes Based on Goals was performed using the =COUNTIFS function to gather the number of Successful, Failed, and Cancelled theater plays. I did not encounter any difficulties with performing this analysis but there could have been challenges using the =COUNTIFS function. Pulling data from multiple tabs could get tricky, so I can see where potential problems may arise from using that function.

### Analysis of Outcomes Based on Launch Date

![Outcomes Based on Launch Date](../Desktop/bootcamp/Module%201/resources/Theater_Outcomes_vs_Launch.png)
From the analysis of Outcomes Based on Launch Date, we can see that the trends Successful, Failed, and Canceled projects all varies greatly. Succesful projects typically did the best in May and June, then faded off as the year would progress. Failed projects tended to stay relatively flat throughout the year, but October was month where most projects failed. Few projects were canceled, with the trend line remaining flat throughout the year.

### Analysis of Outcomes Based on Goals

![Outcomes Based on Goals](../Desktop/bootcamp/Module%201/resources/Outcomes_vs_Goals.png)
From the analysis of Outcomes Based on Goals, we can see that as the goal gets larger the more likely a project is to fail or be canceled. Less than $1,000 projects have a 70% success rate, but as the goal gets larger the percentage successful decreases dramatically. When the goal gets to above $50,000, the projects only have a 19% success rate. Keeping projects smaller is a better way for a project to become successful.

### Challenges and Difficulties Encountered

There were no real difficulties encountered with completing this analysis. Creating a pivot table and using the =COUTNIF function were straightforward. For a new user, however, pulling data from multiple tabs could get tricky, so I can see where potential problems could arise from using a function like COUNTIFS.

## Results

From Outcomes Based on Launch Date, succesful projects typically did the best in May and June, then faded off as the year would progress. Failed projects tended to stay relatively flat throughout the year, but October was month where most projects failed. From Outcomes Based on Goals, keeping projects smaller is a better way for a project to become successful. The only limitations of this dataset were that there were no canceled data for the month of October for Outcomes Based on Launch Date. Other possible graphs that could have been created are a pie chart for the percentages in Outcomes Based on Goals, or a stacked bar graph for Outcomes Based on Launch Date.

