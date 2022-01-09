# Surfs_Up

## Overview of the statistical analysis

 - W. Avy liked my analysis, but he wanted more information about temperature trends before opening the surf shop. Specifically, he wanted temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. Using Python, Pandas functions and methods, and SQLAlchemy, I’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the months of June and December. I’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

## Results
### June Temperate Statistics:
![JUNE](https://user-images.githubusercontent.com/91230277/148702540-9417e5de-c257-46e2-9c70-b7ff97fe5d04.png)
### December Temperature Statistics
![DECEMBER](https://user-images.githubusercontent.com/91230277/148702544-f080df2b-ba34-4811-a328-947d6fc3ff22.png)

These two tables tell us about the differing weather patterns for the two monthly periods. Some takeaways:

Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little fluctuation between the two periods from an average standpoint.
the maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
the minimum temperature of 56 (December) and 64 (June) show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.
## Summary
Oevrall the weather in December and June are historically very similar, although December has a wider range of results, with its high being close to June's but its low well below June's.

Additional queries that could be run include: Precipation difference between June and December to determine is one has more rainy weather, as well as a comaparison by weather station, as we may see higher/lower temperatures and precipitation levels at different locations. We would be primarily interested in the weather station closest to our prospective location, which would narrow the results and provide the best data for us to consider.
