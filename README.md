# Getting Started with CyberGISX (AAG 2023)

## Introduction
This notebook will walk you through some basic techniques for **spatial analysis and visualization** in the CyberGIS-Jupyter environment. We will use [CDC county-level Social Vulnerability Index (SVI) data](https://www.atsdr.cdc.gov/placeandhealth/svi/documentation/SVI_documentation_2020.html) to examine the characteristics of SVI and whether they are spatially autocorrelated. 

Specifically, this notebook includes functions for <br>
1. Changing coordinate systems, 
2. Creating Choropleth maps, and 
3. Conducting Moran's I and Local Indicators of Spatial Association (LISA). 

## Data Structure
```bash
├── Getting_Start_with_CyberGISX_AAG2023.ipynb
├── LICENSE
├── README.md
└── data
    ├── SVI2020_US_county.cpg
    ├── SVI2020_US_county.dbf
    ├── SVI2020_US_county.prj
    ├── SVI2020_US_county.sbn
    ├── SVI2020_US_county.sbx
    ├── SVI2020_US_county.shp
    ├── SVI2020_US_county.shp.xml
    ├── SVI2020_US_county.shx
    └── state_lookup.csv
```