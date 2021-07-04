# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
![mecha lm](https://github.com/arelysrsd87/MechaCar_Statistical_Analysis/blob/main/Images/mecha_lm%20output.jpg)  
- The vehicle length, and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the model. As a result, the vehicle length and vehicle ground clearance have a significant impact on miles per gallon on the MechaCar prototype. Contrarily, the vehicle weight, spoiler angle, and All Wheel Drive (AWD) have p-Values that indicate a random amount of variance with the dataset.
- The p-Value for this model, 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis, which further indcates that the slope of this linear model is not zero.
- This linear model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. This multiple regression model does predict mpg of MechaCar prototypes effectively.
## Summary Statistics on Suspension Coils
![total summary](https://github.com/arelysrsd87/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.jpg)
![lot summary](https://github.com/arelysrsd87/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.jpg)  
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 
- When looking at the entire population of the production lot, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variance requirement. Similarly, Lot 1 and Lot 2 are well within the 100 PSI variance requirement: with variances of 0.98 and 7.47, respectively. However, Lot 3 shoows much larger variance in performance and consistency, with a variance of 170.29. 
## T-Tests on Suspension Coils
![mecha coil t-test](https://github.com/arelysrsd87/MechaCar_Statistical_Analysis/blob/main/Images/mecha_t_test.jpg)   
- The true mean of the mecha coil sample is 1498.78, which we also saw in the summary statistics above. With a p-Value of 0.06, which is higher than the common significance level of 0.05, there is NOT enough evidence to support rejecting the null hypothesis. In other words, the mean of all three of these manufacturing lots is statistically similar to the presumed population mean of 1500.
![lot 1](https://github.com/arelysrsd87/MechaCar_Statistical_Analysis/blob/main/Images/lot_1_t_test.jpg)   
- Lot 1 sample has the true sample mean of 1500. With a p-Value of 1, clearly we cannot reject the null hypothesis that there is no statistical difference between the observed sample mean and the presumed population mean (1500).
![lot 2](https://github.com/arelysrsd87/MechaCar_Statistical_Analysis/blob/main/Images/lot_2_t_test.jpg)    
- Lot 2 has essentially the same outcome with a sample mean of 1500.02, a p-Value of 0.61; the null hypothesis cannot be rejected, and the sample mean and the population mean of 1500 are statistically similar.
![lot 3](https://github.com/arelysrsd87/MechaCar_Statistical_Analysis/blob/main/Images/lot_3_t_test.jpg)   
- Lot 3 has the sample mean is 1496.14 and the p-Value is 0.04, which is lower than the common significance level of 0.05. All indicating to reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.
## Study Design: MechaCar vs Competition
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
- What metric or metrics are you going to test?
- What is the null hypothesis or alternative hypothesis?
- What statistical test would you use to test the hypothesis? And why?
- What data is needed to run the statistical test?