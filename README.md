# surfs_up
Oahu Weather analysis

### Environment
Python 3.7.3  
Anaconda 1.9.0  
Conda 4.12.0  
Jupyter notebook 6.1.12  
Pandas 1.3.4  
SQLite 2.6.0

## Overview
The purpose of this analysis is to analyze weather data (mainly precipitation and temperature) in order to convince the investors about the "Surf n' Shake" project.   
The investor is specifically concerned about the weather in Oahu for the months of June and December. The investor wants determine if the surf and ice cream shop business is sustainable year-round.

## Results
The data analyzed presents Ohau as a sustainable year-round location for a surf-and-ice cream business.

* Summer (June) and winter (December) average temparatures are between 71 and 75 degrees. This is a great average temperature for surf and ice-cream.  
* Summer (June) and winter (December) temperatures variation (std) is less than 4 degrees. This means that the temperature isn't highly variable which suggests that Oahu is sustainable year-round location for surf and ice cream.  

![Jun_Temp_Desc](https://github.com/MarcoFernandez14/surfs_up/blob/main/June%20Temperature.png)
![Dec_Temp_Desc](https://github.com/MarcoFernandez14/surfs_up/blob/main/December%20Temperature.png)

* Even if the minimum and maximum temperatures could be a problem, the frecuency or quantity of observations of these temperatures is very low.

![Jun_Temp_Plot](https://github.com/MarcoFernandez14/surfs_up/blob/main/June%20Temperature%20plot.png)
![Dec_Temp_Plot](https://github.com/MarcoFernandez14/surfs_up/blob/main/December%20Temperature%20plot.png)

## Summary
The conclusion is that Oahu is a great place to invest in a surf-and-ice cream shop. The weather is nice year-round. The lows and highs temperatures are rare.  
Also, looking at the precipitation data, we can observe that the average rainfall is light which supports further the investment.  

I generated additional queries to obtain June and December precipitation merged statistics as below.  
![Precipitation](https://github.com/MarcoFernandez14/surfs_up/blob/main/Precipitation.png)

To gather more weather data, we cloud analyze:  
- Precipitation.  
- Other months than June and December to better identify weather seasonality.  
- How the elevation relates with average temperature and precipitation.  
- If we add access to the data, wind speed is an important piece of information for surfing.  

