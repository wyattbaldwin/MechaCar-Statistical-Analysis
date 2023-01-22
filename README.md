# MechaCar Statistical Analysis
## Purpose

The purpose of this analysis is to understand how different factors affect the miles per gallon (MPG) of the MechaCar prototype. This includes looking at how vehicle length, weight, spoiler angle, ground clearance, and whether or not it is all-wheel drive (AWD) affect the MPG. Additionally, we will be analyzing the suspension coils of the MechaCar prototypes to understand the variance and if it meets design specifications. By understanding these factors, we hope to help the manufacturing team overcome any issues they may be facing and make suggestions for future studies to compare the MechaCar to other vehicles on the market.

## Linear Regression to Predict MPG

We used a linear regression model to predict the MPG of MechaCar prototypes based on different variables. The results show that vehicle length and ground clearance have the biggest impact on MPG. The slope of the model is non-zero, which means that as certain variables increase or decrease, the MPG will also change. However, we do not have enough evidence to say that all variables have an impact. Overall, the model is able to effectively predict MPG with an R-squared value of 0.71, which means that 71% of the variation in MPG can be explained by the variables in the model.

<img src="https://github.com/wyattbaldwin/MechaCar_Statistical_Analysis/blob/main/Images/1.png?raw=true">

## Summary Statistics on Suspension Coils

The MechaCar prototypes have design specifications that the variance of the suspension coils must not exceed 100 PSI. When looking at all manufacturing lots together, the variance meets this specification at 62.29 PSI. However, when looking at each lot individually, not all lots meet this specification. Lot 1 and Lot 2 meet the specification, but Lot 3 does not with a variance of 170.29 PSI.

<img src="https://github.com/wyattbaldwin/MechaCar_Statistical_Analysis/blob/main/Images/2.png?raw=true">

<img src="https://github.com/wyattbaldwin/MechaCar_Statistical_Analysis/blob/main/Images/3.png?raw=true">

## T-Tests on Suspension Coils

We also conducted t-tests to compare the PSI of the MechaCar prototypes to a population mean of 1500 PSI. The results show that the PSI of all manufacturing lots and Lot 1 are not statistically different from the population mean, but Lot 2 and Lot 3 are. This means that the PSI of Lot 2 and Lot 3 is significantly different from the population mean.

<img src="https://github.com/wyattbaldwin/MechaCar_Statistical_Analysis/blob/main/Images/4.png?raw=true">

Overall, the analysis shows that vehicle length and ground clearance have the biggest impact on the MPG of the MechaCar prototypes. Additionally, the variance of the suspension coils in Lot 3 does not meet design specifications and the PSI of Lot 2 and Lot 3 is significantly different from the population mean. These findings can help the manufacturing team overcome any issues they may be facing and suggest areas for future studies.
