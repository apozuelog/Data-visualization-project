# Data-visualization-project
Ford GoBike analisys and visualization.
***************************************************************************************
* NOTE: The files gobike.csv and clean_master_gobike.csv, not copied for exced 25 MB. 
***************************************************************************************

Customer experience users Ford GoBike System in 2018/2019
Andrés Pozuelo 
May 2019

What is Ford GoBike?
Ford GoBike is the Bay Area's bike share system. Bay Area Bike Share was introduced in 2013 as a pilot program for the region, with 700 bikes and 70 stations across San Francisco and San Jose. Once expansion is complete, Ford GoBike will grow to 7,000 bikes across San Francisco, the East Bay and San Jose.

Ford GoBike, like other bike share systems, consists of a fleet of specially designed, sturdy and durable bikes that are locked into a network of docking stations throughout the city. The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips. People use bike share to commute to work or school, run errands, get to appointments or social engagements and more. It's a fun, convenient and affordable way to get around.

The bikes are available for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network when they become a member or purchase a pass.


Original structure

This first dataset has more than 2.7 million records in 16 columns and includes records from 2018-01-01 to 2019-09-30.


The final structure has more than 2.5 million records in 21 columns where we can see:

* The times of the journeys
* From where and where with geolocation
* Age, gender and type of user
* The id of the bicycle and if it is shared for the all trip.

In addition columns of year, week, month, day and hour have been added for a better subsequent analysis


Main features

* Initially I would like to see what is the general trend of monthly use, use by age and by gender in general terms
* Later I would like to check the same data with the year 2019 to see the trend.
* How many are the peak hours, the days of the week with the highest demand and if they affect the months with the lowest temperatures?
* And above all, see the flows of users going to and from where, time, and if they repeat the same flows back hours later.

	
***************************************************************************************	
Final analysis:

As more significant results I would highlight:

* In 2019 there is an increase of approximately 100% in GoBike users.
* The use of GoBike by men is much higher, but their age is similar, between 30 and 40 years of age.
* Its use is greater than 7:00 a.m. to 10:00 p.m. and from 4:00 p.m. to 7:00 p.m., which suggests that it is to go to and from work.
* We can also observe that more users are returning than they are. This is because in the morning most of the users go in another means of transport faster, but take the opportunity to return to GoBike.
* If the return is to occur after 18:00, the effect is the opposite, fewer people return than they were.
* Finally, the flow of people are reduced in few destinations. Possibly because that's where the jobs are.
***************************************************************************************



