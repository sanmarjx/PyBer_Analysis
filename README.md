# PyBer_Analysis
## Overview
The goal of this perform analysis on Pyber ride sharing data and provide visualizations in order to determine a way to provide access and improve affordability for underserved neighborhoods.
In order to achieve this goal the data was analyzed using Python's Pandas and Matplotlib.

## Results
After aggregating the data, a new data frame was created to be able to easily observe differences in the numer of total rides, total drivers, total fares, average fare per ride and average fare per driver between each city type.
![Summary_Data_Frame](https://user-images.githubusercontent.com/116690861/204149320-9d209a05-19d8-43fd-b174-42bd1024016a.png)

A few things can be observed in this data frame:
- Urban cities have the highest number of total rides.
- Urban cities have 4 times as many drivers as suburban cities and 30 times as many as the rural cities
- Rural cities have the highest average fare per ride and per driver
- Urban cities have the highest demand for ridesharing services

The analysis did not end there. In order to ilustrate the results a line chart was created to show the total fare by city type from January 1st, 2019 to April 30th, 2019. 

![2019_Fare_by_City_Type](https://user-images.githubusercontent.com/116690861/204149831-e1366868-0931-4e7d-a14b-45af26b78cdc.png)

There a few other findings in this graph:
- The tree city types start the year in an ascending pattern that peaks at the end of February. The Urban cities are able to maintain the high level of fares through a little bit of March but the Suburban and Rural areas see a big drop.
- The Urban and Rural cities increase again leading into April. This is different from the Suburban cities that do not see another surge until mid April.

## Summary and Recommendations
1. Looking at the number of total rides and drivers it seems like the Rural cities are underserved. However, another study would be necessary before hiring more drivers for those areas. This study should focus on determining if the small number of rides are caused by a slow demand or if they are caused by not having enough drivers. It could be that the Rural cities have a much larger area to cover so each ride is longer.
2. It looks like the number of drivers in Suburban areas could be increased to reduce the average fare per ride. The demand in these areas is already much higher than the rural cities but the average fare per ride is still high.
3. The average fare per driver in Urban cities is much lower than the other two city types. In order to help with this, Pyber should consider a marketing campaign. Looking at the Total Fare by City Type chart, mid February sees a jump in total fares. This would be a good time to start an ad campaign.
