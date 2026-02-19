# Ehsan Tabatabaie | Engineering Portfolio

## A Bracket for a Toy car

In this page I am demonstrating the steps I took to design a bracket of toy car.

![Bracket_generated-image](Bracket_generated-image.png)

## Design considerations
- Each spring will apply load of 10kgf at most
- Minimume Factor of Safety 2
- Materila: AL-Alloy 1060
- Electric motor has the MAX RPM 1500

## Design considerations

The goal was to creat the most effective design approache. Since there is no aesthetic consideration form customer. 


| Initial Desing with thickness of 10 mm  | FEA simulation result | 
| :---: | :---: |
|![Container^Cake_Container 2_LowerSide_HalfWallCutSketch](Container^Cake_Container%202_LowerSide_HalfWallCutSketch.PNG)| ![Bracket_01_01](Bracket_01_01.PNG)|

The stress distribution shows the area of the plate with higher stress leve regardless of the statuse of passing the Yield point.

| Area of the bracket that endur stress  | Implementing the design using stress distribution diagram | 
| :---: | :---: |
|![Bracket_01_02](Bracket_01_02.PNG)| ![Bracket_01_03](Bracket_01_03.PNG)|

| Resultant Bracket and reducing the thickness to 5 mm reducing the weight  | FEA results for the factor of safety | 
| :---: | :---: |
|![Bracket_01_04](Bracket_01_04.PNG)| ![Bracket_01_05_Tto5](Bracket_01_05_Tto5.PNG)|

| FEA Stress result  | FEA results for the improved version | 
| :---: | :---: |
|![Bracket_01_06](Bracket_01_06.PNG)| ![Bracket_01_07](Bracket_01_07.PNG)|


| FEA Stress result  | FEA results for the improved version | 
| :---: | :---: |
|![Bracket_01_08](Bracket_01_08.PNG)| ![Bracket_01_09](Bracket_01_09.PNG)|


| FEA Stress result to 2 mm | FEA results for the improved version | 
| :---: | :---: |
|![Bracket_01_10_Tto2](Bracket_01_10_Tto2.PNG)| ![Bracket_01_1](Bracket_01_11.PNG)|

Final version 
![Bracket_01_12](Bracket_01_12.PNG)


