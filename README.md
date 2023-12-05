# Oyster Aquaculture Suitability

An assignment for EDS223: Geospatial Analysis and Remote Sensing for the Masters of Environmental Data Science Program at UCSB. 

The goal of the project is to gain experience working with spatial data and broadening workflows by creating functions in R by using ocean data from the west coast of the US. I am using this data to find the suitable areas for oyster aquaculture and then modifying this code to take inputs of depth range and temperature range to find the suitable are for other aquaculture species. Steps of this work:

1. Reading in raster and shape files
2. Finding suitable oyster aquaculture areas
3. Mapping the results
4. Creating a function that will report and map suitable areas for any aquaculture species based on inputs of minimum depth, maximum depth, minimum temperature, and maximum temperature

## Citations
Data was obtained from:

[NOAA 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php)  

[General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area)  

[Marineregions.org](https://www.marineregions.org/eez.php)

## File Structure

      aquaculture-suitability  
       │   README.md  
       |   .gitignore  
       │   aquaculture-suitability.qmd      
       │
       └───data
            │   wc_regions_clean.shp
            │   depth.tif
            │   average_annual_sst_2008.tif
            │   average_annual_sst_2009.tif        
            │   average_annual_sst_2010.tif        
            │   average_annual_sst_2011.tif
            │   average_annual_sst_2012.tif    
        
