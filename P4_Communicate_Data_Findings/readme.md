# Ford GoBike System Data (February 2019)
## by Cynthia Leu


## Dataset

The dataset consists of information regarding 183K+ Ford GoBike individual trip records from February 2019, provided [online](https://s3.amazonaws.com/baywheels-data/index.html) for free public use. After some data wrangling, the final dataset to be used for data exploration has 21 variables and 170K+ trip records. 


## Summary of Findings

In the exploration, I found that there were strong relationships between user type, hour in the day of the bike trip, day of the week of the bike trip, and trip duration. Customer distribution by hour is more evenly spead, but it's clear that the bimodial peaks during commute hours are dominated by subscribers. In fact, thanks to those work commuters, bike usage is much greater on weekdays compared to weekends. The distribution for trip duration is much flatter for subscribers, while customers have a longer distribution. Trip duration increases over the weekend, but stays fairly even on the weekdays. In the presentation, I will elaborate more on these findings and relationship. 

Outside of the main variables of interest, I also tried to look for other relationships. While member age does have a distinct distribution, I thought it would fluctuate more based on user type. However, I didn't find that relationship, at least not in this particular dataset. There was also not much to say about gender behavior, though it was interesting that the user base is so male-dominated (75% of records). An interesting but unsurprising finding is of the popular bike stations. Most of the bike rides start around the San Francisco Financial District, where many people in the Bay Area work.


## Key Insights for Presentation

For the presentation , I focus on the different usage patterns by subscribers and customers. I start by introducing the user type variable, pointing out how more than 90% of Ford GoBike System's user base are subscribers.

Then, I introduce the time and demand-related variables. To start, I use the heatmaps of of hour-of-day and day-of-week across user type. This view effectively demonstrates how demand changes by hour or by day, depending on user. To get the point across, I chose color palette magma_r to easily visualize high and low usage. I dig a little deeper by using a point plot to explore average trip duration and day-of-week across user type. Color-encoding is a practical way to see the difference over time for the two user types.