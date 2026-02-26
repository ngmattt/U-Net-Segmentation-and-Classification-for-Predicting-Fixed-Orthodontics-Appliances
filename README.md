# U-Net Segmentation and Classification for predicting braces

## Overview
This project explores the use of deep learning and machine learning methods to detect and classify orthodontic braces from dental radiograph images. The workflow includes using a U-Net architecture for image segmentation followed by downstream classification models with selected extracted features.

## Methods

### U-Net Segmentation 
A U-Net convolutional neural network is used to segment dental images. The model learns pixel-level masks identifying relevant orthodontic regions. The segmentation outputs are then used for visualization and feature extraction. 

### Classification Models
Features derived from the segmented images used include: area of braces and percentage of braces area. The models used include: 
- Logistic Regression
- Random Forest
- Decision Tree
- k-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Ensemble Models

### Performance
Model performance is evaluated using:
- ROC curves
- Learning curves
- Summary statistics 

### Data

Due to size and privacy constraints, datasets are not stored in this repository.

To reproduce the results:
- Use your local dataset directory
- Update paths inside the notebooks accordingly

