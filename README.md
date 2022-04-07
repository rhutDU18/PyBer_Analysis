# PyBer_Analysis

 
 



##   Overview of the Analysis:
 
 
 The goal of this analysis was to provide rideshare visualiztions for Pyber to help improve public access to ride sharing services and affordable pricing for underserved or low income areas.  Different visualizations were used in order to highlight certain featues of the ride share data and city share data to illustrate a clearer picture of the rider and driver usages in urban, suburban, and rural regions.
 
The new analysis is designed to provide Pyber CEO and relevant stakeholders a better snapshot of ride-share data for the first quarter of 2019. The intention is to have a better defined analysis of weekly fare totals for both urban, suburban, and rural areas gathered from 2019-01-01 to 2019-04-28. 


 
 Variailtiy between months was accounted for through the use of error bars to show month to month deviations in fare price falling above or below the mean. To get 
 
 
 
 
 
 
 

 
 
 
 
 
 ### Results:
 
 ![This is an image](https://github.com/rhutDU18/PyBer_Analysis/blob/main/Analysis/Pyber_fare_summary.png?raw=true)
 
 
 
 
The results from our Pyber_Summary_DF shows the ride share differences between city types.  The complete dataset shows us that urban cities have the largest amount of total fares at $39,854.38 and 1625 total rides.  Urban cities have more drivers than total rides which means that average rides for consumers cost the least out of all three city types. This means that fares for drivers will be the lowest out of the three total city types.  Suburban cities total fare amounts of $19,356.33 constitute a large percentage of the revenue Pyber generates. Average fare per ride and average fare per driver are closer aligned than other city types. Rural cities have the least amount of total fares at only $4,372.93. They have the lowest amount of drivers which means they have higher fares per ride and the higest fare per drivers.  
 

 
 
 
 
 
 ![This is an image](https://github.com/rhutDU18/PyBer_Analysis/blob/main/Analysis/Pyber_Summary_DF.png?raw=true)
 
 
This multiple line chart shows the total fares for each city type between the months of Janurary and April and was determined by taking the total number of rides and diving by total fare amounts to determine average fare per ride. The average fare per driver was calculated by dividing total drivers by total fares. Total drivers and total rides were found for each city type urban, suburban, and rural.  
 
Analyzing a smaller time frame means we can more accuately make assumptions about our data. We can see that some months contribute a very small amount of the overall fare collected for the year. March through July are the most profitable for Pyber with the highest levels of ride-sharing happening during the late spring to early summer. There is also a small peak during the latter half of october. 

 
 
 
 
 
 
 
 
 #### Summary:
 
 The object oriented interface method creates simple line graphs which show changes over time (one value against time)
 
 
 pie charts are used to show comparisons. High visual appeal but limited and only represent one dataset or catagory
 
 
 
 barcharts help display changes over time with multiple values. By inverting the axis we can show ride sharing data differently to emphasize which months 
 
 
 
 
scatterplots = really good at depicting multiple datasets over time. More importantly though it shows positive and negative correlations or no correlation between two factors. The regression analysis can helps us determine which of the 3 types of correlation the data is showing between the two values. 
 
 
