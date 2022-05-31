# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![ThisIsAnImage](https://github.com/nbhatia1014/MechaCar_Statistical_Analysis/blob/main/Images/Linear%20Regression.PNG)
Shown above is the resulting model we created to predict MPG.

![ThisIsAnImage](https://github.com/nbhatia1014/MechaCar_Statistical_Analysis/blob/main/Images/Statistical%20Results.PNG)
Shown above is the statistical summary of the model. Based on the summary, Vehicle_length, and ground_clearance are likely to provide non-random amounts of variance to the model.

Based on the pvalue, there is sufficient evidence to reject our null hypothesis. This indicates the slope is not zero.

The r-squared value signifies that approximately 71% of all mpg predictions will be determined by this model. In my opinion this does not effectively predict mpg.

## Summary Statistics on Suspension Coils
![ThisIsAnImage](https://github.com/nbhatia1014/MechaCar_Statistical_Analysis/blob/main/Images/Total_Summary.PNG)
Shown above is the total combined summary of the lots. The variance of 62.3 is within our 100 PSI range.

![ThisIsAnImage](https://github.com/nbhatia1014/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.PNG)
Shown above is the lots broken down. Lots 1 and 2 are well within our variance range with ~1 psi and ~7 psi variances.

## T-Tests on Suspension Coils

### Lot 1 T-Test
![ThisIsAnImage](https://github.com/nbhatia1014/MechaCar_Statistical_Analysis/blob/main/Images/Lot1_tTest.PNG)

### Lot 2 T-Test
![ThisIsAnImage](https://github.com/nbhatia1014/MechaCar_Statistical_Analysis/blob/main/Images/Lot2_Ttest.PNG)

### Lot 3 T-Test
![ThisIsAnImage](https://github.com/nbhatia1014/MechaCar_Statistical_Analysis/blob/main/Images/Lot3_T_test.PNG)

### All Lots T-Test
![ThisIsAnImage](https://github.com/nbhatia1014/MechaCar_Statistical_Analysis/blob/main/Images/All_lots%20T_test.PNG)

## Study Design: MechaCar vs Competition
1.) Metrics:
For this study, I would test the MechaCar's Selling Price vs the Competitors. It would test the following independent variables:
 - Safety Feature Rating,
 - Drive Package,
 - Engine Type,
 - Resale Value,
 - Average Annual Cost of Ownership, and
 - MPG.
 
2.) Null and Alternative Hypothesis:
- Null Hypothesis (Ho): MechaCar is priced correctly based on the performance of the key independent variables / metrics listed above.
- Alternative Hypothesis (Ha): MechaCar is not priced correctly based on the performance of key independent variables / metrics listed above.
   
3.) Statistical Test:
- Using a multiple linear regression model, the metrics that have the highest correlation/predicatability for Current Selling Price would be determined. It would let us know which variables / combination of variables has the greatest impact on price.
