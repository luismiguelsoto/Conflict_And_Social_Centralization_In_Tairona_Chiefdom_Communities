Conflict And Social Centralization In Tairona Chiefdom Communities In The Río Frío Basin, Sierra Nevada De Santa Marta, Colombia
--------------------------------------------------------------

This repository contains the R scripts and datasets used to examine how conflict shaped socio-political organization and demographic centralization in the Tairona chiefdom communities of the Río Frío Basin (Sierra Nevada de Santa Marta, Colombia) during the final pre-Hispanic occupation (10th–16th centuries AD).

Repository Structure:
----------------------------------
1. GIS:
   - Contains the spatial data files (shapefile components and raster files) defining the study area:
     • POLYGON_SURVEY_UNTILL_2023.shp
     • ALL_SITES_TAIRONA_PERIOD.shp
     • SITES_VIEWSHED.shp
     • ALL_STRUCTURES_TAIRONA.shp
     • CENTROID_SITES_TAIRONA.shp
     • DEM_40KM.tif

2. R Code Files:
   - The main R script (or R Markdown file) contains the code to:
     a) Load required packages.
     b) Download the Excel datasets and GIS files directly from GitHub.
     c) Process the data and perform the analysis.
     d) Generate the figures or tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: [R 4.4.1]
- Key R packages used in this project include (with version numbers):
    •  terra: version 1.8.5
    •  sf: version 1.0.19
    •  raster: version 3.6.32
    •  ggplot2: version 3.5.1
    •  ggnewscale: version 0.5.1
    •  ggspatial: version 1.1.9
    •  tidyverse: version 2.0.0
    •  ggpubr: version 0.6.0
    •  ggfortify: version 0.4.17
    •  visreg: version 2.7.0
    •  vcd: version 1.4.13
    •  scatterplot3d: version 0.3.44
    •  dplyr: version 1.1.4
    •  tidyr: version 1.3.1
    •  strucchange: version 1.5.4
    •  tmap: version 4.0
    •  spdep: version 1.3.8
    •  spatialreg: version 1.3.6
    •  gstat: version 2.1.3
    •  sp: version 2.1.4
    •  ggthemes: version 5.1.0
    •  ggrepel: version 0.9.6
    •  corrplot: version 0.95
    •  viridis: version 0.6.5

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R script (or R Markdown file) in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the Excel and GIS files directly from GitHub.
4. Run the R script from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues, consult the comments in the code or contact the corresponding author.

Manuscript Summary:
----------------------------------
This article investigates how conflict influenced the socio-political organization and demographic centralization of Tairona chiefdom communities in the Río Frío Basin, Sierra Nevada de Santa Marta, during the Tairona period (10th–16th centuries A.D). Drawing from European chronicles and geostatistical methods, we examine the Pocigüeica chiefdom, a political entity recognized for its belligerent character and warrior chiefs with segmented decision-making structures, which resisted Spanish conquest in the 16th century A.D. As part of an ongoing regional-scale survey and reconnaissance program, this study examines how political integration and demographic centralization related to territorial strategies linked to intercommunity conflict. Although ethnohistoric sources highlight Tairona belligerence, archaeological research has not explored the relationship between conflict, political leadership, and social organization. By integrating spatial analysis, settlement pattern data, and multivariate analysis, this paper provides an empirical framework to assess warfare’s role as both a disruptive and integrative force in complex society evolution.

For questions or further information, please contact: lms313@pitt.edu
