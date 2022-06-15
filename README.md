# Mechacar_stastical
# Linear Regression to predict MPG
-	 We designed a linear Regression model the mpg of MechaCar prototype using variable vehicle weight, length, spoiler angle, ground clearance, AWD. Using those variables we got this output. 
 ![Linear Regression deliverable](https://user-images.githubusercontent.com/99147715/173736983-f2427ff7-3cf3-4494-939a-401d313faf0e.PNG)
-	The variables that provide nonrandom amount of variance where the vehicle weights and ground clearance.
-	The slope of the regression is not zero because the p value is less than .05 proving that data is significant and corelates to effect of MPG. 
-	The r-squared provided .7149 means that there is a 71.49 percent that the data point will fall in line with the model we create. 
# Summary Statistics on suspension coil 
For deliverable 2 we created a summary of the suspension coils across all lots. The MechaCar Suspension coil says that variance of will never go above 100.00 PSI. The data gathered from lots 1, 2, and 3 according to the data we gathered lots 1 and 2 meet the specification, but lot 3 does exceed it with a variance greater than 100.00 with variance of 170.00. Lots 1 and 2 both share the median psi of 1500.00 which matches the median psi 1500.00. 
 ![Total_summary](https://user-images.githubusercontent.com/99147715/173737031-91bf0224-0d9a-4b8d-8375-40acd4ead334.PNG)
![manufacturing lot](https://user-images.githubusercontent.com/99147715/173737056-4a5de430-6499-439f-98a9-26941aa0c917.PNG)
# T_test suspension 
       For deliverable 3 we performed a T-test to see if each lot is statistically different for all lots from a mean of 1500.00. Our null hypothesis is that there is not statistical difference and alternate hypothesis. From the t_test we gathered that lots 1 and 2 are not statistically different with p-values of 1 and .602. Lot 3 although is statistically different with a p-value .041. 
![T_test lot1](https://user-images.githubusercontent.com/99147715/173737082-67f03a0d-595d-499a-9a32-46fa577baeed.PNG)

![T_test lot2](https://user-images.githubusercontent.com/99147715/173737095-49c1c6ab-8140-4951-910f-dccf75fbbd8a.PNG)

![T_test lot3](https://user-images.githubusercontent.com/99147715/173737142-17cccd28-eb5f-4394-97d5-fca4b8c3ca4b.PNG)

# Study Design
In order to do a test to perform a study between the prototype and the competition we can use cost of maintenance to test between the two products. Since MPG, reliability, and maintenance are major factors in car buying. We can make a null hypothesis stating that that pricing is either the same or more expensive.  To do this we can run a t-test along with a normal linear regression to get the R squared. 

