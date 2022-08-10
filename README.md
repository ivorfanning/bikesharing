# Bikesharing Project - Analysis of NYC Citi Bike in August 2019

# Project Overview

This Project was inspired when we were using citi bikes to travel around in New York City, and NYC has this bikesharing program across Manhattan, Brooklyn, Queens, the Bronx and New Jersey City, it is really a convenience way for travellers. After visiting NYC, we have an idea which is it possible to copy the bikesharing business operation in our home town Des Moines. Thus we need to analyze the data provided by citi bike.

By doing that, the first step we need is to change the data type of tripduration column by using jupyter notebook, and then connect the updated data into Tableau to do the analysis.

# Results

First we count the total number of rides in August 2019, which is 2,344,224 rides. This is a large number of use for bikesharing program,that means the program is popular among the cities.

Then we plot the gender breakdown to see which gender use bike more frequently. From the pie chart, it is easily to see male are willing to use the bike than females.
![gender breakdown pie](https://github.com/ivorfanning/bikesharing/blob/main/images1/gender%20breakdown.png)

From the following bar chart, it is shown that the peak hours of using bikes in August are 7-8am and 17-18pm, which are the interval of commute time, so the bikesharing program is popular among the commute people.
![peak hr in Aug](https://github.com/ivorfanning/bikesharing/blob/main/images1/peak%20hr%20in%20Aug.png)

Another evidence is the heat map we ploted, from the following heat map, it was darker on 7-8am and 17-18pm from Monday to Friday.

On weekend, the trips are usually take on between 10am-17pm, which means the use of bikes are most likely take by vistors in weekend.
![trips for hour](https://github.com/ivorfanning/bikesharing/blob/main/images1/trips%20for%20hour.png)

Further more, we breakdown the trips for gender on everyday use. Clearly we can tell male users are more likely to ride bike if the distance allowed.
![trips for gender](https://github.com/ivorfanning/bikesharing/blob/main/images1/trips%20for%20gender.png)
![trips by gender by wkd](https://github.com/ivorfanning/bikesharing/blob/main/images1/trips%20by%20gender%20by%20wkd.png)

Lastly, we polt the line chart for checkout time for user and gender. From the following charts, we conclude the checkout time is usually under 60 minites, and males checkout out time is almost triple the females, which is prove our views males are willing to ride bike than females.
![checkout time for user](https://github.com/ivorfanning/bikesharing/blob/main/images1/checkout%20time%20for%20user.png)

![checkout time by gender](https://github.com/ivorfanning/bikesharing/blob/main/images1/checkout%20time%20by%20gender.png)

The full dashboard could be viewed at https://public.tableau.com/app/profile/ivorfanning/viz/citibikestory/citibikestory?publish=yes
# Summary

The bikesharing program is a great idea for short distance commute and convenience for nearby communities. It could save time, reduce traffic jam and gain much more fun. However the program still has its limitations, such as the age, maintainence, and cost of fix of the bikes.

A few additional visualizations needs to be performed with the given dataset are for example:

- The times of bike usage and age range
- The distance of user travel
- The popular starting and ending stations.
