# Surfs Up Challenge

# Overview

## Our client wants to open a new business in Hawaii.  The business will be a surf shop that also sells ice cream.  The purpose of this analysis project is to determine if the location selected had suitable weather conditions for the business model to succeed.  An SQLite file containing 7 years of weather data for Hawaii will be imported and then filtered to show summary statistics in June and December.  

# Results

## For this challenge we focused on the differences in temperature during June and December.  The results of the analysis are as follows:

![image](https://user-images.githubusercontent.com/106286533/182211717-78076b4c-5b8c-4c9f-ba65-bc096a6e364c.png)
![image](https://user-images.githubusercontent.com/106286533/182211752-3e25da9b-11e7-43fd-b0cf-aee682a1392b.png)

•	The average temperature in December is almost 4 degrees colder than June.  June is 74.9 and December is 71.04.  Overall, they are close and should not negatively affect the business in December.

•	The maximum temperature in both months is very close at 85 for June and 83 for December.    The upper quartile is also very close with only 3 degrees difference between June and December.  This suggests that the temperature stays pretty consistent.

•	The biggest difference between June and December is the low temperature which drops down to 56 in December from 64 in June.  The lower quartile shows slightly more consistent temperatures at 69 and 73 respectively.  Further analysis should be done to determine any possible outliers in December as there is a 13-degree gap between the min and lower quartile.  We could cross reference any weather events that happened causing the low temperature to drop.

# Summary and Recommendations

## In summary the temperature data comparison for June and December showed they were very similar overall and should not affect the business.  I have a few recommendations to get a more accurate picture of all weather data to help in determining in this is the best place to open as well as what the business hours of operation should be.

## A statistic that should be considered here is precipitation.  We touched on it slightly during the initial exploration of the dataset(pictured below), but it was limited to 1 year.  A query should be done to determine average rainfall and percent of rainfall by month over a multi-year period.  Based on the results, this can also be filtered down into each month to do a deeper dive if necessary. 

![image](https://user-images.githubusercontent.com/106286533/182211850-ad226fc5-3f62-4778-a2c2-429073cd5a84.png)

## The analysis of temperature can also be expanded on to include at least 2 other months to represent all 4 seasons.  This will give a more accurate picture of how the seasons affect the temperature, if at all.  

## In addition, we could try to find an additional dataset that includes temperature by time of day.  This would help determine what the best hours of operation would be for the shop. 
