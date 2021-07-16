# Challenge 5 - PyBer Analysis
## Purpose
Using ride-sharing data for a variety of city types, plot and analyze the data to help inform business decisions based on whether a city is rural, suburban, or urban.
## Results
After merging the data tables provided, a summary by city type was generated to show a clear side-by-side comparison.

![Total Fare by City Type](/analysis/PyBer_city_type_table.png)

As expected, rural cities show the lowest totals of rides, drivers, and total fares, and urban cities show the highest.  The average fare per ride also varies increases slightly as population density decreases.  Somewhat more notable is the massive difference in average fare per driver in rural and urban cities - for this time period, drivers made an average of $40 more in rural areas.

Next, a plot was created. The merged data was pivoted and re-indexed by date, using a date sample size of one day to ensure smoother plot (the fare timestamps were accurate to the minute).  The result was a day-by-day plot of the total fares for each city type, as seen below.  

![Total Fare by City Type](/analysis/PyBer_fare_summary.png)

There are not many variations in daily fares for any of the city types.  That is to say, the plots are relatively flat, with a only a few notable exceptions:
* In late february, there's a spike in fares across all city types