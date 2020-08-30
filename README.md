# PyBer Analysis
## Overview of the Analysis
### Purpose
The purpose of this analysis is to perform a exploratory analysis on data in a large dataset and use data visualizations to present the data. The task is to create a variety of charts to showcase the ride-sharing data by city type. Then create a multiple-line graph to show the total weekly fares for each city type. After the analysis create a report to summarize how the data differs by city type and how those differences can be used by decision-makers in PyBer. The first task was to create dataframes of total rides, total drivers, total fares, average fare per ride, and average fare per driver by the type of city. Next task is to pull the data by type, date and the sum of fare. With this data we were able to pivot to present the type of city and the date of the drives and sum of the fares within that date. From there we refined the date range from 2019-01-01 to 2019-04-29 and reset the index to datetime data type which will allow to resample the data in weekly bins and take the sum to get the total fares for each week. Lastly, taking the cleaned up dataframe display it into a multiple line chart to display the data in a data visualization. The results show that there are more riders and drivers in urban areas. Suburban areas come in second in majority of riders and drives. Lastly, rural areas have the least riders and drivers. But, the cost of the ride and for a driver is highest in rural areas, then comes suburban, the cheapest in urban areas. Per line chart, there are more urban riders per week than rural riders per week. 

## Results

### Pyber Summary 

!(Pyber Summary)[analyis/pyber_summary_df.png]

From this table we can see urban areas have the highest total in rides, total in drivers, and total in fares. On the other hand urban areas have a cheaper average fare per ride and cheaper average fare per driver. Then comes suburban areas which is in the middle; they have less total in rides, total in drivers, and total in fares. Like urban areas, their average fare per ride and average fare per driver is less, but still quite high due to being in suburban areas. Lastly, in rural areas their total rides, total drivers, and total fares are way less then urban and suburban areas. But their averag fare per ride and average fare per driver is the highest compared to urban and suburban areas.




## Summary
