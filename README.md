## Hi I am Douae AMZIL 👋

I am a Geoinformation Engineering student with a background in Computer Engineering.

My work combines GIS, spatial analysis, remote sensing, GeoAI and WebGIS development. I enjoy transforming spatial data into maps, analytical tools and decision-support solutions.

I have worked on projects involving:
- 🗺️ GIS & spatial decision support
- 🛰️ Remote sensing and satellite image analysis
- 🤖 GeoAI and supervised classification
- 🌐 WebGIS development
- 🧩 QGIS plugin development and workflow automation
- 🗄️ Spatial databases with PostgreSQL/PostGIS

🎯 Currently looking for a **6-month PFE internship starting in 2027**.

📍 Morocco

# 🚀 Featured Projects

## 🌍 Loss & Damage WebGIS Platform

Development of a WebGIS platform for managing, mapping and analyzing climate-related disasters, losses and damages in Morocco.

The platform supports spatial data management, multi-level territorial analysis, collaborative data contribution and decision-support visualization.

### Main features
- Interactive mapping of disaster events and affected territories
- Region → Province → Commune spatial filtering
- Management of points, lines and polygons
- Sector-based loss and damage indicators
- Thematic maps and spatial/statistical analysis
- Event submission and validation workflow
- Partner and administrator role management
- Notifications and collaboration workflows
- Spatial data validation using PostGIS
- Analysis dashboards, tables and charts

### Technologies
`React` `Vite` `Leaflet` `Node.js` `Express` `PostgreSQL/PostGIS` `GeoJSON` `REST API` `Recharts`

### Project Preview

## 🔥 GeoAI Burned Area Detection — Derdara Forest

GeoAI workflow for detecting and mapping burned areas in Derdara Forest, Chefchaouen, using Sentinel-2 imagery and Random Forest classification.

### Main work
- Selected pre-fire and post-fire Sentinel-2 imagery
- Applied cloud, cirrus, shadow and snow masking using the SCL layer
- Generated median composites for both periods
- Calculated NDVI, NBR and dNBR
- Detected burned areas using a dNBR threshold
- Produced a fire-severity map
- Created burned / non-burned training polygons
- Extracted spectral bands and derived indices for model training
- Trained a Random Forest classifier with 100 trees
- Split samples into 80% training and 20% testing
- Evaluated the model using a confusion matrix, accuracy and Kappa
- Compared dNBR and Random Forest burned-area estimates

### Results
- dNBR estimated burned area: **99.31 ha**
- Random Forest estimated burned area: **105.63 ha**
- Test accuracy: **100%** on the selected test samples

### Technologies
`Google Earth Engine` `Sentinel-2` `Random Forest` `Google Colab` `Remote Sensing` `GeoAI`

## 🧩 QGIS Plugin — Urban Planning Decision Support & Remote Sensing

Development of a QGIS plugin combining vector spatial analysis and raster remote-sensing workflows.

### Vector module
- Project identification and geographic localization
- Definition of analysis buffer zones
- Spatial intersection with urban-planning layers
- Analysis of public, private, communal and forest domains
- Detection of existing derogations
- Generation of a decision-support result
- Export of results to PDF, CSV and PNG

### Raster module
- Connection to Copernicus satellite data
- Search and selection of Sentinel-2 imagery
- Image download workflow
- Processing of satellite imagery
- Calculation of vegetation and water indices such as NDVI, NDWI and EVI

### Technologies
`Python` `PyQGIS` `QGIS` `Qt` `Vector Analysis` `Raster Processing` `Copernicus`


## 🌲 Forest Cover Change Monitoring — Maâmora Forest

Remote-sensing project for analyzing long-term and recent forest-cover changes in the Maâmora Forest, Morocco.

### Part 1 — Global Forest Change
- Digitized study areas in QGIS
- Exported study areas as GeoJSON
- Used the Global Forest Change dataset
- Analyzed tree cover, forest loss and forest gain
- Adapted and executed a Python notebook in Digital Earth Africa
- Corrected GeoJSON loading and dynamic area selection
- Generated maps and temporal graphs of forest-cover changes

### Part 2 — Sentinel-2 & NDVI
- Compared Sentinel-2 imagery between 2018 and 2024
- Produced RGB visualizations
- Calculated and compared NDVI
- Generated NDVI difference maps
- Produced histograms to analyze vegetation changes
- Interpreted spatial and temporal forest-cover evolution

### Technologies
`Digital Earth Africa` `QGIS` `Python` `GeoJSON` `Sentinel-2` `NDVI` `Remote Sensing`

## 🏫 School Site Selection & Optimal Road Route — Stowe, Vermont

GIS decision-support project for identifying a suitable location for a new school and determining an optimal access route.

### Site selection
- Calculated Euclidean distances to schools and recreational facilities
- Calculated and reclassified terrain slope
- Reclassified land-use data
- Weighted multiple spatial criteria
- Applied Weighted Overlay analysis
- Removed isolated pixels using Majority Filter
- Selected suitable areas larger than 4.0469 ha intersecting roads

### Optimal route analysis
- Reclassified slope according to construction cost
- Assigned construction costs to land-use classes
- Created a combined cost surface
- Calculated Cost Distance and Backlink rasters
- Extracted the least-cost path to the selected school site
- Automated parts of the workflow using ModelBuilder

### Technologies
`ArcGIS` `ArcMap` `ModelBuilder` `Multi-Criteria Analysis` `Cost Distance` `Spatial Analysis`
