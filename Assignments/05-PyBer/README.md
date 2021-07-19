# PyBer Analysis with Matplotlib

## Overview of Project
V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type.

## Results

### Total Rides by city type
Based on the analysis and visualization tools, we can conclude that there are significantly more rides in Urban(1625) cities, followed by Suburban(625) and Rural(125) respectively.
![image_name](./Analysis/rides_type.png)

### Total Drivers by city type
The percent of total drivers per city type follows the same trend as above, with Urban(2405) having more drivers than Suburban(490) and Rural(78).
![image_name](./Analysis/drivers_type.png)

### Total Fares per ride and driver
The average fare per ride follows the trend inversely, with Rural($34.62) having the highest average fare followed by Suburban($30.97) and Urban($24.53).  This also causes the average fare per driver to follow that trend.  We can see in the figure below that Rural drivers average $55.49 while Suburban drivers average $39.50 and Urban drivers average $16.57
![image_name](./Resources/pyber_df.png)

### Total Fare by city type
The percentage of total fares is more densely centered around Urban cities with Suburban following behind at 30.5% of fares and Rural cities are the lowest.
![image_name](./Analysis/fare_type.png)

## Summary
Using the ride-sharing data provided, I ran an analysis and visualized some of the summaries to report the new findings.  Based on the results, we can conclude that city type (i.e. population density) plays the critical role in determining the metrics for PyBer.  While the average fare is much higher in smaller cities, the number of rides due to availability causes the Urban cities to still be much more successful.  The multiple-line chart I was tasked to create further portrays this conclusion, even across all peaks and dips.
![image_name](./Analysis/Pyber_fare_summary.png)
