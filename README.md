# Bikesharing

## Overview

Conducting an analysis on bike trip data during the month of August 2019 to convince investors that a bike-sharing program in Des Moines is a solid business proposal. 

For the analysis I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. 
Creating a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week


## Results

[Link to Full Tableau Report](https://public.tableau.com/app/profile/alexis.lorenz/viz/CitibikeStory_16639663078800/Citibike_Story?publish=yes)

<br />

<img width="355" alt="citibike_tripdayofweek" src="https://user-images.githubusercontent.com/107652317/192061971-2cc2d48a-8e72-47f3-9841-645b6d86520b.PNG">
The most popular days of the week for riders is Monday, Tuesday, Thnursday, and Friday.

<br />

<img width="623" alt="bikeciti_tripbyhour" src="https://user-images.githubusercontent.com/107652317/192061798-f4702fd0-4bf9-45e8-8f64-29a019435579.PNG">
The most populaer times people rode were between the hours of 8-9am and 5-7pm. 

<br />

<img width="569" alt="bikeciti_tripduration" src="https://user-images.githubusercontent.com/107652317/192061878-9fa2494d-d845-4752-89d9-5a1283f15666.PNG">
Males and Females road an average of 5-6 minutes per trip.

<br />

<img width="376" alt="citibike_tripcount" src="https://user-images.githubusercontent.com/107652317/192062151-54b2a5d9-d657-4161-b0c6-cfca2ed5c28b.PNG">
Trips were mostly taken by males between the hours of 5-6pm on a Thursday 

<br />

<img width="372" alt="citibike_tripbyuserandgender" src="https://user-images.githubusercontent.com/107652317/192062179-0e0178fa-eb95-45de-8671-d54268dbb01b.PNG">
Male subscribers were more abundant than any other user.

<br />

<img width="466" alt="citibike_user" src="https://user-images.githubusercontent.com/107652317/192062764-f810c515-a943-4ea7-8805-dc6250405f06.PNG">
There is significantly more subscribers than customers.

<br />

<img width="536" alt="citibike_age" src="https://user-images.githubusercontent.com/107652317/192062804-afa0218c-dfb8-422a-ba42-7aae0ca1c9fd.PNG">
Most users seemed to be between he ages of 25-30 years old. 



## Summary
The analysis shows that bikes were mostly checked out by males and were subscribers. Possibly meaning that customers and females ride more on the weekend. Also, bikes were checked out usually between the hours of 8-9am and 5-7pm. This indicates that the bikes were most likely used for work commute. The trips consisted of an average trip time around 5-6 minutes. The busiest days were Monday, Tuesday, Thursday, and Friday. I would suggest to create a visualization for the age and gender. A visualization for the stations (start and end) with tripdration to see the distance among trips could be useful as well. 

### Resources

* Pandas
* Tableau Public
* CSV file
