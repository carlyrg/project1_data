# Group Project
### New York City vs San Francisco Bike Share program

As a group we analyzed the city-wide bike share programs in New York City and San Francisco, individually then comparing them to each other. Due to limitations we were only able to take a six-month snapshot of the data that was available. The time period we looked at included some winter months and given that New York experiences more of a winter than California that skews the data some, making it appear as though San Francisco has a much higher usage rate than New York City which is not accurate. While total numbers may be off for each location we believe that we are still able to identify trends in the both peak usage times and the type of rider most likely to use the service.

Our data was available online and I downloaded each month for each city individually then merged them together after a significant amount of cleaning data formats and getting column headers to match between the files. From there I loaded the data into Pandas DataFrames and created age group bins and grouped DataFrames by city to make further analysis easier. I relied heavily on Pandas for analysis of the data and used Matplotlib, Plotly and Seaborn libraries for the data visualizations.

A couple of our high-level observations included:
-	General age of the rider: 
-	Males make up significantly more than half of all riders
-	Peak usage hours are during work rush-hours, with evening being slightly more popular than the morning time
-	Pinpointed most frequently used stations for starting/ending a ride

My focus in this project was on age demographics and that is predominately what you will find in this fork of the group project repository.
