# Ehsan Tabatabaie | Engineering Portfolio
# Initial Steps in designing a thermoform tool for a Cake container

## Project Overview
This page contains the process I took to initiate CAD design in tooling for a thermoforming part. The goal was to create step to creat a parametric model for this tool.
So faar the process containe creation of initial step for one side of thecontainer.

**As the initial step we need the input from customer**
* **Purpose**: Protective packaging
* **Mechanical stresses**: Impact , compression, and vibration resistance.
* **Thermal environment**: Operating temperature range of 20 to 120.
* **Chemical exposure**: Resistance to moisture, solvents, or other chemicals.
* **Size and shape**: Holds 6 count of one sixth of a 10 inch cake with a height of 2 inches .
* **Aesthetic considerations**: Surface finish, color, texture.

## Materials

| Material | Mechanical Strength | Cost | Recyclability | Food Safety | Transparency | Chemical Resistance | Popularity in Food Industry |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Polypropylene (PP) | High | Low to Moderate | Widely recyclable (recycling code #5) | Excellent (FDA approved) | Opaque to translucent | Good (resistant to acids, bases) | Very High |
| Polyethylene Terephthalate (PET)/PETG | Moderate to High | Moderate | Widely recyclable (recycling code #1)| Excellent (FDA approved) | High (clear) | Moderate (sensitive to strong bases) | High |
| High-Impact Polystyrene (HIPS) | Moderate | Low | Limited recyclability (recycling code #6) | Good (FDA approved) | High (clear) | Moderate (sensitive to solvents) | Moderate |
| Polyethylene (PE) | Moderate | Low | Widely recyclable (recycling codes #2, #4) | Excellent (FDA approved) | Opaque to translucent | Good (resistant to moisture, chemicals) | High |
| Polylactic Acid (PLA) / CPLA | Moderate to Low | Moderate to High | Compostable, limited recycling | Good (FDA approved) | High (clear) | Moderate (sensitive to heat and moisture) | Growing (eco-friendly trend) |

Explanation of Terms:
* **Mechanical Strength**: Ability to withstand physical stress without deformation or breaking.
* **Cost**: Relative cost for mass production (Low, Moderate, High).
* **Recyclability**: Availability and ease of recycling or composting.
* **Food Safety**: Compliance with food contact regulations (FDA or equivalent).
* **Transparency**: Clarity level for product visibility.
* **Chemical Resistance**: Resistance to acids, bases, solvents, and moisture.
* **Popularity**: Common usage level in the food packaging industry.

From this table it seems the first choise is ***Polyethylene Terephthalate (PET)/PETG*** for the material, due to its **Recyclability**, **Transparency**, and **Mechanical Strength**.

|![A loptop on the Cooling Pad](3D.JPG) | ![A loptop on the Cooling Pad](preview.JPG) |
					

## 2. Design Visuals
* Steps: 	
1- I created a simplified version of the item to put into the thermoset package
	One sixth of a 10 inches cake with height of 2 inches
2- Put the item into an assembly and then created the package around it with an offset tool.
Consideration: 
Here the customer input is needed: the type of packaging, How should the container be with respect to the item? Here I considered one eighth ( 1 / 8 ) of inches should be a proper combination of flexibility and handling the item inside the packaging

3- Packaging separation height.
The created shell around the item should be opened. The height of remaining the item inside the package highly depends on the customer’s proposed application.
A retail market: The food item should be highly exposed after opening for the ease of access.
	The separation height should be around 0.5 of inches.
A person using the package: The food item should be secure even after opening the container.
	The separation height should be around 1 inch.
A special customer: The food item should be secure even after opening the container and be easily accessible.
	The separation height should be around 1 inch and extra features added to the container.

Assume the customer is a retail market.
So from the bottom of the shell I created an offset of 0.5 inch for the separator plane.


4- I hid the upper part and created work on the lower part of the container making the structure using surface modeling.
Adding features to the lower part of the container while avoiding adding dimension to the model and maintaining the fully constrained sketches.


Below are the rendering of the model.
<p align="center">
  <img src="01.JPG" height="480" style="vertical-align:middle">
</p>

<p align="center">
  <img src="02.JPG" height="480" style="margin-right: 10px;">
  <img src="03.JPG" height="480">
</p>

<p align="center">
  <img src="04.JPG" width="45%" />
  <img src="05.JPG" width="45%" />
</p>
