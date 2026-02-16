# Ehsan Tabatabaie | Engineering Portfolio
# An initial Step in Designing a Thermoform Tool for a Cake Container

## Project Overview
This page documents the process I took to initiate the CAD design for a thermoforming tool. The goal was to create a **parametric model** for this tool. So far, the process includes the creation of the initial steps for one side of the container.

**As the initial step, we require input from the customer:**
* **Purpose**: Protective packaging.
* **Mechanical stresses**: Impact, compression, and vibration resistance.
* **Thermal environment**: Operating temperature range of **20°F to 120°F**.
* **Chemical exposure**: Resistance to moisture, solvents, or other chemicals.
* **Size and shape**: Holds a 6-count arrangement of one-sixth slices of a 10-inch cake with a height of 2 inches.
* **Aesthetic considerations**: Surface finish, color, and texture.

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

Based on this table, the primary choice is **Polyethylene Terephthalate (PET/PETG)** due to its **recyclability**, **transparency**, and **mechanical strength**.
		

## Design Steps
1- **Creation of a representative of the food item**: I created a simplified version of the item for the thermoform package: one-sixth of a 10-inch cake with a height of 2 inches.
2- **Arrangement in the package**: The items were placed into an assembly with an arrangement of six slices.

| ![Top View](Cake_Container%202.PNG) | ![Side View](Cake_Container%203.PNG) | ![Internal](Cake_Container%204.PNG) |
| :---: | :---: | :---: |
| Circular Arrangement: Good for presentation | Triangle packaging: New style | Rectangular presentation: better for packaging and transportation |

Since for the majority of Cakes the final Cake designs are circular, here the packaging considered to be circular for aesthetic appearance and customer satifaction. In this arrangement there is an offset between slices of the Cake.

3- **Tool Considerations**:
  **Draft angle**: The final tool requires a draft angle for ease of part separation.

| minimum draft angle | female features | male features |
| :---: | :---: | :---: |
| 1 to 2 degrees | 1.5 to 2 degrees | 4 to 6 degrees |

***General recommendation of 5 degrees for draft angle***
Since the parting line is a parametric value, the draft angle will be applied in both positive and negative directions for the upper and lower halves of the package.

**Parting line**: The parting line considered to be **0.5 inches** from the bottom surface, meaning a half-inch of the food item remains in the lower package base after opening.
| Parts with draft for lower part and upper part in the assembly | Circular pattern of the items for assurance of proper arrangement of the assembly | 
| :---: | :---: |
|![Cake_Container 202_BothSidesDrafted_Adjusting](Cake_Container%202_BothSidesDrafted_Adjusting.PNG) | ![Cake_Container 202_BothSidesDrafted](Cake_Container%202_BothSidesDrafted.PNG) |

**Connection and consistency in the design**
The separation level defined in the assembly using a plane. In the case changing the separation line the height of this plane can be modified.
Both upper part and lower part will be initiated as a part in the assembly with initial reference to the items in the assembly. This way in the case of modifications the rest will be updated or there will be less effort in keeping things in order.

* 4 - Lower part of the container

| It started by taking offset surface with zero distance from the original part | Then Creation of a trim surface to include small extended separation wall | Trimming to final sizes |
| :---: | :---: | :---: |
|![Container^Cake_Container 2_LowerSide_HalfWallCutSketch](Container^Cake_Container%202_LowerSide_HalfWallCutSketch.PNG) | ![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_2](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_2.PNG) | [Container^Cake_Container 2_LowerSide_HalfWallCutSketch_3](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_3.PNG) |


|Circular pattern will create the whole lower part out line | In the case of missing a surface it can be easily added | 
| :---: | :---: |
|![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_4](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_4.PNG) | ![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_5](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_5.PNG) | 
  
|Completing the adjacent wall | Adding the lock mechanism | 
| :---: | :---: |
|![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_6](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_6.PNG) | ![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_7](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_7.PNG) |

THe final part created by knitting the surfaces representing one sixth of the whole structure and circular pattern the result creating a new knitted surface.
So far the consideration was for very fit package of the food item which is not a very correct design as the the food item need to have some gap for ease taking out.
In order to create this scenario the actual food item needs to be scaled up a considered to be slightly larger. Here in oder to check the parametric functionality of the the design the Cake size changed to slices of 12 inches Cake. The modification applied to the initial input and by some fixes the final surface correctly created.
Here is the result based on input of a 12 inches Cake. 
![Container^Cake_Container 2_LowerSide_HalfWallCutSketch_8](Container^Cake_Container%202_LowerSide_HalfWallCutSketch_8.PNG)

The surface need fillets and a thickness of 0.005 inches to be used to create the tool.
This surface will be part of the design process for the upper side of the container, particularly for the shared area and region of contact.

