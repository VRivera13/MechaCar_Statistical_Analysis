# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

> The variables that provided a non-random amount of variance were vehicle Weight, spoiler angle, and AWD.

* Is the slope of the linear model considered to be zero? Why or why not?

> The slope of the linear model is not zero as the p-value is 5.35 x 10^11.  The given p-value is smaller than the significance level of 0.05%

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

> Being the R-squared value is 71% this would indicate that the time model will predict the mpg value correctly 71% of the time.

## Summary Statistics on Suspension Coils

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

> The current data reflects that only Lots 1 and 2 meeting the design specifications as their variances are below the requirement.    Lot 3 unfortunately exceeds the design specification exceptionally.    With regards to the lots in total, they would meet the design specificaiton as a whole.

## T-Tests on Suspension Coils

* For lots 1 and 2,  the PSI values are similar to  the population mean. However for lot 3 the p-value is .042 which means there is evidence that the suspension coil varies from the population mean. All t-tests can be seen below:

### All Lots:
![all lots](https://github.com/VRivera13/MechaCar_Statistical_Analysis/blob/main/images/Across%20all%20lots.PNG)
### Lot 1:
![lot1](https://github.com/VRivera13/MechaCar_Statistical_Analysis/blob/main/images/Lot%201.PNG)
### Lot 2:
![lot2](https://github.com/VRivera13/MechaCar_Statistical_Analysis/blob/main/images/Lot%202.PNG)
### Lot 3:

## Study Design: MechaCar vs Competition

>When purchasing a vehicle, people tend to look at the city/highway fuel efficiency.   Cost, fuel efficiency, and safety rating seem to be top items the public looks for when deciding to purchase a vehicle.  To compare the MechaCar to the competition, tests should be conducted on these factors to put together a valuable compare. A null hypothesis would outline if that the MechaCar is not different from the competition and the alternative hypothesis would provide the opposite result. We would need to collect data from an assortment of competitor vechiles to conduct t-teststo compare the population  of the selected types of competitor vehicles.
