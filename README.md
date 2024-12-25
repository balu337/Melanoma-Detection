# Melanoma-Detection

Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. Objective of this projecct is to build a model which will help in classificaiton of type of skin cancer based on images of skin.

# Table of Contents
* [Problem Statement](#Problem-Statement)
* [Technologies Used](#Techcnologies-Used)
* [Conclusions](#Conclusions)
* [Acknowledgements](#Acknowledgments)

## Problem Statement
To build a CNN based model which can accurately detect melanoma. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

# Approach
- Load the data ( images ) and underrstand the labels/classes. Split the Data in to Training, Validation and Test sets.
- Build a CNN architecture and evaluate the accuracy of model on training data set.
- After priliminary run, analyze the model learning using accuracy and loss curves.
- Based on speccific run observations make changes to the model architecture to avoid overfitting or under fitting. To reduced overfitting data is rebalanced and also syntheic data is created
  
## Conclusions
*   Overfitting had reduced after rebalancing number of images for each lable and increasing the number of images for training. Dropout method is used for regularization.
*   Accuracy for training and validation has improved considerable after rebalancing, normalization and increasing the traning data.
  
## Techcnologies Used
- keras
- tensorflow
- pandas 
- numpy
- sns

  
## Acknowledgments
