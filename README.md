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
     c) Process the data, build similarity matrices, calculate centrality metrics, and perform network analysis.
     d) Generate the figures and tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: [R 4.4.1]
- Key R packages used in this project include (with version numbers):
    •  sf: e.g., version 1.0-0 (built under R 4.4.2; linking to GEOS 3.12.2, GDAL 3.9.3, PROJ 9.4.1)
    •  spdep: (built under R 4.4.2)
    •  ggplot2: e.g., version 3.3.6
    •  viridis: (version as provided by CRAN)
    •  car: (version as provided by CRAN)
    •  spatstat.explore: e.g., version 3.3-2
    •  spatstat.geom: e.g., version 3.3-3
    •  spatstat.model: e.g., version 3.3-2
    •  network: installed version 1.18.2 (update available: 1.19.0)
    •  ggspatial: (built under R 4.4.2)
    •  vegan: e.g., version 2.6-8
    •  scales: (version as provided by CRAN)
    •  dplyr: (version as provided by CRAN)
    •  patchwork: (version as provided by CRAN)
    •  tidygraph: (version as provided by CRAN)
    •  ggraph: (version as provided by CRAN)
    •  GGally: (version as provided by CRAN)
    •  FSA: e.g., version 0.9.5
    •  ggpubr: (version as provided by CRAN)
    •  writexl: (version as provided by CRAN)
    •  openxlsx: (version as provided by CRAN)
    •  sna: e.g., version 2.8 (created on 2024-09-07)
    •  statnet: e.g., version 2019.6 (2019-06-13)
    •  igraph: (version as provided by CRAN)
    •  DT: (version as provided by CRAN)
    •  tnet: (version as provided by CRAN)
    •  kableExtra: (version as provided by CRAN)
    •  readxl: (version as provided by CRAN)
    •  dunn.test: (version as provided by CRAN)

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R script (or R Markdown file) in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the Excel and GIS files directly from GitHub.
4. Run the R script from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues, consult the comments in the code or contact the corresponding author.

Manuscript Summary:
----------------------------------
This article investigates how conflict influenced the socio‑political organization and demographic centralization of the Tairona chiefdom communities in the Río Frío Basin of the Sierra Nevada de Santa Marta during the final pre‑Hispanic occupation, the Tairona period (10th–16th centuries AD). Based on European chronicles and geostatistical methods, we investigate the existence of the Pocigüeica chiefdom, an apparent political entity recognized for its belligerent character and led by warrior chiefs with a decision-making structure segmented into factions or kinship groups, which resisted the Spanish conquest in the 16th century AD. A systematic study of 40 km² in the Río Frío basin examines how conflict influenced population distribution and pre-Hispanic political integration in these communities. Although ethnohistoric sources highlight the belligerence of Tairona chiefdom communities, archaeological research has so far not explored the relationship between conflict, political leadership and social organization. Thus, this article proposes and explores for the first time in the archaeology of the Sierra Nevada de Santa Marta the evaluation of the conflict in shaping the socio-political complexity of the region.

For questions or further information, please contact:
lms313@pitt.edu
