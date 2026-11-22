# **2021 Extreme Compounded Winter Storms Cause Power grid Catastrophe**

<img width="1200" height="675" alt="041922_Texas_powerlines" src="https://github.com/user-attachments/assets/3209db48-ce28-4eb3-bbd8-da9629a8a28f" />

#### Author: 

Karla Ramos [[GitHub Profile](https://github.com/Karlavramos)]

## General Summary
This repository contains all documents used to map and analyze the impacts of 2021 compounded winter storms that led to a major power crisis. In this assignment, we identified the impacts of these series of extreme winter storms by estimating the number of homes in the Houston metropolitan area that lost power and investigate whether not these impacts were disproportionately felt.

## Repository Contents

```{r}

texas_extreme_winter
└───README.md
└───Rmd/Proj files    
└─── texas_extreme_winter.qmd 
└───.gitignore
    └───data
        └───gis_osm_buildings_a_free_1.gpkg
        └───gis_osm_roads_free_1.gpkg
        └───VNP46A1
            └───VIIRS data files
```

## Data
**Night lights:** VIIRS data is distributed through NASA’s Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC).
  Data files:
  - VNP46A1.A2021038.h08v05.001.2021039064328.tif: tile h08v05, collected on 2021-02-07
  - VNP46A1.A2021038.h08v06.001.2021039064329.tif: tile h08v06, collected on 2021-02-07
  - VNP46A1.A2021047.h08v05.001.2021048091106.tif: tile h08v05, collected on 2021-02-16
  - VNP46A1.A2021047.h08v06.001.2021048091105.tif: tile h08v06, collected on 2021-02-16


**Roads:** We used Geofabrik’s download sites to retrieve a shapefile of all highways in Texas and prepared a Geopackage (.gpkg file) containing just the subset of roads that intersect the Houston metropolitan area. 
  Data file: gis_osm_roads_free_1.gpkg
  
**Buildings:** Provided for assignment from Geofabrick and prepared a GeoPackage containing only houses in the Houston metropolitan area.
  Data file: gis_osm_buildings_a_free_1.gpkg

Data provided by Annie Adams, Bren School of Environmental Science & Management, [University of California, Santa Barbara], via [EDS 223: Geospatial Analysis & Remote Sensing], [November 2026]

## References
Wikipedia. 2021. “2021 Texas power crisis.” Last modified October 2, 2021. https://en.wikipedia.org/wiki/2021_Texas_power_crisis.

Zhou, R. Z., Hu, Y., Lei, Z., Heng, C., & Bing, Z. (2024). Understanding the disparate impacts of the 2021 Texas winter storm and power outages through mobile phone location data and nighttime light images. International Journal of Disaster Risk Reduction, 103, 104339. https://doi.org/10.1016/j.ijdrr.2024.104339

## Acknowledgments

This analysis was completed as part of [EDS 223: Geospatial Analysis & Remote Sensing](https://eds-223-geospatial.github.io/), Master of Environmental Data Science, UC Santa Barbara. Assignment details: [Homework 3](https://eds-223-geospatial.github.io/assignments/HW3.html).
