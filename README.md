# PyBer_Analysis

 
 



##   Overview of the Analysis:
 
 
 The goal of this analysis was to provide rideshare visualiztions for Pyber to help improve public access to ride sharing services and affordable pricing for underserved or low income areas.  Different visualizations were used in order to highlight certain featues of the ride share data and city share data to illustrate a clearer picture of the rider and driver usages in urban, suburban, and rural regions.
 
The new analysis is designed to provide Pyber CEO and relevant stakeholders a better snapshot of ride-share data for the first quarter of 2019. The intention is to have a better defined analysis of weekly fare totals for both urban, suburban, and rural areas gathered from 2019-01-01 to 2019-04-28. The smaller timeframe makes it easier to account for any variability between our values over a short period of time. 

 

 
 
 
 
 
 ### Results:
 
 ![This is an image](https://github.com/rhutDU18/PyBer_Analysis/blob/main/Analysis/Pyber_fare_summary.png?raw=true)
 
 
 
 
The results from our Pyber_Summary_DF shows the ride share differences between city types.  The complete dataset shows us that urban cities have the largest amount of total fares at $39,854.38 and 1625 total rides.  Urban cities have more drivers than total rides which means that average rides for consumers cost the least out of all three city types. This means that fares for drivers will be the lowest out of the three total city types.  Suburban cities total fare amounts of $19,356.33 constitute a large percentage of the revenue Pyber generates. Average fare per ride and average fare per driver are closer aligned than other city types. Rural cities have the least amount of total fares at only $4,372.93. They have the lowest amount of drivers which means they have higher fares per ride and the higest fare per drivers.  
 

 
 
 
 
 
 ![This is an image](https://github.com/rhutDU18/PyBer_Analysis/blob/main/Analysis/Pyber_Summary_DF.png?raw=true)
 
 
This multiple line chart shows the total fares for each city type between the months of Janurary and April.  This was determined by taking the total number of rides and dividing it by total fare amounts to determine average fare per ride. The average fare per driver was calculated by dividing total drivers by total fares. Total drivers and total rides were found for each city type urban, suburban, and rural using Pyber ride_share and city_data.
 

 

 
 #### Summary:
 
 
Analyzing a smaller time frame means we can more accurately make assumptions about our ride share data.  Based off the Total Fare by City Type chart I would recommond three approaches that could help improve Pyber reduce disparities amongst city types for both riders and drivers.

1) Urban ride fares are on average $10 cheaper than rural ride fares. While rural fares make up a small percentage of the Pybers revenue increasing the amount the drivers in rural regions could help drive fare prices down and expand ride share access in underserved community types. 
2) Suburban city types have the closest average fare per ride and average fare per driver cost however this city type experiences the largest drop in rideshare usage during the last week of February which may highlight the need to lower fare pricing for suburban city type. 
3) Urban driver fares are almost 3 times lower as suburban driver fares.  Limiting Pyber drivers in urban settings could help raise fares retained by their employees. Also increasing fares in urban settings with traditional higher incomes could help reduce these disparities. 
