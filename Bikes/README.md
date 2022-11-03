# 201902- Fordgobike Data Exploration

## Dataset

The data consists of information regarding 18,342 bike share trips, 
including duration seconds, gender and other features. The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv),


## Summary of Findings

In the exploration, I found that there was a relationship between the trip duration
and the distance covered, although the relationship was a weak one.  I checked the 
distribution of duration minutes and the distance covered. I discovered both variables
were positively skewed. I also looked at the disparity of the age variable. 

I then looked at the interactions of variables with each other. The user type had an 
interesting interaction with the distance covered as well as the duration minutes. 
The count of each user types could not be used to judge the average trip duration and
distance covered as they vary from one user to the other.

## Key Insights for Presentation

For the presentation, I considered the main variables of interest. I start by introducing the
duration minutes, then the distance variable.

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the bar chart of weekdays and user types. I also looked at the distance covered 
by each user types, then the average duration minutes by each user type. The other
categorical variable, gender was covered afterwards, using box plots. I've made
sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.
