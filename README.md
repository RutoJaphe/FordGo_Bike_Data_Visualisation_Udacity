# Ford Go Bike Data Vizualisation
## by Japheth Rutoh


## Dataset

The dataset used for analysis is a bike share dataset containing information about bike rides in the San Francisco Bay Area, for the month of February 2019. I wanted to see how long the bike rides took so the main feature for analysis is the bike ride duration.

The original dataset was made up of 183412 rows and 16 columns but after the data wrangling process there were 175147 rows and 6 columns. The final columns are the following:
 - duration_sec 
 - start_time
 - user_type
 - member_birth_year
 - member_gender
 - bike_share_for_all_trip
> I extracted new features from existing ones. Thes are:
 - day_of_week
 - day 
 - age
 - duration_min 
> <code>duration_min</code> is <code>duration_sec</code> divided by 60 which converts it into minutes.

## Summary of Findings

> Bike ride duration being the main feature I found out that most rides take between 6 and 9 minutes.
> Thursday had the highest number of rides compared to the other days of the week.
> The number of rides generally rose from the start of the week and dropped during the weekend.
> Male users made up the largest percentage of users with 74%.
> The average ride duration for Subscribers is lower than the average  duration for Customers, and the average duration for Customers spiked during the weekend while the average duration for Subscribers only rose slightly.
> The total ride duration for Subscribers was far more than the total bike duration for Customers.



## Key Insights for Presentation

> - The distribution of the main feature; duration.
> - The number of rides by day of the week
> - Weekly bike ride duration by user type i.e Customers and Subscribers
> - The distribution of duration vs age, categorized by the user type
> - The distribution of duration vs user type, categorized by gender.
> - Line plots for the average weekly bike duration and the total weekly bike duration, to show the weekly trend.