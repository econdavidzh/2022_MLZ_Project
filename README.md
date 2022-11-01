# Cancer detection from image features with a logistic regression model

This project has been created to practice what's been studied in the 2022 Machine Learning Zoomcamp by Alexey Grigorev.

## About the dataset:

### Source: 
https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28original%29

### Creator:
Dr. WIlliam H. Wolberg (physician)
University of Wisconsin Hospitals
Madison, Wisconsin, USA

### Donor:
Olvi Mangasarian (mangasarian '@' cs.wisc.edu)
Received by David W. Aha (aha '@' cs.jhu.edu)

### Data Set Information:
Samples arrive periodically as Dr. Wolberg reports his clinical cases. The database therefore reflects this chronological grouping of the data. This grouping information appears immediately below, having been removed from the data itself:

- Group 1: 367 instances (January 1989)
- Group 2: 70 instances (October 1989)
- Group 3: 31 instances (February 1990)
- Group 4: 17 instances (April 1990)
- Group 5: 48 instances (August 1990)
- Group 6: 49 instances (Updated January 1991)
- Group 7: 31 instances (June 1991)
- Group 8: 86 instances (November 1991)
- Total: 699 points (as of the donated datbase on 15 July 1992)

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
