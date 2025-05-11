# Moscow Vegetation Analysis

This project calculates the NDVI (Normalised Difference Vegetation Index) for the districts of Moscow (Russia) in June 2024. The analysis is based on Landsat 8-9 OLI/TIRS C2 L2 sensor data.
Include the USGS credentials required to download the Landsat data in the `.env` file.

In addition, the difference between NDVI indices is calculated using gee and geemap. Water areas found by the MNDWI index (>0.5) are excluded from the analysis.

Libraries and tools used: shapely, rasterio, geopandas, pystac_client, rasterstats, Google Earth Engine


<img src="img/ndvi_moscow.png" width=58.62% title="NDVI Moscow"><img src="img/ndvi_moscow_districts.png" width=39.35% title="NDVI Moscow Districs">

<img src="img/ndvi_2024_.png" width=49% title="NDVI Moscow 2024"><img src="img/ndvi_diff_2019_2024_.png" width=49% title="NDVI Differerence 2019-2024">
