# PyBer Analysis

## 1. Overview

The purpose of this project is to showcase the relationships between the cities and the number of drivers and riders using the Pyber ridesharing app. In this project I used Python, Pandas, Jupyter Notebook and Matplotlib to analyse and provide data visualizations for PyBer data that was provided to me in a CSV file. 

## 2. Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

### Fig 1. Total Fare by City Type
![PyBer_fare_by_city]()

When evaluating the total fare cost by city type from January to May of 2019, you can see that during the Rural areas tend to generate less revenue compared to Urban areas. Throughout the evaluated time period each of the different city types appear to generate fairly steady revenue, and each saw a spike in total fares during the end of Feburary. 

### Fig 2. Summary Dataframe by City Type
![PyBer_fare_summary](https://github.com/CorinneBean/PyBer_Analysis/blob/5b504ef1c9f577d57eb5275a26da6029c571120e/analysis/PyBer_fare_summary.png)

When reviewing the Summary Datafram by City Type, it becomes obvious that the number of total rides and total drivers in Urban areas is substantionally higher in comparison to suburban or rural areas. This correlates with the higher fares that is generated in this area during the evaluation period. When you look at the average fare per rider and driver it is also clear that users of the PyBer ridesharing app in the different city types it is clear that users in the rural areas spend more than users in the urban areas per fare. This could be a result of the distances between locations for each ride. In urban areas desired locations are within a closer proxminity than in rural areas. This makes it easier for drivers to provide more rides at a lower cost vs those in rural or suburban areas.

### **Conclusions**

1. Urban cities generate the most revenue for PyBer
2. Customers in Urban cities pay less per ride and therefore drivers earn less per ride
3. Rural areas seem to be underserved and customers in those areas face more expensive fares than in Urban or Suburban cities

## 3. Summary

After careful analysis of the provided data the following is recommended:

1. The current dataset is only within a 4 month period. To get a better understanding where improvements need to be made within each city type I would recommend looking at a larger timeframe to get a better understanding of trends within each area.
2. The cost per ride for rural areas is much higher when compared to urban or suburban areas. This could be because of distance between destinations which could make the ridesharing app less desirable in these areas. A deeper analysis to understand the cause for this could provide the company with a way to increase the number of rides generated in these areas. So I would recommend looking at the distances between destinations, and average time per ride to see if this is infact the cause.
3. I would increase the number of drivers in the rural and suburban areas to accomodate for the riders within that area. Currently these two areas appear to have less drivers than current demands. Long wait times for rides, or drivers not being available could also account for lower rides in these areas compared to the urban city types. 

 
