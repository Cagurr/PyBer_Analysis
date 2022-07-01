# PyBer_Analysis

## Overview of PyBer Analysis

After starting as a data analyst with PyBer, a python-based ride-sharing app company, I was tasked to perform an exploratory data analysis on rider and driver data across the nation. The data was to be read from csv files into panda dataframes to create numermous visualizations to depict the relationship between the type of city (e.g., Rural, Urban, and Suburban) and the number of riders and driver.  The visualizations should also highlight the percentage of total fares by riders, drivers, and type of city.  The analysis should help PyBer executives improve the access and determine affordability in underserved cities.
 
### Resources

* Data Source:  city_data.csv, ride_data.csv
* Software:  Python 3.6.1, Jupyter Notebook (anaconda3), Visual Studio Code, 1.38.1
* Packages:  Pandas, NumPy, Matplotlib

## PyBer Analysis Results

### Summary of differences in ride-sharing data across cities

PyBer Summary Data Frame:
![Summary_df.png](Resources/Summary_df.png)

Across the three city types, urban cities make up a majority of the riders and drivers.  As you would expect the number of riders and drivers decreases as the respective populations decrease.  That being said, suburban had the second most riders and drivers.  Rural areas had the lowest participation of riders and drivers.  Interestingly, the averages fares were inversely related to rider and driver participation.  Meaning that Rural cities generated a higher average fare per rider and driver.

   * Differences in total rides
      
      Referencing the PyBer Summary Data Frame above, the number of rides provided in urban areas is almost two-thirds (or 1,625 rides) of the total rides provided.  PyBer has a the largest presence in urban areas by a long shot.  Rural areas by contract represented only 125 rides.

   * Differences in total drivers
      
      Similar to total rides, drivers were heavily concentrated in urban cities.  Roughly four out of five drivers were located in urban areas.  Suburban cities had the second largest concentration of drivers where nearly 17 percent of the drivers are located in these cities.  Suprisingly, only 78 drivers were located in rural areas.  

   * Differences in total fares

      While reviewing the PyBer Summary Data Frame above, we quickly see that urban cities make up more than half (or 64 percent) of the total revenue generated.  Suburban cities make up nearly 30 percent of the total revenue generated, and rural cities make up the lowest portion of revenue generated (or 6 percent).       

   * Differences in average fares per ride

      Interestingly, the revenue relationship is inversed when we review the average fares per ride.  This means that urban cities have the lowest average fares per ride.  Suburban cities have the second highest average fares per ride.  Last, rural cities have the highest average fares per ride.  This is largely due to the number of riders per city type.  Rural cities have by far the lowest number of riders, so the fares are spread across a smaller number of units.

   * Differences in average fares per driver

      When we review the average fares per driver, we see the same inverted relationship that we observed above in the average fares per ride.  Like above, the number of drivers (the denominator of the equation) will greatly impact the average fares by driver.  Because of this relationship, urban cities have the lowest average fares per driver.  On the other end of the spectrum, rural cities have the highest average fares per driver.

   * Differences in total fares by city type

      Total Fare by City Type:
      ![TotalFaresbyCity.png](Resources/TotalFaresbyCity.png)

      When viewing the line graph above, urban cities stand out as the largest revenue generator.  After reviewing the number of rides provided in the preceding section, we could have guessed that suburban cities have the second highest total fares, and rural cities have the lowest total fares.  This is confirmed by the Total Fares by City Type line chart above.
      
## Summary of Recommendations

To help the PyBer executives improve the access and determine affordability in underserved cities, I recommend:

   1. Market the average fare per ride in rural and suburban cities and/or create incentives to increase the number of suburban and rural drivers.  This will increase access in underserved areas.

   2. Focus expanding PyBer in urban cities to target riders most likely to use ride-sharing services.  This will greatly increase revenue through significantly larger user bases in urban areas.

   3. Capturing new data points to understand the best target ratio of drivers to riders in each city type.  This will allow PyBer executives to create a targt level of drivers based on various rider levels (i.e., number of rides). 

## PyBer Analysis Code Snippets

Create Pivot Table:
![PivotCode.png](Resources/PivotCode.png)

Resample Code:
![ResampleCode.png](Resources/ResampleCode.png)

Create Line Graph:
![LineGraphCode.png](Resources/LineGraphCode.png)