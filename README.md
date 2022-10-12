# pyber-analysis

A classwork example in which data visualizations are created for a ride-sharing company

---
# Overview
This is a classwork example in which "I am hired as a Data Analyst for PyBer, a Python based ridesharing company valued at $2.3 billion". My initial assignment is to use Pandas and Matplotlib in Jupyter Notebook to create visualizations of ride share data in rural, suburban, and urban service areas from data compiled in January to May of 2019. These visualizations will be used in decisions to improve access to ridesharing services as well as to determine affordability for underserved neighborhoods. Several points of ride data were collected including fare paid and city type. Data collected about the service areas were presented in city_data.csv, while data collected about invididual rides were presented in ride_data.csv. These files were merged into PyBer_ride_data.csv to be further manipulated.

## Purpose
Initially I created a bubble chart to show average fare versus the total number of rides with the bubble size based on the total number of drivers for each city type. I then found the average number of rides for each city type, the range of fares for each city type, and the range of drivers for each city type. Finally I created pie charts to show percent of total fares, percent of total rides, and percent of total drivers for each city type. 

While these figures were helpful to paint a picture of underserved neighborhoods and localities, having a multiple line graph that shows total weekly fares for each city type would be benefical to the project manager. This would aggregate the data into one easy to read graph that would show differences in total fare earnings per city type, which would in turn show which city type is earning the most and the least at certain points in the year. 

---

# Results 

* The urban city type earns significantly more fares than suburban and rural city types every month in the sample. 
* Urban city type earnings fluctuate between $1,500 and $2,500 while rural city type earnings fluctuate between $0 and $500. 
* Urban city type top earnings are only 1/3 of urban city type lowest earnings. 
* Suburban city type earnings fluctuate in a similar pattern as urban city type earnings, symbolizing that certain events, holidays, weather patterns, or traffic patterns may similarly impact urban and suburban citizens. While rural city type fluxtuations follow one peak in the last quarter of Februrary 2019 and one peak in the first quarter of Marth 2019, rural high fare times differ from urban and suburban high fare times. 

![Total fare by city type screenshot](/analysis/PyBer_fare_summary.png)

# Summary

I would first recommend to further incentivize drivers to join the rural ridesharing community. Low fare earnings in rural areas are the start to a painful cycle in these areas: no drivers means no ride times available, no ride times available means that no one will seek a ridesharing service, no demand will further solidify the idea that no drivers are needed, which will result in low fares and wages, further driving drivers away from these areas. 

Next, I would recommend to pinpoint high volume times for each city type within a year timespan. This way localities can hire extra drivers to meet demand during these times. If rural residents are able to get rides in times of need, like during a high volume event, they will be more likely to use ridesharing services on occasion since they will see the service as an adequate option. 

Lastly, I would recommend advertising to lower earning city types to gain reliable drivers and returning customers. Running a gamified advertisement or interactive incentive could assist lower earning city types while in a "growing phase". 

