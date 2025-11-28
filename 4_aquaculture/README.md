# Homework 4: Aquaculture Suitable Areas

### Description

This folder contains the contents for homework 4. This homework's main goal is to find suitable areas for oyster aquaculture given optimal sea surface temperatures and depth measurements. Additionally, the workflow is converted into a function to apply to any species given suitable temperature and depth parameters.

``` 
.
├── 4_aquaculture.Rproj
├── aquaculture_suitability.qmd
├── data
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── wc_regions_clean.dbf
│   ├── wc_regions_clean.prj
│   ├── wc_regions_clean.shp
│   └── wc_regions_clean.shx
└── README.md
```

### Data

-   Sea Surface Temperatures (SST): The annual average SST data used spans from 2008 - 2012. The .tif files were prepared by the course instructors but were generated from [NOAA's 5km Daily Global Satellite SST Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php).

-   Bathymetry: The bathymetry raster was also provided and can be accessed through the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data-products/gridded-bathymetry-data#area).

-   Exclusive Economic Zones (EEZ): The maritime boundaries are designated by the EEZ off of the west coast US. The .shp files were sourced from [Marineregions.org](https://www.marineregions.org/eez.php).


### References

- NOAA Coral Reef Watch. 2019, updated daily. NOAA Coral Reef Watch Version 3.1 Daily 5km Satellite Regional Virtual Station Time Series Data for West Coast USA, 2008-2012. College Park, Maryland, USA: NOAA Coral Reef Watch. Data set accessed November 20, 2025 at https://coralreefwatch.noaa.gov/product/vs/data.php.

- GEBCO Compilation Group (2025) GEBCO 2025 Grid (doi:10.5285/37c52e96-24ea-67ce-e063-7086abc05f29). Accessed November 20, 2025 from https://www.gebco.net/data-products/gridded-bathymetry-data#area.

- Flanders Marine Institute (2024). Union of the ESRI Country shapefile and the Exclusive Economic Zones (version 4). Available online at https://www.marineregions.org/. https://doi.org/10.14284/698. Accessed on November 20, 2025.

### Author

Zach Loo

