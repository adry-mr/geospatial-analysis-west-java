# Geospatial Data

This folder contains the geospatial data files used in the **Geospatial Analysis of West Java** project. The files in this directory are crucial for analyzing the geographic distribution and administrative boundaries within the West Java region, specifically highlighting Bogor City.

## Files Included

The following files are included in this folder and together make up the shapefile dataset:

- **`pulau_jawa_kab.shp`**: The main shapefile containing the geometry data for the regions.
- **`pulau_jawa_kab.shx`**: The shape index format, which is an index of the geometry.
- **`pulau_jawa_kab.dbf`**: The attribute format file that stores the attribute data (e.g., names, IDs) in tabular form.
- **`pulau_jawa_kab.prj`**: The projection format file that contains the coordinate system and projection information.
- **`pulau_jawa_kab.cpg`**: The code page file, specifying the character encoding for the `.dbf` file.
- **`pulau_jawa_kab.sbn` and `pulau_jawa_kab.sbx`**: The spatial index files that speed up spatial queries.
- **`pulau_jawa_kab.shp.xml`**: The metadata file, providing additional information about the shapefile.
  
## Usage

These files are used in the Jupyter notebook to perform spatial analysis on the West Java region. The shapefile (`.shp`) is the primary data source, while the other files support its proper functioning in GIS software and Python libraries like GeoPandas.

Ensure all these files are present in the same directory when loading the shapefile in your GIS software or Python environment.

## Notes

- Make sure not to modify or delete any of these files individually, as they are interdependent.

