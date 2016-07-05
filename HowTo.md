###Purpose
The goal is to create a georeferenced tiff images in Quantum that Avenza 'PDF Maps' is capable of importing. 

---
###Base Maps

Add the "OpenLayers" plug in via the Plugins tab. ReStart Quantum after you add this toolbar.
Before addin the basemap to your map:
  - Project > Project properties > CRS tab > Activate radio button for CRS (Coordinate Reference System)
  - Select WGS 84 / Pseudo Mercator (Authority ID EPSG:3857) > OK
  - Add your vector layers 
  - On your main menu ribbon select Web > OpenLayers plugin > select your map
  - Zoom to the extent of your vector layers/adjust scale to render
---
###Layout
Once you have yor data styled and basemap added to your data view, we'll use Print Composer to apply an appropriate layout for export. This is the equivilant interface as the layout view in ArcGIS. When exporting a map to PDF Maps in Avenza I find the most appropriate size is an E Sheet(34x44 in). 
  - Project > New Print Composer > Create a Name for your Map in the 'Composer title' dialog box.
  - Once the blank layout has appeared > Layout > Add Map > Click and Drag to create the space in which you would like your map to render on the layout display. 
  - Select from the Presets drop down on the 'Page Size' section (right hand side of screen) > ANSI E (34x44in)
  - Export Settings > Export Resolution = 300dpi
