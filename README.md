# PyBer Analysis 

## Goal
The goal of this project is to analyze ride sharing data to determine where the business is most profitable and help with business decisions regarding allocation of company resources. The fist step of this analysis is to get a summary of the data sorted by the types Rural, Urban, and Suburban. Within the new summary we will look at the; Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per driver in the respective types.

### Process
1. Use the merged data from city_data.csv and ride_data.csv.
2. Create a summary data frame for Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per driver.
3. From the new summary data frame create pivot table.
4. Change the data type using .index to date time.
5. Create a new data frame using resample() to get the sum of the fares for each week.
6. Create a visualization of the new data frame to show the sum of fares by city type between January 1st, 2019 to April 29th, 2019.

#### Results
![PyBer_Summary_df.PNG](https://github.com/mselover21/PyBer_Analysis/blob/main/analysis/PyBer_Summary_df.PNG)

Looking at the Pyber Summary we can see that there is a trend amongst all the data. Rural has the least of all the categories from Total Rides to Average fare per driver. The opposite can be said about Urban, which has the highest totals of all the categories from Total Rides to Average Fare per driver. While Suburban is in between both Rural and Urban. 
1. Urban by far has the most Total rides with 1,625, Suburban has 625, and Rural with the least 125. This is expected due to population density of cities versus rural communities.
2. Again Urban has the most Total Drivers with 2,405, Suburban has 490, and Rural has 78. This is aslo an expected result due to population density of cites vs rural areas.
3.Urban makes the most Total Fares with $39,854.38, Suburban has about half the Total Fares of Urban with $19,356.33, and Rural has the least with $4,327.93. This is an expected result due to the respective results for Total Rides and Total Drivers for the three City Types.
4. Rural has the highest Average Fare per Ride however with $34.62, Surburban has an average of $30.17, and Urban has the lowest with $24.53. This information makes sense due to Rural having fewer drivers which would increase the rate per ride due to less drivers. Also Urban has a much higher amount of drivers than the other two types meaning that fares would be lower.
5. Rural has a much higher Average Fare per Driver with $55.49, Suburban has an average of $39.50, and Urban has the least with $16.57. Again due Rural having less drivers and Urban having the highest it makes sense that the Average Fare per Driver would be so high and low respectively.

![Total_Fare_by_City_Type_Plot.PNG](https://github.com/mselover21/PyBer_Analysis/blob/main/analysis/Total_Fare_by_City_Type_Plot.PNG)

When looking at the data by week there are a few takeaways that can affect how we make decisions to positivly effect the business.
1. Urban cities have a gradual increase from January to the end of February. While March has a pateren of increase and decreasing on a weely basis.
2. Suburban tells a more interesting story having a relative increase from January to the end of Februrary. There is a sharp increase at the end of February and a sharper decrease at at the beggining of March.
3. Rural citites have a more gradual increase through the months of January to April. It also shares the same spike at the end of February as Urban and Suburban communities.

##### Summary
The ride share data we have tells a very interesting story. There are three things that we can do that will positivly effect our busisness. Due the increases for all three city types at the end of Februrary I feel we should increase the fares during that time since it does show to be a peak time for our busisness for all city types. I also feel that we may want to offer discounts on fares for all three city types during the month of March. This will help promote more use of our companies ride shares and help increase the total fares for the month of March. The last recommendation I have is to reduce the fare cost for Rural cities. Due to the average fare being the highest it could help increase the use of our ride shares in rural communities by offering rides at a discount. Overall the data tells us a very interesting story and will help us make posititve business solutions in the future.
