# Cyclistic Case Study

Cyclistic is a bike rental company that has over 5800 bikes and 600 docking stations. Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. We will need to understand how casual members and annual members differs in order to design marketing strategies. The task will be to analyse and understand the difference and recommend strategies to convert casual members into annual members.


## Data 
  The data was provided in the Google Data Analytics Course's Capstone Project. From 3 years of data , we chose the data of year 2022.      
  Month wise data of the year 2022 was wrangled and 5667717 entries were obtained.

### Data Cleaning and Manipulation
<ul>
  <li>Converted dates to epoch time and subtracted all the epochs by the first recorded epoch in order to make the numbers small.</li>
  <li>Missing values in the columns were replaced with other terms.</li>
  <li>Month,Date,Year was split for further analysis. The day was also identifies to understand the specific day wise trends.</li>
  <li>Ride times that were less than 0 was removed.</li>
</ul>

## Findings

 <ul>
   <li>Members have more rides than casual users , but when it is about the total time consumed , casual users have used this service more than members. This may mean that members use the service frequently but for a short period of time. Casual users use this servic for a long amount time or they retain the vehicle for a longer time.</li>
  <br>
   <li>Month wise analysis: The difference between casual and member is high in most of the months except the summer months (May,June,July,August). Casual users are using our service more in the summer season and this can be for sightseeing Chicago during summer.</li>
</ul>
<img width="700" height="300" src="/Findings/month-wise-analysis.png">

<ul>
  <li>Day wise analysis: In weekends we can see the difference between casual and member is the least. This means that casual members use our services more in the weekends. </li>
</ul>
<img width="700" height="300" src="/Findings/day-wise-analysis.png">

<ul>
  <li>When we compare the bike stations that are frequently used by members and the casual users , we can identify a pattern where the stations used by casual users are nearby tourist attractions of Chicago. The stations used by members are near Universities , Working places and public tranit stations.</li>
  
</ul>
<img width="700" height="500" src="/Findings/freq-map.png">

