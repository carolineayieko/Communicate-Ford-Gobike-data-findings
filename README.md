# Exploration of Fordgobike 2019 data

## by Caroline Ayieko


## Dataset

This data includes information about 183412 individual rides made in a bike-sharing system covering the greater San Francisco Bay area in the month of Febraury. The dataset can be downloaded here and has attributes such as duration, user type, start/end time, as well as additional information such as bike id, rental access method, start/end station, etc. The dataset was cleaned by removing outliers in the Exploration step while erroneous data types were corrected in the wrangling step. I added columns: `duration_minute`, `start_data`, `start_hour`, `start_dayofweek` and `start_month`




## Summary of Findings

In the exploration,I did a univariate, bivariate and multivariate visualizations.I used number of trips which is basically the count, then did most of the visualization using duration in minutes as the main variable, and  other categorical variable  and checked their effect on durations and also versus each other. The number of trips peaked around 8-9am and 17-18pm during a day, there were more trips on work days (Mon-Fri ) compared to weekends. Riding on peak hours of 8-9am and 5-6pm shows that the bikes are mostly used for commute to work early in the morning and early in the evening.The riding trips tend to be shorter on Monday through Friday compared to weekends. I found that user type affects bike usage in number of rides and trip duration. Although subscribers make a lot more trips than customers, customers generally take longer durations in their trips than subscribers. Both subscribers and customers take longer trips during weekend than weekdays. Subscribers took more trips during the weekdays and less on weekend(probably resting from work). 

Most riders were male subscribers who rode for a shorter duration as compared to their female counterparts. The females shows a tendency to go for a longer duration together with other gender. The univariate for for user type shows higher number of subscriber, it does show that they take more trips as compared to customers


## Key Insights for Presentation

The presentation I will show how duration of trip is affected by categorical variables such as user_type which will be our main focus. I will also present the effects of other categorical variables on duration and how time of day, day of the week affects the counts and duration of trip.I'll plot the visualizations to see impacts of user type on duration and usage(in number of rides) and focus on how different groups of users use the service(in terms of gender, and age.

