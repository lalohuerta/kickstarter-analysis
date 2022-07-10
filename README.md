# An Analysis of Kickstarter Campaigns
Trending analysis kickstarters  
[![Parent-categories-outcomes-picture.png](https://i.postimg.cc/TPJ1Z3zt/Parent-categories-outcomes-picture.png)](https://postimg.cc/t1796pC6)
* As you can see the more succesful Parent Categories are Music & Theater 
[![Kickstarter-Campaigns.png](https://i.postimg.cc/0NVxYKR1/Kickstarter-Campaigns.png)](https://postimg.cc/KK3dFz80)

* The top three Months to start a campaign based on the information are:

* May
* Jun 
* July

Final analysis: Some conclusions say that the three countries which you may invest in creating campaigns for theater plays between May and July are:

1. USA
2. Great Britain 
3. Canada 




# Chalenge Week 01 

# Kickstarting with Excel

## Overview of Project

### Purpose

Perform data analysis based on launch dates and funding goals for all the plays. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To complete this analysis you must follow the next steps:

- First you need to (Year) by Data created conversion 

[![Captura-de-Pantalla-2022-07-07-a-la-s-14-00-10.png](https://i.postimg.cc/GhG8jLyK/Captura-de-Pantalla-2022-07-07-a-la-s-14-00-10.png)](https://postimg.cc/zVDGz1pH)

- Second you have to add a pivotTable in Insert tab. Filtered by Parent category & Years, in Columns you need to see Outcomes, Rows with Data created conversion and Values with the count of outcomes. You want to see this information by month 

[![Captura-de-Pantalla-2022-07-07-a-la-s-14-01-44.png](https://i.postimg.cc/YqP4k4wt/Captura-de-Pantalla-2022-07-07-a-la-s-14-01-44.png)](https://postimg.cc/PPmfQ5x7)

Finally you need to create a PivotChart to visualize the relation between Outcomes & Date created conversion (Months), to do this add a PivotChart in PivotTable Analize tab, select line chart in the design Tab by clicking Change Chart Type. Add a title for the chart "Theater Outcomes Based on Launch Date"

[![Theater-Outcomes-vs-Launch.png](https://i.postimg.cc/X7MstfWf/Theater-Outcomes-vs-Launch.png)](https://postimg.cc/s1cPhZvx)

### Analysis of Outcomes Based on Goals

To complete this analysis you must follow the next steps:

First you need to create a new sheet and label it "Outcomes Based on Goals.", create the following columns to hold the data:
- Goal
- Number Successful
- Number Failed
- Number Canceled
- Total Projects
- Percentage Successful
- Percentage Failed
- Percentage Canceled

Second, in the goal column create ranges since less than 1,000 to 50,000 or more. Intervals each 5,000, you will use COUNTIFS() function to populate the Outcome, ranges created before and "plays" in "Subcategory" column in the kickstarter sheet, then calculate the Outcome percentage.

[![Captura-de-Pantalla-2022-07-09-a-la-s-21-10-13.png](https://i.postimg.cc/T3wprCZv/Captura-de-Pantalla-2022-07-09-a-la-s-21-10-13.png)](https://postimg.cc/gnCzpqzg)

Finally you need to create a line chart titled "Outcomes Based on Goal" so you can see the relation between the goal range and the percentage of each outcome. 

[![Outcomes-vs-Goals.png](https://i.postimg.cc/vZcZ1DVQ/Outcomes-vs-Goals.png)](https://postimg.cc/rD2k3Vjb)

### Challenges and Difficulties Encountered

In the Challenge I uploaded on Thursday 7th of July the chart "Outcome based on goal" was not the same as the online challenge. Had a jumpstart session same Thursday morning but appearently was not my session, so I let the chart as it appeared, on Friday I had my first tutoring session and I asked there. My tutor told me to double check the file I was working with because for some reason the values in that file were not the same as the file in CANVAS, so I downloaded the file again and copy the values in my file. Whit this action the chart "Outcome based on goal" changed and appeared as shown in the CANVAS challenge. I never known what happened with the file I was working with and why the values changed.                                                 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	
	* The months with more successful Theater Outcomes are May, June & July.
	* Is better not to Launch Theater plays by the last quarter of the year. 

- What can you conclude about the Outcomes based on Goals?

	* In the chart you can see a tendency related to the fact that the more you invest in a play, the lower the probability of being successful is.

- What are some limitations of this dataset?

	* Information 4 years old could be not accurate enough for actual projects. 

- What are some other possible tables and/or graphs that we could create?

	* In fact, a lot of information can be obtained from this database depending on the purpose of each project. In my case, I decided to analyze which film/video genre has the most failures in the US, creating a pie pivot chart.


	[![More-Failed-US.png](https://i.postimg.cc/Hs5QMRf5/More-Failed-US.png)](https://postimg.cc/SJS2FTQN)
