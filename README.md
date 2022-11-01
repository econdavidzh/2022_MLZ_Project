# Cancer detection from image features with a logistic regression model

This project has been created to practice what's been studied in the 2022 Machine Learning Zoomcamp by Alexey Grigorev.

## About the dataset:
https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)

## Data Set Information:

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at [Web Link]

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

The actual linear program used to obtain the separating plane in the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

### Variables included in the dataset:
- **id**: ID number
- **diagnosis**: The diagnosis of breast tissues (M = malignant, B = benign)
- **radius_mean**: mean of distances from center to points on the perimeter
- **texture_mean**: standard deviation of gray-scale values
- **perimeter_mean**: mean size of the core tumor
- **area_mean** 
- **smoothness_mean**: mean of local variation in radius lengths
- **compactness_mean**: mean of perimeter^2 / area - 1.0
- **concavity_mean**: mean of severity of concave portions of the contour
- **concave points_mean**: mean for number of concave portions of the contour
- **symmetry_mean**: 
- **fractal_dimension_mean**: mean for "coastline approximation" - 1
- **radius_se**: standard error for the mean of distances from center to points on the perimeter
- **texture_se**: standard error for standard deviation of gray-scale values
- **perimeter_se**:
- **area_se**:
- **smoothness_se**: standard error for local variation in radius lengths
- **compactness_se**: standard error for perimeter^2 / area - 1.0
- **concavity_se**: standard error for severity of concave portions of the contour
- **concave points_se**: standard error for number of concave portions of the contour
- **symmetry_se**: 
- **fractal_dimension_se**: standard error for "coastline approximation" - 1
- **radius_worst**: "worst" or largest mean value for mean of distances from center to points on the perimeter
- **texture_worst**: "worst" or largest mean value for standard deviation of gray-scale values
- **perimeter_worst**:
- **area_worst**:
- **smoothness_worst**: "worst" or largest mean value for local variation in radius lengths
- **compactness_worst**: "worst" or largest mean value for perimeter^2 / area - 1.0
- **concavity_worst**: "worst" or largest mean value for severity of concave portions of the contour
- **concave points_worst**: "worst" or largest mean value for number of concave portions of the contour
- **symmetry_worst**:
- **fractal_dimension_worst**: "worst" or largest mean value for "coastline approximation" - 1
