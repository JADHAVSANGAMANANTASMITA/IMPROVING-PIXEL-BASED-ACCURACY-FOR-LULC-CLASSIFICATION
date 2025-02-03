# Improving Pixel-Based Accuracy for Land Use/Land Cover Classification

## Abstract
This project focuses on improving pixel-based accuracy for land use/land cover (LULC) classification by applying Shannon Entropy and the Urban Expansion Intensity Index (UEII) models. It evaluates the effectiveness of various classification models and auxiliary features in improving LULC accuracy, with a case study conducted in Mumbai city.

## Table of Contents
1. [Introduction](#introduction)
2. [Literature Review](#literature-review)
3. [Materials and Methodology](#materials-and-methodology)
   - [Study Area](#study-area)
   - [Data Collection](#data-collection)
   - [Auxiliary Data](#auxiliary-data)
   - [LULC Classification Method](#lulc-classification-method)
   - [Classification Accuracy Assessment](#classification-accuracy-assessment)
4. [Results and Discussion](#results-and-discussion)
5. [Future Scope](#future-scope)
6. [Conclusion](#conclusion)
7. [References](#references)

## Introduction
### 1.1 Introduction
The study delves into the significance of accurately classifying land use and land cover, which is crucial for urban planning and management.

### 1.2 Objective
To improve the accuracy of LULC classification using various models and auxiliary features.

## Literature Review
This section reviews previous work related to urban expansion models, classification techniques, and their implications for land cover studies.

## Materials and Methodology
### 3.1 General
The methodology integrates remote sensing data with various statistical and modeling techniques to assess urban expansion.

### 3.2 Study Area
The case study focuses on the city of Mumbai, India, where urban dynamics are pronounced.

### 3.3 Data Collection
Data sources include:
- **Sentinel-2 MSI, Level-2A** (10m, 20m resolution) - for land use classification.
- **SRTM DEM** (approximately 30m resolution) - for elevation data.
- **Administrative Boundary** - shapefile for Mumbai city boundary.

### 3.4 Auxiliary Data
Various spectral indices, including NDVI, NDWI, NDBI, NBR, and NDMI, were utilized to enhance classification accuracy.

### 3.5 LULC Classification Method
Multiple classification models, including four different pixel-based approaches, were applied and assessed.

### 3.6 Classification Accuracy Assessment
The assessment of accuracy was performed through user’s and producer’s accuracy metrics.

## Results and Discussion
The results indicated that the integration of auxiliary features significantly improved classification accuracy, with the best model (P4) achieving an overall accuracy of 96.49%.

## Future Scope
### 5.1 Shannon Entropy
Shannon’s entropy provides insights into the spatial distribution of urban growth, analyzing its concentration and dispersion.

### 5.2 Urban Expansion Intensity Index
The UEII facilitates a statistical assessment of urban spatial expansion over time.

## Conclusion
The study confirms that incorporating auxiliary features, particularly topographic data, enhances the overall accuracy of LULC classification in Mumbai city. This improved accuracy can be leveraged for further analysis and informed urban planning.

## References
1. Al-Sharif, A. A. A. and Pradhan, B. (2016). Spatio-temporal Prediction of Urban Expansion Using Bivariate Statistical Models. *Applied Spatial Analysis and Policy*, 9, 213-231. doi: [10.1007/s12061-015-9147-1](https://doi.org/10.1007/s12061-015-9147-1)
2. Al-Shalabi, M., Billa, L., Pradhan, B., Mansor, S., and Al-Sharif, A. A. A. (2013). Modelling urban growth evolution and land-use changes using GIS based cellular automata and SLEUTH models: the case of Sana’a metropolitan city, Yemen. *Environmental Earth Sciences*, 70, 425-437. doi: [10.1007/s12665-012-2137-6](https://doi.org/10.1007/s12665-012-2137-6)
3. Cabral, P., Augusto, G., Tewolde, M., and Araya, Y. (2013). Entropy in Urban Systems. *Entropy*, 15. doi: [10.3390/e15125223](https://doi.org/10.3390/e15125223)
4. Corcoran, J. M., Knight, J. F., and Gallant, A. L. (2013). Influence of Multi-Source and Multi-Temporal Remotely Sensed and Ancillary Data on the Accuracy of Random Forest Classification of Wetlands in Northern Minnesota. *Remote Sensing*, 5(7), 3212–3238.
5. He, C., Shi, P. J., and Chen, J. (2000). A study on landuse/cover change in Beijing area. *Geographical Research*, 20, 679-687.
6. Huang, H., et al. (2017). Mapping Major Land Cover Dynamics in Beijing Using All Landsat Images in Google Earth Engine. *Remote Sensing of Environment*, 202, 166–176.
