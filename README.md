# Challenge 5 - PyBer Analysis
## Purpose
Using ride-sharing data for a variety of city types, plot and analyze the data to help inform business decisions based on whether a city is rural, suburban, or urban.
## Results
After merging the data tables provided, a summary by city type was generated to show a clear side-by-side comparison.

![Total Fare by City Type](/analysis/PyBer_city_type_table.png)

As expected, rural cities show the lowest totals of rides, drivers, and total fares, and urban cities show the highest.  The average fare per ride also varies increases slightly as population density decreases.  Somewhat more notable is the massive difference in average fare per driver in rural and urban cities - for this time period, drivers made an average of $40 more in rural areas.

Next, a line plot was created using a series for each city type. The merged data was pivoted and re-indexed by date, using a date sample size of one day to ensure smoother plot (the fare timestamps were accurate to the minute).  The result was a day-by-day plot of the total fares for each city type, as seen below.  

![Total Fare by City Type](/analysis/PyBer_fare_summary.png)

Here are the observations:
* There are not many variations in daily fares for any of the city types.  That is to say, the plots are relatively flat, with a few weekly exceptions:
    * The first week of the year is one of the worst weeks for fares, especially for Urban and Suburban cities.
    * In late february, there's a spike in fares across all city types, for the week of February 18th, 2019 - this week happens to coincide with President's weekend in the US.
* Each city type represents a discrete tier of fare totals.  This indicates that segmenting the data in this way is essential when trying to make comparisons.

## Summary
Here are three business recommendations for the CEO:
1. It's clear that President's Day weekend, and possibly other 3-day holiday weekends are strong days for business, so there is likely high demand. Getting more drivers on the road via driver-focused promotions leading up to the weekend could easily lead to more revenue. 
2. The early winter months are weak days for business -- especially in urban cities. Promotions and advertising during those dates may help to pick up revenue.
3. Rural cities do not show much demand for rides at all. Advertising may be necessary in these cities, or perhaps some additional field research into the reason that ride counts are so low.
