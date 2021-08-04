<h2><u>CitiBike Data Visualisation</u></h2>

Utilizing the <a href="https://www.citibikenyc.com/system-data">raw data</a> from the CitiBike site, I have selected the time frame of 6 months, from July to December 2020 and combined the data.
From the dataset, there are data regarding the start and end stations details (Name, ID, and Geo Coordinates) and user details (user type, gender, trip durations, birth year)
6 months worth of data are combined to investigate the changes in trips recorded throughout.

<h4>Identify the most popular start and end stations</h4>
<img src="/snips/sStationsMap.gif" alt="" width="600" height="360">
<p>By identifying the most popular start and end stations, more bikes can be placed at the popular start stations as more users are likely to start their journey here. As for  the most popular end stations, as most bikes will be returned here, bikes can be retrieve from these stations and then return to the start stations if needed. 
By toggling the months, user can see each month's data according to the color scheme. From the provided snippet, those stations that are displaying the shade of Red are the more popular stations, whereas the cooler color (blue) are less popular. The following map shows the end stations location with their heat levels.
</p>
<img src="/snips/eStationsMap.JPG" alt="" width="600" height="360">

<h4>Identify the least popular start and end stations</h4>

 <tr>
    <td align="center"><img src="/snips/top10sstations.JPG" alt="" width="400" height="200" align="left"></td>
    <td align="center"><img src="/snips/least10sstations.JPG" alt="" width="400" height="200"></td>
  </tr>
<tr><td>The current problem is not knowing where to allocate bikes and where to collect them from. By Identifying the popularity of a Start and End station, the city can improve the availability of the bikes at the start station and know where to gather those that have been return and reallocate them for the next use.</td></tr>
 
 <hr>
  
 <tr>
    <td align="center"><img src="/snips/top10estations.JPG" alt="" width="400" height="200" align="left"></td>
    <td align="center"><img src="/snips/least10estations.JPG" alt="" width="400" height="200"></td>
  </tr>
   </tr>
<tr><td>Similarly, Start stations that are least popular should have less bikes allocated to them and there is no point to attempt to collect bikes from destinations that are not as popular. With these data, the city can also identify which stations are both popular start and end so the bikes can be returned by users instead of allocating resources to get the bikes back from one location to the other.</td></tr>
 

<h4>Identify if the age of the user correlates to usage duration</h4>
<p>When it comes to bike usage, the city needs to know which demography to target. One would think that the younger environmentally concious group will utilise bikes more than the older generation. Or would it be the older generation who are used to bikes?</p>
<img src="/snips/tripvage.JPG" alt="" width="600" height="360">


Identify if male users use the bikes more than female users

Identify the peak hours throughout the last 6 months of 2020

Identify which Bike needs more attention in Maintenance due to usage

Identify the legitimacy of users who are aged more than 100 years old

Checkout the Visualisations on <a href="https://public.tableau.com/views/Citibike_16277367443490/CitiBikeStory?:language=en-US&:display_count=n&:origin=viz_share_link"> Tableau here</a>



