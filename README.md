# Biodiversity Intactness Index change in Phoenix, AZ

This repository contains materials for task 2 of the final project, of the course EDS 220 - Working with Environmental Datasets. The material is used to conduct an analysis of the biodiversity of the Phoenix (AZ) subdivision between 2017 and 2020, using raster data to understand the Biodiversity Intactness Index and biodiversity loss.

## File Structure

```
.
├── data
│   └── tl_2020_04_cousub
├── final-task2-phoenix-biodiversity-MIURA.ipynb
└── README.md
```

## Data

- Biodiversity Intactness Index (BII) Time Series: Accessed from the Microsoft Planetary Computer STAC catalog, specifically the `io-biodiversity` collection. Datasets contain estimates of terrestrial Biodiversity Intactness as 100-meter gridded rasters for the years 2017-2020.
    - Date Accessed: December 4, 2025
    - Data Accessed: [Microsoft Planetary Computer STAC catalog Example Notebook](https://planetarycomputer.microsoft.com/dataset/io-biodiversity#Example-Notebook)

- Phoenix Subdivision Shapefile: Accessed from the United States Census Bureau, Geography Division. The dataframe contains census geometries for the state of Arizona
    - Date Accessed: November 19, 2025
    - Data Accessed: [2020 TIGER/Line® Shapefiles: County Subdivisions Download site](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=County+Subdivisions)

 
## References

Impact Observatory (2017), Biodiversity Inactness[io-biodiversity]. Microsoft Planetary Computer STAC catalog. https://planetarycomputer.microsoft.com/dataset/io-biodiversity#overview, accessed on December 4, 2025.

U.S. Census Bureau, 2020 TIGER/Line Shapefiles: County[tl_2020_04_cousub], https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=County+Subdivisions, accessed on December 4, 2025.
