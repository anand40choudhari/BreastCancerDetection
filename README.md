# BreastCancerDetection

Build classification machine Learning model to classify the cancer into two classes, M and B.
(M : malignant, B : benign)

-Attribute Information:

1) ID number
2) Diagnosis
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

-Following are the contents of the projects:

1. Importing the libraries and datasets
2. Data exploration
3. Dealing with missing values
4. Dealing with categorical data
5. Countplot
6. Correlation matrix and heatmap
7. Splitting the dataset into train and test
8. Feature Scalling
9. Building the model
     a) Logistics Regression
     b) Random Forest
10. Cross validations for both models
11. Randomized search to find the best parameters
12. Final Model using best parameters
13. Cross Validation on final model
14. Prediction of type of cancer for single observation using final Model

-Prediction of type of cancer for observation:
[[17.99,10.38,122.8,1001.0,0.1184,0.2776,0.3001,0.1471,0.2419,0.07871,1.095,0.9053,8.589,153.4,0.006399,
              0.04904,0.05372999999999999,0.01587,0.03003,0.006193,25.38,17.33,184.6,2019.0,0.1622,0.6656,
              0.7119,0.2654,0.4601,0.1189]]

-Final Result:

Patient with above observation can have cancer of type M : malignant.
