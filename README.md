# Machine-Learning_Geopsatial-Science_Pyton

This project was created based on research activity that was published in IOP Conference Series: Earth and Environmental Science 2021. Below is the link for the article:

https://iopscience.iop.org/article/10.1088/1755-1315/884/1/012006

All script wrote in Python with Jupyter Notebook for the computation platform. QGIS is also used to help partially with spatial data management and map generation.

## Methods
![Flow Chart](https://user-images.githubusercontent.com/60123331/148004929-38164564-4ed6-433d-8a40-dfa10b3a3280.png)

## Training and Testing dataset
  Training and Testing data on this research mean the distribution of landslide and non-landslide spots. There were three ways to do the landslide data inventory in this research, which are: 1) field survey in 2020, 2) landslide events records from BPBD Kabupaten Mojokerto data collection and 3) 2011—2020 Google Earth Pro imagery interpretation. The data collection resulted in 383 landslide events shown in Figure.
  The use of machine learning to model the landslide probability can be considered as a typical binary classification. As a consequence, the exact same number of non-landslide spots are also needed. Landslide events are symbolized as “1” and non-landslide events are symbolized as “0”. This research used supervised machine learning analysis to predict the landslide and non-landslide events into the dependent variable.
![Sampling of Training   Testing Dataset (Landslide   Non-landslide Spots)](https://user-images.githubusercontent.com/60123331/148004062-6f3a459b-fce1-4f5e-8cc4-5e71359940f6.jpeg)

## Landslide Triggering Factor
  There were twelve triggering factors to landslide used in this research, which includes topographic, geologic, hydrologic and topographic conditions. Topographic parameters were TWI (Topographic Wetness Index), TPI (Topographic Position Index), SPI (Stream Power Index), slope, elevation, profile curvature and distance to drainage. Each factor in a raster format. Therefore, some shapefile data must be converted into a raster with the same spatial resolution of ALOS Palsar DEM which is 12 meters. Not only every raster-format spatial data must encompass the same coordinate system, but also the spatial resolution and pixel numbers. If the spatial resolution and pixel numbers are inconsistent, the analysis process is rejected
![Landslide Triggering Factors](https://user-images.githubusercontent.com/60123331/148004361-3e4e8f25-9e91-4098-8c7c-15e67231fb68.jpeg)

## Landslide Susceptibility Map
![Landslide Susceptibility Map of Pacet District](https://user-images.githubusercontent.com/60123331/148005127-0728f386-9b58-4584-8d0e-982e7fb1ae47.jpeg)



