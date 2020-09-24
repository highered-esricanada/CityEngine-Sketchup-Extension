## CityEngine Sketchup Extension <img src="/logo.png" width="30" alt="Logo">

The CityEngine SketchUp Extension allows users to create models in SketchUp using [CityEngine's](https://www.esri.com/en-us/arcgis/products/arcgis-cityengine/overview) procedural modelling capabilities.

## Requirements
The extension works with the Windows version of SketchUp 2017, 2018, 2019, and 2020. The installer for the extension assumes you have intalled SketchUp to the main Program Files folder.

## Instructions
1. Download the installer [here](https://github.com/highered-esricanada/CityEngine-Sketchup-Extension/releases/latest/download/CityEngine.SketchUp.Installer.exe
).
1. Run the installer executable and choose the versions of SketchUp for which you would like to install the extension.
1. Launch SketchUp.
1. Once you're in the SketchUp 3D viewport, click **Extensions -> Show CityEngine Window** to open the attribute editor.
1. The installer includes three rule packages from Esri's [Rule of the Week](https://www.esri.com/arcgis-blog/products/3d-gis/3d-gis/cityengine-rule-of-the-week/). Choose one from the dropdown to see the available attributes you can modify. Draw either a rectangle for the Taj Mahal and Windmill rule or create an extruded 3D shape for the 3D orientation rule.
1. Select the faces that you have drawn.
1. If selecting polygons that represent the base footprint where your model will be generated, right-click the selected polygons and click **Reverse Faces** (models are generated on the white side of SketchUp faces). 
1. Click Generate to create the CityEngine model.

## Demo
![demo](/demo.gif)

## Add Rule Packages
Rule packages can be added to the **C:\ProgramData\SketchUp\RPK** folder to increase the types of models that can be generated. You can find rule packages on Esri Canada's [3D City Model Resources Site](https://highered-esricanada.github.io/3D-City-Model-Resources/), which showcases useful rule packages that have been uploaded to [ArcGIS Online](https://www.arcgis.com/).

## Licensing
The SketchUp CityEngine Extension is under the same license as the included [CityEngine SDK](https://github.com/Esri/cityengine-sdk), and is free for non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. No redistribution is allowed.
