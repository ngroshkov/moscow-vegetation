# Moscow Vegetation Analysis

This project calculates the NDVI (Normalised Difference Vegetation Index) for the districts of Moscow (Russia) in June 2024. The analysis is based on Landsat 8-9 OLI/TIRS C2 L2 sensor data.
Include the USGS credentials required to download the Landsat data in the `.env` file.

Libraries and tools used: shapely, rasterio, geopandas, pystac_client, rasterstats.

![NDVI](img/ndvi.png?raw=true "NDVI")
![NDVI Moscow](img/ndvi_moscow.png?raw=true "NDVI Moscow")
![Mean NDVI per Moscow Districs](img/mean_ndvi_moscow_districs.png?raw=true "Mean NDVI per Moscow Districs")
