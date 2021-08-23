<h3>Tableau Demo - CitiBike Data Visualisation</h3>
<hr>

Utilizing the <a href="https://www.citibikenyc.com/system-data" target="_blank">raw data</a> from the CitiBike site, I have selected the time frame of 6 months, from July to December 2020 and combined the data.
From the dataset, there are data regarding the start and end stations details (Name, ID, and Geo Coordinates) and user details (user type, gender, trip durations, birth year)
6 months worth of data are combined to investigate the changes in trips recorded throughout.

<h3>Identify the most popular start and end stations</h3>
<img src="/snips/sStationsMap.gif" alt="" width="650" height="360">
<p>By identifying the most popular start and end stations, more bikes can be placed at the popular start stations as more users are likely to start their journey here. As for  the most popular end stations, as most bikes will be returned here, bikes can be retrieve from these stations and then return to the start stations if needed. 
By toggling the months, user can see each month's data according to the color scheme. From the provided snippet, those stations that are displaying the shade of Red are the more popular stations, whereas the cooler color (blue) are less popular. The following map shows the end stations location with their heat levels.
</p>
<img src="/snips/eStationsMap.JPG" alt="" width="650" height="360">

<h3>Identify the least popular start and end stations</h3>

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
 

<h3 id="mentioned">Identify if the age of the user correlates to usage duration</h3>
<p>When it comes to bike usage, the city needs to know which demography to target. One would think that the younger environmentally concious group will utilise bikes more than the older generation. Or would it be the older generation who are used to bikes?</p>
<img src="/snips/tripvage.JPG" alt="" width="650" height="360">
<p>However when the 6 months worth of data is visualised, we can see that users at the age of 52 are using the bikes the most (over 1.4 Million trips over the last 6 months) with trips averaging at 36 minutes. Interestingly, there is another age group that draws our attention here. Yes they are those of 78 and above. In the data itself, there are even users who are more than 100 years old. We will present our findings later in the <a href="#legit_age">following section</a>.</p>

<h3>Identify if male users use the bikes more than female users</h3>
<p>When it comes to gender, similarly to age of the user, the city can use this data to target the gender that they want to promote the bike services to. It is most likely speculated that men uses the bikes more due to the logistics of their attire and hair styles. </p>
<img src="/snips/tripDurationvGender.JPG" alt="" width="650" height="360">
<p>Upon exploring the data, the hypothesis is true with the Male Gender utilising the services more than females. The highest record was in September 2020 with more than 1.4 Million trips taken with a total duration count of 28 Million minutes. At the same month, Female users ae only accounted to almost half of the male users at less than 750,000 users. Perhaps the city can redesign the bikes to be more gender neutral or utilise advertising materials with women coming off bikes, taking their helmet off and doing the slow-mo hair flips.</p>

<h3>Identify the peak hours throughout the last 6 months of 2020</h3>
Will the busiest time for bike use be in the mornings where users rush to work? It would be too tiring to ride a bike after 8 hours of work I assume.
<img src="/snips/peakhours.JPG" alt="" width="650" height="360">
Looking at the visualised data, nothing screams relief and excitement when an employee gets to leave the office at the end of the day - This can be verified by Fred Flintstone's iconic <a href="https://www.youtube.com/watch?v=qpGx4foRdPw" target="_blank">"Yabba-Dabba-Doo"</a>. We can see that the peak hours are mostly around "Home time" although trips did spike during the early mornings.
Nearing the holiday month (December), the peak time was earlier as employees are likely to be allowed to finish work earlier.

<h3>Identify which Bike needs more attention in Maintenance due to usage</h3>
Visualising the Bike ID with the trips recorded, the city can better use this data to focus on Bikes that are frequently used in order to run regular maintenance on them.
Parts such as the chains, tyres and brakes can wear out overtime and it is best to use this data to pay attention to those bikes that have been frequently used. 
<img src="/snips/bikemaintenance.JPG" alt="" width="650" height="360">
The city can also forecast the parts required to be ordered by knowing when and which bikes to service. Some bikes require more attention on certain months so its good to not only focus on the most used bikes in the fleet.

<h3 id="legit_age">Identify the legitimacy of users who are aged more than 100 years old</h3>
Coming back to this phenomenon as mentioned <a href="#mentioned">previously</a>. We see users who are more than 80 years old using the bikes and they use it at a duration longer than users at 52 years of age (With almost up to an Hour of usage). Is Biking the answer to stay Youthful and prolong life? Or are there users who do not want to reveal their age due to privacy?
If the user's age are legitimate, it could mean a few things, either they are slower to get to their destination due to their age, stopped for a long time, or just superly active with their 1 hour Cardio on bikes. 
<img src="/snips/fakeageuser.JPG" alt="" width="650" height="360">
Seeing how active the "Elderly" are, we wanted to find out if their registered age is true, as there are users whose 121 year old and actively using a bike.
We have filtered down users who are not subscribers and have not registered their Gender and Age properly, this way we can protect the assets (Bikes) knowing which bike they use and where they have travelled to.






<br><br><br><br><br>
Checkout the Visualisations on <a href="https://public.tableau.com/views/Citibike_16277367443490/CitiBikeStory?:language=en-US&:display_count=n&:origin=viz_share_link" target="_blank"> Tableau here <br>
<img src="/snips/story.gif" alt="" width="600" height="454"></a> 




