# Ehsan Tabatabaie | Engineering Portfolio

## A Bracket for a Toy car

In this page I am demonstrating the steps I took to design a bracket of toy car.
The bracket will connect two spring to the the wheels providing flexibility.

![Bracket_generated-image](Bracket_generated-image.png)

## Design considerations
Here are the design considerations and rquirement for this part. The goal was to creat the most effective design approache. Since there is no aesthetic consideration form customer.
The goal is to reduce weight and as a result cost and a higher cutomer satifaction.
- Each spring will apply load of 10kgf at most
- Minimume Factor of Safety 2 should be impelented
- Materila: AL-Alloy 1060
- The car has an Electric motor with MAX RPM 1500
- Two months warranty


| Initialy with consideration of the location of connection and the direction of the spring of the car, an outline created  | The basic raw design was a rectangular block with thickness of 10 mm here is theFEA simulation result| 
| :---: | :---: |
|![Bracket_01_01](Bracket_01_00.PNG)| ![Bracket_01_01](Bracket_01_01.PNG)|

Regardless of the statuse of the Yield point, the stress distribution shows the area of the plate that endur stress .

| Area of the initial bracket that take the stress  | Implementing the design updated using stress distribution diagram | 
| :---: | :---: |
|![Bracket_01_02](Bracket_01_02.PNG)| ![Bracket_01_03](Bracket_01_03.PNG)|

Here by adding the area that participates in the stress and removing the area without participation the part with most contribution to the loads is created.
The next step was since the innitial desing has much higher strength with FOS of around 30 by reducing the thickness to 5mm the better version created.
| Resultant Bracket and reducing the thickness to 5 mm reducing the weight  | FEA results for the factor of safety | 
| :---: | :---: |
|![Bracket_01_04](Bracket_01_04.PNG)| ![Bracket_01_05_Tto5](Bracket_01_05_Tto5.PNG)|

Next step was to remove the area with lower participation in the load distribution.
On the left side result of stress distribution for thenew design demonstrated the are that can be removed withing acceptable range.
Looking at yeild strenght the thiness reduced to 3 mm. For this step since the connection of the spring has limitations the area around the spring connection has bushing preserving the thickness and guiding pins for the springs.
The right side demonstrate stress distribution for the updated design shwoing the are with higher sress concentration. It is important to observe that the sress distribution is changing with change of the geometry.

| FEA Stress result of 1st improvement | FEA results for the improved version | 
| :---: | :---: |
|![Bracket_01_06](Bracket_01_06.PNG)| ![Bracket_01_07](Bracket_01_07.PNG)|

The left side figure demonstrate the area of the design that endure stress value abouve the 10 times yield strenght. the right side figure demonstrate the improved version boundign the stres to about FOS of 10 (8.9).

| FEA Stress result  | FEA results for the improved version | 
| :---: | :---: |
|![Bracket_01_08](Bracket_01_08.PNG)| ![Bracket_01_09](Bracket_01_09.PNG)|

Reducing the thickness of the material from 3mm to 2mm improve weight lost in the materal by anout 30%. further weight lost achived by moving the area between the two spring connector. On the right side the updated version with FOS of 3 achived. 
| FEA Stress result to 2 mm | FEA results for the improved version | 
| :---: | :---: |
|![Bracket_01_10_Tto2](Bracket_01_10_Tto2.PNG)| ![Bracket_01_1](Bracket_01_11.PNG)|

Final version with aluminum
Checking the natural frequency of the part, the first natural frequency is around 1500 HZ which is much higher that 1500rpm. Also on the right side the life expectancy of the part is reported for 1000000 maximume impact (assuming charging time 4 hours of operation, speed of 1m/s, 1 full impact per meter) privdes us with 66 days of warranty.
The simulation can go higher with other senarios.
 
| NAtural frequency analysis | Fatigue FEA results | 
| :---: | :---: |
|![Bracket_01_12](Bracket_01_12.PNG)|![Bracket_01_12_01](Bracket_01_12_01.PNG)|

## Alternative considerations
Alternate version with PE high density
| ![Bracket_01_12_01_PEHD](Bracket_01_12_01_PEHD.PNG)| ![Bracket_01_12_01_PEHD_LC](Bracket_01_12_01_PEHD_LC.PNG) | 
| :---: | :---: |
| ![Bracket_01_12_01_PEHD_NF](Bracket_01_12_01_PEHD_NF.PNG)| ![Bracket_01_12_01_PEHD_URes](Bracket_01_12_01_PEHD_URes.PNG) | 


