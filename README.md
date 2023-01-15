# PyBer Analysis

---
## Overview

---
Ride sharing has become the norm in urban areas. The convenience of being delivered to your destination without the hassle of finding parking or subway schedules is attractive to most urban dwellers. Ride sharing is also seeing considerable growth in suburban and rural areas. The ustomer needs for these regions are different, so too is the profitability in the different regions. The data explored today looks at the three city types (urban, suburban, and rural), and the differences will be highlighted. 

---
## Results

---
We will start with a very broad picture of the data. The bubble plot below shows that urban cities have more riders, with the fares being highest in rural areas. The inverse relationship between ride count and fares is not unexpected, as urban trips tend to be shorter and less expensive while rural trips are longer and cost more.  

![PyBer Data high level overview.](https://github.com/jaime-mclean/PyBer_Analysis/blob/main/analysis/Fig1.png) 

The breakdown of the data is as follows:

* Total Rides
  * Urban: 1625
  * Suburban: 625
  * Rural: 125
* Total Fares
  * Urban: $ 39, 854.38
  * Suburban: $ 19, 356.33
  * Rural: $ 4,327.93
* Total Drivers
  * Urban: 2405
  * Suburban: 490
  * Rural: 78
* Average Fare per Ride
  * Urban: $ 24.53
  * Suburban: $ 30.97
  * Rural: $ 34.62
* Average Fare per Driver
  * Urban: $ 16.57
  * Suburban: $ 39.50
  * Rural: $ 55.49
 
 It is worth noting that there are more drivers than rides in urban areas, indicating possible overstaffing or inactive drivers in the urban markets.
 
  The following graph shows the fares collected by week for all three city types. 
  
![PyBer Data by week.](https://github.com/jaime-mclean/PyBer_Analysis/blob/main/analysis/Fig8.png) 


---
## Summary

---
In terms of total fares, the urban cities are far more productive that either suburban or rural areas, likely driven by the far greater numbers of rides in urban cities. There is a greater than 10-fold difference in the number of rides in urban areas compared to rural areas. This can be explained by the difference in population and vehicle ownership, which is greater in suburban and rural areas compared to urban cities. The total drivers trend with the number of rides, and can be explained by the same regional characteristics as the ride counts. The diffrences in geography likely account for the differences in fares in the three regions. As mentioned in the overview, rural trips tend to be longer due to the distance between destinations of interest. The average fare per ride reflects this, with the average rural fare being almost $10.00 more than the average urban fare. The average fare per driver is more than 3-fold higher in rural areas than in urban areas, and more than 2-fold higher in suburban areas than urban areas. The distance only accouints for part of this, as the umber of drivers relativce to the number of rides is inverted in urban cities. The higher denominator is lowering the cost per driver. Before a remedy for this can be determined, I would suggest looking at customer satisfaction metrics to determine if urban cities are overstaffed, or the suburbs and rural areas are understaffed. Staffing levels can then be adjusted based on need to optimize fares for both customers and drivers. IT may also be of some benefit to determine how many active drivers, rather than total drivers, there are in each city. This should improve the average fare per driver in urban areas, which can benefit recruiting in underserved areas. Finally, the total fares by city type show that urban areas generate far more fare revenue on a weekly basis, which is expected based on the volume produced in urban cities. There is a slight increase from the begining of January to March, and then a slight decline into April. 
