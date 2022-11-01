# Breast Cancer Detection from image features

![FNA](https://github.com/econdavidzh/2022_MLZ_Project/blob/main/Images/FNA.png?raw=true)

Image source: https://www.researchgate.net/figure/Captured-images-of-layers-of-glass-with-smears-of-breast-mass-obtained-by-FNA-the-parts_fig3_232811011

This project has been created to practice what's been studied in the 2022 Machine Learning Zoomcamp by Alexey Grigorev.

## About the dataset:
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

### Description:
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

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
