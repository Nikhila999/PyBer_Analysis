# PyBer_Analysis

## Overview of the analysis

The purpose of this analysis is to help PyBer improve the access to ride-sharing services and determine affortability to all neighborhoods by displaying the relationship between type of city, average fare, number of drivers, number of rides and its percentages. In this analysis, we are creating a summary analysis on ride-sharing data by its type.

## Results

The ride-sharing summary dataframe has three city types, Urban, Suburban and Rural. Now, lets take a close look at the details.
   - Total Rides: Urban area has more number of rides (1,625) compared to suburban (625) and rural (125). Total number of rides in rural area is 13 times less than in urban area.
    
   - Total Drivers: Similar to total rides metric, total number of drivers in uarban area are 2,405 that is atleast 30 times more than total number of drivers in rural areas (78). Suburban has 490 drivers.
    
   - Total Fares: Total fares in urban ($39,854.38) is way more than suburban ($19,356.33) and rural areas ($4,327.93) consistent with the total rides and total drivers metrics.
    
   - Average Fare per Ride: The average fare per ride is slighly more in rural areas ($34.62) compared to the urban ($24.53). Suburban average fare is half way between urban and rural at $30.97.
    
   - Average Fare per Driver: The drivers in rural area makes more money on a ride ($55.49) than in suburban ($39.50) or urban ($16.57). Because there are many drivers in urban area, eventhough total rides are high the average fare per driver is very low. Drivers make 3.5 time less in urban city type.

![](https://github.com/Nikhila999/PyBer_Analysis/blob/main/analysis/citytype_summary.png)

In the line graph, we are representing the total fare per week for the first four months on year 2019. The average fare per week for rural city type oscillates between 0 and $500 and for suburban the average weekly fare is between higher $600 to little under $1,500. The Urban area has the average fare per week start at around $1600 and going up to $2500, Feb.

![](https://github.com/Nikhila999/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary

Analyzing the results of the ride-sharing summary data per city types, we can conclude that,
1. Rural areas are underserved, with just 78 drivers. The average fare per driver is high in rural city type could be because the people have to drive long distance to reach destination unlike urban areas. Rural are is under served with just 78 drivers, we could increase the drivers and make our ride-sharing services available for more people.
2. It is interesting to look at the suburban city type, because its metrics are in between urban and rural. This city type is also moderately under served with 490 drivers and 625 rides. Suburban area can benefit from increasing the number of drivers.
3. In urban city type, ride-sharing is economical with average price per ride is $24.53. Average fare per driver is very less because there are more drivers available. Although the total fares are high for urban area, it is advised that we do not add more drivers.

