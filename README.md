# PyBer_Analysis

## Project Overview
V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Matplotlib 3.3.4, Anaconda 4.10.3, Python 3.7.10, Git version 2.33.0.windows.2, Jupyter notebook.

##  Results

### DataFrame
A Dataframe by City Type was created combining two data sets. The merging was done using the groupby() functions, accordingly the fare per ride and fare per driver averages could be calculated. Results as follows:
![Dataframe](https://github.com/Jcreye75/PyBer_Analysis/blob/4863adfbf00457f142e97f5678ccfd2bbba86c23/analysis/Dataframe.png
-	As it can be seen, most quantity of rides occurs on Urban Types, and the less one is the Rural ones. In line with this, que quantity of drivers is aligned to the volume required per type of city. The major number of drivers are concentrated on the Urban Type, while Rural types concentrate the smaller number of drivers.
-	In the other hand, specialization (less amount of drivers and rides) had the best average fare per ride or rider, and the generality had the minor average fare per ride and driver, as it can be seen on Urban line.

###  About Graph (Linear – Total Fares for each city type)
Per the DataFrame generated, per Type of City from Jan 1st up to April 28th from 2018, the total fare was graphed as follows: (Using Matplotlib).   
![PyBer_fare_summary](https://github.com/Jcreye75/PyBer_Analysis/blob/c6ad52508dab4265e84dd1bd39d95c748bb3c42a/analysis/PyBer_fare_summary.png)
-	According to the results on the table of the Datafame commented, lower line belongs to Rural (blue), orange line to the suburban type and higher line belongs to the Rural type.
-	Something occurred after February mid, that all three types of cities showed, and rise tin the fares which decreased again and the beginning of march. 
-	The rest of the days, it can be seen an oscillating behavior, which must be explained looking for the correlation of each type of cities, it can be seen that one increase while the other decrease, but it happens once, it is not a common behavior. Needs to be done a deeply analysis.

## Summary
