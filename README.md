# PyBer_Analysis

## Project Overview
Using input CSV files containing information regarding PyBer rides for different city types we implement Panda Dataframes to obtain a statistical analysis of how ride information changes depending on city types. We will compare Rural, Suburban, and Urban cities.

## Resources
- Data source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.6, Jupyter notebook 6.4.8

## Results

After creating a pandas data frame using the source files we can obtain the following Scattered Summary Plot that shows how the Average Fares behave in comparison to the total number of city rides for Urban, Suburban, and Rural cities:

![Fig1](https://user-images.githubusercontent.com/20058842/177629134-9e0811c0-90f0-468c-b895-ba3feb3b357c.png)

From the above plot we can clearly see that there are a lot of more Urban Cities, than Suburban and Rural ones. For Urban Cities we have more rides at lower average prices compared to Rural and Suburban cities. There are also a lot more driver. On the other extreme we see that the average prices for Rural Cities tend to be higher than the rest, also showing there are fewer driver and less rides took place.

We can view the following whisker plot statistics for Ride Count Data by City Type, Ride Fare Data by City Type, and Driver Count Data:

![Fig2](https://user-images.githubusercontent.com/20058842/177621698-7b16478f-fc02-4eeb-8565-dc42cec8afaf.png)

![Fig3](https://user-images.githubusercontent.com/20058842/177624994-f7f8d17e-2212-4035-b81e-da1f2ebcee7f.png)

![Fig4](https://user-images.githubusercontent.com/20058842/177625033-2e3993db-3021-49e7-a9ba-c48a8557c178.png)


From the figures above we can see how data is distributed for each city type. It is to note the only one outlier can be found for the Ride Count Data for Urban cities. We can now view the following Percentage Statistics for Total Fares, Total Rides, and Total Drivers by city type:

![Fig5](https://user-images.githubusercontent.com/20058842/177624478-d5c95862-2052-4857-b4fb-747e065f9704.png)

![Fig6](https://user-images.githubusercontent.com/20058842/177624516-3774b03f-3a3e-4d0c-8c1d-80eb34ba4fd6.png)

![Fig7](https://user-images.githubusercontent.com/20058842/177624543-eb772140-78ef-4e8a-b20e-a6f6280976c4.png)


After obtaining a new data frame that displays Total Rides, Total Drivers, Total Fares, Average Fare per Ride and Average Fare per Driver for each city type we can obtain and conclude the following.

![fares](https://user-images.githubusercontent.com/20058842/177619751-b85a5d8e-c72c-4389-a42b-21a360a1d497.png)

- Rural rides are on average more expensive than Suburban and Urban rides with an average cost of $34.62. The average fare for each driver will also be the highest among each city type with a value of $55.49 per driver. The number of total rides and drivers will always be lower in rural cities. This benefits the few drivers in rural areas since the average fare will be very high.

- Suburban rides have an average cost of $30.97. The average fare for each driver has a value of $39.50 per driver. The amount of total rides and drivers will be in between rural and urban areas.

- Urban rides are on average less expensive than Suburban and Rural rides with an average cost of $24.53. The average fare for each driver will also lower with a value of $16.57 per driver. The higher the amount of demand for a ride, the higher the number of drivers that can be found in that area. This is not good for each driver since the average fare will lower.

After reviewing Total Fare by City Types, we can confirm that the more populated the the area is, the more the overall profit will be higher. We can also see that by grabbing the first 4 months of 2019, the fare prices are stable making prices independent from the time of the year.

## Summary

It is clear that most of the rides come from Urban cities as there is a larger population and more needs for a ride. We can say that Urban cities have more drivers which lowers the average fares for these cities. This is not beneficial for drivers themselves. We can also conclude that Rural areas have higher prices, but having a low demand does not impact as much as Suburban and Urban cities do for overall profits. Drivers in Rural areas will get paid more for each one of the rides they do.
