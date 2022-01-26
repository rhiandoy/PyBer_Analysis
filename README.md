# PyBer_Analysis
## Resources Used
- Python 3.10
- Pandas
- Matplotlib
## Overview of Analysis
We were given the assignment of creating a multiple-line graph showing the 2019 ride sharing data of Urban, Suburban, and Rural cities. This analysis would help ride share companies view the correlation between ride fare and demand for rides in three types of populated cities. We obtained data from the city csv file and the rider data csv file to get a combined dataframe showing:
- Total Rides
- Total Drivers
- Total Fares
- Average Fare Per Ride
- Average Fare Per Driver

We ultimately used groupby(), sum(), count(), index(), and pivot() functions to gather and format the data into a summary dataframe which was then used to graph the weekly fare in USD between Rural, Suburban, and Urban cities. 
## Results
We calculated a higher volume of rides the greater the city type with 68.4% in Urban, 26.3% in Suburban, and 5.3% in Rural communities. 
Similarly, the percent of total drivers followed with 80.9% in Urban cities, 16.5% in Suburban, and 2.6% in Rural. 
While the percentage of total fares per city type was higher in Urban cities (62.7%) than Rural (6.8%), the average fare PER ride is higher in smaller city types than larger cities. 

![Pyber_summary](https://github.com/rhiandoy/PyBer_Analysis/blob/6ed4e923c2f23af13eb9b78dc4a25dea5ee72e8b/pyber_summary.png)

Above shows the dataframe created with the five variables of data within the three city types between the months of January 2019 to the end of April 2019.
The Urban cities have a greater number of total rides, drivers and fares (USD) than both the Rural and Suburban cities. 
When looking at the average fare per ride/driver, Urban cities have a much lower rate than the others.
This helps us see the relationship between fare price and distance. Rural communities are more spread apart so the average ride tends to be more expensive than those in Suburban/Urban communities where the distance isnt as great.

![Pyber_fare_summary](https://github.com/rhiandoy/PyBer_Analysis/blob/6ed4e923c2f23af13eb9b78dc4a25dea5ee72e8b/Resources/Pyber_fare_summary.png)

This multiple-line graph depicts the weekly analysis of fare data throughout the months of January to May
in all three city types. Urban cities remain higher in revenue than Suburban and Rural cities throughout each week and month. All city types saw a peak in revenue at the end of February followed by a dip as March begins. 

## Summary
Although the Rural cities do not have as many drivers or riders, they have higher ride fares than larger cities. The CEO of PyBer might want to focus on how to hire more drivers to gain more revenue in these small communities, or lower the fare price so that more riders would consider using this service instead of driving themselves or taking other modes of transportation. 

Since Urban cities outperform Rural and Suburban cities in every category, it would be important to focus building up the company in these types of cities. Establishing a ride-sharing service in multiple populous cities instead of splitting efforts between Urban and Rural cities could help build revenue.

Suburban cities have potential to bring in higher revenue if a greater amount of drivers were employed to meet the demand of rides being requested. 
