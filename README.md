# About
This python based project analyzes and predicts the LULC(Land Use Land Cover) patterns in central region of india.
Land uses and land covers are classified as follows:
1. Water Bodies --> Rivers, Lakes
2. Vegetation --> Forests, Agriculture, Greenland
3. Buildup Area

Landsat-8 OLI data is used to analyze the LULC patterns of the time range 2013-2022(quater-wise) using QGIS tool. LSTM(Long-Short Term Memory), a deep learning algorithm, is used for time-series analysis and prediction. 

# Region of Interest
![lulc_region of interest](https://github.com/Diksha4111/Minor02-LULC/assets/78994799/5d0fb8c1-600d-42ac-8658-2d1c4734abc8)

# Central region of india
![lulc_central region of india](https://github.com/Diksha4111/Minor02-LULC/assets/78994799/468c7cbd-6d2c-4515-b61e-9070d370db47)

# Implementation 01
## merging landsat-8 OLI data in QGIS to obtain the desired region of interest 
![implementation-01](https://github.com/Diksha4111/Minor02-LULC/assets/78994799/10fbe454-3ffe-4173-928f-be72519f0ef5)

# Implementation 02
## clipping merged landsat-8 OLI data in QGIS to obtain desired region of interest
![implementation-02](https://github.com/Diksha4111/Minor02-LULC/assets/78994799/805f037a-0ef7-4cfc-ab2e-548637d27ee0)

# Implementation 03
## Performing supervised classification into various land use land cover(LULC) classes in QGIS of clipped landsat-8 data
![implementation-03](https://github.com/Diksha4111/Minor02-LULC/assets/78994799/21296c63-c41e-438d-88c2-9b9be55df431)

