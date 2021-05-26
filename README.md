# PyBer Analysis
## Overview 

We were consulted to run some analysis for a ride sharing company to determine some important information from their past history and see if those results could be used to formulate a plan forward for the next year. There were two data sets that were given to us via csv file. The first was ride data on a per ride basis (time of ride, fare, etc.). The second was a general data demographic city sheet (mainly focusing on type of city). The scope of our work was to determine total fares on a weekly basis per city type. 

## Results 

During our analysis, we use the panda function within python to create data frame, pivot tables, and graphs. However, the first step was to merge the both data sheets together on city to create a dataframe. Utlizing the groupby function, we could manipulate data to determine which city type had the logged the most fares. Referencing the data frame below, it shows that the urban cities logged the most rides and most of the revenue. However, it is interesting to note, that even though they had the most rides, the average fare per ride was the lowest. This would make sense as most urban trips are shorter. The rural cites logged the least amount of trips; however, had a larger fare per ride... which would make sense as there is probably more distance to travel in a rural area. Lastly, looking at the data, there is a spike of trips at the end of Feb. for all three city types. At a macro level it is hard to determine why this could be but could be looked into further. Maybe there is a holiday near the end of Feb. and everyone is wanting to get out of the house. 

### Summary of Rides by City 
![Summary of Rides by City](https://github.com/mccoycory/PyBer_Analysis/blob/main/Resources/Summary%20Ride%20Data.png)

### Weekly Fare Pivot table by Date Range 
![Weekly Fare Pivot Table by Date](https://github.com/mccoycory/PyBer_Analysis/blob/main/Resources/Pivot%20Table%20Weekly%20Fare.png)

### Weely Fare Line Chart by City Type
![Weekly Fare Line Chare by City](https://github.com/mccoycory/PyBer_Analysis/blob/main/Resources/Weekly%20Fairs%20by%20City%20Type%20.png)

## Summary 
Based on the project and the data analysis during the project I would recommened the following for this ride sharing company.

-- Continue to leverage urban drivers for rides. Right now, this is your cash cow. Offer promotions, free rides for people who share the app, free rides for first time users etc. 
-- Encourage drivers with larger cars to hang around the suburban areas. Most suburban homes have families and will need a larger car to haul their family around. 
-- The rural cities have the largest average fare per ride. This is a great market to continue to develop your product. I would offer some discount rides over a certain mile or time range. Additionally, as people move from the city to rural places during COVID, it is a great time to market that fun trip to a destination of your choice. 
