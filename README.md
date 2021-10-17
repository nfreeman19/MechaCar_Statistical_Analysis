# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![myTest](https://github.com/nfreeman19/MechaCar_Statistical_Analysis/blob/main/Images/Screen%20Shot%202021-10-15%20at%2012.42.27%20PM.png)

In the summary output, the Pr(>ltl) value for each of the coefficients represents that probability of a random amount of variance to the linear model. According to the results, ground clearance and mpg provided a non-random amount of variance to the mpg values in the dataset. The p-value of the linear regression regression model is 6.712e-11, which is smaller than the assumed significance level of 0.05% meaning that the slope of the linear model is not zero. In addition, the r-squared value of the linear regression model is 0.6791, meaning that roughly 68% of all predictions will be correct when using this model thus making it an effective predictor of mpg of MechaCar prototypes.

## Summary Statistics on Suspension Coils
### Total Summary:

![myTest](https://github.com/nfreeman19/MechaCar_Statistical_Analysis/blob/main/Images/Screen%20Shot%202021-10-16%20at%209.14.39%20AM.png)

### Lot Summary:
![myTest](https://github.com/nfreeman19/MechaCar_Statistical_Analysis/blob/main/Images/Screen%20Shot%202021-10-16%20at%209.14.51%20AM.png)

In the total summary, we found the mean, median, variance and standard deviation of the suspension coil’s PSI column. In the lot summary, we also found the mean, median, variance and standard deviation of the suspension coil’s PSI column, but it is separated by manufacturing lot. In total, the entire population of the production lot has a variance of 62.29 PSI, which is within the 100 PSI limit. However, when looking at each manufacturing lot individually, only Lot 1 (variance of 0.98 PSI) and Lot 2 (variance of 7.47 PSI) are within the 100 PSI limit as Lot 3 has a variance of 170.29 PSI. 

## T-Tests on Suspension Coils

### T-Test results across all manufacturing lots:

![myTest](https://github.com/nfreeman19/MechaCar_Statistical_Analysis/blob/main/Images/Screen%20Shot%202021-10-16%20at%209.49.15%20AM.png)

### T-Test results for each manufacturing lot:

![myTest](https://github.com/nfreeman19/MechaCar_Statistical_Analysis/blob/main/Images/Screen%20Shot%202021-10-16%20at%209.38.36%20AM.png)

Across all manufacturing lots, the mean of the sample is 1498.78. Also, the p-value is 0.06028, which is above the common significance level of 0.05, so there is not enough evidence to support rejecting the null hypothesis. When looking at each of the manufacturing lots individually, lot 1 has a mean of 1500 and a p-value of 1, lot 2 has a mean of 1500.2 and a p-value of 0.6072, and lot 3 has a mean of 1496.14 and a p-value of 0.04168. This analysis shows that the null hypothesis cannot be rejected in lot 1 and lot 2 but the null hypothesis should be rejected in lot 3. 

## Study Design: MechaCar vs. Competition 

An additional test that I would like to do is to compare the safety rating, horsepower and highway fuel efficiency of MechaCar against the competition. In this scenario, the null hypothesis is that the mean of the safety rating is zero and the alternative hypothesis is that the mean of the safety rating is not zero. Also in this scenario, using a multiple linear regression statistical summary would show how the variables impact the safety ratings for MechaCar and the competition. A random sample of MechaCar and their competitors would need to be collected including the safety ratings, highway fuel efficiency and horsepower for each. 

