# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

### Coefficients 
![Co_1](https://user-images.githubusercontent.com/88383836/145416170-1c81e33a-9f95-473f-9267-82d84b813da5.PNG)

•	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

-The  dependent variables that provided non-random amounts of variance were vehicle length, ground clearance, and AWD. The coefficients for these variables had no exponents which makes the range of values less random than the other variables. 

### P-Value & R^2
![Pval_R2_1](https://user-images.githubusercontent.com/88383836/145416030-2173f742-7be7-4623-a07f-553d1fb78da7.PNG)

•	Is the slope of the linear model considered to be zero? Why or why not?

-No, according to the p-value (5.35e-11) there is a significant trend in the data. This p-value is way below the .05 (5 in 100) possibility of no correlation. 

•	Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

-The linear model predicts a moderate to strong strength in correlation based on the r-squared value of .7149. This states that roughly 72% of the time these factors will impact a MechaCars mpg. 

## Summary Statistics on Suspension Coils 

### Lot 3 Variance & Standard Deviation
![Lot_3_2](https://user-images.githubusercontent.com/88383836/145416399-5a7c79d6-54a9-4912-8551-5d93ef599def.PNG)

•	The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

-The data shows all lots have a similar mean and median of values that meet the criteria of the design specifications for MechaCar. Further breakdown of each individual lot shows that Lot 3 has very high variance and standard deviation values. This can present inconsistencies with compliance to overall satisfactory with design specifications. 

## T-Tests on Suspension Coils 

### Test: Determine if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.

### All Lots
![All_Lots](https://user-images.githubusercontent.com/88383836/145436798-14d12a9a-7b47-4eb6-a4db-b7d06119fe9e.PNG)

### Lot 1
![Lot_1](https://user-images.githubusercontent.com/88383836/145436469-dca70f7f-7240-4795-9246-6662f08d0963.PNG)

### Lot 2 
![Lot_2](https://user-images.githubusercontent.com/88383836/145436857-4159e9b3-3e31-496b-9bdb-f5f42afb129c.PNG)

### Lot 3
![Lot_3](https://user-images.githubusercontent.com/88383836/145436903-e777b234-a155-4a7f-bfd5-50601f5c4fed.PNG)

### Results Summary
•	Lot 3 has a p-value of .04168. This details that there is a significant statical correlation between PSI and population mean of 1500 pounds per sq. inch. Lot 1 & 2 have high p-values indicating that PSI and population mean have little to no correlation. 

 ## Study Design: MechaCar vs Competition
 
Adding location type as a metric would provide substantial insight about competition. Evaluating data based on what type of area you live in (rural, suburban, and urban) would give more insight on which cars work efficiently and where. The null hypothesis to  evaluate location and efficiency would be; if we have the same car in any location type, then there will be no difference in efficiency metrics such as mpg. The alternative hypothesis would be; if we have the same car in any location type, then efficiency metrics like mpg will show a change. A linear model can evaluate the same car and based on location the car is used in we can view all the coefficients that factor into fuel efficiency. The data necessary to conduct this test would involve location of the car in use and more data than just mpg to evaluate efficiency, for example, maintenance costs. 
