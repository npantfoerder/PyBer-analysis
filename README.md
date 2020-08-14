# PyBer with Matplotlib

## Overview of the Analysis
### Purpose
The CEO of PyBer, a Python based ride-sharing app company, has asked for a compelling visualization of all the rideshare data from January through April of 2019. This analysis will help PyBer improve access to ride-sharing services and determine affortability for under-served neighborhoods.

## Results
### Differences in Ride-Sharing Data
The summary DataFrame shows the total rides, total drivers, total fares, average fare per ride, and average fare per driver for each type of city. There were 66 urban, 36 suburban, and 18 rural cities in the data. The total number of rides for each type of city matches what we might expect; the total of 1,625 rides in urban cities is the highest and the total of 125 rides in rural cities is the lowest. The total number of drivers and the total fares for each city type also follow this pattern. 

Rural cities have the highest average fare per ride ($34.62) and urban cities have the lowest ($24.53). The average fare per driver is also highest in rural cities ($55.49) and lowest in urban cities ($16.57). This can be seen in the summary DataFrame printed below:

<img src='https://github.com/npantfoerder/PyBer-analysis/blob/master/analysis/PyBer_summary_df.png'>

The "Toal Fares by City Type" graph shows the differences in weekly total fares from January to April. Urban cities have the highest total fares ranging from $1,661.68 to $2,470.93 as shown by the yellow line. The red line shows that the total fares in suburban cities which ranges from $721.60 to $1,412.74 on a weekly basis. The lowest total fares is depicted by the blue line for rural cities and ranges from $67.65 to $501.24. In late February, the total fares in all types of cities seem to be at their highest. The relationship between total fares and date is depicted in the graph below:

<img src='https://github.com/npantfoerder/PyBer-analysis/blob/master/analysis/PyBer_fare_summary.png'>

## Summary
### Business Recommendations
- Based on the results, one recommendation to the CEO for addressing disparities among the city types is...
- Another recommendation to the CEO is...
- A third recommendation for addressing disparities among city types is...

#### Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7.3, Anaconda 4.8.3, Matplotlib 3.2.2
