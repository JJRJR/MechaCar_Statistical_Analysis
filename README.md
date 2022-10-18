# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehicle weight, spoiler angle, and AWD all fell under the non random amount of variance

![image](https://user-images.githubusercontent.com/108442512/196522387-5d93e2d1-8af1-4eb2-8ad6-4ab8a85a9d7f.png)

- Is the slope of the linear model considered to be zero? Why or why not?

the p-value of our linear regression analysis is 5.35e-11, which is much smaller than our assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.

![image](https://user-images.githubusercontent.com/108442512/196525152-7b668b3f-2f4f-4167-a05d-7b3f95b99f76.png)


- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The R-squared value is 71%, which means approximately 71% of the time the model will predict MPG values correctly. There are probably other factors that were not captured in the datasaet that contribute to the MPG variability of the MechaCar prototypes. There are variables unaccounted for here that contribute to MPG.

![image](https://user-images.githubusercontent.com/108442512/196534168-5c411b65-ef5e-4381-90ce-28523b8f477e.png)
