# Surfs Up with SQLite
Surf's Up with Advanced Data Storage and Retrieval: [Program File](https://github.com/sqrtofpi/surfs_up/blob/1450308796edbaebecf40cdf58855fa3c7dfa7ef/SurfsUp_Challenge.ipynb)

## Project Overview

A key investor, W. Avy, is interested in building a surf and ice cream shop named "Waves and Ice Cream" on the island of Oahu, Hawaii initially but could potentially expand to other islands if the shop does well. W. Avy has expressed concern about the amount of precipitation on Oahu as there needs to be enough rain to keep everything green, but not too much that would impact ideal surfing and ice cream weather. We will be helping W. Avy with the analysis utilizing data from multiple weather stations along with SQLAlchemy to query the data stored in an SQLite database to provide him the results of our analysis along with any recommendations we think are useful for him to understand while making the decision to invest or not. This code will ultimately be used incorporated to a "Flask App", allowing W. Avy to access the data from the web browser of his choice to showcase the results to the investors board of directors.

## Results

#### June Temperature Analysis

![Oahu June Temps](https://github.com/sqrtofpi/surfs_up/blob/1450308796edbaebecf40cdf58855fa3c7dfa7ef/Resources/Oahu%20June%20Temps.png)

The data from Oahu's temperature in June from the years' 2010 to 2017 included 1,700 observations with an average temperature of 71 degrees F, primarily varying roughly 3.7 degrees higher or lower during this timeframe. This indicates there is a very temperate climate with realtively low temperature fluctuations.

#### December Temperature Analysis

![Oahu December Temps](https://github.com/sqrtofpi/surfs_up/blob/1450308796edbaebecf40cdf58855fa3c7dfa7ef/Resources/Oahu%20December%20Temps.png)

The data from Oahu's temperature in December from the years' 2010 to 2017 included1,517 observations with an average temperature of 71 degrees F, also varying roughly 3.7 degrees higher or lower during this timeframe. This again indicates there is a very temperate climate that is stable with relatively low temperature fluctuations.

#### Results Summary

- There were 183 less observations in December than in June
- The temperature is roughly 3 to 4 degrees F warmer in Oahu during June than in December
- The standard deviation of June and December's data is roughly equivalent indicating a very stable climate
- The maximum observed temperature is in the mid 80's in both summer and winter month's making it an ideal climate

## Project Summary

A comparison of the temperature data in Oahu Hawaii over the period of 7 years suggests this would be a very ideal location to open up a surf and ice cream shop. The temperature remains very stable through both the summer and winter solstice which would provide the best chance of success for a business that is closely related to this variable.

Although temperature is a very important consideration; there are a couple more queries that should be performed to complete the analysis:

1. We should also consider the precipitation as that was a key consideration of W. Avy at the outset of the project. In doing so the investors may learn there is a difference worth considering before making a decision to proceed;
2. Likewise, we should also consider the data iteself, grouping the data by location may also show there may be a slightly better location to open the shop that limits the negative weather conditions and provides the best chance of success for this business.

Ultimately our data supports proceding with this shop and pending any surprises or anomolies from the additional queries, our recommendation is to proceed as this location should be able to support a surfing and ice cream business all year long.

