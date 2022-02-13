# (Ford Gobike Data Exploration)
## by (Nada Alzahrani)

This project is split into two main parts. In the first part, on Ford Gobike dataset, you can perform an exploratory data analysis. I will use data science and data visualization libraries from Python to explore the variables of the dataset and understand the structure, oddities, patterns and relationships of the data. The study should be organized in this section, ranging from simple univariate relationships to multivariate relationships.


I will take my key conclusions from my exploration in the second part and express them through an explanatory analysis to others. To this end, to convey my findings, I will create a slide deck that leverages polished, explanatory visualizations.
 

## Dataset
> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area, in 2019. The dataset containing the Ford Gobike trip data of approximately 183,412 with 16 characteristics:

- duration_sec
- start_time
- end_time
- start_station_id
- start_station_name
- start_station_latitude 
- start_station_longitude
- end_station_id
- end_station_name
- end_station_latitude 
- end_station_longitude
- bike_id
- user_type
- member_birth_year
- member_gender
- bike_share_for_all_trip
The majority of variables are 9 numerical, and others are 2 datetime, 4 type of object and 1 type of boolean.


## Summary of Findings

> Trip period is so dependent on the age of the member that the duration of the trip is longer than the older ages when the age is between 20 and 40. For the age, length, and gender, the others jump to 3000 trip duration at an older age -about 60 years- for the others. 

> Both Customer and Subscriber show similar patterns for age and trip duration for the age, duration, but the trip duration for subscribers is higher for older age.


## Key Insights for Presentation

> Trip Duration Distribution: 
Trip Durations take on a very wide variety of values in the dataset. First the number of trips values increases from about 8000 values to 12000 values at a height of about 600 seconds, but then begins to fall below 2000 values. 

> User Age Distribution: 
The distribution is more distributed between the ages of 20-40.