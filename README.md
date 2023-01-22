# MechaCar Statistical Analysis
AutosRUs' new prototype, the MechaCar, is having trouble with production and they're using data from the production process to figure out what's causing the issue. They're using a math technique called linear regression to predict the car's miles per gallon, but it's not working well because there are other factors that are affecting the car's miles per gallon that they haven't taken into account yet.

## Linear Regression to Predict MPG
The linear model used to determine the statistical difference in each variable is shown in Figure 1. The intercept, ground clearance, and vehicle length were the lowest possibility to provide a non-random amount of variance to the mpg values in the dataset as shown in Figure 2. The slope of the linear model is not considered to be zero. It is impossible to create a graph due to the number of variables used and dimensions. They are impossible to plot more than 3 variables, which this model has, on a graph. This linear model does not predict mpg of MechaCar prototypes effectively. This is due to the fact that the intercept is statistically significant. When a intercept is statistically significant, there are other variables and factors that are statistically significant that has not been included in the model.

<img src="1">

Figure 1. Data output of generate multiple linear regression model

<img src="2">

Figure 2. Data output of generated summary statistics

## Summary Statistics on Suspension Coils
The standards for the MechaCar suspension coils is that it must not exceed 100 pounds per square inch. In the total lots, the current manufacturing data meet the design specification as shown in Figure 3. However, not all of the lots meet this standard. As shown in Figure 4, Lot 1 and Lot 2 meet this standard. Lot 1 has a variance of 0.9796 pounds per square inch and Lot 2 has a variance of 7.469 pounds per square inch. Lot 3 has a variance of 170.28 pounds per square inch. In the data for Lot 3, there is a lot more variance in the data than Lot 1 and Lot 2.

<img src="3">

Figure 3. Total Summary of the Suspension_Coil.csv to get mean, median, variance, and standard deviation of the suspension coil's PSI column.

<img src="4">

Figure 4. Each manufacturing lot summary table showing the mean, median, variance, and standard deviation of suspension coil's PSI column

## T-Tests on Suspension Coils
For the PSI across all manufacturing lots is not statistically different from the population mean of 1,500 pounds per square inch as shown in Figure 5. Assuming that the significance level was the common 0.05 percent for all of the t-tests, our p-value is 0.05734 which means the p-value is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and that the two means are statistically similar.

<img src="5">

Figure 5. the PSI across all manufacturing lots is statistically different from the population mean of 1,500 pounds per square inch

For the PSI for Manufacturing Lot 1 is not statistically different from the population mean of 1,500 pounds per square inch as shown in Figure 6. The p-value for Lot 1 is 0.9982 which is above significance value. Therefore, we do not have sufficient evidence to reject the null hypothesis, and that the two means are statistically similar.

<img src="6">

Figure 6. Manufacturing lot 1 is statistically different from the population mean of 1,500 pounds per square inch

For the PSI for Manufacturing Lot 2 is not statistically different from the population mean of 1,500 pounds per square inch as shown in Figure 7. The p-value for Lot 2 is 0.6115 which is above significance value. Therefore, we do not have sufficient evidence to reject the null hypothesis, and that the two means are statistically similar.

<img src="7">

Figure 7. Manufacturing lot 2 is statistically different from the population mean of 1,500 pounds per square inch

For the PSI for Manufacturing Lot 3 is statistically different from the population mean of 1,500 pounds per square inch as shown in Figure 8. The p-value for Lot 3 is 0.01 which is below significance value. Therefore, we have sufficient evidence to reject the null hypothesis, and that the two means are statistically different.

<img src="8">

Figure 8. Manufacturing lot 3 is statistically different from the population mean of 1,500 pounds per square inch

From the results of these tests, it can be seen that Lot 3 does not meet the design specifications for the suspension coils and may be causing issues with the MechaCar's production. Further investigation and analysis should be done on Lot 3 to determine the root cause of the problem and find a solution.

To further investigate the problem with the suspension coils in Lot 3, we can conduct additional statistical tests and analysis to identify which specific variables and factors are causing the high variance in the data. We can also gather more data on the manufacturing process of Lot 3 to see if there are any discrepancies or issues that are causing the deviation from the design specifications. Additionally, we can compare the data from Lot 3 to the data from Lot 1 and Lot 2 to see if there are any notable differences in the manufacturing process or materials used.

It is also important to keep in mind that this analysis is only one aspect of the problem and there may be other factors contributing to the MechaCar's production issues. Therefore, it is essential to conduct a comprehensive examination of all aspects of the manufacturing process and gather data from various sources to fully understand the issue and find a solution.



