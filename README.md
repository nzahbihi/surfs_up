# surfs_up
## Analysis Overview
The purpose of this analysis is to investigate the temperature in Oahu, Hawaii. Prospectively, this information could be used to determine whether an ice cream and surf shop can open there with success. To look into this query, we analyzed the data for the following information:
  * The number of data points
  * The average
  * The standard deviation
  * The minimum and maximum temperatures
  * The 25th, 50th, and 75th percentiles

## Resources
  * Data Source: hawaii.sqlite
  * Software: Jupyter Notebook 6.4.8.

## Results
After extracting the temperature data for June and December, we utilized the describe() function to get an overview of the information:

![June Temperatures](https://user-images.githubusercontent.com/106129195/184059392-169b94b7-3987-4f1d-9c37-fa0505617361.png) ![December Temperatures](https://user-images.githubusercontent.com/106129195/184059459-1af0cccb-35d2-4c79-a417-e6b13b4be9a1.png)

There are a number of observations we can make based off the tables above:
  * For June, we had 1,700 data points. For December, we had 1,517 data points. While these two still have a large number of data points, December containing fewer data points could possibly skew the data. If we had more data point for December, it could give us a better insight into the temperature information for that month.
  * The standard deviation for December is higher than June's by 0.488503. This could indicate that the data for December is more spread out than June's, thereby meaning that the data for December could be less reliable than June's.
  * The 25%, 50%, and 75% percentiles show that December is 3-4 degrees cooler than June. However, December's coldest temperature recorded was 56 degrees, whereas June's was 64 degrees. Having these particularly chilly days could possibly present as a challenge for keeping the store open year-round.
  
## Summary
Comparing the two tables posted, as expected, temperature-wise December is cooler than June in Oahu, Hawaii. As stated above, December's temperature data does contain fewer data points than June's. Having more data for December could give us a more comparable view. To gain a deeper understanding of the weather of the two months, let us investigate the precipitation data, using the same methods we used for analyzing the temperature data:

![June Precipitation](https://user-images.githubusercontent.com/106129195/184063605-d6da3237-7133-42ef-8bb2-41a05653e301.png) ![December Precipitation](https://user-images.githubusercontent.com/106129195/184063705-84d35e6f-8088-4219-b7d1-f43d6e4948b1.png)

Similarly to the temperature data, we have fewer data points for December's precipitation compared to June's. The standard deviation is also slightly higher for December. However, December does receive more precipitation on average compared to June. The highest recorded precipitation was 6.42 inches for December, while for June, the highest recorded precipitation was 4.43 inches.

According to this analysis, the weather could have an effect on the success of the prospective store. To gain a better insight, the code written could be applied to all twelve months of the years of data we have to ascertain how the weather is like year-round in Oahu, Hawaii.
