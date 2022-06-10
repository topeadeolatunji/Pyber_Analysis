# Pyber: Ride-sharing Application

## Overview of the Analysis
The report is looking at ride-sharing data across three different city types (urban, suburban and rural), and understanding the disparities in ride and driver counts, total fares for each ride in a specific city that falls under the city types (urban, suburban and rural) category, over a period of 5 months, from January to May of 2019. As the Data Analyst for Pyber, I will be utilising Matplotlib to help understand the relationship among city types. I have gathered data on rides, fares, drivers, etc. The ultimate goal is to understand patterns, trends, correlations and visually plot relatioship among the relevant variables such as fares, rides, drivers in city types, and provive insightful recommendation about my findings.


## Results
There are notable differences in the ride-sharing data among the city types. Let's start with the basic statistics by city types:

### Urban 
![image](https://user-images.githubusercontent.com/104689265/172965026-9683e277-8693-424e-b6ff-fa4a2b75380c.png)

Urban city type has the most count of ride data given that urban cities are highly concentrated in terms of population. There are 1,625 ride data in urban cities, which makes up about 69% of the total rides data gathered over the 5-month period. Urban cities made up about 63% of the total fares among the city types, and 81% of the driver counts. 

### Suburban
![image](https://user-images.githubusercontent.com/104689265/172966103-d37b1030-6c6e-4520-acfa-8bccde5e2bbe.png)

Suburban city type has the second-largest count of ride data given that suburban cities are more spread out compared to urban cities. There are 625 ride data in suburban cities, which makes up about 26% of the total rides data gathered over the 5-month period. Suburban cities made up about 31% of the total fares among the city types, and 16.5% of the driver counts. 

### Rural
![image](https://user-images.githubusercontent.com/104689265/172966375-fcc6249b-c0ba-4d5c-9276-9f93a423c6ae.png)

Rural city type has the least count of ride data given that rural cities are the most spread out from a population standpoint and the least dense of all the city types. There are 125 ride data in rural cities, which pales in comparison to the other city types and makes up 5.3% of the total rides data gathered over the 5-month period. Rural cities made up about 7% of the total fares among the city types, and 2.6% of the driver counts.

Comparing all city types in a box plot gives a better understanding about the disparities in rides, fares and driver count. See image below.

![image](https://user-images.githubusercontent.com/104689265/172967469-13880af4-1ed0-4952-8c9b-c3c112adb1bd.png)

![image](https://user-images.githubusercontent.com/104689265/172967581-e4dbfc2f-2369-49cf-82e1-d8491d405ca2.png)

![image](https://user-images.githubusercontent.com/104689265/172968298-7bf4c8d4-fbc5-455d-afae-9db30bbd43cb.png)

Putting together all of the above. Below is a table summary that depicts city type including total rides, fares and driver counts. The average fare and average per driver tells a lot about the overall contrast between rural and urban city types. Average fare and fare per driver is lower in urban cities because, rides are likely shorter distances and therefore less costly compares to rural areas with longer distance rides. The conclusion to be made is that ride-sharing is best scaled in urban cities, thus making fares less costly.

## Summary

![image](https://user-images.githubusercontent.com/104689265/172968895-079d2bd0-8d9c-4b2c-a660-b802134aa75a.png)

Putting together all of the above. Above is a table summary that depicts city type including total rides, fares and driver counts. The average fare and average per driver tells a lot about the overall contrast between rural and urban city types. Average fare and fare per driver is lower in urban cities because, rides are likely shorter distances and therefore less costly compares to rural areas with longer distance rides. Given the above, here are 3 actionable ideas as part of business recommendation:

        1. Ride-sharing is best scaled in urban cities, where the rides and number of drivers are dominant. We should look to continue to focus effort in urban       cities.
        2. Continue to gain market share from competition such as taxis, by offering competitive rates to riders and incentivising drivers by offering better pay
        
        3. Ensure easier access among city types such as travel to and from urban, suburban and rural, making it easier for riders to come to urban cities from the other city types during festivals and events. This will ensure more profitable rides and also increase drivers outside of urban cities.
