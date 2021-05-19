# PyBer Analysis

## Overview of Analysis

**PyBer** is a Python based ride-sharing app company.  As a new data analyst at PyBer, our first assignment was to perform an exploratory analysis on data from large CSV files.
The analysis showcased the relationships between the type of cities, number of drivers and riders, as well as percentages of total fares, drivers and riders based on the type of cities.  The goal for the initial analysis was to improve access and affordability for under served neighborhoods.<br>
However the CEO requested for a new analysis.  The new analysis and visualization created below will help identify total weekly fares for each city type.
The report has been created based on data gathered from January to May 2019.

### Resources:

##### Data source:

[city_data.csv](https://github.com/taranahassan/PyBer_Analysis/blob/main/Resources/city_data.csv)  <br>
[ride_data.csv](https://github.com/taranahassan/PyBer_Analysis/blob/main/Resources/ride_data.csv)  <br>
##### Source code:  [PyBer_Challenge](https://github.com/taranahassan/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)  <br>
##### Software used: Python 3.7.9 64-bit (conda); jupyter-notebook : 6.1.4  <br>


## Ride-sharing Results

In the initial analysis, once we merged the data from each CSV file and created a new PyBer dataframe, we were able to categorize all information by each city type; **Rural**, **Suburban**, **Urban**.  The data we extracted were:

  **1.**  Total rides by city type<br>
  **2.**  Total drivers by city type<br>
  **3.**  Total fares by city type<br>
  **4.**  Average fares per driver<br>
  **5.**  Average fares per ride<br>

*_PyBer summary created with the results:_*

![PyBer_summary](https://github.com/taranahassan/PyBer_Analysis/blob/main/Image_examples/PyBer_summary.png?raw=true)<br>


Based on the above PyBer summary, we can identify that:

  - Urban cities are the most lucatrive.  There is demand in the area and supply to meet it.  Which correlates to the lowest fare per driver. There are almost 5 and 30 times more drivers compared to the suburban and rural cities respectively.<br>  
  - Suburban cities are the second type of city to generate revenue.  With 1000 less rides and approximatly 2000 drivers less than the Urban cities, their average fare per driver is 2.3 times higher.  This is due to the average ride having more distance.<br>
  - Rural cities have the lowest revenue.  This could be due to higher rates per ride.  The average rate is about $10 higher than the urban cities and approximately $3 higher than the suburban cities.  Though when analyzing further the rural cities average fare per driver is $38.92 higher than the urban cities and $15.99 higher than the suburbs.  These statistics suggest that there may not be enough supply in the area or not enough demand.<br>
  
  
In the second part of the analysis, we segregated and filtered the data further to isolate fares for the first quadrimester; January to end of April 2019.  We tabulated the totals to get a total sum of fares per week in the month.  Below is a sample of the code:<br>

![Weekly_fare_code_sample](https://github.com/taranahassan/PyBer_Analysis/blob/main/Image_examples/Weekly_fare_code_sample.png?raw=true)<br>

A multiple line chart was created with the results from the second analysis.<br>

![PyBer_fare_summary](https://github.com/taranahassan/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true)<br>

Looking at the chart, we can see there is no specific pattern except towards the end of February where all 3 city types have a spike upwards.  This could be due to number of rides occuring.<br>


## Summary

My recommendations would be:<br>

    a)  To check if the fare rates in the suburban and rural areas are at par with the company or the urban cities' rates.  
    b)  Calculating the average distance for each type of city and compare to understand if distance plays a role in the fare per ride for rural areas.  
    c)  This will also help isolating discrepencies if any for fare per driver.  Lastly check if there is a need to increase the number of drivers in the rural area.  
