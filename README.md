# Kickstarting with Excel

## Overview of Project

This project is for analysis of Kickstarter data to see trends between the launch date of theater and it's outcome, and in the second analysis we can see successful, failed and canceled percentages for the plays subcatergory.

###purpose

This analysis helps Louise to decide in which month she has more chances to make a successful campaign for the theater and in which goal range she can have more chances to make a successful play. 


## Analysis and Challenges

###Analysis

In the first analysis, we compared the outcomes of all the shows in the theater category ('successful', 'failed', and 'canceled') to the months when the shows were launched in the Kickstarter datasheet.
In the second analysis, we found the percentages of different outcomes of plays based of their fundraising goals within the goal's ranges.

###Challenges

A missrepresentation of data could pose a challenge and lead to inaccurate outcomes.  If for example, the percentages are not calculated properly, the graphs could be misrepresented.

### Analysis of Outcomes Based on Launch Date

Here, a PivotTable is used to count the number outcomes of all the shows under the category of 'theater' based on the month at which the shows were launched. We only used 'successful', 'failed', and 'canceled' outcomes for this analysis. Then We used a PivotChart to visualize our findings as a line graph. 

### Analysis of Outcomes Based on Goals

The total amount of outcomes were calculated using the number of successful, failed and canceled campaigns for the plays subcategory within different goal ranges. The function used for this was countifs(). We also calculated the percentage for success, failed and canceled.  This was visualized in a line chart. 

### Challenges and Difficulties Encountered

There were no difficulties encountered during the analysis. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

As shown in the **Theater_Outcomes_vs_Launch.png**, There is an increase in successful shows from January to May with May having the highest number of successful shows.  After May the trend of successful shows decreases to the end of the year. The highest number of successful shows happen in the summer months. There is no clear trend seen for failed and cancelled plays from the chart. 

- What can you conclude about the Outcomes based on Goals?

As shown in the **Outcomes_vs_Goals.png** chart, the chances of having a successful show decreases as the fundraising goal increases.  However, in the 35000-45000 range the success rate goes up but at that goal there seems to be a risk due to uncertainty due to the imediate decrease of sucessfull shows within the next range.

- What are some limitations of this dataset?
Some limitations to this data is the inclusion of unnecessary data such as currency and show description. since we are only calculating successes, failiures, and cancellations, knowing which currency is being used is not relevant to our conclusions. The staff pick column was also not needed since it has no effect on the outcome of the shows.

- What are some other possible tables and/or graphs that we could create?

Other possible charts and graphs that could be created with this data could include the success average, median, and standart deviation.  we can also use a box chart to find any outlier data points.
