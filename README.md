# Des Moines Bikesharing Project
For this project, we are teaming up with a partner in an endeavor to launch a bikesharing program in Des Moines, Iowa. We're putting together a pitch for potential investors, and we've located a great resource for analysis: a publicly available Citi bikes dataset of rides in New York City. 

## Overview
While Des Moines and New York City are very different places, we're excited to have a robust dataset that will probably tell us a great deal about bikesharing usage patterns. Drawing on our data expertise and critical thinking skills, we'll work with the data and determine how we can apply our findings from this New York City dataset to the potential Des Moines program.

We will conduct our research using Tableau, and build a business proposal using Tableau's story feature.

[link to dashboard](https://public.tableau.com/profile/mike.flowers#!/vizhome/Bikesharing_Challenge_16150482631120/Story1?publish=yes)

## Results
We used data from August 2019, and discovered many interesting patterns about daily and weekly bikeshare use. Here are several examples.

![Total Rides, and Gender and User Breakdown](https://github.com/flowersmichael/bikesharing/blob/main/Total%20Rides%2C%20Gender%20and%20User%20Breakdown.png)

In August of 2019, people used Citi bikes in New York City for over 2.3 million trips. A little over 80% of those rides were subcriber rides. Roughly 70% of the rides were by men.


![Top Starting Locations](https://github.com/flowersmichael/bikesharing/blob/main/Top%20Starting%20Locations.png)

The map below demonstrates that many of the most popular ride start locations are clustered around Midtown Manhattan.


![August Peak Hours](https://github.com/flowersmichael/bikesharing/blob/main/August%20Peak%20Hours.png)

The morning commute 8 o'clock hour, and the evening commute 5-7pm hours are the peak ridership hours.

It's also noteworthy that four of the top five peak usage hours are the evening hours between 4-8pm. This demonstrates that Citi bikes are a more popular commute option in the evening compared to the morning.


![Checkout Times by User and Gender](https://github.com/flowersmichael/bikesharing/blob/main/Checkout%20Times%20by%20User%20and%20Gender.png)

The great majority of rides last less than 20 minutes, with 5 minutes being the most popular duration. Nearly all rides are under one hour long.

Males and females have similar ride duration profiles, with rides by females tending to last a little longer.


![Trips by Weekday per Hour](https://github.com/flowersmichael/bikesharing/blob/main/Trips%20by%20Weekday%20per%20Hour.png)

The most popular times during the week for bike dropoffs at the end of rides are the morning commute (in particular between 8-9am) and the evening commute (between 5-7pm). Thursday in particular looks like a popular day for commute rides. There's a noteworthy drop in ridershipe during the Wednesday evening commute that's worth investigating.

On weekends, the most popular ride times are from late morning into the evening.


![Trips by Gender (Weekday per Hour)](https://github.com/flowersmichael/bikesharing/blob/main/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

Looking at popular ride times by gender, females and males have very similar profiles.

For rides of unknown gender, the ride time profile is different. Their most popular ride times are midday on the weekends, with less commute traffic. This might suggest that these riders are often tourists or other customers who don't want to take any extra time completing their profile with gender information.

![Trips by Gender by Weekday](https://github.com/flowersmichael/bikesharing/blob/main/User%20Trips%20by%20Gender%20by%20Weekday.png)

Finally, we break down daily use trends between pay-per-use customers versus subscribers.

Customers have less daily variance, although Wednesdays are the lightest day, and across genders  customer counts on weekends tend to be a little higher than weekdays.

Female and male subscriber rides are concentrated on weekdays. On a relative basis to other categories, there are a lot fewer unknown gender subscribers. In this analysis we don't discern much difference in their use patterns across the days of the week.


## Summary
This analysis is a great start for predicting how popular our proposed Des Moines bikesharing program will be. That said, as noted before, Des Moines, Iowa, is a very different place from New York City. It would be great to compare this data with that of another city with a different demographic and weather profile, and see how many of the patterns hold up. I do believe it's safe to assume that in most places, ride traffic would be heaviest during weekday commute hours and weekends from late morning into the evening.

Absent data from another city, there are other visualizations from this dataset that would further inform our analysis. For example, it'd be helpful to look at data from a different month, especially a winter month like January or February. It'd be interesting to see how different weather and daylight hours impacts what hours during the week are the most popular ride times. It'd also be interesting to get a general feel for which month of the year are the most popular for riding. This could help inform maintenance and upgrade planning. Another very helpful datapoint would be the number of bikes per city resident and/or worker. This per capita figure could be applied to Des Moines data to plan the scale of the program.






