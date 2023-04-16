# CitiBike_Trip_Data_Anlaysis

Goal of this project is to analyze CitiBike data and uncover unexpected phenomena that will help the bike company understand usage patterns among different bikers. Additionally, understanding used routes and temporal patterns will help Citibike decide how to allocate resources at bike locations, routes and potentially partner with other companies to incentivize ridership.

This project uses Python with Pandas library and Tableau to visualize and analyze CitiBike data.

## Resources

* Link to Tableau Story: [CitiBike Trip Data Anlaysis](https://public.tableau.com/views/Citibikeanalysis_16816106459860/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link "CitiBike Trip Data Anlaysis")
* Data Source: JC-202303-citibike-tripdata.csv.zip found at [Citi Bike Trip Histories](https://citibikenyc.com/system-data "Citi Bike Trip Histories")

## Results & Analysis

### Understanding Usage Differences Between Casual and Member Riders:

<p align="center">
<img src="https://user-images.githubusercontent.com/118090932/232262696-88c5819c-4dca-4a06-9d09-2b5b76ec1fc7.png" width="650" height="500">
</p>

<p align="center">
Figure 1. Casual VS. Member Riders
</p>

The Dashboard in Figure 1 shows that:
* In March 2023, there were 62,833 rides recorded.
* Of these, 49,163 were completed by riders with membership while 13,670 were completed by casual riders.
* When we compared the classic vs. electric bike use between the two groups, the casual riders were two times more likely to use classic bikes, whereas members were four times more likely to use classic bikes.
* When we look at the number of rides taken on each day of the week, bike usage peaked mid-week. 
* Although usage patterns were quite similiar between casual and member riders, there was higher bike usage by casual members on Sundays.

### Understanding Usage Differences Between Casual and Member Riders:
<p align="center">
<img src="https://user-images.githubusercontent.com/118090932/232263152-405e1357-b9d4-4895-a090-74c836caef4f.png" width="550" height="500">
</p>
<p align="center">
Figure 2. Peak Ridership
</p>

The Dashboard in Figure 2 shows that:
* March evening peak hours were 5PM & 6PM for both casual and member riders
* While 7AM & 8AM were morning peak hours for member riders, 7AM was the least busy time for ccasual riders.
* During the week, peak ridership hours are concentrated between 5PM-7PM, while over the weekend, peak ridership hours were between noon and 5PM.

### Understanding Usage Difference

<img align="left" width="500" height="300" src="https://user-images.githubusercontent.com/118090932/232263821-827a4e58-8860-43c3-a962-ab3cc6dccf03.png">

<img align="right" width="450" height="300" src="https://user-images.githubusercontent.com/118090932/232263831-2e79db46-cc14-4f2a-833a-b07b8ae6cf07.png">

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

<p align="center">
Figure 3. Peak Ridership Throughout the Week
</p>

Figure 3 shows that:
* During the week, ridership peaks at 8AM and 6PM, on Friday the evening peak is at 5PM and on Sunday, it is at 4PM.
* Electric bike ridership goes down on the weekend compared to classic bike usage.
* During weekdays, classic bike ridership can increase four fold while, electric bike usage can increase by six to seven fold.
### Bike Station Distribution and Popularity

<p align="center">
<img src="https://user-images.githubusercontent.com/118090932/232264890-3cdf9d4b-ebac-45ad-9169-f98b61a17148.png" width="750" height="500">
</p>

<p align="center">
Figure 4. Bike Station Distribution & Popularity & Household income
</p>

Figure 4 is a map that shows:
* The location of bike stations and their populatiry indicated by circle size
* Average household income
* Most of the bike stations are found in areas with average household income between $81,000 to $250,000
* Number of bike stations are less in areas where household income is less than $60,000

### High Ridership Stations

<p align="center">
<img src="https://user-images.githubusercontent.com/118090932/232265295-46370338-69b9-4e84-91dd-b5bceb238c0e.png" width="750" height="500">
</p>
<p align="center">
Figure 5. High Ridership Frequency Stations
</p>

Figure 5 shows that the following four stations are the busiest with high ridership:
* Hoboken Terminal, Gove St. Path, Newport Pkwy and South Waterfront

### Ride Length Based on Origin and Destination

<p align="center">
<img src="https://user-images.githubusercontent.com/118090932/232265612-335b566e-04b5-4bd7-87a1-6b7e8e1cd1da.png" width="750" height="500">
</p>
<p align="center">
Figure 6. Ride Length & Destination
</p>

Figure 6 is a map that summarizes information about the length of a bike trip from a location of origin to all destinations from completed rides. 
* This map shows that riders travel out of Hoboken and Gove stations often
* While the ride length and time vary, longer distance trips do not necessarily indicate longer trip durations.

## Conclusion

Casual riders make up twenty-two percent of all riders, while member riders make up the remaining seventy-eight percent. Considering peak time patterns, most of the member ridership peaks during rush our before and after workday hours. On the other hand, casual ridership peaks late Friday evening and Sunday afternoons. CitiBike could provide membership opportunities during these peak hours to casual riders to increase their numbers. Additionally, casual riders are more likely to ride electric bikes compared to members, consequently CitiBike could make them more available to these riders. 
Considering bike stations with higher ridership numbers are found in neighborhoods with higher income, CitiBike could implement incentives for ridership in neighborhoods with lower incomes in order to 
