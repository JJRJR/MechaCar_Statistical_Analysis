# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Vehicle weight, spoiler angle, and AWD all fell under the nonrandom amount of variance

![image](https://user-images.githubusercontent.com/108442512/196522387-5d93e2d1-8af1-4eb2-8ad6-4ab8a85a9d7f.png)

The p-value of our linear regression analysis is 5.35e-11, which is much smaller than our assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.

![image](https://user-images.githubusercontent.com/108442512/196525152-7b668b3f-2f4f-4167-a05d-7b3f95b99f76.png)

The R-squared value is 71%, which means approximately 71% of the time the model will predict MPG values correctly. There are probably other factors that were not captured in the dataset that contribute to the MPG variability of the MechaCar prototypes. There are variables unaccounted for here that contribute to MPG.

![image](https://user-images.githubusercontent.com/108442512/196534168-5c411b65-ef5e-4381-90ce-28523b8f477e.png)

## Summary Statistics on Suspension Coils

Lots 1 and 2 both meet the design variance of not exceeding 100 pounds per square inch with a variance of 0.98 and 7.5 respectively. Lot 3 did not meet the specifications with a variance result of 170.29

## T-Tests on Suspension Coils

Lots 1 and 2 are both statistically the same as the population means whereas Lot 3 is not, with a p-value of 0.04168. See the results below:

![image](https://user-images.githubusercontent.com/108442512/196555588-5f349a8f-fbb8-4198-9102-1f09c43f8038.png)

![image](https://user-images.githubusercontent.com/108442512/196555758-a8b92d95-7ff5-4b0d-b261-dc359c606b76.png)

![image](https://user-images.githubusercontent.com/108442512/196555812-8027dfd1-7d54-4d93-816d-deb19c9440c3.png)

![image](https://user-images.githubusercontent.com/108442512/196555860-d257df15-8e40-4ca1-9287-ef69dc4be04c.png)

## Study Design: MechaCar vs Competition

A large amount of the workforce is leaving the offices and working from home now. Consumers may be turning in their fuel-efficient cars for more of a luxury experience due to a lower amount of travel distance. The null hypothesis would be "Have more luxury vehicles been sold in 2021 than in previous years?" and the alternative hypothesis is that luxury cars did not sell more in 2021 than in previous years. The metrics used would be type of luxury car, the number of luxury cars sold and the year they were sold in. I would use an ANOVA test to compare the means between all the years to determine the average amounts sold for each year.


