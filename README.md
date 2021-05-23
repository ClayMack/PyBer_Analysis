# Pyber analysis

* Use Jupyter Notebooks

* Use Python, Pandas, Matplotlib, and Numpy to analyze ride sharing data 

* Track ride sharing trends based on key metrics to make recommendations to the CEO for addressing any disparities among the city types (Urban, Suburban, and Rural)

## Overview of the Pyber analysis:

* Using Jupyter Notebooks, load Matplotlib and pandas
* load data from two csv files (city and ride data) and merge into a single dataframe.
* Create data frames to calculate data metrics using groupby, sum, pivot, resample, and loc functions
* Create various plots for trend analysis using Matplotlib

## Challenge Objective:
Using your Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. To finalize, submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer

## Results:
Pyber ride-sharing data summary among the different city types:

![Pyber Summary by City Type.](https://github.com/ClayMack/PyBer_Analysis/blob/main/analysis/Fig9.png "Pyber Summary by City Type.")

* The data shows that there are more rides and drivers in Urban cities compared to Suburban and Rural cities. Due to supply and demand the average fare per ride is the lowest, yet does bring in the most revenue compared to the other cities types combined
* Rural cities tend to have very few drivers and rides which probably corresponds to each other. Rural cities by fare contribute the least revenue to Pyber
* Suburban cities show to in between the two other city types and contributes just under half of the total revenue to Pyber 
* An intersting observation is that there are more drivers in Urban cities than the total rides. This indicates an oversaturation of drivers and could possibly lead to high turnover 

Pyber weekly fares by city types (1/1/2019 - 4/29/2019) :

![Pyber Fares by City Types.](https://github.com/ClayMack/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png "Pyber Fares by City Types.")

* Urban: In January the revenue is around $1,600 and climbs to $2,500 through late February before leveling off to about $2,250 in April
* Suburban: In January the revenue is around $1,000 for most of the time period exept a spike in late Febraury to  $1412.74. The trend indicates that the fares are increasing throughout April and could possibly see a new peak
* Rural: Weekly fares start out around $200 tend to be realativly flat compared to the other two city tyes. there is a spike at the beggining of Apri to $501.24


## Summary:

Recommendations to CEO:

1. Limit new drivers in Urban cities. The ratio of drivers to rides is 0.68. There seems to be an oversaturation of drivers that could be pushing the fare average down. if the ratio were to increase, the total fares should increase. 

1. Increase the number of drivers in Suburban cities. The ratio of drivers to rides is 1.27.  The numbers show that the demand is there and additional drivers could support addtional revenue.

1. Increase the number of drivers in Rural cities, but with caution. The ratio of drivers to rides is 1.60.  This shows that the demand is low and adding more drivers could support addtional revenue, but the push to increase rides may not yeild much revenue.

1. Ride distance is missing in the analysis. Had that been factored in there may be additonal areas to focus on. I recommend adding that variable to the analysis.




