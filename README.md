# Aquaculture Suitability


## Overview
This project revolves around analyzing bathymetry, Sea Surface Temperature (SST), and Environmental Economic Zone (EEZ) data to find suitable locations for Oyster aquaculture. I ultimately develop an aquaculture suitability funciton which, given input parameters of ideal depth and temperature ranges for a specified species, outputs two maps displaying the total area and percentage area suitable for aquaculture of that species in EEZs along the West Coast of the United States. 



## Data

I use a few key datasets in this project:

### Sea Surface Temperature (SST) Data
In this project, I will use average annual sea surface temperature (SST) from the years 2008 to 2012 to characterize the average sea surface temperature within the region. The data I'll be working with was originally generated from [NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php).

### Bathymetry Data

To characterize the depth of the ocean I will use the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area).[^gebco]

### Environmental Economic Zone (EEZ) Data

I will be designating maritime boundaries using Exclusive Economic Zones off of the west coast of US from [Marineregions.org](https://www.marineregions.org/eez.php).

### State boundaries

I use the [US Census' Cartographic Boundary](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html) files ["States"](https://www2.census.gov/geo/tiger/GENZ2018/shp/cb_2018_us_state_20m.zip) shapefile data at 20 meter resolution for my basemap.  

## Repository Structure


## Acknowledgement

This repository and associated materials are based on an assignment for EDS223: Geospatial Analysis and Remote Sensing for the Masters of Environmental Data Science Program at UCSB, taught by Ruth Oliver.


GEBCO Compilation Group (2022) GEBCO_2022 Grid (doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c).

Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. (2017). Mapping the global potential for marine aquaculture. *Nature Ecology & Evolution*, 1, 1317-1324.

Hall, S. J., Delaporte, A., Phillips, M. J., Beveridge, M. & O’Keefe, M. (2011). Blue Frontiers: Managing the Environmental Costs of Aquaculture. The WorldFish Center, Penang, Malaysia. 



[^hall]:Hall, S. J., Delaporte, A., Phillips, M. J., Beveridge, M. & O’Keefe, M. Blue Frontiers: Managing the Environmental Costs of Aquaculture (The WorldFish Center, Penang, Malaysia, 2011). 

[^gentry]:Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential for marine aquaculture. *Nature Ecology & Evolution*, 1, 1317-1324 (2017).

[^gebco]:GEBCO Compilation Group (2022) GEBCO_2022 Grid (doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c).