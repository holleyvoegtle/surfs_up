# surf’s up

## Overview of the analysis
We want to open a surf and shake shop; a store gear toward tourists that rents surfboards as well as ice cream. Our first investor W. Avy, a local on the island of Oahu is very interested in the idea. But he tried a similar venture a few years ago and it failed due to weather,  poor location, and precipitation. W. Avy wanted to see how the weather patterns look throughout the year and then make a decision based on our data results. 

The tools that were initially used to analyze the data were a SQLite database with SQLAlchemy as well as Python with Jupyter notebook. We initially took the precipitation data for 12 months from 9 stations around Oahu. We also looked at the average temperature in those 12 months. The result of that inquiry was the average temperature is around 75 degrees Fahrenheit and the perciptaion came mostly during the rainy season of Fall and winter. 

After that analysis was completed, W. Avy wanted us to look at the data set for temperatures for June and December.  

## Results 

The results of the final analysis for temperatures in June and December showed:
1. June’s mean temperature is 74.9 F and December is 71.1 F. See examples of the DataFrames for the first five temperature taken in June and December:

![June](https://github.com/holleyvoegtle/surfs_up/blob/main/images/JuneTemps_head.png)
![December](https://github.com/holleyvoegtle/surfs_up/blob/main/images/DecTemps_head.png)


2. The standard deviation of both these temperatures is only about 3 degrees. See the results is the following DataFrames:

![Summary Stats for June](https://github.com/holleyvoegtle/surfs_up/blob/main/images/SummaryStatsJune.png)
![Summary Stats for December](https://github.com/holleyvoegtle/surfs_up/blob/main/images/SummaryStatsDec.png)


3. The maximum temperatures were only 85 F for June and 83 F for December.

## Summary 
What we see from the final results when comparing June and December temperatures is that there is no a lot of variation between the time of year. This is a great result for a business that will be open year round. Temperatures stay pretty consistent throughout the year and the based on our previous data results, the precipitation is low thoughtout the year as well. 

In order for a final decision to be made on investing in the surf and shake shop, two additional queries should be made. The first one should be looking at many parts of the island. The data we are given does not specify where on island these parameters are being taken. Based on the temperature and precipitation range, we must assume this in in the Waikiki/Honolulu area. Other parts of the island such as the North Shore are cooler and rainier during different times of the year. Oahu is a big island made up of many micro-climates. 
The second query should also look at density of tourists and if an area is already saturated with surf and ice cream shops. That can make a big difference on the success of our shop. 
