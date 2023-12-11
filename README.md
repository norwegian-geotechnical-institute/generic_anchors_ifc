# generic_anchors_ifc
A generic Grasshopper tool for export of geometry and information modell of anchors at different Levels of Developement (LODs) to IFC, using Geometry Gym.

## Dependencies
The Grasshopper-script is developed using Rhino 7 Commercial, build 2023-09-24

It contains 133 objects, and depends on 3 plug-ins:
  - ggRhinoIFC                     by Geometry Gym Pty Ltd (23.8.16.0)
  - Pufferfish                     by Michael Pryor (2.9.0.0)
  - LunchBox                       by 'unknown author' (2016.3.21.0)

This file will not load correctly unless the aforementioned plug-ins are installed.

## IFC exported result
We have tested to open the IFC-files under **\IFC export** using usBIM (free ware) and Trimble Connect. Some other BIM viewers may have problem visualising the line geometryies.
