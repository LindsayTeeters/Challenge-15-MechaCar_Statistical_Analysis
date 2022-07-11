# Challenge-15-MechaCar_Statistical_Analysis

  ## Overview

We are part of the data analytics team at AutosRUs. Upper Management needs some help with details on a special project. They need some analysis work done on the new prototype for their MechaCar. We have been asked to gather and deliver the following information:
  - Deliverable 1: Linear Regression to Predict MPG
  - Deliverable 2: Summary Statistics on Suspension Coils
  - Deliverable 3: T-Test on Suspension Coils
  - Deliverable 4: Design a Study Comparing the MechaCar to the Competition

---------------------------------------------------------------------------------------------------------------------------
  ## Linear Regression to Predict MPG


![Deliverable 1](https://github.com/LindsayTeeters/Challenge-15-MechaCar_Statistical_Analysis/blob/main/Resources/summary%20mpg%20vehicle%20lengthwidth.png)


Addressed Questions:

<b><I>1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?</I></b>
The ground clearance and vehicle length both would greatly affect miles per gallon. These two are non-random variables when considering mpg.

<b><I>2. Is the slope of the linear model considered to be zero? Why or why not?</I></b>
The slope of this linear model is not 0. The p-value is 5.35. Some of the variables drastically impact the miles per gallon of the vehicle.

<b><I>Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?</I></b>
Although its not 100%, this linear model is a good model to predict miles per gallon (mpg) or the MechCar prototupe. The R-squared is 0.7149, which is an adequate level to base the predicitons off of. 


---------------------------------------------------------------------------------------------------------------------------
  ## Summary Statistics on Suspension Coils
  
  <b><i>Total Summary</i></b>
  
  ![Total Summary](https://github.com/LindsayTeeters/Challenge-15-MechaCar_Statistical_Analysis/blob/main/Resources/Total_Summary.png)
 
 <b><i> Lot Summary</i></b>
 
  ![Lot Summary](https://github.com/LindsayTeeters/Challenge-15-MechaCar_Statistical_Analysis/blob/main/Resources/Lot%20Summary%20Table.png)

Addressed Question:

<b><I>1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?</I></b>
Looking at the overall summary table above, the suspension coils are well under the 100 pounds per square inch variance. However, looking at each lot line seperately, not all pass this requriement. Lot 3 exceeds the 100 pound limit by almost double the amount. This lot is pushing the overall variance higher. If this one was removed, it the other lots would fall much more inline. 

------------------------------------------------------------------------------------------------------------------------
## T-Tests on Suspension Coils

<b><i>T-Test #1</i></b>

![TTest1](https://github.com/LindsayTeeters/Challenge-15-MechaCar_Statistical_Analysis/blob/main/Resources/Lot%201%20T-test.png)

- Lot 1 T-test had a p-value of 1. This means that there is not enough evidence to reject the null hypothesis. The mean PSI is not statsistically different from the popuplation mean of 1,500 pounds per square inch. 

<b><i>T-Test #2</i></b>

![TTest2](https://github.com/LindsayTeeters/Challenge-15-MechaCar_Statistical_Analysis/blob/main/Resources/Lot%202%20T-test.png)

- Lot 2 T-test had a p-value of 0.06. This means there is enough to reject the null hypothesis. THe mean PSI is statistically different from the population mean of 1,500 pounds per square inch.

<b><i>T-Test #3</i></b>

![TTest3](https://github.com/LindsayTeeters/Challenge-15-MechaCar_Statistical_Analysis/blob/main/Resources/Lot%203%20T-test.png)

- Lot T-test had a p-value of 0.04. This means there is enough evidence to reject the null hypothesis. THe mean PSI is statistically different from the population mean of 1,500 pounds per square inch.

---------------------------------------------------------------------------------------------------------------------

## Study Design: MechaCar vs Competition

  Many other factors need to be tested in this prototype. Consumers do research and compare many different points when they go to buy a car. One of the most important features consumers took at is safety features or ratings. AutosRUs would should look at the ratings of competitor vehicle's to see how the prototype would be rated. Safety features such as crash test, airbag placement, and braking are just a couple variables. What speeds does the prototype holds stay whole before fracturing on impact? Or How many miles does the car travel when brakes are suddenly applied at certain speeds. What is the maintenance per mile for this prototype. 
  
  Looking at the safety ratings of MechaCar and similar competitors would give a good range for data. THe null hypothesis of the MechaCar would not have statistically higher safety ratings tham those of similar competitor vehilces. The alternative hypothesis would be that AutoRUs's Mechacar does have statistically higher safety ratings than similar competitors. This could be tested by a one-tailed t-test. This would then determine any differences between the safety feature groups in the comparisons. The data for this statistical test would be easy to get safety ratings of various features for the MechaCar and comparative models of competitors.

----------------------------------------------------------------------------------------------------------------------------
