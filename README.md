# Surfs_Up

## Overview

This analysis incorporates the usage of sqlalchemy in Python to access an sqlite database containing weather observations across different stations in Oahu, Hawaii. The completed analysis is to aid the party in determining the feasibility of an ice cream shop business in respect to ambient outside temperature. The months of June and Decemeber are compared to see if the business can be sustained year-round. 

## Results

Completion of the analysis yielded the following statistics for both June and December: 

June:
![June](/screenshots/juneTemps.png)

December: 
![December](/screenshots/decemberTemps.png)

Key Differences: 
* December temperatures are on average ~4°F lower than that of June
* Per the standard deviation value, December's temperatures are more varied throughout the month, although there are 11% fewer datapoints than June. 
* The lowest temperature in December is lower than that of June by 8°F

## Summary 

We see that on a pure numbers basis, December is colder than June. The data does not present if there is more wind present or if there are more frequent cloudy days in either month that may affect how the temperature of the day can be further perceived. There is precipitation data present, to which aan additional query could be made tallying the number of days in each month that experienced rain. Additionally, correlations could be made similarly by filtering through stations' elevations and their respective temperatures. 