###Purpose
The goal is to create a georeferenced tiff images in Quantum that Avenza 'PDF Maps' is capable of importing. 

---
###BaseMaps

Add the "OpenLayers" plug in via the Plugins tab. ReStart Quantum after you add this toolbar.
Before addin the basemap to your map:
  - Project > Project properties > CRS tab > Activate radio button for CRS (Coordinate Reference System)
  - Select WGS 84 / Pseudo Mercator (Authority ID EPSG:3857) > OK
  - Add your vector layers 
  - On your main menu ribbon select Web > OpenLayers plugin > select your map
  - Zoom to the extent of your vector layers/adjust scale to render
