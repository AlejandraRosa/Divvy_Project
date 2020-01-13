Analyzing Divvy’s 2018 Ridership

Our goal with this project is to gain a better understanding of the Divvy ridership in order to:
The questions we wanted to answer included:
1.	What are the most popular times for people to ride?
2.	How does the weather affect our ridership?
3.	Demographically, who are our riders?
4.	Do we skew towards single riders or annual pass riders?
5.	Where are the most used divvy stops?

This data was published by Divvy themselves and posted to the Chicago DoT site which is where we downloaded the CSV from.
We first had to union our four quarterly data sheets into one data frame to make it once CSV from the whole year.
After that, for consistency, we had to change the time formatting to match.
We wanted our analysis to focus on the times of rides, locations, and who was riding so those columns 
Conclusions:
1.	Time of Day where most bikes are in use – We found that the typical commute times were the most commonly used ride times. 5pm and 9am were the highest volume
2.	Through the Heat map, we were able to see that the most used divvy stations were in the loop and as you went north, west, or south, they were used less frequently. Given how many stations there were overall, it’s tough to determine which is the most used on the map, so we decided to re-order the DF by most used to least used and mapped again to see the top ten stops.
3.	Days of the week – We were curious how the day of the week would impact number of rides. As shown in our bar plot, ridership remains fairly uniform across each day of the week. A healthy mix of commuters and tourists 
4.	It was interesting to find that although the vast majority of rides were made by subscribers, the most commonly used stops included Navy Pier and Millennium park where tourists are the most common riders. Weekends do have the most rides by volume but it isn’t by a wide margin
5.	Demographics: We found that our ridership skews male and subscriber. This is not surprising as most of our rides would be from repeat riders who are subscribed and not spending 10 dollars per ride.
6.	Top Stations to Start rides and End rides -  We found that 
7.	How this will impact Divvy Operations
