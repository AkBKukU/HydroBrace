# Hydro Thunder CAD Replacement and Support Components  
  
## Hydro Thunder Dashboard Brace

![A 3d render of the part](doc/cad-image.png "A render of the bracket model")

This is a 3D printable part to clamp down on the dashboard to reinforce the frequently broken plastic that secures it to the metal base. The parts are printed with one as modeled and the other mirrored from the original. The are installed with the original bolts over the plastic dashboard.

Adding foam to the bottom of the parts before putting them on may make them work even better as it will increase friction by fitting into the textured surface more.

## Hydro Thunder Throttle Mount Plate

![A 3d render of the throttle mount plate](doc/cad-throttle-image.png "A render of the mount model")


The intermediate mounting bracket to attach the throttle to the control panel is prone to tearing. The file `HydroThrottleplate-Unfold.dxf` is a replacement design for this made in a thicker piece of steel to both repair and prevent future damage. The design file is designed against material of the follow parameters availble at [sendcutsend.com](https://sendcutsend.com)  
  
**[CRS Mild Steel 0.119" (3mm)](https://sendcutsend.com/materials/mild-steel/):**  
 - K-Factor: `0.38`  
 - Bend Radius: `1.6002 mm`  
 - Thickness: `3.0226 mm`

If you want to change the material type you will need to modify the FreeCAD design file which uses the [SheetMetal Workbench](https://wiki.freecad.org/SheetMetal_Workbench) plugin. The K-factor is set on the unfolding of an object, material thickness and bend radius are set for the plugin on the base level object but for this project are referenced from a spreadsheet to make adjustments easier.