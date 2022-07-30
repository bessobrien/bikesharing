# Bikesharing - NYC Citi Bike Data Review

## Overview

The purpose of this project was to review the NYC Citi Bike bikesharing data and use the learning to create visualizations and conclusions for the possibility of a bikesharing program in Des Moines, Iowa. We utilized Jupyter Notebook and used Pandas to convert the trip duration to a datetime format. We then utilized Tableau for the visualizations.

## Analysis and Results

We utilized Jupyter Notebook and pandas to convert the trip duration to a datetime format. After exporting that datafram as a csv, we were ready to visualize. Utilizing Tableau, we put together a series of visualizations to help us make decisions for the project. The Tableau story is found here: [Tableau Dashboard - NYC Citi Bike Data Review](https://public.tableau.com/app/profile/bess.o.brien/viz/NYCCitiBikeDataReview/NYCCitiBikeReview)

Some key notes from this data:

1. **Checkout Time by User**

![user_time](https://github.com/bessobrien/bikesharing/blob/main/Resources/trip_duration.png)

This was the typical trip duration. We saw that most trip durations overall were less than an hour.

2. **Checkout Time by Gender**

![time_gender](https://github.com/bessobrien/bikesharing/blob/main/Resources/duration_gender.png)

This was the trip duration, but split out by gender. From this, we can see that regardless of gender, trips typically last under an hour.

3. **Trips by Weekday for Each Hour**

![wkdy_hr](https://github.com/bessobrien/bikesharing/blob/main/Resources/weekday_hour.png)

This visual showed a heatmap of our top times by weekday. This shows us that 8-9am and 5-7pm are peak hours, and Thursday is the heaviest weekday.

4. **Trips by Gender (Weekday per Hour)**

![gndr_wk_hr](https://github.com/bessobrien/bikesharing/blob/main/Resources/trip_gender_weekday.png)

Another heatmap, but split out by gender. We see here that regardless of gender, peak hours and days remain consistent.

5. **User Trips by Gender by Weekday**

![gndr_wkday](https://github.com/bessobrien/bikesharing/blob/main/Resources/trip_gender_day.png)

This was split to show a customer vs subscriber, the weekday, and gender in a heatmap. Most of the rides were accomplished by subscribers, and again we see male as the top frequent rider gender and Thursday as the peak day.

6. **Top Starting Location**

![starting](https://github.com/bessobrien/bikesharing/blob/main/Resources/starting.png)

This is a map visual with the top starting locations. From here, we can see that the most frequented areas are close together, and the rides are a combination of commuters and tourists.

7. **Bike Utilization**

![bike_util](https://github.com/bessobrien/bikesharing/blob/main/Resources/Bike_utilization.png)

Here we can see the bike id's and their total trips. This helps us plan that some bikes will be used more than others and will require more frequent maintenance.

## Summary

Overall, this data was helpful to us in realizing some interesting factors to take into account. A couple key takeaways:

1. Some bikes will be used more than others and maintenance should be expected accordingly. In addition it will be important to budget that maintenance in.
2. Top starting locations were grouped in similar spots. To start with the program in Des Moines, we should start with a smaller number of bikes in key areas of tourism and commute as a beta test.
3. Trip durations were consistently under 1 hour for the majority of the rides. From this we can plan bike stations accordingly.

There are a couple more visualizations that would help us with our analysis:

1. A map showing a select number of starting and stopping stations to provide context on typical distance needed between stations.
2. A bar chart that shows the top bikes that were utilized the most. An extra mention on total number of bikes will help us determine extra maintenance needed on a percentage of the bikes.
