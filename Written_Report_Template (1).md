# Kickstarting with Excel

## Overview of Project
Louise wants to launch a kickstarter campaign to raise money for the play she wants to produce.  We have acquired data on other kickstarter campaigns to help guide Louise with her decision. 

### Purpose
The purpose of this project is to utilize Excel, PivotTables and PivotCharts to present the data in a useable format to help Louise make her decision.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
All of the campaigns in this project were sorted by the month in which they were started.  The number of campaigns within each month were then counted by whether they were successful or not.
The line chart that was created from this PivotTable makes it simple to compare how many campaigns each month were successful or failed or canceled.
![line chart of Outcomes Based on Launch Date](https://github.com/AndyHerron/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_Vs_Launch.png)


### Analysis of Outcomes Based on Goals
The kickstarter goals in this project were grouped into categories of $5000 intervals.  The percentage of campaigns that were successful were then calculated within each category by their goal amounts.
The campaigns that had the highest rate of success were campaigns with smaller goal amounts.  75.8% of the campaigns under $1000 were successful.  Campaigns up to $5000 also had a good rate of success, at 72.7%.
The next highest percentages were for campaigns with significantly higher goals, with a 66.7% rate of success for campaigns between $35,000 and $45,000.  Campaigns with mid-range goals (from $15000 to $35000) failed
more often than they succeeded.  Campaigns with goals between $5000 and $15000 did succeed more than fail, but only by a narrow margin.  The success rate for that range was only about 55%, or just more than half.
![line chart of Outcomes vs. Goals](https://github.com/AndyHerron/kickstarter-analysis/blob/main/Resources/Outcomes_Vs_Goals.png)

### Challenges and Difficulties Encountered
The difficulties that I had with this project were using Excel functions that I was unfamiliar with, and then formatting them correctly.  I had never used IF, COUNTIF, YEAR and MONTH functions before, and
also had never nested functions within Excel.  I certainly had never event attempted anything like this one:
=IF(w2=1, "Jan",IF(w2=2, "Feb",IF(w2=3,"Mar",IF(w2=4, "Apr",IF(w2=5, "May",IF(w2=6, "Jun", IF(w2=7, "Jul",IF(w2=8, "Aug", IF(w2=9, "Sep", IF(w2=10, "Oct", IF(w2=11, "Nov", "Dec")))))))))))


## Results

- *What are two conclusions you can draw about the Outcomes based on Launch Date?*
There does seem to be a benefit to starting kickstarter campaigns for theater in the spring.  Campaigns had a higher rate of success if they were started in April, May, June or July.
The highest numbers of campaigns were also started from May to August.  The colder months (November, December & January) had significantly lower rates of success than those 
started in May and June.  The fact that many more campaigns are started in spring doesn't seem to affect their success rate.  The campaigns are apparently not competing with each other.

- *What can you conclude about the Outcomes based on Goals?*
The highest rate of success for campaigns is for the campaigns with modest goals.  Keeping your goal under $5000 seems to increase the likelyhood that you will be successful.  

- *What are some limitations of this dataset?*

- *What are some other possible tables and/or graphs that we could create?*
It could be helpful to Louise to know the average number of donors to successful vs. failed campaigns.

