## Introduction
Dataset Description
This dataset collects information from Citibike useage across NYC. The data includes individual rides by users as well as station useage where citibikes are set up.
Alta Bicycle Share, the company that owns and operates the Citi Bike program, is facing some unexpected financial difficulties as a result of dropping sponsorship revenue for the bike share program. Faced with a revenue shortfall, Alta would like you to mine the Citi Bike stations and trips data to come up with solutions and projected revenue impact. Alternatively, you could investigate ways to reduce expenses without impacting ride volume too negatively.
- User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
- Gender (unknown, male, female)

## Exploration for Analysis
- Trip Length
- What day of the week, time, and months have the most users of the bikes
- Age
- Stations Analysis

## Techniques Used:
- Used the BigQuery API to pull in the data using SQL
- Used a series of graphical analysis to showcase the distribution of the data and show potential opportunities to increase revenue

## Conclusions:
- Assumptions: In the spring and summer months there are higher users due to tourism There is an app to use a bike or to sign into an account to use one
- The average trip by a citibike user is about 12.4 minutes, and riders are nearly all subscribers and men
- Highest density of riders during early morning between 6 and 9, and the afternoon and late evening from 3 to 7
- On the weekend there are far less citi bike riders than on the weekday
- May to September definitely get more people riding due to the weather, longer days, and overall use.
- We observed that the heavy riders are Gen Z and Millenials (1980 - 1996) and in terms of Gender there is about 2:1 Men vs Women
- The top 10 busiest start stations are nearly the same end stations

## Recommendations:
- Alta Bicycle Share should focus on running weekend camapigns where they can set up a 2-Day pass for the weekends during the high volume months to increase citi bike useage. This would help tourists get around but also allow locals to explore the city through a new method
- Alta Bicycle Share should run a marketing campaign for women to engage and empower them to safetly get to and from home to work or to their leisurely activities
- Since a majority of citi bike riders are Subscribe, Alta Bicycle Share should consider increasing the price of their annual subscription.
- Alta Bicycle Share should consider testing out if placing more bikes in the top 10 busiest Start and End stations will increase people in buying an annual membership or being a customer.
- Extra: Although my code was crashing my kernal everytime. I manually googled some of these station locations, and Alta Bicycle Share should consider looking at merging the boroughs together.
