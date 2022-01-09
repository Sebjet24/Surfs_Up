# Surfs_Up

## Overview of the statistical analysis

 - W. Avy liked my analysis, but he wanted more information about temperature trends before opening the surf shop. Specifically, he wanted temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. Using Python, Pandas functions and methods, and SQLAlchemy, I’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the months of June and December. I’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

## Results
### June Temperate Statistics:
![JUNE](https://user-images.githubusercontent.com/91230277/148702540-9417e5de-c257-46e2-9c70-b7ff97fe5d04.png)
### December Temperature Statistics
![DECEMBER](https://user-images.githubusercontent.com/91230277/148702544-f080df2b-ba34-4811-a328-947d6fc3ff22.png)

These two tables show how the weather trends for the two monthly periods differ. Some key points to overview:
 - Between June and December, the average temperature is 75 degrees and 71 degrees, respectively, indicating a moderate temperature with minimal variation between the two times.
 - The highest temperatures of 85 degrees Fahrenheit in June and 83 degrees Fahrenheit in December are also very comparable.
 - The largest difference is between the minimum temperatures of 56 (December) and 64 (June), which represents a considerably lower temperature level in December that may not be favorable to ice cream or surfing. We would expect a bit greater volatility in the December statistics, with standard deviations of 3.25 (June) and 3.74 (December).

## Summary
Historically, the weather in December and June has been relatively similar, albeit December has a broader range of outcomes, with a high that is similar to June's but a low that is much below June's.

Additional searches that might be done include: the difference in precipitation between June and December to discover which month has more wet weather, as well as a comparison by weather station, since various weather stations may have higher/lower temperatures and precipitation levels. I'd be most interested in the weather station nearest to our potential site, since this would restrict the results and give us with the most relevant data.
