# Ehsan Tabatabaie | Engineering Portfolio
# Initial Steps in designing a thermoform tool for a Cake container

## Project Overview
This page contains the process I took to initiate CAD design in tooling for a thermoforming part. The goal was to create step to creat a parametric model for this tool.
So faar the process containe creation of initial step for one side of thecontainer.

**As the initial step we need the input from customer**
* **Purpose**: Protective packaging
* **Mechanical stresses**: Impact , compression, and vibration resistance.
* **Thermal environment**: Operating temperature range of 20 to 120 farenhight.
* **Chemical exposure**: Resistance to moisture, solvents, or other chemicals.
* **Size and shape**: Holds 6 count of one sixth of a 10 inche cake with a height of 2 inches .
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
			

## Design 
**Steps:**
*	1- Creation of a representive of the food item: I created a simplified version of the item to put into the thermoset package : One sixth of a 10 inches cake with height of 2 inches.
* 	2- Arrangment in the package: Put the item into an assembly with arrangment of six of them.

| ![Top View](Cake_Container%202.PNG) | ![Side View](Cake_Container%203.PNG) | ![Internal](Cake_Container%204.PNG) |
| :---: | :---: | :---: |
| Circular Arrangment: Good for presentation | Triangle packaging: New style | Rectangular presentation: better for packaging and transportatoin |

Since for the majority of Cakes the final designs are cicular, here the packaging considered to be circular for aththetic aperance and customer satifaction. In this aarangment there is an offese between slices of the Cake.


* 3- Tool Considerations
  **Draft angle**: The final tool needs to have draft andgle for the ease of part separation.

| minimume draft angle | female featurs | male featurs |
| :---: | :---: | :---: |
| 1 to 2 degrees | 1.5 to 2 degrees | 4 to 6 degrees |

***With general recomendation of 5 degrees for draft angle***

Since the tool will be derived  directly from the part, the general recomendation of 5 degree for draft angle will be applied to the part.
Since the parting line in the package is a parametric value, the draft andle will be in both negative and positive directions. One is for the lower half of the package and the other one for the other side.

**Parting line**: The parting line considered to be 0.5 inches from the bottom surface, means half of the inches of the foor item will remaine in the package after opening.
| Parts with draft for lower part and upper part in the assembly | Circular pattern of the items for assurance of proper arrangement of the assembly | 
| :---: | :---: |
|![Cake_Container 202_BothSidesDrafted_Adjusting](Cake_Container%202_BothSidesDrafted_Adjusting.PNG) | ![Cake_Container 202_BothSidesDrafted](Cake_Container%202_BothSidesDrafted.PNG) |

**Connection and consistancy in the design**
The separation level defined in the assembly using a plane. In the case changing the separation ling the height of this plane can be modified.
Both upper part and lwer part will be initiated as a part in the assembly with initial reference to the items in the assembly. This way in the case of modifications the rest will be updated or there will be less effor in keeping things in order.

* 4 - Lower part of the container

| It started by taking offset surface with zero distance from the original part | Then Creation of a trem surface to include small extended separation wall | Trimming to final sizes |
| :---: | :---: | :---: |
|![Container^Cake_Container 2_LowerSide_HalfWallCutSketch](Container^Cake_Container%202_LowerSide_HalfWallCutSketch.PNG) | ![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_2](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_2.PNG) | [Container^Cake_Container 2_LowerSide_HalfWallCutSketch_3](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_3.PNG) |


|Circular pattern will creat the whole lower part out line | In the case of missing a surface it can be easily added | 
| :---: | :---: |
|![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_4](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_4.PNG) | ![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_5](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_5.PNG) | 
  
|Completing the adjacent wall | Adding the lock mechanism | 
| :---: | :---: |
|![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_6](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_6.PNG) | ![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_7](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_7.PNG) |

THe final part created by knitting the surfces representing one sith of the whole structure and circular pattern the result creating a new knetted surface.
So far the consideration was for very fit package of the food item which is not a very correct desigen as the the food item need to have some gap for ease taking out.
In order to create tis scenario the actual food item needs to be scaled up a considered to be slightly larger. Here inoder to check the paramteric functionality of the the design the Ckae size changed to slices of 12 inches Cake. The modification applied to the initial input and by some fixes the final surface correctly created.
Here is the result based on input of a 12 inches cake. 
![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_8](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_8.PNG)

The surface need fillets and a thickness of 0.005 inches to be used to create the tool.
This surface will be part of the design process for the upper side of the container, particularly for the shared area and region of contact.

