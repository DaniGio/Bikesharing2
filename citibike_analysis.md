# NYC Citi Bike Analysis

This is a summary of the analytic work that I did with the NYC Citi Bike data, to understand how it can be applied for the city of Des Moines.

## Bike hider gender overview  
This analysis is focus to respond questions related to gender: 

What is the gender diversity of Des Moines? How does it compare to the gender diversity of New York City? What effect does it have on possible business in Des Moines?

### Analysing gender information
When analysing the NYC Citi Bike data it is possible to see that 81% of the users are subcriber, that means that they have individual users with an account.
19% of the data is Customer - those can be turists or someone that don't rent those bikes very often. One person can have multiple custormer id, so for this analysis we will be focusing more on the subscriber information.

- ![alt text](https://github.com/DaniGio/Bikesharing2/blob/master/Pic/Type%20of%20customer.png)

In the subscriber group, 72 % are male, 26% female and 2% unkown. This shows that the majority of the subscriber users are male.

- ![alt text](https://github.com/DaniGio/Bikesharing2/blob/master/Pic/Type%20and%20Gender.png)

To understand how is the gender distribution in NY, if they have more males than female there, and that is why we have more male users, it was investigated in the 2019 Census. Census shows that 52,3 % are famale in NY and 50,8% are female in Des Moinses. This shows that both cities have more females than male, and eventhoug we have more males bikers. 

- ![alt text](https://github.com/DaniGio/Bikesharing2/blob/master/Pic/Census.png)

Further investigations needs to be conduct to better understand, but at this stage the analysis shows a high indicative that the behaviour could be the same in Des Moines. 
This means that even though Des Moines has a little bit more female than male, the main target user will be males that comute to work with a bike between 8-9 am and that commutes back home around 5 and 6 pm for less than 25 min of durantion/ distance. 
To visualise the avarage durantion per age some ouliers were removed, such as born year before 1940, and extremelly high durantion.

- ![alt text](https://github.com/DaniGio/Bikesharing2/blob/master/Pic/Dashboard.png)

Also it is important to notice that the % of female riders customers increase among people that were borned in 2000 (The Millenials). Additional researches shows that Millennials are Flocking to Des Moines, what can be a good opportunity and a possible target group, if we would like to increase female riders as subscribers.

[additional source] (https://livability.com/ia/des-moines/where-to-live-now/heartland-hotspot-why-millennials-are-flocking-to-des-moines)

- ![alt text](https://github.com/DaniGio/Bikesharing2/blob/master/Pic/Milleniums%20numbers.png)

It would be interesting to understand which suburbs are in the radius of 20-25 min from des moines city, if the people in this radius have cars and how is parking in the city, how is public transportation, etc

### Analysing a possible heatmap area in Des Moines
If analysing the NY heatmap area for the busiest places to start and to finish a bike trip it is possible to see a correlation to the McDonalds locations.

- ![alt text](https://github.com/DaniGio/Bikesharing2/blob/master/Pic/Heatmap%20and%20McDonalds.png)

If we consider that the same behaviour is expected in Des Moines, the heatmap for the busiest locations will be as McDonalds locations below.

- ![alt text](https://github.com/DaniGio/Bikesharing2/blob/master/Pic/Mcdonalds%20distribution%20in%20DesMoines.png)

Considereing the 20-25 min radius analised previusly with the trip duration dashboard, the orange dots would be inside the heatmap radius

- ![alt text](https://github.com/DaniGio/Bikesharing2/blob/master/Pic/Distance.png)

### Next Steps
It would be interesting to understand which suburbs are in the radius of 20-25 min from des moines city, if the people in this radius have cars and how is parking in the city, how is public transportation, etc

For more information, please visit the dashboard and stories below:

-[link to dashboard](https://public.tableau.com/profile/danigio#!/vizhome/Module14_black_15872127517640/LocationHeatmapandMCDonaldsdashboard?publish=yes)

*Dashboards tabs are called: NYC Citi Bike Dashboard and Location Heatmap and MC Donalds dashboard
*Story can be found in the Story tab 1 and 2