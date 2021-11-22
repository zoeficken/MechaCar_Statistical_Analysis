# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="679" alt="Screen Shot 2021-11-21 at 5 35 28 PM" src="https://user-images.githubusercontent.com/88108455/142781621-89d1446b-5222-4cb8-a00c-ac850441d35a.png">

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

- Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. 

Is the slope of the linear model considered to be zero? Why or why not?

- No, the slope is not zero because the p-value is less than 0.05.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

- Since the r^2 value is 71.5%, that means that the model will predict mpg values correctly about 71.5% of the time. This would be mildly effective.

## Summary Statistics on Suspension Coils

Total Summary Table:

<img width="338" alt="Screen Shot 2021-11-21 at 7 21 03 PM" src="https://user-images.githubusercontent.com/88108455/142785068-6400cca4-26ba-47de-b0ff-fcb320e9813b.png">

Lot Summary Table:

<img width="489" alt="Screen Shot 2021-11-21 at 7 22 01 PM" src="https://user-images.githubusercontent.com/88108455/142785101-7b38460b-9be4-472d-88d7-450a273c8b00.png">

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

- I think the current manufacturing data meets the design specification for Lot 1 and Lot 2. They have an extremely similar median and mean. Lot 3 exceeds the specifications due to its variance.

## T-Tests on Suspension Coils

<img width="510" alt="Screen Shot 2021-11-21 at 7 34 09 PM" src="https://user-images.githubusercontent.com/88108455/142785620-f6c3cd81-8dfd-4f16-aa4b-86c0d552c9af.png">
<img width="510" alt="Screen Shot 2021-11-21 at 7 34 25 PM" src="https://user-images.githubusercontent.com/88108455/142785624-00afecbb-9858-4e55-80f8-3cee499134b0.png">

From the above data, we can see that the true mean of the sample. The mean of all 3 of the lots is statistically similar to the presumed mean of 1500:
- Lot 1 has a true sample mean of 1500
- Lot 2 has a sample mean of 1500.2
- Lot 3 has a sample mean of 1496.14 and p-value < 0.05. Here we can reject the null hypothesis.

## Study Design: MechaCar vs. Competition

What metric or metrics are you going to test?

- Cost of vehicle

What is the null hypothesis or alternative hypothesis?

- MechaCar is reasonably priced compared to its competitors. 

What statistical test would you use to test the hypothesis? And why?

- I would use multiple linear regression to accurately portray the factors that predict the selling price of MechaCar.

What data is needed to run the statistical test?

- Prices of competing vehicles
