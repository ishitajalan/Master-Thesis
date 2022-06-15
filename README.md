# Master-Thesis
Code repository for Master Thesis work
Python codes for processing netcdf format of temperature reanalysis products (CPC, ERA5, EWEMBI, PGF) and GLEAM AET product
GLEAM AET product - version 3.5b

The repository contents explained below:

1-NetCDF_to_csv: Processing raw netcdf format to daily csv files (min and max) for each dataset
2-csv_processing: Processing csv files to continous time series for each location point and combining them into one csv file
3-Subbasin_level_data: Estimating the subbasin level weighted average values for temperature. External input taken from ArcGIS to 
calculate the area of each grid in the subbasin
4-To_SWAT_format: Final data processing of subbasin level (daily) time series to SWAT compatible format
GLEAM-Processing: Three step processing of raw GLEAM data into subbasin level (daily) time series
