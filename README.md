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


