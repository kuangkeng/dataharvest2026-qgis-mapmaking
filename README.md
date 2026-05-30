# Make a publication-ready static map with QGIS

**Mini demo at Dataharvest 2026**

Keng (Kuek Ser Kuang Keng, Senior Editor for Rainforest Investigations at Pulitzer Center)

**[View the workshop materials](https://github.com/kuangkeng/dataharvest2026-qgis-mapmaking)**

**[Watch the video recordings](https://drive.google.com/drive/folders/18G7Yn4lNHLKoQs8KtnKSP2OgR1nt-7gR?usp=sharing)**

**[Download the satellite imagery](https://drive.google.com/file/d/1l8nHDwsurQmBD2-zn5VlfWvHhchdlpox/view?usp=sharing) (downloaded from Planet)** 

<img width="3507" height="2480" alt="kk-park-map-2" src="https://github.com/user-attachments/assets/c7b02a12-b861-45c8-912b-c11e31be2264" />

This map example is inspired by a [story published by The Guardian](https://www.theguardian.com/global-development/2025/sep/08/myanmar-military-junta-scam-centres-trafficking-crime-syndicates-kk-park). The photo used for this workshop is also from the same story.

## Why use QGIS to make static maps instead of graphic editing software like Adobe Photoshop/Illustrator? 

#### 1. Data-Driven Accuracy ####
QGIS renders maps directly from geospatial data (shapefiles, GeoJSON, etc.), ensuring geographic accuracy. Photoshop/Illustrator require manual drawing, which introduces human error in proportions, distances, and boundaries.
#### 2. Automatic Projection Handling #### 
QGIS manages coordinate reference systems (CRS) and map projections automatically. Distorting or reprojecting a map in Illustrator requires manual recalculation or workarounds.
#### 3. Reproducibility & Updateability #### 
When data changes (e.g., new election results, updated borders), you simply refresh the data source and re-export. In Illustrator, you'd need to manually redraw or re-trace every change.
#### 4. Scale Bar & North Arrow Are Dynamic #### 
QGIS auto-generates accurate, data-linked scale bars and north arrows that update if you zoom or reproject. In graphic software, these are static decorations you place by hand.
#### 5. Free & Open Source #### 
QGIS is free. Adobe CC costs hundreds of euros per year — a significant budget consideration for freelance journalists or small newsrooms.
#### 6. Attribute-Based Labeling #### 
Place names, region labels, and data values can be auto-generated from attribute tables and styled with rules (e.g., only label cities > 100,000 people). In Illustrator, every label is typed manually.
#### 7. Choropleth & Thematic Maps in Seconds #### 
Coloring regions by data values (population, vote share, income) is automated via classification rules. Doing this in Photoshop means manually filling hundreds of shapes.
#### 8. Built-In Legend Generation #### 
QGIS generates a legend that is automatically linked to your map's symbology. Any style change updates the legend too. In graphic software, legends are built from scratch.
#### 9. Grid & Graticule Tools #### 
QGIS can overlay precise geographic grids (latitude/longitude lines) with correct spacing. Replicating this accurately in Illustrator is tedious and error-prone.
#### 10. Audit Trail & Transparency #### 
A QGIS project file records every data source, layer style, and projection used — making your methodology transparent and verifiable, which is essential for journalistic standards. A flattened Illustrator or Photoshop file tells you nothing about where the data came from.
