# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
- When evaluating vehicles' MPG, it is evident that vehicle length and ground clearance provide a non-random amount of variance to mpg values in the dataset.
- The slope of the linear model is not zero. Because of the correlation between variables and performance, we see the trend as a sloped line.
- The linear model effectively predicts MPG performance effectively. Because we have significant variables/coefficients we are able to predict MPG with some degree of accuracy.

## Summary Statistics on Suspension Coils
The total summary table shows an acceptable level of variance overall.
https://github.com/jereediv/MechaCar_Statistical_Analysis/blob/main/Lot_Summary.png?raw=true
However, the lot summary table shows lot 3 to be unacceptable. Lot 1 and 2 (particularly lot 1) have a low enough variance to bring the total summary within the acceptable range.
https://github.com/jereediv/MechaCar_Statistical_Analysis/blob/main/Total_Summary.png?raw=true

## T-Tests on Suspension Coils
When looking at the T-test for the total sample, the mean is 1498.78. The P-value is slightly higher than .05 (.06) indicating that the mean, collectively is not far from the presumed mean of 1500. Therefore, we cannot reject the null hypothesis.
- Lot 1: With a mean of exactly 1500 and a P-Value of 1, this is by far the most consistent lot and is well within our standard.
- Lot 2: This lot has an insignificant P-Value of 0.6
- Lot 3: There is a significant P-value of 0.042 indicating a non-random difference. This lot is not within our acceptable limit.

## Study Design: MechaCar vs Competition
I would suggest a study that evluates metrics including fuel effeciency (hwy/cty), cost of maintenance, and safety ratings. These are important to most consumers when making a purchase decision. The null hypothesis is that there is no statistical difference between highway and city MPG. The actual hypothesis is that there is a statistical difference. A T-test would be a good approach because we are looking at two different variables against our sample. The data needed would be the MPG performance on the highway as well as in the city.