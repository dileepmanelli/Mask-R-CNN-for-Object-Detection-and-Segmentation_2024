# Mask-R-CNN-for-Object-Detection-and-Segmentation_2024


This repository contains an implementation of Mask R-CNN for object detection and segmentation using TensorFlow.

## Overview

Mask R-CNN is a popular deep learning model for object detection and segmentation. It extends Faster R-CNN by adding a branch for predicting segmentation masks on each Region of Interest (RoI), parallel to the existing branch for classification and bounding box regression.

## Changes

In this implementation, TensorFlow's Keras API is used. Specifically, the following imports have been made:

python
```from tensorflow.keras import backend as K
from tensorflow.keras import layers as KL
from tensorflow.keras import models as KM




Usage
Clone this repository to your local machine:

git clone https://github.com/ahmedfgad/Mask-RCNN-TF2.git

Navigate to the repository directory:

cd Mask-RCNN-TF2

Replace mrcnn--> model.py with this repository model.py

run python maskrcnn_predict.py
```

## Example

![Prediction 1](https://github.com/dileepmanelli/Mask-R-CNN-for-Object-Detection-and-Segmentation_2024/blob/main/Prediction1.png)



