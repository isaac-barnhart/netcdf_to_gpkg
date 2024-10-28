# netcdf_to_gpkg
Converts a NetCDF file to a geopackage file for upload to QGIS.

"""
    Description:
    ------------------
    Reads in a NetCDF file, converts it into a dataframe, clips to an uploaded shapefile, merges shapefile attributes, and saves the file as a geodataframe for upload into QGIS.

        Notes:
            CRS of input .nc file is assumed to be 3857 in this case
            Datasets must be in the same workplace directory as the python script

        Parameters:
        ------------------
        nc_file = Name of the .nc file name

        shapefile = Name of desired shapefile

        output_file = filename of desired output file

        
        Example:
        ------------------
        netcdf("data_file.nc", "shape_file.shp", "merged_dataset.gpkg")

    """
