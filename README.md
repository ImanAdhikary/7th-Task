# Without PCA
## Loading the dataset, checking for null values, removing unnecessary columns, removing outliers

## Feature Scaling for all columns using StandardScaler

## Applying GridSearchCV for 'C' and 'gamma' parameter of SVM for both rbf and linear kernel

## Prediction by the model and finding the cross_val_score for both rbf and linear kernels
 Mean CV Accuracy for rbf kernel:  97.13%
 Mean CV Accuracy for linear kernel:  96.77%

# With PCA

## Applying PCA to convert the training and test dataset into 2D 

## The previous trained GridSearchCV will also be used here

## applying scaling for 2 columns using StandardScaler

## Prediction by the model and finding the cross_val_score for both rbf and linear kernels
  Mean CV Accuracy for rbf kernel:  95.67%
  Mean CV Accuracy for linear kernel:  96.04%

## Visualization of Decision Boundary