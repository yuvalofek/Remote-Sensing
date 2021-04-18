# Fundamentals of Remote Sensing and Earth Observation 

This course focuses on the application of remotely sensed geospatial datasets to analyze physical processes on Earth. We will study the fundamentals of working with geospatial data, and cover topics such as projections, coordinate reference systems and cartography. We will utilize public satellite imagery datasets across the frequency spectrum, including but not limited to optical, infrared, thermal and radar. Students will develop a strong understanding of multiple tools and techniques to process remotely sensed data, including Google Earth Engine, GDAL and QGIS. Students will regularly apply machine learning and image processing algorithms to remotely sensed data throughout the course, and are expected to have strong Python programming skills (e.g. familiarity with Numpy, OpenCV, TensorFlow). The culmination of the course will be a project of the student's choosing, focused on a specific application area of earth observation. 

Instructor: [Krishna Karra](https://www.linkedin.com/in/krishna-karra-8765811b/)

## Projects:
### 1. GeoTIFF manipulation and Dataset Aggregation
> Re-project, resample, and change the spatial extent of GeoTIFFs. Aggregate different metrics over a dataset of GeoTIFFs and write out the results
### 2. Land Cover Classification
> Perform image segmentation to classify land. Perform a thorough preprocessing stage on tf.dataset objects to normalize, augment, and manipulate input. 
### 3. Final Project 
> Independent student choice

## Topic Breakdown by Week:
### 1. Introduction to Raster and Vector Data
* Vector vs. raster data 
* Projections, coordinate reference systems and scale 
* Modern day cartography, what goes into making a map? Different ways to visualize geospatial data 
* Introduction to GDAL, shapely, geopandas, mapshaper 
### 2. L8 & S2, indices, google earth engine, & composites
* Landsat and Sentinel Satelites
* Bands
* Visualizing non-RGB bands
* NDVI
* cloud masking
### 3. Land cover classification 
* How to create good land cover maps
* UNet
* Land cover classification workflow
### 4. Fires 
* Capturing burn scars
* NBR
### 5. Geospatial Image Processing I 
* OpenCV
* Blurring filters
* Morphological transformations
* Edge Detection
* Flood mappung using SAR
### 6. Geospatial Image Processing II
* Machine learning
* Deep learning
* VIIRS and Nighttime Lights (NTL)
### 7. Synthetic Aperture Radar (SAR)
* Introduction to SAR
* How SAR works
* Constraints of SAR
* SAR image formation
* Imaging modes
* Interferometric SAR
* Polarization
### 8. Deforestation
* Monitoring deforestation with SAR
* Bagged trees algorithm
* Coherence
* Methods to track deforestation
### 9. Urban Heat Islands
* Monitoring urban heat using TIR
### 10. Flood Mapping
* [cloud-to-street](https://cloudtostreet.info/)
* Machine learning for flood mapping
* CNNs are a huge improvement
* Importance of predicting under clouds
* Combining satellite data and other sources
* How to formulate a remote sensing project?
### 11. Semantic Segmentation
* The reason for the UNet
* SparseCategoricalEntropy
* Softmax
* Image segmentation
* Convolutional neural networks
* Encoder/Decoder
* Transposed convolutions
* Dilated convolutions
* Loss functions
* Choosing a learning rate
* Regularization
* Normalization
### 12. NA
### 13. NA
