# PyBer_Analysis

## Overview of Analysis

**PyBer** is a Python based ride-sharing app company.  As a new data analyst at PyBer, our first assignment was to perform an exploratory analysis on data from large CSV files.
The analysis showcased the relationships between the type of cities, number of drivers and riders, as well as percentages of total fares, drivers and riders based on the type of cities.  The goal for the initial analysis was to improve access and affordability for under served neighborhoods.
However the CEO requested for a new analysis.  The new analysis and visualization created below will help identify total weekly fares for each city type.
The report has been created based on data gathered from January to May 2019.

### Resources:

##### Data source:

[city_data.csv](https://github.com/taranahassan/PyBer_Analysis/blob/main/Resources/city_data.csv)

[ride_data.csv](https://github.com/taranahassan/PyBer_Analysis/blob/main/Resources/ride_data.csv)

##### Source code:  [PyBer_Challenge](https://github.com/taranahassan/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)


## Ride-sharing Results

In the initial analysis, once we merged the data from each CSV file and created a new PyBer dataframe, we were able to categorize all information by each city type; **Rural**, **Suburban**, **Urban**.  The data we extracted were:

  1.  Total rides by city type
  2.  Total drivers by city type
  3.  Total fares by city type
  4.  Average fares per driver
  5.  Average fares per ride

*PyBer summary created with the results:*

![PyBer_summary](https://github.com/taranahassan/PyBer_Analysis/blob/main/Image_examples/PyBer_summary.png?raw=true)


In the second part of the analysis, we segregated and filtered the data further to isolate fares for the first quadrimester; January to end of April 2019.  To get a total sum of fares per week in the month, we tabulated the totals
