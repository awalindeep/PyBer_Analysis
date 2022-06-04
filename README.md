# PyBer Analysis

PyBer ride-Share company analysis using Matplotlib Library and Pandas Library.

## Project Overview

### Purpose

The purpose of this analysis is to perform data analysis for Ride-Share company **PyBer** and to tell a compelling story with data visualization. This analysis showcases the relationship between the ***type of the city - Urban, suburban and rural*** and their correlation between rides, drivers and fares. The csv files hold data from January to early May of 2019 and focuses on the following:

 - The total number of rides for each city type. 
 - The total number of drivers for each city type. 
 - The sum of the fares for each city type.    
 - The average fare per ride for each city type. 
 - The average fare per driver for each city type. 
 - The total fares for each week by city type.

### Background

The data is gathered in two different [CSV files (the city data and the ride data)](https://github.com/awalindeep/PyBer_Analysis/tree/AwalinGHMAIN/Resources). In this analysis we are using  **Jupyter notebook**  and  **Pandas Library**  to inspect data, merge datasets, perform calculations and create data series and data frames.

In addition to this we used Python’s plotting library  **Matplotlib**  in order to tell visual story and to present complex findings in more informative and engaging way. 


## Results

From the table  _**The Summary Data Frame per City Type**_  we can see the results for each city type – urban, suburban and rural in correlation to the amount of rides, drivers and fares from January to early May of 2019.

![Summary Data Frame](https://github.com/awalindeep/PyBer_Analysis/blob/AwalinGHMAIN/Analysis/Summary_Data_Frame.png)

**The total number of rides for each city type.**

-   The total amount of rides is 2.6-times higher in urban cities than in suburban cities.
-   The total amount of rides is 13-times higher in urban cities than in rural cities.

**The total number of drivers for each city type.**

-   The total amount of drivers is almost 5-times higher in urban cities than in suburban cities.
-   The total amount of drivers is almost 31-times higher in urban cities than in rural cities.

**The sum of the fares for each city type.**

-   The total amount of fares is 2-times higher in urban cities than in suburban cities.
-   The total amount of fares is 9-times higher in urban cities than in rural cities.

**The average fare per ride for each city type.**

-   The average fare per ride is 1.3-times lower in urban cities than in suburban.
-   The average fare per ride is 1.4-times lower in urban cities than in rural cities.

**The average fare per driver for each city type.**

-   The average fare per driver is about 2.4-times lower in urban cities than in suburban cities.
-   The average fare per driver is about 3.3-times lower in urban cities than in rural cities.

**The total fares for each week by city type.**

From the multi-line graph  _Total Fare by City Type_  we can see the results for each city type – urban, suburban and rural in correlation to the total fare amount per week from January to the end of April 2019.

![PyBer fare summary](https://github.com/awalindeep/PyBer_Analysis/blob/AwalinGHMAIN/Analysis/PyBer_fare_summary.png)

-   Urban cities have the highest total fares overall. The amount is ranging from the lowest at about $1,600 per week to the highest at about $2,500 per week.
-   Rural cities have the lowest total fares overall. The amount is ranging from the lowest at about $250 per week to the highest at about $500 per week.
-   Suburban cities fall in between. The total fares amount is ranging from the lowest at about $650 per week to the highest at about $1,450 per week.
-   All cities have pretty steady flow of total fares from week to week with a matching spike in the third week in February.

## Summary

The factor to note from the analyzed results above is disproportional distribution rides and drivers amongst the city type. Urban cities have much higher number of rides and drivers; however, the average fare per ride and per driver is lower than in suburban and rural cities.

_**Based on findings,  three recommendations are : -**_


1.  **Rural cities have the lowest amount of the rides and drivers**, yet the ratio ride to driver is the highest (1.6 compare to 0.67 in urban cities). This indicates fewer drivers in rural cities per ride than in the urban cities. Increasing number of drivers could have positive affect on total amount of fares, yet some additional questions need to be answered before making final suggestions.

    -   Is PyBer profitable in rural cities compare to the suburban and urban cities? Although the sum of total fares is low, it could still be profitable.
    -   What is the ride count per capita compare to other types of the cities? Lower population could cause low ride and driver count and lower need for PyBer service.
    -   What is the average length of the ride? High amount of the average fare can be affected by lengthy rides that results in higher average fare per ride.
    -   How frequently do residents of rural cities use public transportation? Some rural cities might require more PyBer services than others, so focus on increasing service could go to those specific cities.

2.  There is  **a matching peak in third week in February for each city type**. Based on this information I would suggest to research this peak in more detail that can help determine what caused the jump. Therefore, the analysis can be used as a business strategy in the future. For example, if the total amount of fares were increased due to certain event, PyBer could use future events for promotion of their services.
    
3.  **Urban cities have the highest ride and driver count**  and  **the lowest average fare per driver, that is $16.57**. I would suggest deeper research on this area by finding out what is the employee satisfaction rate and the company profit on this number (total fare amount is $39,854.38). If employee rate is high and PyBer is profitable, that would indicate a good business strategy for urban cities. In addition, I would suggest to take a closer look into the peaks and dips that appear from late February to early April in order to find out what is causing them. This could reveal important information for future business planning.
    
## Resources

-   Data Source:
    -  [city_data.csv](https://github.com/awalindeep/PyBer_Analysis/blob/AwalinGHMAIN/Resources/city_data.csv)
    -  [ride_data.csv](https://github.com/awalindeep/PyBer_Analysis/blob/AwalinGHMAIN/Resources/ride_data.csv)
-   Software:
    -   Jupyter Notebook
-   Environment:
    -   Python 
-   Dependencies:
    -   Matplotlib Library
    -   Pandas Library
