# 3D-Modeling-of-U-Shaped-Mechanical-Part


## Objective:
To model a U-shaped mechanical joint that matches the given technical drawing, with precise dimensions and structural features. The design was created in 3D using Tinkercad and includes all essential geometric features for fabrication or simulation (FEA).

Components Created:

## 1. Base Disk (Circular Plate)
  Shape: Cylinder  
  Diameter: 45 mm  
  Height (Thickness): 5 mm  
  Color Used: Orange (Solid)  

## 2. Side Arms (Vertical Supports forming U-shape)
Shape: Boxes (Rectangular Prisms)  
  Each arm dimensions:
  Width: 4.5 mm  
    Depth: ~10 mm (adjusted for spacing)  
    Height: 29 mm  
  Distance between inner faces of arms: 54 mm  
  Quantity: 2  
  Color Used: Red (Solid)  

## 3. Side Holes (for shafts or pins)
Shape: Cylinders (set as Hole)  
Diameter: 5 mm  
Height: 10 mm (to fully pass through the side walls)  
Position: Centered vertically at 14.5 mm from base  
Quantity: 2 (1 on each arm)

## 4. Mounting Holes in Base Disk
Shape: Cylinders (set as Hole)  
Diameter: 5 mm  
Height: 6 mm (enough to pierce through the 5 mm base)  
Quantity: 3  
Position: Arranged in triangular layout (1 front bottom, 2 top sides) matching the technical drawing  

## Tools & Features Used:
Tinkercad Basic Shapes: Cylinder, Box  
Hole Option: Used to subtract geometry for drilling  
Align Tool: For centering the parts perfectly  
Group Tool: To merge all elements into one object  
Snap Grid: Set to 1.0 mm for precise positioning  
Manual Height Adjustment: Using black arrow to set elevation of holes

## Total Features Summary:
Feature                | Count
------------------------|-------
Cylindrical Base       | 1     
Side Arms              | 2     
Side Holes             | 2     
Base Mounting Holes    | 3     
Total Cylindrical Holes| 5     

Final Step:
Exported the model as STL file using Export > .STL  
Ready for:
GitHub Submission  
FEA Simulation  
Comparison with original drawing

------------------------------------------------------
## STL Model Visualization using Kiri:Moto

## Objective:
To visualize and inspect a 3D model (STL format) using the Kiri:Moto tool without printing. The purpose is to check structure, orientation, and slicing preview for documentation.

## Steps Followed:

1. Model Export from Design Tool
  Designed a 3D part using a CAD tool (e.g., Tinkercad).
  Exported the design as a .stl file.

2. Open Kiri:Moto in Browser
Visited the website: https://grid.space/kiri

3. Import the STL Model
Clicked Files > Import to upload the .stl file.
  Verified that the model appeared correctly on the build plate.

4. Adjust View and Orientation
  Rotated and zoomed using the mouse to inspect the model.
  Verified alignment and proportions.

5. Set Parameters (Optional – for visualization only)
  Layer Height: 0.25
  Top Layers: 3
  Base Layers: 3
  Nozzle Temp: 200
  Bed Temp: 60
  Fan On Layer: 1
  Fan Speed: 255
  Print Speed: 50
  Shell Count: 3
  Infill Factor: 1.25
  (Other values left as default)

6. Slice the Model
Clicked the Slice button to generate slicing layers.
Verified the layers using the Preview mode to check:
Shells (blue)
Solid fill (green)
Sparse fill (purple)

8. (Optional) Exported GCode
Clicked Export to generate GCode (not for printing, just to complete the flow).

## Notes:
  This process was used only for visualization and documentation purposes.
  The model was not intended for actual 3D printing at this stage.
  The preview was used to confirm the model is structurally sound and properly sliced.
