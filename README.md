# PyBer_Analysis

## Project Overview
By request of V. Isualize, my colleague Omar and I are presenting a summary of PyBer’s ride-sharing data by city type, Urban, Suburban, and Rural. We used Python, Pandas, and Matplotlib, to create a multiple-line graph that shows the total weekly fares for each city type. Below is a written report that summarizes how the data differs by city type and how those differences can be used by high-level decision-makers at PyBer.

## Resources
We used the following resources to perform this analysis:
- Data Sources: [PyBer_ride_data.csv](https://github.com/fabeza/PyBer_Analysis/blob/697a77e5075dc31fcbae8b5daae62f6fc6977cc4/Resources/PyBer_ride_data.csv), [ride_data.csv](https://github.com/fabeza/PyBer_Analysis/blob/697a77e5075dc31fcbae8b5daae62f6fc6977cc4/Resources/ride_data.csv), [city_data.csv](https://github.com/fabeza/PyBer_Analysis/blob/697a77e5075dc31fcbae8b5daae62f6fc6977cc4/Resources/city_data.csv)
- Software: Python 3.9.12, Jupiter Notebook 6.4.8, Pandas 1.4.2, Matplotlib 3.5.1.

## Summary
The chart below provides important insights into PyBer’s ride-sharing data by city type:

![pyber_summary_df.png](https://github.com/fabeza/PyBer_Analysis/blob/697a77e5075dc31fcbae8b5daae62f6fc6977cc4/analysis/pyber_summary_df.png)

- Total Rides: Urban cities had the highest number of rides, followed by suburban, then rural cities.
- Total Drivers: Urban cities had the highest number of drivers, followed by suburban, then rural cities.
- Total Fares: Urban cities had the highest fare revenue, followed by suburban, then rural cities.
- Average Fare per Ride: Rural cities had the highest average fare per ride, suburban cities had the second highest average fare per ride, and urban cities had the lowest.
- Average Fare per Driver: Rural cities had the highest average fare per driver, suburban cities had the second highest average fare per driver, and urban cities had the lowest.
- In urban cities, the number of drivers is higher than the total rides, which could had an impact on the average fare per ride and driver. It could be possible that the higher number of drivers lowers the average fare, but further analysis is needed to take ride mileage into account for a more accurate analysis.
- In rural cities, the number of drivers is lower than the total rides, which could increase the total fare per ride and driver. As mentioned previously, further analysis with ride mileage included could clarify if the higher fare in rural cities is affected by both lower demand and ride distance.

We expanded the analysis to examine the fares for each week of the first four months of 2019. The multiple-line chart below summarizes provides further details:

![PyBer_fare_summary.png](https://github.com/fabeza/PyBer_Analysis/blob/697a77e5075dc31fcbae8b5daae62f6fc6977cc4/analysis/PyBer_fare_summary.png)

- Urban cities:
  - Urban cities had the highest fare revenue during the third week of February and the second week of March.
  - Urban cities had the lowest fare revenue during the first week of January.
  - Monthly Revenue: January $7,780.64, February $8,950.94, March $11,044.69, April $9,289.51 
  - Urban cities had the highest total fare revenue for this cycle.
- Suburban cities:
  - Suburban cities had the highest fare revenue during the last two weeks of February.
  - Suburban cities had the lowest fare revenue in the first week of January.
  - Monthly Revenue: January $4,248.21, February $4,475.37, March $4,857.19, April $4,302.57
  - Suburban cities had the second highest total fare revenue for this cycle.
- Rural cities:
  - Rural cities had the highest fare revenue during the first week of April.
  - Rural cities had the lowest revenue during the first two weeks of January.
  - Monthly Revenue: January $741.26, February $963.76, March $1,031.65, April $1,177.02
  - Rural cities had the lowest fare revenue for this cycle.

## PyBer Analysis Summary
- PyBer leadership should consider expanding the scope of this analysis to include mileage per ride. This would provide clarity on what makes the fares vary so much between urban and rural cities. 
- PyBer should also consider expanding the scope of this analysis to include marketing data. Where there any specific campaigns launched during the best performing weeks in each city type, and can they be replicated? Overall, January is the slowest month in all three city types. PyBer should consider developing a different marketing and/or promotional pricing strategies to improve ridership.
- PyBer made most of its revenue in urban cities. However, during the analyzed time frame, there were more drivers than rides. PyBer should consider investing in marketing campaigns to increase the number of riders. The line chart provides hints on when it would be best to invest in marketing campaigns, during the slowest month (January) and during the most successful months (March and April).
- Rural cities is where PyBer earns the least. PyBer should also consider marketing campaigns to increase the number of riders and drivers. It would be beneficial to increase both since ride mileage might influence a higher fare per ride.
